<template>
  <div class="msg-container">
    <div class="msg-test"><span>aaaaaaaaaaaaaaaaa</span>{{msg}}</div>
  </div>
</template>

<script>
export default {
  props: {
    msg:''
  },
  data () {
    return {}
  },
  computed: {
  },
  methods: {

  }
}
</script>
<style lang="scss">
  html,body {
    height: 100%;
    margin: 0px;
    padding: 0px;
  }
  .msg-container{
    display: flex;
    position: absolute;
    top: 0px;
    bottom: 0px;
    overflow: hidden;
    & > .msg-test {
      background: #090909;
      color: #fff;
    }
  }
</style>
