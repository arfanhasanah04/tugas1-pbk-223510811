<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Profil 
              Nama: Arfan Hasanah <br>
              Jurusan: Teknik Informatika
               Institusi Pendidikan: Universitas Islam Riau
               Tahun Masuk: 2022 <br>
               Tahun Lulus : target 2026 <br>
               Kontak: arfanha@gmail.com/082165778978
      <a href="https://vitejs.dev/" target="_blank" rel="noopener"></a> 
      <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
