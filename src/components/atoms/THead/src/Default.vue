<template>
  <thead>
    <slot/>
  </thead>
</template>

<script>
import Presenter from '../Presenter.vue'
export default {
  name: 'VbThead',
  extends: Presenter,
  props: {
    ...Presenter.props
  }
}
</script>

<style lang="scss">
@import './style.scss';
</style>
