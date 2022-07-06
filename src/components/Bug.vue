<template functional>
  <div :class="classes">
    <p>{{str}}</p>
    <span><a>Hi bug</a></span>
  </div>
</template>

<script>
export default {
  props: {
    classes: null,
    str: String
  }
}
</script>