para resetar os padroes de fabrica dos navegadores na folha de stilo configuramos tudo para zerar , damos um reset->
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

no css podemos usar variaveis a nosso favor
as variaveis sao usadas para marcar cores predominante e outras coisas, afim de facilitar caso tenha que trocar a cor do site ou aplicacao

iniciamos no css para usar a variaveis->
:root{
    exemplos de variavieis      de cores
    --vermelho:#e50914;
    --preta:#141414;
} 

utilizando as variaveis

exemplo->
body{
    background: var(--preta);
}

porque usamos classes com o nome de container
sao classes wrapper
porque essas classe nao modificam, e a mais abrangencia ao referenciar no css
  para fazer comentarios no css3 basta usar /* comentario */


as classes wrapper, facilitam na hora de tratar e um pagina os elementos pai e os elementos filhos

