<script setup lang="ts">
import { ref } from 'vue';

const signature = undefined;
const image = undefined
ref(signature);
ref(image);


const signatureUploaded = () => {
  console.log(signature);

}

</script>

<template>
  <main>
    <form class="flex flex-col">
      <input @blur="signatureUploaded()" type="file" id="file-input-signature" accept="image/png, image/jpeg">
      <input type="file" id="file-input-img" accept="image/png, image/jpeg">
    </form>
  </main>
</template>
