<template>
  <div>
    <div class="side-bar"><SideBar /></div>
    <div class="content"><Content /></div>
  </div>
</template>

<script>
// @ is an alias to /src
import SideBar from '@/views/SideBar.vue'
import Content from '@/views/Content.vue'

export default {
  name: 'Main',
  components: {
    SideBar,
    Content
  }
}
</script>
