<template>
    <div class="demo">
        <h1>名字:{{name}}</h1>
        <h1>地址:{{address}}</h1>
    </div>
</template>

<script>
    export default {
        name:'School',
        data(){
            return{
                name:'北京大学',
                address:"北京"
            }
        }
    }

</script>

<style>
    .demo{
        background-color: orange;
    }
</style>
