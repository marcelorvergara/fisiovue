<template>
  <div>
    <b-navbar type="dark" variant="dark" class="bg-company-green">
      <div class="container">
      <b-navbar-brand href="#">CFRA</b-navbar-brand>
      <b-navbar-nav class="ml-auto">
        <!-- Navbar dropdowns -->
        <b-nav-item-dropdown text="Pacientes" right>
          <b-dropdown-item href="#">Cadastro</b-dropdown-item>
          <b-dropdown-item href="#">Anamnese</b-dropdown-item>
          <b-dropdown-item href="#">Dados Cadastrais</b-dropdown-item>
          <b-dropdown-item href="#">Evolução Diáris</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="Atendimentos" right>
          <b-dropdown-item href="#">Consultar</b-dropdown-item>
          <b-dropdown-item href="#">Agendar</b-dropdown-item>
          <b-dropdown-item href="#">Remarcar</b-dropdown-item>
          <b-dropdown-item href="#">Cancelar</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="Configurações" right>
          <b-dropdown-item href="#">Usuário</b-dropdown-item>
          <b-dropdown-item href="#">Procedimentos</b-dropdown-item>
          <b-dropdown-item href="#">Pacotes</b-dropdown-item>
          <b-dropdown-item href="#">Salas</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="Financeiro" right>
          <b-dropdown-item href="#">Movimentos</b-dropdown-item>
          <b-dropdown-item href="#">Fornecedores</b-dropdown-item>
          <b-dropdown-item href="#">Pacotes</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="Relatórios" right>
          <b-dropdown-item href="#">Atendimentos</b-dropdown-item>
          <b-dropdown-item href="#">Fluxo de Caixa</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
      </div>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "Menu"
}
</script>

<style scoped>
::v-deep .dropdown .nav-link {
  color: white !important;
}
</style>