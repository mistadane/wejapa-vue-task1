<template>
    <div>
        <h1>{{name}}</h1>
    </div>
</template>


<script>
export default{
    props: {
        name: String
        }
}
</script>

<style scoped>
    h1 {
        text-align: center;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-weight: 700;
        font-size: 50px;
        position: relative;
        top: 200px;
    }
</style>