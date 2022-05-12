<template>
  <div>
    <v-list
      flat
      subheader
    >

      <v-list-item-group
        v-model="settings"
        multiple
        active-class=""
      >
        
      <Tarefa/>
      <Tarefa/>
      <Tarefa/>
        
      </v-list-item-group>
    </v-list>
  </div>
</template>

<script>
import Tarefa from '../components/tarefas/tarefas.vue'

  export default {
    name: 'Home',

    components: {
      Tarefa      
    },
  }
</script>
