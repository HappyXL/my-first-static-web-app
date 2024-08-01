<template>
  <div>Hello {{ value }}
    <h1>HaHa: {{ count }}</h1>
    <button @click="count+=1"></button>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World",
      count: 0,
    };
  }
};
</script>
