<template>
  <div class="list-item">
    <input type="text" :readonly="true" :value="this.task.title" class="form-control"/>
  </div>  
</template>

<script>
export default {
  name: "task",
  props: {
    task: {
      type: Object,
      required: true
    }
  }
};
</script>