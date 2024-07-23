# Projeto Taxi Corrida Maluca - Previsão de Demanda de Táxi

![Taxi](/img/taxi.png)

## Índice

1. [Como usar](#1-como-usar)
2. [Sobre o Projeto](#2-sobre-o-projeto)
    - [Objetivo do Projeto](#objetivo-do-projeto)
    - [Instruções do Projeto](#instruções-do-projeto)
    - [Descrição dos Dados](#descrição-dos-dados)
    - [Avaliação do Projeto](#avaliação-do-projeto)

## 1. Como usar

- Primeiramente, instale todas as dependências do projeto rodando no terminal o comando:

    ```bash
    pip install -r requirements.txt
    ```

- O arquivo [taxi.ipynb](taxi.ipynb) contém os códigos utilizados para a conclusão do projeto.
- O dataset do projeto pode ser encontrado na pasta [dataset](./datasets/). 

## 2. Sobre o Projeto

A empresa Taxi Corrida Maluca está buscando aumentar a eficiência de seus serviços durante os horários de pico nos aeroportos. Para isso, coletou dados históricos sobre pedidos de táxi e deseja prever a quantidade de pedidos para a próxima hora.

### Objetivo do Projeto

O objetivo principal é construir um modelo de previsão de demanda de táxi que seja capaz de prever com precisão o número de pedidos para a próxima hora. A métrica REQM no conjunto de teste não deve exceder 48.

### Instruções do Projeto

O projeto envolve as seguintes etapas:

1. **Preparação dos Dados:** Faça o download dos dados e faça uma nova amostragem com uma hora de diferença. Em seguida, analise os dados para compreender suas características e tendências.

2. **Treinamento de Modelos:** Treine diferentes modelos de previsão com diferentes hiperparâmetros. Reserve 10% do conjunto de dados inicial como amostra de teste.

3. **Teste dos Modelos:** Avalie o desempenho dos modelos usando a amostra de teste e forneça conclusões sobre os resultados obtidos.

### Descrição dos Dados

Os dados são armazenados no arquivo `/datasets/taxi.csv`. [Clique aqui para baixar o conjunto de dados](https://practicum-content.s3.us-west-1.amazonaws.com/datasets/taxi.csv). O número de pedidos está na coluna `num_orders`.

### Avaliação do Projeto

A avaliação do projeto inclui critérios como:

- Seguir as instruções fornecidas
- Preparação adequada dos dados
- Consideração de diferentes modelos e hiperparâmetros
- Organização do código e das conclusões
- Manutenção da estrutura do projeto e limpeza do código

Com essas diretrizes, desejo sucesso em seu projeto! Estou aqui para oferecer suporte adicional, se necessário. Boa sorte!
