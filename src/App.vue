<template>
  <section class="forms-modal">
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <Login></Login>
        </div>

        <div class="col-md-4">
          <CompanyLogin></CompanyLogin>
        </div>

        <div class="col-md-4">
          <RegisterMain></RegisterMain>
        </div>

      </div>
    </div>
  </section>

</template>

<script setup>
import Login from "./components/Forms/Login.vue";
import CompanyLogin from "./components/Forms/CompanyLogin.vue";
import RegisterMain from "./components/Forms/RegisterMain.vue";
</script>

<style scoped>

</style>
