<template>
  <input
    :class="className"
    type="datetime-local">
</template>

<script>
import Presenter from '../Presenter.vue'
export default {
  name: 'VbInputDatetimeLocal',
  extends: Presenter,
  props: {
    ...Presenter.props
  }
}
</script>

<style lang="scss">
@import './style.scss';
</style>
