
# Sistema de Pedidos - Prática de Arquitetura

Esse projeto foi usado para uma atividade da faculdade, com o objetivo de analisar um sistema já pronto, identificar problemas e aplicar melhorias.

O sistema foi executado localmente para entendimento do funcionamento e realização das alterações.



## Parte 1 – Levantamento

1. Qual é o objetivo do sistema?  
O sistema serve para registrar pedidos de produtos e calcular o valor total da compra.

2. Quais funcionalidades o sistema possui?  
Permite adicionar produtos, informar quantidade, calcular o total, remover itens e finalizar o pedido.

3. Como o usuário interage com o sistema?  
O usuário utiliza uma interface web, selecionando produtos, digitando quantidades e clicando em botões para executar as ações.


## Parte 2 – Funcionalidades

O sistema possui funcionalidades básicas como cadastro de itens, cálculo de valores e exibição dos pedidos em tempo real na tela.


## Parte 3 – Interação

A interação é simples e direta, onde o usuário realiza ações pelos botões e o sistema responde imediatamente mostrando os resultados.

## Parte 4 – Estrutura (UML)

Pedido  
- itens  
- total  
- adicionarItem()  
- removerItem()  

Item  
- produto  
- quantidade  
- subtotal  

Produto  
- nome  
- preco  

## Parte 5 – Problemas encontrados

Foi observado que o código possui pouca organização, misturando várias responsabilidades em um mesmo lugar, o que dificulta a manutenção.

Também foi identificado um problema na exibição dos valores: ao adicionar itens o valor aparece inteiro, mas ao finalizar o pedido aparece com casas decimais (ex: 12 e depois 12,5), mostrando falta de padronização.


## Parte 6 – Melhorias propostas

Melhorar a organização do código, separando melhor as responsabilidades, pois isso facilita o entendimento e manutenção.

Também foi proposta a padronização na exibição dos valores, para evitar diferenças e deixar o sistema mais consistente.

## Parte 7 – Refatoração

Foi realizada uma melhoria na organização do código e ajustada a exibição dos valores utilizando formatação padrão, deixando o sistema mais uniforme.

## Parte 8 – Padrões de Projeto

Foi considerado o uso de padrões como Factory para criação de objetos e Singleton para controle dos dados do sistema.

Esses padrões ajudam a melhorar a organização e evitar duplicação de código.

## Controle de Versão

Durante a atividade foi utilizado Git para:

- Criar uma branch para desenvolvimento  
- Realizar commits com alterações  
- Enviar o código para o GitHub  
- Criar um Pull Request  

## Tecnologias utilizadas

- HTML  
- CSS  
- JavaScript
