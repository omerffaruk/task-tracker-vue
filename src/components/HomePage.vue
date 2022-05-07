<template>
  <AddTask />
  <AllTasks />
</template>

<script>
import AddTask from "./AddTask.vue";
import AllTasks from "./AllTasks.vue";

export default {
  name: "HomePage",
  components: {
    AddTask,
    AllTasks,
  },
};
</script>

<style></style>
