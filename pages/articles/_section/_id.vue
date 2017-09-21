<template>
  <span>id: {{id}}</span>
</template>

<script>
export default {
  asyncData ({params}) {
    return {
      id: params.id
    }
  }
}
</script>