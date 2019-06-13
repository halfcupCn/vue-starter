<template>
  <div id="content">
    <img src="logo.png"/>
    <Dropdown @click="window.herf='_blank'"></Dropdown>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import DropDown from './components/Dropdown.vue'

@Component({
  components: {
    DropDown
  }
})
export default class App extends Vue {}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
