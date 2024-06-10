# Aplicação de Lançamento de Compras com Cartão de Crédito

## Descrição do Projeto
Este projeto consiste em uma aplicação Java para lançamento de compras com cartão de crédito. A aplicação permite que o usuário cadastre compras, verifique o saldo do cartão de crédito e ordene a lista de compras por valor.

## Funcionalidades
- **Cadastro de compras com descrição e valor**
- **Verificação do saldo do cartão de crédito**
- **Ordenação da lista de compras por valor**

## Tecnologias Utilizadas
- **Java**
- **Coleções (List, ArrayList)**
- **Ordenação (Collections.sort())**
- **Comparable**

## Como Executar o Projeto
1. Clone o repositório do projeto para sua máquina local.
2. Abra o projeto em sua IDE Java preferida.
3. Compile e execute a classe `Principal.java`.
4. Siga as instruções exibidas no console para interagir com a aplicação.

## Estrutura do Projeto
O projeto é composto pelas seguintes classes:

- **Principal.java**: Classe principal que contém o método `main()` e a lógica de interação com o usuário.
- **Compra.java**: Classe que representa uma compra, contendo informações sobre a descrição e o valor da compra. Essa classe implementa a interface `Comparable` para permitir a ordenação das compras.
- **CartaoDeCredito.java**: Classe que representa um cartão de crédito, contendo informações sobre o limite de crédito e a lista de compras.

## Desafio Implementado
Neste projeto, o principal desafio implementado foi a ordenação da lista de compras por valor. Para isso, foi necessário:

- Implementar a interface `Comparable` na classe `Compra`.
- Definir a regra de ordenação no método `compareTo()` da classe `Compra`, utilizando a classe wrapper `Double` para comparar os valores das compras.
- Utilizar o método `Collections.sort()` para ordenar a lista de compras do cartão de crédito.

## Conclusão
Este projeto demonstra a utilização de coleções, ordenação e a interface `Comparable` em Java. A aplicação desenvolvida permite que o usuário gerencie suas compras com cartão de crédito de forma organizada e eficiente.
