<template>
  <div class="about">
    <h1>This is an about page</h1>
    <HelloExample />
  </div>
</template>
<script>
import HelloExample from "@/components/HelloExample.vue";

export default {
  name: "AboutView",
  components: {
    HelloExample,
  },
};
</script>
