<template>
  <div>
    <FirstComponent/>
    <p>O dado é: {{ testando }}</p>
  </div>
</template>

<script>
  import FirstComponent from './components/FirstComponent.vue'

  export default {
    name: 'App',
    components: {
      FirstComponent
    },
    data() {
      return {
        testando: "teste"
      }
    }
  }
</script>
