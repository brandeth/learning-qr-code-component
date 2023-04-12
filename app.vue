<script lang="ts" setup>
const title = ref('QR Code Component')
const description = ref('Front-end coding challenge')

useHead({
  title,
  meta: [{
    name: 'description',
    content: description
  }]
})
</script>

<template>
  <div class="main">
    <QRCode />
  </div>
</template>
