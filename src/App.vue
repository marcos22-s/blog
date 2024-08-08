<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import rio from './assets/rio.webp'
import carro from './assets/carro.webp'
import volei from './assets/volei.webp'
import ouro from './assets/ouro.webp'


</script>

<template style="background-color: white;">

<img :src="rio" alt="rio"> 



<br>
<p></p>

<div class="postagem2" style="text-align: center;">
<h1 style="color: black; font-family:Georgia, 'Times New Roman', Times, serif;">Classificação da nossa seleção vem?</h1>
<img :src="volei" alt="volei">
<h3 style="color: black;font-family:Georgia, 'Times New Roman', Times, serif">A seleção brasileira de vôlei feminino continua na disputa das Olimpíadas de Paris 2024 e é hora do time enfrentar as oponentes que as eliminaram na Liga das Nações no mês passado. Nesta quinta-feira (1º), às 8h, o Brasil entra em quadra conta o Japão para uma partida que faz parte das rodadas preliminares do Grupo B.
</h3>
</div>

<br>
<p></p>

<div class="postagem2" style="text-align: center;">
<h1 style="color: black;font-family:Georgia, 'Times New Roman', Times, serif">NOSSO PRIMEIRO OUROO!!!!</h1>
<img :src="ouro" alt="ouro">
<h3 style="color: black;font-family:Georgia, 'Times New Roman', Times, serif">O primeiro ouro do Brasil na Olimpíada finalmente chegou.
 Nesta sexta-feira (2), a brasileira Beatriz Souza venceu a israelense Raz Hershko na final da categoria +78kg do judô feminino. 
 <br>
 <br>
 <br>
 

 <footer>
        <p>&copy; 2024 Meu Site. Todos os direitos reservados.</p>
        <p>
            <a href="/privacidade.html">Política de Privacidade</a> |
            <a href="/contato.html">Contato</a>
        </p>
    </footer>
 
</h3>
</div>




</template>

<style scoped>
header {
  line-height: 1.5;
}

template{
  background-color: white;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    height: 20px;
    width: 30px;
    position: center;
  }

  template{
    background-color: white;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
