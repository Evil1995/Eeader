<template>
  <div class="home">
      <SidebarBookShelf></SidebarBookShelf>
      <BookShelf></BookShelf>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import BookShelf from '@/components/BookShelf.vue'
import SidebarBookShelf from '@/components/SidebarBookShelf.vue'

export default {
  name: 'home',
  components: {
    BookShelf,
    SidebarBookShelf,
  }
}
</script>

<style lang='scss' rel='stylesheet/scss'>
.home {
    display: flex;
    justify-content: center;
}
</style>
