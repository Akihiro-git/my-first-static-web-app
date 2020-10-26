<template>
  <div>Hello {{ value }} {{ value2 }}</div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "Vue", 
      value2: "World1"
    };
  }
};
</script>
