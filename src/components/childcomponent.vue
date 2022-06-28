<template>
  <div>{{ advice }}</div>
</template>

<script>
export default {
  name: "childcomponent",
  props: {
    advice: String,
  },
};
</script>