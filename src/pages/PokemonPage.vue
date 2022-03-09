<template>
    
        <h1>Who's This Pokémon?</h1>
        
        <pokemon-picture />

        <pokemon-options />
</template>

<script>
import PokemonOptions from '../components/PokemonOptions'
import PokemonPicture from '../components/PokemonPicture'

export default {
  components: { PokemonPicture, PokemonOptions },

}
</script>

<style>

</style>