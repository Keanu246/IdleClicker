<template>
    <div id="app">
        <Resource name="Bronze" v-bind:amount="bronze" v-bind:credits="credits"></Resource>
        <br>
        <button v-on:click="mineBronze">Mine Bronze</button>
    </div>
</template>

<script>
data () {
  return {
    bronze: 0
  }
}

</script>
