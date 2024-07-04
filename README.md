# Resolução dos desafios do curso de lógica de programação

Praticar lógica de programação, incluindo variáveis, condicionais, loops e interações com o usuário, é crucial para uma carreira em desenvolvimento de software. Esses fundamentos ajudam a resolver problemas de forma estruturada, 
tomar decisões no código, criar iterações controladas e interagir eficazmente com os usuários. Entender esses conceitos facilita o aprendizado de novas tecnologias, 
permite criar soluções inovadoras, depurar código e manter a qualidade do software. Investir nesses princípios desde cedo é essencial para construir uma base sólida na programação.

#### Desafios - Respostas

1) Crie um programa que utilize o `console.log` para exibir uma mensagem de Seja bem vindo.

```js
console.log('Seja bem vindo');
```

2) Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o console.log para exibir a mensagem "Olá, [seu nome]!" no console do navegador.

```js
let nome = 'Danni Nascimento';
console.log(`Olá, ${nome}!`);
```

3) Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o `alert` para exibir a mensagem "Olá, [seu nome]!".

```js
let nome = 'Danni Nascimento';
alert(`Olá, ${nome}!`);
```

4) Utilize o `prompt` e faça a seguinte pergunta: `Qual  a linguagem de programação que você mais gosta?`. Em seguida, armazene a resposta em uma variável e mostre no console do navegador.

```js
let linguagemFavorita = prompt('Qual  a linguagem de programação que você mais gosta?');
console.log("Sua linguagem de programação favorita é: " + linguagemFavorita + "!");
```

5) Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console.

```js
let valor1 = 9;
let valor2 = 10;
let resultado = valor1 + valor2;

console.log(`A soma de ${valor1} e ${valor2} é igual a ${resultado}.`)
```

6) Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console.

```js
let valor1 = 9;
let valor2 = 10;
let resultado = valor1 + valor2;

console.log(`A diferença entre ${valor1} e ${valor2} é igual a ${resultado}.`);
```

7)  Peça ao usuário para inserir sua idade com prompt. Com base na idade inserida, utilize um if para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console.

```js 
let idade = prompt("Qual a sua idade?");
if (idade >= 18) {
    console.log("Você é maior de idade.");
} else {
    console.log("Você é menor de idade.");
}
```

8) Crie uma variável "numero" e peça um valor com `prompt` verifique se é positivo, negativo ou zero. Use if-else para imprimir a respectiva mensagem.

```js
let numero = prompt("Insira um número:");

if (numero > 0) {
    console.log("O número é positivo.");
} else if (numero < 0) {
    console.log("O número é negativo.");
} else {
    console.log("O número é zero.");
}
```

9) Use um loop while para imprimir os números de 1 a 10 no console.

```js
let i = 1;
while (i <= 10) {
    console.log(i);
    i++;
}
```

10) Crie uma variável "nota" e atribua um valor numérico a ela. Use if-else para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console.

```js
let nota = 8; // coloqu aqui  valor da nota do aluno
if (nota >= 7) {
    console.log("Aprovado");
} else {
    console.log("Reprovado");
}

```

11) Use o `Math.ramdon` para gerar qualquer número aleatório e exiba esse número no console.

```js 
let numeroAleatorio = Math.random();
console.log("Número aleatório: " + numeroAleatorio);

```

12) Use o `Math.ramdon` para gerar um número inteiro entre 1 e 10 e exiba esse número no console.

```js
let numeroAleatorio = Math.floor(Math.random() * 10) + 1;
console.log("Número aleatório entre 1 e 10: " + numeroAleatorio);

```


13) Use o `Math.ramdon` para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.

```js
let numeroAleatorio = Math.floor(Math.random() * 1000) + 1;
console.log("Número aleatório entre 1 e 1000: " + numeroAleatorio);

```
