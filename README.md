# 03-About-functions
03 About functions

- Já simplificamos a maneira de pular linhas criando a função pulaLinha(). 
-  Será que é possível fazermos o mesmo com o document.write()?
-  Quando queremos exibir algo para o usuário, sempre temos que escrevê-lo,
-   incluindo também a mensagem entre parênteses, como em:
 # document.write("Olá pessoal!");
 
 
É uma sintaxe extensa. Em vez de escrevermos tudo isso,
criaremos uma função chamada mostra().
Quem mostra, mostra algo, portanto esta função receberá uma mensagem como parâmetro, 
em vez de nenhum. Se compararmos as instruções:


 ## document.write("Olá pessoal!");

## mostra("Olá pessoal");

Vemos que a segunda, além de mais sucinta, 
fica explícita nossa intenção de mostrar algo.
Quando um terceiro olhar nosso código, ao ver mostra(), 
saberá que seu propósito é exibir algo na tela.

E como criamos a função mostra()?
Primeiro colocaremos alguns trechos em comentários, por meio de barras duplas (//).
O programa ignorará a referida linha, que continuará presente para fins didáticos,
para lembrarmos o que havia antes.

Vemos que a segunda, além de mais sucinta, fica explícita nossa intenção de mostrar algo.
Quando um terceiro olhar nosso código,
ao ver mostra(), saberá que seu propósito é exibir algo na tela.

E como criamos a função mostra()? 
Primeiro colocaremos alguns trechos em comentários,
por meio de barras duplas (//). 
O programa ignorará a referida linha, 
que continuará presente para fins didáticos, para lembrarmos o que havia antes.

## <meta charset="UTF-8">

<script>

    function pulaLinha() {

        document.write("<br>");
        document.write("<br>");

}

var ano = 2016;

// document.write("Flávio tem " + (ano - 1977) + " anos");

pulaLinha();

// document.write("Joaquim tem " + (ano - 1996) + " anos");

pulaLinha();

ano = 2017;

// document.write("Barney tem " + (ano - 1976) + " anos");
// document.write("Olá pessoal!");

</script>
-No lugar de document.write() queremos utilizar mostra():
