<template>
    <div id="body">
        <h1>Body</h1>
        <component1/>
        <component2/>
        <component3/>
    </div>
</template>

<script>
import component1 from './Component1.vue'
import component2 from './Component2.vue'
import component3 from './Component3.vue'
export default {
    name: "Body",
    components:{
        component1,
        component2,
        component3
    }
}
</script>

<style>
    #body{
        width:100%;
        height: 65vh;
        background: yellow;
    }
</style>