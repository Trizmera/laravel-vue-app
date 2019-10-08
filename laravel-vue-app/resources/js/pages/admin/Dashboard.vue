<template>
    <div class="container">
        <div class="card card-default">
            <div class="card-header">Painel Admin </div>
            <div class="card-body">
                Bem vindo ao seu painel de administrador
            </div>
        </div>
        <div class="card card-default">
            <div class="card-header">Lista de usuarios</div>
            <div class="card-body">
                <userList></userList>
            </div>
        </div>
    </div>
</template>
<script>
  import userList from '../../components/user-list.vue'
  export default {
    mounted() {
      //
    },
    components: {
      userList
    }
  }
</script>