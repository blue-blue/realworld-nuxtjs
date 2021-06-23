<template>
  <div>{{ userId }}</div>
</template>

<script>
export default {
  name: 'UserId',
  data() {
    return {
      userId: this.$route.params.id, // query 一样适用
    }
  },
}
</script>
