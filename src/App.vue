<script>
// 1 step = importare il componente nel componente principale
import AppTitle from './components/AppTitle.vue';
// 2 step = registrare il componente all' interno del componente padre
export default {
  //PASCAL CASE
  name: 'MyApp',
  //e un oggetto?
  components: {
    AppTitle

  }
}
</script>
//3 step = aggiungere il tag con il nome del componente nel tag template
<template>
  <AppTitle />
</template>


