<template>
    <div id="app">
        <Resource name="Bronze" v-bind:amount="bronze" v-bind:credits="credits" transactional></Resource>
        <br>
        <button v-on:click="mineBronze">Mine Bronze</button>
    </div>
</template>

<script>
import Resource from './components/Resource';
  export default {
    name: 'app',
    components: {
      Resource
    },
    data () {
      return {
        bronze: 0,
        silver: 0,
        gold: 0,
        diamond: 0,
        mine: 1,
        credits: 1000,
        req: 0,
        sword: 0,
        pickaxe: 0,
        miner: 8,
      }
    },
</script>

<style lang="css">
    #app {
        color: green;
    }
</style>
