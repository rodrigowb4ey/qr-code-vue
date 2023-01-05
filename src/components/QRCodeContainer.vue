<template>
  <div
    id="container"
    class="flex gap-y-4 items-center flex-col justify-center align-middle px-3 pb-8 w-1/5 h-2/4 border-2 ring-offset-8 rounded-3xl py-4 bg-white"
  >
    <img
      src="/assets/img/image-qr-code.png"
      class="flex rounded-xl w-72"
      alt="QR Code"
    />
    <h1 class="flex text-slate-800 text-xl text-center font-extrabold">
      Improve your front-end skills by building projects
    </h1>
    <h2 class="flex text-slate-400 text-sm text-center font-normal">
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </h2>
  </div>
</template>

<script>
export default {
  name: "QRCodeContainer",
};
</script>
