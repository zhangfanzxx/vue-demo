<style scoped>
</style>
<template>
    <div class="container">
    <Navigation></Navigation>
	<Layout></layout>
       
    </div>
</template>
<script>
$(function () {  
    alert(123);  
 }); 

import Layout from '@/components/layout'
import Navigation from '@/components/Navigation'
    export default {
        components:{
	Layout,
	Navigation,
	}
    }
</script>
