<template>
  <div>Hello {{ value }}
    <h1>HaHa: {{ count }}</h1>
    <button @click="count+=1">count+1</button>
    <button @click="hello()">count+2</button>
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
  },
  methods: {
    hello: function() {
      this.count +=2
    }
  }
};
</script>
