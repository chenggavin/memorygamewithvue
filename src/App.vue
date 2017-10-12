<template>
  <div id="app">
    <h1> MEMORY MATCHING GAME</h1> 
    <gameboard class="container"></gameboard>
  </div>

</template>

<script>
    import gameboard from './components/gameboard.vue';

    export default {
        name: 'app',
        components: {
            gameboard
        },

    data () {
        return {
                
            cards: [
                    {   
                         id: 1,
                         letter: "a", 
                    },

                    {   
                        id: 2,
                        letter: "b"
                    }
            ]
        }
    }
}
</script>

<style>

</style>
