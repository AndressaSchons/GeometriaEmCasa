<template>
    <main>
        <div>
            <p>{{ nome }}</p>
            <p>{{ descricao }}</p>
        </div>
    </main>
</template>

<script lang="ts">

export default {
    name: 'FaseUmInst', 
    data() {
        return{
            nome: 'QUADRADO',
            //image: "./images/quadrado.png",
            descricao: "POSSUI QUATRO (4) LADOS DE MESMO TAMANHO" 
    }
    
    }
}

</script>
<style scoped>
</style>