<script>
// 1 step = importare il componente nel componente principale
import AppTitle from './components/AppTitle.vue';
import AppJumbo from './components/AppJumbo.vue';
// 2 step = registrare il componente all' interno del componente padre
export default {
  //PASCAL CASE
  name: 'MyApp',
  //e un oggetto?
  components: {
    AppTitle,
    AppJumbo

  }
}
</script>
//3 step = aggiungere il tag con il nome del componente nel tag template
// 3 modi per scrivere un tag
<template>
  <AppTitle />
  <!--<AppTitle></AppTitle>-->
  <!--<app-title />-->
  <AppJumbo />
</template>


