<template>
    <div class="container">
      <tuer-nav></tuer-nav>
      <router-view></router-view>
      <tuer-footer></tuer-footer>
    </div>
</template>

<script>
import 'bulma'
import Footer from '@/components/commons/Footer'
import Nav from '@/components/commons/Nav'
export default {
  name: 'app',
  components: {
    'tuer-footer': Footer,
    'tuer-nav': Nav
  }
}
</script>
