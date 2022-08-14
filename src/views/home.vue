<template >
    <div>
        <h5 style="color:red">Hello from home page</h5>
        <h5>This is home page</h5>
        <about/>
    </div>
</template>
<script>
import about from '../components/about.vue'
import About from '../components/about.vue';
export default {
    name: 'home_page',
    components:{
    about,
    About
}
}
</script>
<style >
    
</style>