# STRINGS JAVASCRIPT

Em JavaScript, Strings são valores compostos de texto e podem conter letras, números, símbolos, pontuação e até emojis!

## Aspas simples e duplas em strings JavaScript

Strings em JavaScript estão contidas em um par de aspas simples '' ou aspas duplas "". Ambas as aspas representam Strings, mas certifique-se de escolher uma e FICAR COM ELA. Se você começar com aspas simples, precisará terminar com aspas simples. Existem prós e contras em usar as aspas simples do IE que tendem a tornar mais fácil escrever HTML dentro de Javascript, pois você não precisa escapar da linha com aspas duplas.

EXEMPLO

'Isto é uma corda. 👏';  
"Esta é a 2ª corda. 💁";

**Incluindo aspas**

Digamos que você esteja tentando usar aspas dentro de uma string. Você precisará usar aspas opostas dentro e fora das aspas simples ou duplas do JavaScript. Isso significa que strings contendo aspas simples precisam usar aspas duplas e strings contendo aspas duplas precisam usar aspas simples.

EXEMPLO

"São seis horas.";  
'Lembre-se de dizer "por favor" e "obrigado."';

  
Como alternativa, você pode usar uma barra invertida \ para escapar das aspas. Isso permite que o JavaScript saiba com antecedência que você deseja usar um [caractere especial](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String#escape_notation) .

Veja como é a reutilização dos exemplos acima:

EXEMPLO

'São seis horas.';  
"Lembre-se de dizer \"por favor\" e \"obrigado.\"";

## Métodos e propriedades de string JavaScript

Strings têm suas próprias variáveis ​​e funções internas, também conhecidas como propriedades e métodos. Aqui estão alguns dos mais comuns.

### Comprimento da String JavaScript

A propriedade length de uma string controla quantos caracteres ela possui.

EXEMPLO

"lagarta".comprimento;

SAÍDA

11

### Método toLowerCase

O método toLowerCase de uma string em JavaScript retorna uma cópia da string com suas letras convertidas em minúsculas. Números, símbolos e outros caracteres não são afetados.

EXEMPLO

"AS CRIANÇAS".toLowerCase();

SAÍDA

"as crianças"

### Método toUpperCase

O método toUpperCase de uma string retorna uma cópia da string com suas letras convertidas em maiúsculas. Números, símbolos e outros caracteres não são afetados.

EXEMPLO

"Eu gostaria de ser grande.".toUpperCase();

SAÍDA

"EU QUERIA SER GRANDE."

### Método de corte

O método trim de uma string retorna uma cópia da string com os caracteres de espaço em branco inicial e final removidos.

EXEMPLO

" mas mantenha os espaços do meio ".trim();

SAÍDA

"mas mantenha os espaços do meio"

## Números

**Números** são valores que podem ser usados ​​em operações matemáticas. Você não precisa de nenhuma sintaxe especial para números — basta escrevê-los diretamente no JavaScript.

EXEMPLO

12345;

#### Decimais e frações

JavaScript não distingue entre números inteiros e decimais, então você pode usá-los juntos sem precisar converter de um para o outro.

EXEMPLO

10 + 3,14159;

SAÍDA

13.14159

**Frações** não existem em JavaScript, mas você pode reescrevê-las como problemas de divisão usando o [operador de divisão](https://www.javascript.com/learn/operators) /. Observe que o número resultante é sempre convertido em decimais — assim como em uma calculadora.  

EXEMPLO

1/3;

SAÍDA

0,3333333333333333

Frações impróprias usam o operador de divisão da mesma maneira.  

EXEMPLO

11/10;

SAÍDA

1.1

Para usar números mistos, você precisa adicionar o número inteiro e a fração.  

EXEMPLO

1 + (4/3);

SAÍDA

2.333333333333333

#### Números negativos

Você pode tornar um número negativo colocando o operador - na frente.

EXEMPLO

-3;

SAÍDA

-3;

Você também pode obter um número negativo subtraindo um número de um número menor.  

EXEMPLO

5 - 7;

SAÍDA

-2

# Booleanos

Em JavaScript, um valor booleano é aquele que pode ser TRUE ou FALSE. Se você precisa saber “sim” ou “não” sobre algo, então você deve usar a função booleana. Parece extremamente simples, mas os booleanos são usados ​​o tempo todo na programação JavaScript e são extremamente úteis. Qualquer coisa que precise estar “ativada” ou “desativada”, “sim” ou “não”, “verdadeira” ou “falsa”, ou que tenha apenas um propósito temporário, geralmente é adequada para booleanos.

Abaixo está um exemplo de como usar booleanos em JavaScript:

EXEMPLO

var luzes da cozinha = false;  
luzes da cozinha = true;  
cozinhaLuzes;

SAÍDA

verdadeiro

Neste exemplo, a variável "kitchenLights" sendo definida como "true" indicaria que as luzes estão acesas. Se foi definido como "falso", isso significa que eles estão desativados.

É útil armazenar booleanos em variáveis ​​para acompanhar seus valores e alterá-los ao longo do tempo. Booleanos são usados ​​como funções para obter os valores de variáveis, objetos, condições e expressões. Na verdade, os booleanos são críticos para que as condicionais funcionem.

Em seu código, quando você precisa saber se uma condição está sendo atendida ou não antes de prosseguir para a próxima etapa, a função booleana se torna sua melhor amiga. Se _tal e tal_ for VERDADEIRO, então faça isso. Se for FALSE, então faça outra coisa.

Considere algo simples como fazer um sanduíche. Na sua cabeça, você realmente estará passando por uma série de booleanos e condicionais:

Eu tenho pão? Verdadeiro ou falso. Se for TRUE, então posso prosseguir para a próxima etapa, se tenho ou não mostarda, presunto, etc. Se for FALSE, precisarei ir à loja para comprar pão. E assim por diante.

Você nunca pode assumir nada ao programar - você tem que escrever a lógica explicitamente, e grande parte disso é simplesmente saber se uma condição está sendo atendida ou não. Daí a importância dos booleanos em JavaScript.

## Operadores

**Operadores** são os símbolos entre valores que permitem diferentes operações como adição, subtração, multiplicação e muito mais.  
O JavaScript tem dezenas de operadores, então vamos nos concentrar naqueles que você provavelmente verá com mais frequência.

#### Aritmética

O operador + **adiciona** dois números.

EXEMPLO

1 + 2;

SAÍDA

3

O operador - **subtrai** um número de outro.

EXEMPLO

50 - 15;

SAÍDA

35

O operador * **multiplica** dois números. Observe que é um asterisco e não o símbolo × comumente usado em matemática.

EXEMPLO

3 * 12;

SAÍDA

36

O operador / **divide** um número por outro. Observe que é uma barra e não o símbolo ÷ comumente usado em matemática.  

EXEMPLO

12/4;

SAÍDA

3

As expressões JavaScript seguem uma [ordem de operações](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence) , portanto, embora + seja escrito primeiro no exemplo a seguir, a multiplicação ocorre primeiro entre os dois últimos números e *.  

EXEMPLO

1 + 100 * 5;

SAÍDA

501

Se quiser mais controle sobre o pedido, é aí que o operador de **agrupamento** é útil.  

####   
Agrupamento  

() operador **agrupa** outros valores e operações. O código localizado entre parênteses é avaliado primeiro, pois o JavaScript resolve cada operação movendo-se da esquerda para a direita.  
Adicionar o operador de agrupamento ao exemplo anterior faz com que 1 + 100 seja avaliado primeiro.

EXEMPLO

(1 + 100) * 5;

SAÍDA

505

#### Concatenação

O operador + também pode concatenar strings, que é outra maneira de dizer que pode adicioná-las.

EXEMPLO

"notícias" + "papel";

SAÍDA

"jornal"

#### Tarefa

O operador = atribui valores. É usado para definir o valor das [variáveis](https://www.javascript.com/learn/variables) .

EXEMPLO

var jantar = "sushi";

## Variáveis

**Variáveis** ​​são valores nomeados e podem armazenar qualquer tipo de valor JavaScript.

Veja como declarar uma variável:

EXEMPLO

var x = 100;

E aqui está o que está acontecendo no exemplo acima:  

-   var é a palavra-chave que informa ao JavaScript que você está declarando uma variável.
-   x é o nome dessa variável.
-   = é o operador que informa ao JavaScript que um valor virá em seguida.
-   100 é o valor para a variável armazenar.

#### Usando variáveis

Depois de declarar uma variável, você pode referenciá-la pelo nome em outro lugar do seu código.

EXEMPLO

var x = 100;  
x + 102;

SAÍDA

202

Você pode até usar uma variável ao declarar outras variáveis.

EXEMPLO

var x = 100;  
var y = x + 102;  
y;

SAÍDA

202

#### Reatribuindo variáveis  

Você pode dar um novo valor a uma variável existente a qualquer momento após ela ser declarada.

EXEMPLO

var clima = "chuvoso";  
tempo = "sol";  
clima;

SAÍDA

"ensolarado"

#### Variáveis ​​de nomenclatura  

Os nomes de variáveis ​​são bastante flexíveis, desde que você siga algumas regras:  

-   Comece com uma letra, sublinhado _ ou cifrão $.
-   Após a primeira letra, você pode usar números, bem como letras, sublinhados ou cifrões.
-   Não use nenhuma das palavras-chave reservadas do JavaScript.

Com isso em mente, aqui estão os nomes de variáveis ​​válidos:

EXEMPLO

var camelCase = "palavra em minúscula, depois em maiúscula";  
var jantar2Go = "pizza";  
var I_AM_HUNGRY = verdadeiro;  
var _Hello_ = "que bela saudação"  
var $_$ = "olhos de dinheiro";  

E aqui estão alguns nomes de variáveis ​​inválidos - tente identificar o que há de errado com cada um deles:  

EXEMPLO

var% total = 78;  
var 2fast2catch = "reivindicação em negrito";  
função var = falso;  
var classe = "fácil";

Os nomes das variáveis ​​diferenciam maiúsculas de minúsculas, portanto, myVar, MyVar e myvar são variáveis ​​diferentes. Mas, geralmente, é uma boa prática evitar nomear variáveis ​​de forma tão semelhante.

# Funções

**As funções JavaScript** são blocos de código reutilizáveis ​​que executam uma tarefa específica, recebendo alguma forma de entrada e retornando uma saída.

Para definir uma função, você deve usar a palavra-chave **function** , seguida de um **name** , seguido de parênteses **( )** . Então você tem que escrever a lógica da função entre colchetes **{}**

Aqui está um exemplo de como escrever uma função em JavaScript:

EXEMPLO

function somaDoisNúmeros(x, y) {  
return x + y;  
}

Há muita coisa acontecendo no exemplo acima, então vamos analisar cada parte individualmente.

-   “Função” é a palavra- **chave** necessária para realmente começar a declarar uma função
    
-   “addTwoNumbers” é o **nome** da função , que é personalizável. Os nomes das funções podem conter letras, números e certos caracteres especiais, assim como [as variáveis](https://www.javascript.com/learn/variables) .
    
-   (x, y) são **parâmetros** , que são nomes de variáveis ​​para as entradas que a função aceitará. Esses parâmetros também são chamados de **argumentos.**
    
-   “Return” é a palavra- **chave** que sai da função e compartilha um valor opcional fora
    
-   O código que a função irá executar deve ser colocado entre chaves **{}**
    

## Usando funções

Uma vez que uma função JS é definida (declarada), você pode usá-la referenciando seu nome com parênteses ( ) logo após. Observe que uma função _não_ _precisa_ ter parâmetros - eles podem simplesmente ser deixados em branco entre parênteses:

EXEMPLO

function saudarOPlaneta() {  
return "Olá mundo!";  
}  
​greetThePlanet  
();

SAÍDA

"Olá Mundo!"

Pode haver zero, um ou vários argumentos em uma função. No exemplo acima, a função "greetThePlanet" simplesmente retorna a frase "Hello World!", e não requer nenhum parâmetro (argumento) para isso.

No entanto, se uma função _tiver_ parâmetros, você precisará fornecer valores dentro dos parênteses ao usar a função:  

EXEMPLO

function quadrado(numero) {  
return numero * numero;  
}  
​quadrado  
(16);

SAÍDA

256

No exemplo acima, você deve fornecer um número dentro dos parênteses para que a função funcione e receba uma saída adequada. Caso contrário, seu código não funcionará e você receberá uma mensagem de erro.

Se sua função receber mais de um argumento, basta separá-los com uma vírgula dentro dos parênteses. Você pode consultar a função "addTwoNumbers" na parte superior desta página para obter um exemplo.

## Por que usar funções JS?

As funções são ótimas para eficiência - você pode defini-las uma vez e usá-las várias vezes, conforme necessário. Você não precisa reescrever o mesmo código ou código semelhante repetidamente. As funções JavaScript também permitem que você insira diferentes entradas, ou argumentos, para obter resultados diferentes, com base nas informações com as quais está trabalhando. O uso de funções JavaScript economiza muito tempo e torna seu código menos complicado.

# CONDICIONAIS JAVASCRIPT

As instruções condicionais controlam o comportamento em JavaScript e determinam se partes de código podem ou não ser executadas.

Existem vários tipos diferentes de condicionais em JavaScript, incluindo:

-   Instruções “If”: onde se uma condição for verdadeira é usada para especificar a execução de um bloco de código.
-   Instruções “Else”: onde se a mesma condição for falsa especifica a execução de um bloco de código.  
    
-   Instruções “Else if”: especifica um novo teste se a primeira condição for falsa.

Agora que você tem as definições básicas de instruções condicionais do JavaScript, vamos mostrar exemplos de cada uma.

**// **[Aprenda a se tornar um desenvolvedor web com habilidades da Pluralsight](https://www.pluralsight.com/career/web-developer)****  

## Exemplo de declaração if

Como o tipo mais comum de condicional, a instrução if só é executada se a condição entre parênteses () for [true](https://developer.mozilla.org/en-US/docs/Glossary/Truthy) .

EXEMPLO

if (10 > 5) {  
var resultado = "se bloco";  
}  
​ resultado  
;

SAÍDA

"se bloquear"

Veja o que está acontecendo no exemplo acima:

-   A palavra-chave if diz ao JavaScript para iniciar a instrução condicional.
-   (10 > 5) é a condição a ser testada, que neste caso é verdadeira — 10 é maior que 5.
-   A parte contida entre chaves {} é o bloco de código a ser executado.
-   Como a condição passa, a variável resultado recebe o valor "se bloco".

## Exemplo de declaração Else

Você pode estender uma instrução if com uma instrução else, que adiciona outro bloco para ser executado quando a condicional if não for aprovada.

EXEMPLO

if ("gato" === "cachorro") {  
var resultado = "se bloco";  
} else {  
var resultado = "else bloco";  
}  
resultado;

SAÍDA

"outro bloco"

  
No exemplo acima, "cat" e "dog" não são iguais, então o bloco else é executado e a variável result obtém o valor "else block".  

## Exemplo de instrução Else If

Você também pode estender uma instrução if com uma instrução else if, que adiciona outra condicional com seu próprio bloco.

EXEMPLO

if (false) {  
var resultado = "if bloco";  
} else if (true) {  
var resultado = "else if bloco";  
} else {  
var resultado = "else bloco";  
}  
  
resultado;

SAÍDA

"outra se bloquear"

  
Você pode usar várias condicionais if else, mas observe que apenas o primeiro else if é executado. JavaScript ignora quaisquer condicionais restantes depois de executar a primeira que passa.  

EXEMPLO

if (false) {  
var resultado = "if bloco";  
} else if (true) {  
var resultado = "first else if block";  
} else if (true) {  
var resultado = "segundo else if bloco";  
} else {  
var resultado = "else bloco";  
}  
​ resultado  
;

SAÍDA

"primeiro senão se bloquear"

  
Uma instrução else if não precisa de uma instrução else seguinte para funcionar. Se nenhuma das condições if ou if forem aprovadas, o JavaScript avança e não executa nenhum dos blocos condicionais de código.  

EXEMPLO

if (false) {  
var resultado = "if bloco";  
} else if (false) {  
var resultado = "else if bloco";  
}  
​ resultado  
;

SAÍDA

"primeiro senão se bloquear"

## Arrays

**Matrizes** são valores semelhantes a contêineres que podem conter outros valores. Os valores dentro de um array são chamados de elementos.  

EXEMPLO

var café da manhã = ["café", "croissant"];  
café da manhã;

SAÍDA

["café", "croissant"]

Os elementos da matriz não precisam ser todos do mesmo tipo de valor. Os elementos podem ser qualquer tipo de valor JavaScript — até mesmo outros arrays.  

EXEMPLO

var miscelânea = [100, "pintar", [200, "pincel"], false];  
mistura;

SAÍDA

[100, "pintar", [200, "pincel"], falso]

####   
Acessando elementos

  
Para acessar um dos elementos dentro de um array, você precisará usar os colchetes e um número como este: myArray[3]. Arrays JavaScript começam em 0, então o primeiro elemento sempre estará dentro de [0].

EXEMPLO

var irmãs = ["Tia", "Tamera"];  
irmãs[0];

SAÍDA

"Tia"

Para obter o _último elemento,_ você pode usar colchetes e '1' a menos que a propriedade length do array.

EXEMPLO

var atores = ["Felicia", "Nathan", "Neil"];  
atores[atores.comprimento - 1];

SAÍDA

"Neil"

Isso também funciona para definir o valor de um elemento.

EXEMPLO

var cores = ["vermelho", "yelo", "azul"];  
cores[1] = "amarelo";  
cores;

SAÍDA

["vermelho", "amarelo", "azul"]

####   
Propriedades e métodos

Os arrays têm suas próprias variáveis ​​e funções internas, também conhecidas como **propriedades** e **métodos** . Aqui estão alguns dos mais comuns.

**length**  
A propriedade length de um array armazena o número de elementos dentro do array.

EXEMPLO

["a", "b", "c", 1, 2, 3]. comprimento;

SAÍDA

6

**  
concat**  
O método concat de um array retorna um novo array que combina os valores de dois arrays.

EXEMPLO

["tortilla chips"].concat(["salsa", "queso", "guacamole"]);

SAÍDA

["tortilla chips", "salsa", "queso", "guacamole"]

**  
pop**  
O método pop de um array remove o último elemento do array e retorna o valor desse elemento.

EXEMPLO

["Júpiter", "Saturno", "Urano", "Netuno", "Plutão"].pop();

SAÍDA

"Plutão"

**  
push**  
O método push de um array adiciona um elemento ao array e retorna o comprimento do array.

EXEMPLO

["João", "Kate"].push(8);

SAÍDA

3

**  
reverse**  
O método reverse de um array retorna uma cópia do array na ordem oposta.

EXEMPLO

["a", "b", "c"].reverse();

SAÍDA

["c", "b", "a"]

# Objetos

Objetos JavaScript são melhor explicados pensando em um objeto do mundo real. Pegue um carro, por exemplo. Existem carros de todas as formas e tamanhos - cores diferentes, marcas e modelos diferentes, pesos diferentes, etc. Cada carro tem essas propriedades, mas os valores são diferentes de um carro para outro. Um Ford Focus vermelho e um Honda Civic azul são ambos “carros”, mas são marcas, modelos e cores diferentes.

Objetos JavaScript são variáveis ​​que contêm vários **valores** de dados . Os valores dentro de um objeto JS são conhecidos como **propriedades** . Objetos usam **chaves** para nomear valores, assim como é feito com variáveis.

Vejamos outro exemplo. Desta vez vamos pensar em um curso que você tem que fazer. O nome do curso é “GRA 2032”, começa às 8h e termina às 10h. Veja como transformaríamos isso em um objeto em JavaScript:

EXEMPLO

var curso = {  
nome: "GRA 2032",  
início: 8,  
fim: 10  
};

Os valores de objetos JavaScript são escritos no formato **nome:valor** e os diferentes pares são separados por vírgulas. Os pares nome:valor não precisam estar em linhas diferentes para que o código funcione, mas é muito mais fácil ler e entender o código formatando-o dessa maneira. Você também deve usar as chaves de abertura e fechamento **{}** ao definir seus objetos

Existem duas maneiras de acessar o valor de uma propriedade de objeto. Você pode usar a notação de ponto com o nome da propriedade após o ponto - _objectName.propertyName_ como no exemplo abaixo:

EXEMPLO

var curso = {  
nome: "GRA 2032",  
início: 8,  
fim: 10  
};  
​curso.nome  
;

SAÍDA

"GRA 2032"

Ou você pode usar a notação de colchetes com o nome da propriedade dentro de uma string entre colchetes - _objectName[“propertyName”]_ como no exemplo abaixo:

EXEMPLO

var curso = {  
nome: "GRA 2032",  
início: 8,  
fim: 10  
};  
​curso  
["nome"];

SAÍDA

"GRA 2032"

Para alterar o valor de uma propriedade em um objeto JS existente, você pode usar uma opção muito semelhante ao acessar o valor. Você pode usar a notação de ponto:

EXEMPLO

var character = {  
name: "Donna",  
hair: "red"  
};  
​character.hair  
= "loiro";  
​character  
;

SAÍDA

{  
"nome": "Donna",  
"cabelo": "loira"  
}

Ou a notação de colchetes:

EXEMPLO

var caractere = {  
nome: "Donna",  
cabelo: "vermelho"  
};  
character["cabelo"] = "loiro";  
  
personagem;  

SAÍDA

{  
"nome": "Donna",  
"cabelo": "loira"  
}

Os objetos também podem conter funções, que são chamadas de **métodos** . Métodos são apenas a palavra para funções quando são armazenados como uma propriedade dentro de um objeto JavaScript. Por exemplo, se você tem um objeto “person”, com as propriedades de “firstName” e “lastName”, mas quer uma propriedade para “fullName”, você pode criar um **método** que irá somar o nome e o sobrenome juntos para você e devolver o nome completo como propriedade. Veja o exemplo abaixo:

EXEMPLO

var pessoa= {  
firstName: "Jack",  
lastName: "Smith",  
fullName: function () {  
return this.firstName + " " + this.lastName;  
}  
};  
  
pessoa.nomecompleto();  
  

SAÍDA

"Jack Smith"  

Você pode acessar um método de maneira muito semelhante a acessar as outras propriedades - _objectName.methodName()_ ou seja, pessoa.fullName()

