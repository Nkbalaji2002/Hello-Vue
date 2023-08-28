<script>
export default {
  data() {
    return {
      message: "Hello Vue World",
    };
  },
};
</script>

<!-- html -->
<template>
  <div class="p-4" id="app">
    <div class="flex justify-center items-center ml-0 mr-0 mt-auto mb-auto">
      <div class="rounded-xl p-10 bg-blue-500 text-white text-center text-2xl">
        {{ message }}
      </div>
    </div>
  </div>
</template>

