<script lang="ts">
import { useRouter } from 'vue-router';
const router = useRouter();
const goToBuild = ()=> router.push('/motos');

</script>


<template>
  <div class="flex flex-row align-items-center justify-content-evenly">
    <section class="flex flex-column align-items-center">
      <h1>Monte sua moto!</h1>
      <button class="mt-4 app-dark-button" @click="goToBuild" id="order">Quero montar</button>
    </section>
      <section>
        <img src="/moto.png" alt="moto">
    </section>
  </div>
</template>

<style scoped lang="scss">
h1{
  font-size: 5rem;
  width: 25rem;
  text-align: center;
}
#order{
  height: 3.2rem;
  width: 20rem;
  border-radius: 2.5rem;
}

</style>
