<template>
  <task-bar />
</template>

<script lang="ts">
import TaskBar from './components/TaskBar.vue';

export default {
  name: 'App',
  components: {
    TaskBar,
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body {
  width: 100vw;
}

.add-item {
  text-align: center;
  margin-top: 5vh;
}

.task-bar {
  width: 60vw;
}
</style>
