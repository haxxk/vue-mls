<template>

<div >
  <mu-flexbox class="mt8">
    <mu-flexbox-item class="flex-demo">
     <img src="../../assets/6.gif" class="img6"/>
      <p>1分抽奖</p>
    </mu-flexbox-item>
    <mu-flexbox-item class="flex-demo">
     <img src="../../assets/7.png" class="img7"/>
      <p>9.9封顶</p>
    </mu-flexbox-item>
    <mu-flexbox-item class="flex-demo">
      <img src="../../assets/8.png" class="img8"/>
      <p>时尚拼团</p>
    </mu-flexbox-item>
    <mu-flexbox-item class="flex-demo">
      <img src="../../assets/9.png" class="img9"/>
     <p>大家都在买</p>
    </mu-flexbox-item>
  </mu-flexbox>
      
  <mu-flexbox class="mt8">
    <mu-flexbox-item class="flex-demo">
     <img src="../../assets/6.gif" class="img6"/>
      <p>1分抽奖</p>
    </mu-flexbox-item>
    <mu-flexbox-item class="flex-demo">
     <img src="../../assets/7.png" class="img7"/>
      <p>9.9封顶</p>
    </mu-flexbox-item>
    <mu-flexbox-item class="flex-demo">
      <img src="../../assets/8.png" class="img8"/>
      <p>时尚拼团</p>
    </mu-flexbox-item>
    <mu-flexbox-item class="flex-demo">
      <img src="../../assets/9.png" class="img9"/>
     <p>大家都在买</p>
    </mu-flexbox-item>
  </mu-flexbox>
  
  
</div>
</template>
<script>
    export default {
        name:"grid",
    }
</script>
<style lang="css">

.mt8 {
  margin-top: 0.1rem;
}
.flex-demo {
  
  height: 0.9rem;
  background-color:  #fff;
  text-align: center;
  line-height:0.1rem;
}

.img6,.img7,.img8,.img9{
  width:0.5rem;
  height:0.5rem;
}
</style>