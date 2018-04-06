<template>
    <h1>Hello {{ name }}!</h1>
</template>

<script>
export default {
  data: () => {
    return { name: "world" }
  },
  head() {
    return {
      title: "About Us - Nuxt.js",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "About our company Nuxt.js "
        }
      ]
    }
  }
}
</script>