<template>
  <section>
    <h3><span>My Boards</span> ▸ {{ name }}</h3>
    <div>...</div>
  </section>
</template>

<style scoped>
  section {
    text-align: left;
  }

  h3 {
    color: #37474f;
    text-align: left;
    margin: 1.5rem;
  }

  span {
    color: #546e7a;
  }
</style>
<script>
export default {
  name: 'board-view',
  components: {},
  props: {
    name: String,
    id: String,
  },
};
</script>
