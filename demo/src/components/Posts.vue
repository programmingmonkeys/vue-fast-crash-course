<template>
  <div>
    {{ message }}
    <button class="btn btn-primary">Click</button>
  </div>
</template>

<script>
export default {
  name: 'PostExample',
  data() {
    return {
      message: 'this is a test'
    }
  }
}
</script>

<style scoped></style>
