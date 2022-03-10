<template>
    <h1>Who's That Pokémon?</h1>
        
    <pokemon-picture :pokemonId="4" :showPokemon="true"/>

    <pokemon-options />
            
</template>

<script>
import PokemonOptions from '@/components/PokemonOptions'
import PokemonPicture from '@/components/PokemonPicture'

import getPokemonOptions from '@/helpers/getPokemonOptions'


export default {
    components: { PokemonOptions, PokemonPicture },
     
    

}
</script>
