<template>
  <div>
    <p>Componentes de mensagem</p>

    <div>
      <form id="burger-form">
        <div class="input-container">
            <label for="nome">Nome do Cliente</label>
            <input type="text" id="nome" name="name" v-model="nome" placeholder="Digite o seu nome">
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "BurgerForm",
};
</script>

<style scoped>
</style>