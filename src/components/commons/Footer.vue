<template>
<footer class="footer">
  <div class="container">
    <div class="content has-text-centered">
      <p>网站基于Nodejs开发 版权所有 © 2012-2014 Tuer.me <span>| 友情连接 </span><a href="http://www.duole.com/" target="_blank">多乐电台 </a><!--<a href="http://www.touchs.me/" target="_blank">Touchs</a>--></p>
      <p>
        <a href="http://m.tuer.me">WAP版 </a>
        <a href="http://www.tuer.me/about/">关于兔耳 </a>
        <a href="http://www.tuer.me/help/">使用帮助 </a>
        <a href="http://www.tuer.me/diary/50851ba98bd5768b4d000001">提交BUG </a>
      </p>
      <p v-html="cnzz"></p>
    </div>
  </div>
</footer>
</template>

<script>
var cnzzprotocol = document.location.protocol === 'https:' ? ' https://' : ' http://'
var cnzzhtml = unescape('%3Cspan id="cnzz_stat_icon_5598883"%3E%3C/span%3E%3Cscript src="' + cnzzprotocol + 's96.cnzz.com/stat.php%3Fid%3D5598883%26online%3D1%26show%3Dline" type="text/javascript"%3E%3C/script%3E')
console.log(cnzzhtml)
export default {
  name: 'footer',
  data: () => {
    return {
      cnzz: cnzzhtml
    }
  }
}
</script>
