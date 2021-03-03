<template>
    <div class="tab-bar-item">
        <div :class="{isActived:isActive}">
            <slot name="item-text"></slot>
        </div>
    </div>

</template>

<script>
  export default {
    name: "TabBarItem",
    data() {
      return {
        isActive: true
      }
    }
  }
</script>

<style scoped>
    @import '../../../assets/css/base.css';

    .tab-bar-item{
        flex: 1;
        text-align: center;
        height: 49px;
    }

    .isActived{
        color: red
    }
</style>
