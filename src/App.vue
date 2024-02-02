<script setup>
import FirstComponent from './components/FirstComponent.vue';
import {ref} from 'vue'

const message = ref("This is a data from the parent component")

const actionFromParent =()=>{
  alert("Action from parent")
}
</script>

<template>
  <div>
    <h1>Hello Class</h1>
    <FirstComponent :message="message"/>

    <input type="text" v-model="message">
  </div>
</template>

<style scoped>

</style>
