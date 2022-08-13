
<template>
<div>
    <input v-model="nome"/>
   <p> Ola eu sou o {{nome}}</p>
  
</div>
</template>
<script>
export default{
     name: 'componenteAgua',
     data() {
        return {
            nome: ''
        }
     }
     }

</script>


