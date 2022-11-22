<template>
  <section>
    <QRCode />
  </section>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import QRCode from "./components/QRCode.vue";

export default defineComponent({
  name: "App",
  components: {
    QRCode,
  },
});
</script>
