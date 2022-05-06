<template>
  <div>
    <!-- o que esta dentro do v-if é javascript 
    o comando else só funciona se vier sucedido de um if -->
    <p v-if="esta_trabalhando">Estou trabalhando no momento.</p>
    <p v-else>Estou em busca de oportunidades</p>
    <p>Utilizo as seguintes tecnologias:</p>
    <ul>
      <li>JavaScript</li>
      <li>PHP</li>
      <li>Python</li>
    </ul>
    <div>
      <button @click="showEmail">{{textoBotao}}</button>
    </div>
    <p v-show="mostrar_email">made uma msg para: {{email}} </p>
    <p>Para acessar meu portifólio <a v-bind:href="link" target="blank">basta clicar aqui </a></p>
    <PictureS/>
  </div>
</template>

<script>

import PictureS from './PictureS.vue'

export default {
    name: 'InfoUser',
    components: {
    PictureS
},
    data(){
      return{
        esta_trabalhando: false,
        mostrar_email: true,
        email: 'mateus@email.com',
        link: 'https://google.com'
      }
    },
    methods:{
      showEmail(){
        this.mostrar_email = !this.mostrar_email
        if(!this.mostrar_email){
          this.textoBotao = 'Mostrar E-mail'
        }else{
          this.textoBotao = 'Esconder E-mail'
        }
      }
    }
}
</script>
