<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        message: 'Hello World!'
      }
    }
  }
</script>


<template>
  <div class="bg-blue-500 p-4 rounded-lg">
      <h1 class="text-center text-white font-sans text-2xl">
        {{ message }}
      </h1>
    </div>
</template>
