<template>
  <section
    class="flex mx-auto justify-center content-center items-stretch max-w-md"
  >
    <div
      class="rounded-2xl bg-white shadow-sm mx-8 p-4 pb-6 mt-20 lg:mt-36 lg:mx-12"
    >
      <img src="../assets/image-qr-code.png" class="rounded-2xl" />
      <h1 class="text-2xl font-bold text-center pt-6">
        Improve your front-end skills by building projects
      </h1>
      <p class="text-gray-500 text-center py-5 px-2">
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "QRCode",
  props: {
    msg: String,
  },
});
</script>
