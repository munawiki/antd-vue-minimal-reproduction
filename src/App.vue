<template>
  <div>
    <a-typography-title class="hello-world">Ant Design Vue</a-typography-title>
  </div>
</template>

<script lang="ts">
import { TypographyTitle } from "ant-design-vue";
import { defineComponent } from "vue";

export default defineComponent({
  components: {
    "a-typography-title": TypographyTitle,
  },
});
</script>

<style scoped></style>
