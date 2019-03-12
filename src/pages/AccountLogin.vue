<template>
  <q-page class='column items-center q-mt-xl' padding>
    <h1>Login</h1>
    <p>Sign In to your Account</p>
    <q-field
      style='width: 80%; max-width: 400px;'
      icon='mail'
    >
      <q-input v-model='email' float-label='Email'/>
    </q-field>
    <q-field
      style='width: 80%; max-width: 400px'
      icon='lock'
    >
      <q-input v-model='password' float-label='Password'/>
    </q-field>
    <div class='row justify-between items-center q-mt-xl' style='width: 80%; max-width: 400px'>
      <router-link to='/reset' class='text-blue' style='text-decoration: none;'>Forgot Password?</router-link>
      <router-link to='/dashboard'><q-btn class='bg-blue text-white'>Login</q-btn></router-link>
    </div>
  </q-page>
</template>

<script>
export default {
  name: 'AccountLogin',
  data: function () {
    return {
      email: '',
      password: '',
    }
  }
}
</script>

<style>
</style>
