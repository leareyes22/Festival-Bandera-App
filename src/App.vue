<script setup lang="ts">
import image1Url from '@/assets/artistas-confirmados-al-festival-bandera-1024x1024.webp'
</script>

<template>
  <div>
    <v-img :src="image1Url" class="bg-white" width="600" :aspect-ratio="1" />
  </div>
</template>

<style scoped lang="scss">
div {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-image: url('@/assets/FestivalBandera.jpg') !important;
  height: 100%;
  padding: 5%;
}

.bg-white {
  border-radius: 5px;

  :hover {
    filter: brightness(0.5);
    cursor: pointer;
  }
}

h1 {
  color: #e10165;
  margin-top: 10px;
  margin-bottom: 10px;
  border: solid 2px whitesmoke;
  padding: 5px;
  font-weight: 600;
}
</style>
