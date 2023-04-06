# Pesquisa-Java
Pesquisa sobre os tipos de dados, estrutura condicional, tipos de elementos android studio e estrutura de repetição da linguagem Java.

<b>Sites de Pesquisa</b>
<br>
<br>
https://www.w3schools.com/java/java_data_types.asp
https://www.academicotech.com/post/tipos-de-dados-em-java
https://www.javatpoint.com/pt/tipo-de-dado-em-java
https://www.treinaweb.com.br/blog/estruturas-condicionais-e-estruturas-de-repeticao-em-java
https://productoversee.com/java-estruturas-de-repeticao/
https://www.devmedia.com.br/iniciando-na-linguagem-java/21136
https://blog.grancursosonline.com.br/os-tipos-primitivos-da-linguagem-java/

<h2><b> Pesquisa: </b></h2>
<br>
<h3><b> Tipos de Dados </b><h3>
 
 <h5>Os dados são importantes em qualquer linguagem, e no Java não é diferente, por isso iremos explicar a teoria dos tipos de dados primitivos do Java e o que eles fazem na prática quando utlizados em um programa. Podemos dividir esses dados nos tipos: integral, ponto flutuante e booleano.</h5>
 
 <h4> Integral - Byte</h4>
  <h5><b>Ocupa 8 bits de memória e é responável por armazenar números inteiros de -128 e 127. É o mais indicado para a idade de uma pessoa, por exemplo.</b></h5>
 
 <h4> Integral - Short</h4>
  <h5><b>Os dados do tipo Short são maiores que os "bytes", podendo armazenar valores entre -32.768 até 32.767, ocupando 16 bits de memória.</b></h5>
 
 <h4> Integral - Int</h4>
  <h5><b>Com tamanho maior que o short, é capaz de armazenar números entre -2.147.483.648 e 2.147.483.647., sendo necessário o espaço de 32 bits.</b></h5>
 
 <h4> Integral - Long</h4>
  <h5><b>Sendo o maior disponível em relação a números na linguagem Java, contempla valores entre -9.223.372.036.854.775.808 e 9.223.372.036.854.775.807. Diferentemente de outros tipos de dado, no Long é possível colocar um "L" ao final do número, para indicar ser deste tipo.</b></h5>
 
 <h4> Integral - Char</h4>
  <h5><b>Com limite máximo de 16 bits de memória, é utilizado para armazenar caracteres, como letras, por exemplo. </b></h5>
 
 <h4> Ponto Flutuante - Float</h4>
  <h5><b>Valor ilimitado de caracteres que podem ser englobados, possui uma menor precisão que o Double (ou seja, menos casas após a vírgula) e ocupa 32 bits de memória.</b></h5>
 
 <h4> Ponto Flutuante - Double</h4>
  <h5>Também possui um valor ilimitado de caracteres que podem ser englobados, tendo uma grande vantagem em relação ao armazenamento do float, pois são necessários 64 bits de armazenamento.Sendo assim, é mais utilizado, já que possui o dobro de capacidade do outro tipo de ponto flutuante.<b>
</b></h5>
 
 <h4> Booleano - True e False</h4>
  <h5><b> Ocupando só um bit de memória, recebe apenas dois valores: sim, ou não, true ou false.</b></h5>
 
<h3><b> Estrutura Condicional </b></h3>

 <h5><b>Estruturas condicionais são de suma importância para programas, pois sem elas, as instruções da maioria dos programas seriam executadas sequencialmente sem nenhum reaproveitamento, sendo assim bem mais trabalhoso e complexo.</b></h5>
  
  
<h4> Instrução - If <h4>

  O If é utilizado basicamente como uma forma de "avaliar" condições, explicando e traduzindo de maneira literal, seria como falar "se (condição) for verdadeira, então execute". Exemplo básico:
  
  ```
  if (condição) {
      instrução1;
      instrução2;
  }
  ```
  
