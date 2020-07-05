<template>
  <div class="learning-vue">
    {{ message }}
  </div>
</template>

<script>
export default {
  name: 'LearningVue',
  data: function () {
    return {
      message: 'Hello Vue!',
    };
  },
};
</script>
