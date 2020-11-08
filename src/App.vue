<template>
  <div id="app">
  
    <div class="w-full h-full">
        <div class="w-4/5 h-auto border border-gray-400 p-10 rounded shadow-lg mx-auto mt-10 bg-gray-300">
            <button class="py-3 px-3 bg-blue-600 text-white font-semibold rounded" @click="componentSelected = 'Login' ">Login</button>
            <button class="py-3 px-3 bg-blue-600 text-white font-semibold rounded" @click="componentSelected = 'UpdatePass' ">Change Password</button>
            <keep-alive>
            <component :is="componentSelected"></component>
            </keep-alive>
        </div>
    </div>
  </div>
</template>

<script>

import Form from './Components/FormComponent';
import Login from './Components/Login';
import UpdatePass from './Components/UpdatePass';

export default {
  components: {
    Form,
    Login,
    UpdatePass
  },
  data() {
    return {
      componentSelected: 'Login'
    }
  },
}
</script>