<h4> Instrução - Else </h4>
  
  <b>O else é um pouco diferente, é o complemento para caso a instrução não for verdadeira, como proceder se
   ela não for ( tendo a possibilidade de adicionar outra condição ou instrução), em poucas palavras. Um exemplo:
  
  ```
  if (resposta == 10) {
     // Se a variável for igual a 10, a frase abaixo será escrita
     System.out.println(“Você acertou!”);
     } 
  else {
     // Caso contrário, a frase abaixo será escrita
     System.out.println(“Você errou!”);
     }
  ```
  </b>

<h4> Instrução - Switch/Case </h4>

  <b>O Switch/Case vem como uma alternativa para ocasiões em que são necessários muitos "Ifs" em um programa. Basicamente, sua função é testar o valor contido em uma determinada variável realizando uma comparação com cada uma das opções. Cada uma dessas possíveis opções é determinada pela instrução condicional "Case". Um exemplo:
  
  ```
  int mes = 2;
      switch (mes) {
       case 1:
         System.out.println(“O mês é janeiro”);
       break;
       case 2:
         System.out.println(“O mês é fevereiro”);
       break;
      }
  ```
  </b>
 
 <h3><b> Estruturas de Repetição </b></h3>
  
 <b> As estruturas de repetição são usadas para fazer com que o programa possa ser executado uma ou várias vezes, dependendo dda quantidade de repetições que você definir. O melhores nomes a se usar para definir a variável que irá carregar a "quantidade" de repetições são os caracteres: i, j, k, cont...
  Para definir a quantidade de repetições, o ideal a se fazer é um incremento. Exemplo:
  
 ```
  i++;
 ```
  </b>
 
 <h4><b> Estrutura de Repetição - While </b></h4>
 
  <b>Estrutura que verifica se determinado critério e verdadeiro para executar o looping N vezes. Por exemplo:
   
  ```
  int i = 0;
   
  while (i < 10){
   System.out.printIn("Esse número é menor que 10");    
   i++;
  ```
 </b>

 <h4><b> Estrutura de Repetição - Do... While </b></h4> 
  
 <b> Esta estrutura tem seu funcionamento inverso ao comando while, ou eja, excuta o looping pelo menos uma vez antes de verificar a condição. Exemplo:
 
  ```
  int i = 1;
  
  do{
   System.out.printIn("Esse número é menor que 10");
   i++;
  } while (i <10);
  ```
 </b>
  
  <h4><b> Estrutura de Repetição - For </b></h4> 
  
  <b> Comando utilizado para quado se tem um número limitado de repetições. Exemplo:
   
   ```
   for(int i = 1; i < 10; i++;){
    System.out.printIn("Esse número é menor que 10");
   }
   ```
  </b>
   
   <h3><b> Elementos visuais do Android Studio <b><h3>
   
   <h4><b>Text</b></h4>
    
   <h5><b>Como o próprio nome já diz, é um elemento visual gráfico voltado ao texto, a parte escrita da aplicação. O text tem algumas variações dentro de si, algums delas são:
  
  ```
    - TextView: o principal objetivo é mostrar o texto na tela do aplicativo.
    - AutoCompleteTextView: é um texto que pode ser editado pelo usuário, e também mostra as sugestões possiveis para completar o que esá sendo digitado.
    - MultiAutoleteTextView: uma extensão do AutoCompleteTextView, mas a diferença é que e mostra uma sugestão de conclusão para o que o usário está digitando.
  ``` 
   </h5></b>
   
   <h4><b>Button</b></h4>
    
   <h5><b> Um botão "clicável", que pode direcionar o usuário a alguma outra tela ou pode realizar uma ação, dependendo de sua configuração. Assim como o text, o button também tem suas variações, dentre elas:
    
  ```
    - CHeckBocx: são botões que podem ser marcados com um "check", podendo ser utilizado para escolhas, etc. Podemos encontrar essas checkbox em formulários de múltipla escolha.
    - RadioButton: pode ser considerado um botão de opção, pois ao ser clicado, o botão fica preenchido, assim mostrando a opção ecolhida pelo usuário.
    - Switch: pode ser considerado um botão de ativado/desativado. É muito comum vermos esse tipo de botão nas opções do visor do celular, por exemplo: o wifi, dados móveis, bluetooth, etc.
  ```  
   </b></h5>
