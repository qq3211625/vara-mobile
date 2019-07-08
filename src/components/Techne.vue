<template>
  <div >
    <div class="vara">
      <div class="vara-LOGO">
        <img src="./images/vara.png" alt="vara">
      </div>
      <div class="COMING-SOON" >
        <p>COMING SOON</p>
      </div>
      <div class="footer" >
        <p>Vara Fresh Pty Ltd</p>
        <p>480 Princes Highway, Bomaderry NSW 2541</p>
        <p>© 2019 Vara Fresh Holdings Pty Ltd</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      // reshight:0,
      msg: 'Welcome to Your Vue.js App'
    }
  },
  updated () {
    // reshight = document.documentElement.clientHeight
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" rel="stylesheet/stylus" scoped>
      .vara
        width: 100%;
        height: 100%;
        background-color: #9dd9d1;
        overflow: hidden;
        font-family: PingFangSC-Regular;
        .vara-LOGO
          height: 260px;
          margin-top: 58px;
          text-align: center;
          & > img
            height: 260px;
            width: 260px;
        .COMING-SOON
          text-align: center;
          margin-top: 62px;
          & > p:nth-child(1)
            font-size: 18px;
            font-weight: 600;
            color: #fff;
        .footer
          width: 100%;
          text-align: center;
          color: #fff;
          margin-top: 172px;
          & > p:nth-child(1)
            font-size: 13px;
            font-weight: 400;
          & > p:nth-child(2)
            font-size: 13px;
            font-weight: 400;
            margin: 9px 0 8px;
          & > p:nth-child(3)
            font-size: 10px;
            font-weight: 400;
</style>
