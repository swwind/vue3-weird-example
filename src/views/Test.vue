<template>
  <div class="test">
    <h1>Your id is {{ id }}</h1>
  </div>
</template>

<script>
export default {
  props: {
    id: {
      type: String,
      required: true
    }
  },
  async setup (props) {
    console.log('props is ', props)
  }
}
</script>
