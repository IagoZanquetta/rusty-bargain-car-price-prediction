# rusty-bargain-car-price-prediction
Projeto de machine learning para prever preços de carros usados da Rusty Bargain com comparação entre desempenho, velocidade e qualidade dos modelos.

## Visão Geral

Este projeto tem como objetivo desenvolver modelos de machine learning para prever o preço de carros usados da empresa fictícia **Rusty Bargain**. A análise busca encontrar uma solução que ofereça boa qualidade preditiva sem comprometer o tempo de treinamento e a velocidade de predição.

O projeto considera diferentes algoritmos e compara seus resultados com base em métricas de desempenho e eficiência computacional, apoiando uma escolha mais adequada para uso prático.

## Problema de Negócio

A Rusty Bargain deseja implementar um sistema capaz de estimar o valor de mercado de carros usados com rapidez e boa precisão. Isso é importante para melhorar a experiência dos clientes, apoiar decisões internas e tornar o processo de precificação mais eficiente.

Neste projeto, diferentes modelos são treinados, avaliados e comparados para identificar a melhor alternativa considerando não apenas a qualidade da previsão, mas também o custo computacional.

## Conjunto de Dados

O conjunto de dados contém informações sobre veículos usados, incluindo variáveis relacionadas às características técnicas e comerciais dos automóveis.

Entre os atributos analisados, podem estar informações como:

- tipo de veículo
- marca
- modelo
- ano de registro
- potência
- quilometragem
- tipo de combustível
- transmissão
- tipo de reparo
- data de criação do anúncio
- preço do veículo

O arquivo utilizado no projeto está organizado na pasta `datasets/`:

- `car_data.csv`

## Objetivo do Projeto

Desenvolver um modelo de machine learning capaz de prever o preço de carros usados para a Rusty Bargain, equilibrando qualidade preditiva, tempo de treinamento e velocidade de inferência.

## Objetivos da Análise

Este projeto busca responder perguntas como:

- É possível prever com boa precisão o preço de carros usados?
- Qual modelo oferece o melhor equilíbrio entre qualidade e velocidade?
- Quais abordagens são mais adequadas para uso em um cenário real de negócio?
- O ganho de desempenho justifica o custo computacional adicional de modelos mais complexos?

## Etapas do Projeto

O projeto foi desenvolvido nas seguintes etapas:

1. carregamento e inspeção inicial dos dados
2. limpeza e preparação do conjunto de dados
3. tratamento de variáveis categóricas e ausentes
4. separação entre treino e teste
5. treinamento de diferentes modelos
6. comparação de métricas e tempo de execução
7. seleção do modelo final
8. conclusões de negócio

## Ferramentas e Bibliotecas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Estrutura do Repositório

```text
rusty-bargain-car-price-prediction/
├── .gitignore
├── README.md
├── requirements.txt
├── rusty_bargain_car_price_prediction.ipynb
└── datasets/
    └── car_data.csv
````

## Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/IagoZanquetta/rusty-bargain-car-price-prediction.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd rusty-bargain-car-price-prediction
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra o arquivo `rusty_bargain_car_price_prediction.ipynb` no Jupyter Notebook, JupyterLab ou VS Code.

5. Execute as células em ordem.

## Principais Pontos Analisados

Entre os principais focos do projeto, estão:

* preparação dos dados para modelagem
* comparação entre diferentes algoritmos de regressão
* avaliação de qualidade preditiva
* medição de tempo de treinamento e predição
* análise do equilíbrio entre desempenho e custo computacional
* escolha do modelo mais adequado para aplicação prática

## Resultados

Comparação de diferentes algoritmos de regressão e avaliação não apenas da qualidade das previsões, mas também do custo computacional associado. Identificação de uma abordagem mais adequada para uso prático, considerando a necessidade de eficiência em um cenário real de precificação.

O notebook inclui:

* limpeza e preparação dos dados
* modelagem preditiva
* comparação entre diferentes algoritmos
* avaliação por métricas de regressão
* análise de tempo de execução
* escolha do modelo final
* conclusões com foco em negócio

## Conclusão

Este projeto demonstra como técnicas de machine learning podem ser aplicadas para prever preços de carros usados em um contexto de negócio realista. Ao comparar modelos não apenas pela qualidade das previsões, mas também pela eficiência computacional, a análise permite selecionar uma solução mais equilibrada e viável para implementação prática.

## O que foi aprendido

Desenvolvimento e consolidação de habilidades em:
- limpeza e preparação de dados tabulares
- tratamento de variáveis categóricas
- comparação entre modelos de regressão
- avaliação de métricas de erro
- análise conjunta de desempenho e custo computacional

## Melhorias Futuras

Possibilidades de evolução do projeto:
- testar modelos adicionais com gradient boosting mais avançado
- ampliar o ajuste de hiperparâmetros
- incluir análise de importância das variáveis
- avaliar técnicas extras de engenharia de atributos

## Autor

**Iago Zanquetta**
