<template>
  <div class="test">
    <h1>Your id is {{ id }}</h1>
  </div>
</template>

<script>
export default {
  async setup (props) {
    console.log('id is ' + props.id)
    return {
      id: props.id
    }
  }
}
</script>
