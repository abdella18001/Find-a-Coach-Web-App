<template>
    <TheHeader></TheHeader>
    <div>Hello world</div>
</template>

<script>
import TheHeader from './Components/layouts/TheHeader.vue';
export default {
    components:{
        TheHeader
    }
}
</script>

<style >
*{
    box-sizing: border-box;
}

html{
    font-family: sans-serif;
}

body{
    margin: 0 ;
}
</style>