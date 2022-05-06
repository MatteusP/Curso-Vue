<template>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Projetos</a></li>
        <li><a href="#">contato</a></li>
    </ul>
</template>

<script>
export default {
    name: "HeadeR",
}
</script>


<style scoped>
    ul{
        list-style: none;
        display: flex;
        justify-content: center;
        background-color: #999;
        font-size: 20px;
    }
    li{
        margin-right: 10px;
    }
    a{
        color: #ddd;
        text-decoration: none;
        transition: .5s;
    }
    a.hover{
        color: aqua;
    }
</style>

