<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <tree msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import tree from '@/components/tree.vue'; // @ is an alias to /src

@Options({
  components: {
    tree,
  },
})
export default class Home extends Vue {}
</script>
