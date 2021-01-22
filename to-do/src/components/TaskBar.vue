<template>
  <div class="add-item">
    <input type="text" class="task-bar" v-model="text" />
    <button>Add</button>
  </div>
  <p>{{ text }}</p>
</template>

<script>
export default {
  name: 'TaskBar',
  data() {
    return {
      text: '',
    };
  },
};
</script>

<style scoped>
input {
  border: none;
  border-bottom: 1px solid black;
  margin-right: 20px;
  outline: none;
  padding-bottom: 8px;
}

button {
  border: none;
  cursor: pointer;
  padding: 5px 10px;
  background-color: #4e4ceafa;
  font-size: 12pt;
  font-weight: bold;
  color: white;
  border-radius: 5px;
}
</style>
