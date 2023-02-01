<template>
  <h1>{{ title }}</h1>
  <p>{{ like }} like</p>
</template>

<script>
export default {
  name: 'BlogPost',
  props: ['title', 'like']
}
</script>