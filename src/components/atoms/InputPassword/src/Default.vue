<template>
  <input
    :class="className"
    type="password">
</template>

<script>
import Presenter from '../Presenter.vue'
export default {
  name: 'VbInputPassword',
  extends: Presenter,
  props: {
    ...Presenter.props
  }
}
</script>

<style lang="scss">
@import './style.scss';
</style>
