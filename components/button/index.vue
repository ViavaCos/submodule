<template>
  <div class="test-button" @click="$emit('click')">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'test-button'
}
</script>

<style lang="less">
@import './index.less';
</style>