<template>
  <div id="setting">
    <my-todo />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import MyTodo from '@/components/MyTodo.vue' // @ is an alias to /src

export default Vue.extend({
  name: 'SettingView',
  components: {
    MyTodo
  }
})
</script>
