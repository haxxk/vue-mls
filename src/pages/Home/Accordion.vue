<template>
    <mt-swipe :auto="4000" class="accordion">
        <mt-swipe-item ><img src="../../assets/3.png" class="img3"/></mt-swipe-item>
        <mt-swipe-item ><img src="../../assets/4.png" class="img4"/></mt-swipe-item>
        <mt-swipe-item ><img src="../../assets/5.png" class="img5"/></mt-swipe-item>
    </mt-swipe>
</template>

<script>




    export default {
        name:"accordion"
    }



</script>

<style>
    .accordion{
        height:2rem;
    }
    .img3,.img4,.img5{
        width:100%;
        height:2rem;
    }
</style>