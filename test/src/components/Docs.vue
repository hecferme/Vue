<template>
    <div>
        <h1>DocExpire</h1>
        <div v-bind:key="item.id" v-for="item in items">
            <h3>
                {{item.name}}
            </h3>
            <p> Expires
                {{item.exp}}
            </p>

        </div>
    </div>
</template>

<script>
export default {
    name: "Docs",
    props: ["items"]
}
</script>

<style scoped>

</style>
