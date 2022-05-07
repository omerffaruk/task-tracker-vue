<template>
  <form class="add-task-form">
    <div class="form-control">
      <label for="task-name">Task</label>
      <input type="text" id="task-name" placeholder="Task" v-model="taskName" />
    </div>
    <div class="form-control">
      <label for="task-date">Date & Time</label>
      <input
        type="text"
        id="task-date"
        v-model="taskDate"
        placeholder="Date & Time"
      />
    </div>

    <button type="submit">Save Task</button>
  </form>
</template>

<script></script>

<style></style>
