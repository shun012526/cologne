<template>
  <div class="container">
    <div>
      <h1>cologne-web</h1>
      <div>{{ firebaseData.one }}</div>
    </div>
  </div>
</template>

<script>
export default {
  async asyncData({ $axios }) {
    const data = await $axios.get(
      `https://cologne-web-7a158.firebaseio.com/product.json`
    )
    return {
      firebaseData: data.data,
    }
  },
}
</script>
