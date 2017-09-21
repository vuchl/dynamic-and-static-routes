<template>
  <h2>{{section}}</h2>
</template>

<script>
export default {
  asyncData ({params}) {
    return {
      section: params.section
    }
  }
}
</script>