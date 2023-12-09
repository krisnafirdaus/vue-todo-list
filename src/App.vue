<script>
  import ItemComponent from './components/ItemComponent.vue';
  import TodoList from './components/TodoList.vue';

  export default {
    components: {
      ItemComponent,
      TodoList
    },
  data() {
    return {
      items: [
        {
          id: 1,
          text: "item 1"
        },
        {
          id: 2,
          text: "item 2"
        }
      ]
    }
  }
}
</script>

<template>
  <!-- <ul>
    <ItemComponent v-for="item in items" :key="item.id" :item="item" />
  </ul> -->
  <TodoList />
</template>

<style scoped>
body {
  color: black;
}
</style>
