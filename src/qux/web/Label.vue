<template>
  <div :class="['qux-label', cssClass]" @click="onClick">
     <span class="qux-common-label">
      {{dataBindingLabel}}
    </span>
  </div>
</template>
<style lang="scss">
    @import '../scss/qux-label.scss';
</style>
<script>

import _Base from './_Base.vue'

export default {
  name: 'qLabel',
  mixins: [_Base],
  data: function () {
      return {
      }
  },
  mounted () {
    // console.debug('Label.mounted()', this.element)
  }
}
</script>
