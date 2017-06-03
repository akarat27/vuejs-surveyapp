<template>
  <Modal
    v-model="modal1"
    title=""
    @on-ok="ok"
    @on-cancel="cancel">
    <p slot="header">555</p>
    <p>Login facebook</p>
  </Modal>
</template>
<script>
    export default {
      data () {
        return {
          modal1: true
        }
      },
      methods: {
        ok () {
          // this.$Message.info('点击了确定');
          console.log('ok')
        },
        cancel () {
          // this.$Message.info('点击了取消');
          console.log('cancel')
        }
      }
    }
</script>
<style scoped>

</style>
