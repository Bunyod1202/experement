<template>
  <div class="">
    <TermRu />
  </div>
</template>

<script>
import { defineComponent } from "vue";
import TermRu from "src/components/Table.vue";
export default defineComponent({
  name: "PageIndex",
  components: {
    TermRu,
  },
});
</script>
