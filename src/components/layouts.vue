<template>
  <section class="container" > <!--最外层容器-->
    <section class="menu"> <!--左边的容器-->
    <menus></menus>
    </section>
    <section class="content-container"><!--右边的容器-->
    <todo></todo>
    </section>
  </section>
</template>
<script>
import todo from './todo';
import menus from './menus';
  export  default {
    components:{
      menus,
      todo
    }
  };
</script>
<style lang="less">
@import '../common/style/layouts.less';
</style>