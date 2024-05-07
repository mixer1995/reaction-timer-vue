<template>
    <h3>Best scores:</h3>
    <div v-for="(score, i) in scores" :key="i">
       {{ ++i }}) {{ score }} seconds
    </div>
</template>

<script>
export default {
    props: {
        scores: {
            type: Array
        }
    }
}
</script>

<style scoped>

</style>