<template>
 <q-page class='column items-center q-mt-xl' padding>
   <h2 style='font-size: 54px;' class='q-mb-sm'>Reset Account</h2>
   <q-field
     style='width: 80%; max-width: 400px;'
     icon='mail'
   >
     <q-input v-model='item.email' type='email' float-label='Email'/>
   </q-field>
   <div class='row justify-between items-center q-mt-xl' style='width: 80%; max-width: 400px;'>
     <div></div>
     <q-btn class='bg-blue text-white'>Reset</q-btn>
   </div>
 </q-page>
</template>

<script>
export default {
 name: 'AccountReset',
 data: function () {
   return {
     item: {
       email: ''
     }
   }
 },
 methods: {

 }
}
</script>

<style>
</style>