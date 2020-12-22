<template>
  <div>
    <h2>Search组件</h2>
    <h3>params.keyword:{{ $router.params.keyword }}</h3>
    <h3>query.keyword2:{{ $router.query.keyword2 }}</h3>
    <h3>props.keyword: {{ keyword3 }}</h3>
    <h3>props.keyword2: {{ keyword4 }}</h3>
  </div>
</template>

<script>
export default {
  name: "Search",
  props: ["keyword3", "keyword4"],
};
</script>

<style scoped></style>
