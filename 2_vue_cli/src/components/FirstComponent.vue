<template>
  <div>
    <h1>Olá vueee!</h1>
    <p>Meu nome é {{ nome }} e trabalho como {{ profissao }}</p>
  </div>
</template>

<script>
export default {
  name: "FirstComponent",
  data() {
    return {
      nome: "Matheus",
      profissao: "Programador",
    };
  },
};
</script>