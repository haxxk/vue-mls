<template>
<mu-appbar>
    <img src="../../assets/1.png" slot="left" class="img1"/>
    <mu-text-field icon="search" class="appbar-search-field" hintText="套装" fullWidth />
    <img src="../../assets/2.png" slot="right" class="img2"/>
</mu-appbar>
</template>

<script>




    export default {
        name:'search'
    }
</script>

<style lang="less">
.img1{
  width:0.3rem;
  height:0.3rem;
}
.img2{
  width:0.2rem;
  height:0.18rem;
}

.appbar-search-field{
  color: #FFF;
  margin-bottom: 0;
  &.focus-state {
    color: #FFF;
  }
  .mu-text-field-hint {
    color: fade(#FFF, 54%);
  }
  .mu-text-field-input {
    color: #FFF;
  }
  .mu-text-field-focus-line {
    background-color: #FFF;
  }
}
</style>