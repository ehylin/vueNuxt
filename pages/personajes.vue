<template>
    <div>
        <v-container>
            <v-layout align-center justify-center row>
                <v-card 
                    v-for="(personaje, id) in $store.state.personajes.data"
                    :key="id"
                    class="mx-auto card-vue"
                    max-width="344"
                >
                <v-img
                :src="personaje.imagen"
                height="200px"
                ></v-img>
                    <v-card-title>
                    {{personaje.nombre}}
                    </v-card-title>
                </v-card>
  
            </v-layout>
        </v-container>
    </div>
</template>

<script>
export default {
    name: 'Personajes',

   
    data: () => ({
      personajes: []   
    }),
        
};
</script>

<style lang="scss" scoped>

</style>