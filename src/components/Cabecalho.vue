<template>
  <header>
    <h1>{{ valor }}</h1>
  </header>
</template>

<script>
export default {
  props: ["valor"],
};
</script>

<style>
header {
  background-color: rgb(201, 183, 156);
  color: white;
  height: 60px;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>