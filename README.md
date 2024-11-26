
# 🧮 Calculadora de IMC
Este projeto é uma Calculadora de IMC (Índice de Massa Corporal) desenvolvida com React e organizada de maneira modular. A aplicação realiza o cálculo do IMC a partir dos valores de altura e peso fornecidos pelo usuário e apresenta o resultado acompanhado de uma classificação detalhada.

### 📋 Estrutura do Projeto
#### Componentes Principais
#### Button
Um componente reutilizável que encapsula a funcionalidade de botões.
Recebe propriedades dinâmicas como identificador (id), texto exibido no botão (text) e a ação a ser executada (action).
Facilita a criação de botões consistentes e com comportamentos específicos.

#### ImcCalc
Componente responsável pela interface do formulário onde o usuário insere seus dados de altura e peso.
Implementa validações simples para aceitar apenas números e separadores válidos nas entradas.
Inclui botões de ação para calcular o IMC e limpar os campos do formulário.
Trabalha com estados controlados utilizando hooks do React (useState) para gerenciar os valores de entrada dinamicamente.

#### App
Componente principal que gerencia o fluxo entre as diferentes etapas da aplicação:
Exibe o formulário inicial para entrada de dados.
Processa o cálculo do IMC e classifica o resultado.
Alterna para uma tabela de classificação com base nos resultados.
Utiliza estados para armazenar o valor do IMC, a classificação associada e o estilo visual aplicado ao resultado.

### 🔄 Fluxo de Funcionamento

#### Entrada de Dados:

O usuário insere valores de altura e peso no formulário renderizado pelo componente ImcCalc.
Validações garantem que apenas números e separadores válidos sejam aceitos.
Cálculo do IMC:

O botão de cálculo, fornecido pelo componente Button, aciona a função calcImc, que:
Converte os valores de entrada para o formato adequado.
Realiza o cálculo com base na fórmula do IMC: peso / (altura * altura).
Classifica o resultado comparando-o com um conjunto de dados predefinidos.
Exibição do Resultado:

Caso os dados sejam válidos, o resultado do cálculo e a classificação são exibidos, juntamente com a possibilidade de reiniciar o cálculo.
Reinício:

O botão "Limpar" ou "Reiniciar" redefine os estados da aplicação para permitir um novo cálculo.
# 🛠️ Tecnologias Utilizadas
<div style="display: inline_block"><br>
  <img align="center" alt="Rafa-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Rafa-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="Rafa-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Rafa-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Rafa-Nodejs" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original-wordmark.svg" />
>
</div>

