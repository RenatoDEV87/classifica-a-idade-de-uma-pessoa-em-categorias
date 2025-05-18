# Crie um programa que classifica a idade de uma pessoa em categorias (criança, adolescente, adulto, idoso) com base no valor fornecido utilizando uma estrutura de controle if-else.

Exercício 02: Classificação de Idade

---

## 📑 Índice

1. [📖 Descrição](#descrição)  
2. [💻 Código](#código)  
3. [🚀 Como Executar](#como-executar)   
4. [🛠️ Tecnologias Utilizadas](#tecnologias-utilizadas)  
5. [📜 Licença](#licença)  

---

## Descrição

Este exercício recebe a idade de uma pessoa digitada pelo usuário e classifica em categorias: criança, adolescente, adulto ou idoso.
A classificação é feita utilizando uma estrutura de controle condicional `ìf-else` para verificar em qual faixa a idade se enquadra e exibir a categoria correspondente no console. 

---

## Código

Abaixo está o código-fonte do programa:

```JavaScript
const prompt = require('prompt-sync')();

let idade = prompt("Digite a sua idade: ");
idade = parseInt(idade);

if (isNaN(idade) || idade < 0) {
  console.log("Por favor, digite uma idade válida.");
} else {
  if (idade <= 12) {
    console.log("Você é uma criança.");
  } else if (idade <= 17) {
    console.log("Você é um adolescente.");
  } else if (idade <= 59) {
    console.log("Você é um adulto.");
  } else {
    console.log("Você é um idoso.");
  }
}

```

---

## Como Executar

🛠️ Instruções para executar localmente

1. Instale o Node.js se ainda não tiver: https://nodejs.org

2. Abra o terminal e instale o prompt-sync (usado para entrada do usuário):

```
npm install prompt-sync
```

3. Salve o arquivo como `exercicio_02.js` e execute com:

```
node exercicio_01.js
```

---

## Tecnologias Utilizadas

- Linguagem: JavaScrpit
- Node.Js

---

## Licença

Este projeto está licenciado sob a MIT License.

