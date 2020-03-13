<template>
    <div id="component3">
        <h1>Component 3</h1>
        <p id="hover" v-on:click="changeColor">CLICK ME</p>
    </div>
</template>

<script>
export default {
    name: "component3",
    methods:{
        changeColor: function(){
            document.getElementById('header').style.backgroundColor = "black";
            document.getElementById('footer').style.backgroundColor = "black";
        }
    }
}
</script>

<style scoped>
    #component3{
        border-top: 1px solid black;
    }
    #component3 p{
        font-size: 30px;
        display: inline-block;
        border: 2px solid black;
        padding: 10px;
    }

</style>