<script>
// 1) Importazione del componente 
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

  export default {
  data() {
    return { 
        message: 'Proviamo ad implementare un Immagine'
    }
  },
  // 2) Dichiarizone del componente
  components: {
    AppTitle,
    AppHero
  },
}
</script>

<template>
    <!-- Utilizzo del componente  -->
  <AppTitle />

  
  <div class="tittle">
    <h2>
      {{ message }}
    </h2>
    
  </div>
  
  <AppHero />
  
</template>

<style scoped>
.tittle {
  text-align: center;
}

.tittle > h2 {
  color: lightcoral;
}

</style>
