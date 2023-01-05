<template>
  <main class="flex items-center flex-col justify-center align-middle py-36">
    <QRCodeContainer></QRCodeContainer>
  </main>
</template>

<script>
import QRCodeContainer from "./components/QRCodeContainer.vue";

export default {
  name: "App",
  components: {
    QRCodeContainer,
  },
};
</script>
