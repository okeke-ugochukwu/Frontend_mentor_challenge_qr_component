<script>
import qrText from './components/text.vue';
import qrCode from './components/qrCode.vue';

export default {
  name: 'App',
  components: {
    qrText,
    qrCode
  }
}
</script>


<template>
  <div id="app">
    <qrCode/>
    <qrText/>
  </div>
</template>



<style lang="scss">
  @import './styles/style.scss';
</style>
