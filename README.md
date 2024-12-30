# 📊 Economic Data Analysis Project via Federal Reserve Economic Data (FRED)

# Spotify Streaming Insights: Análise e Previsão de Tendências Musicais

<p align="center">
  <a href="https://github.com/Edu-png">
    <img src="https://img.shields.io/badge/Autor-Eduardo%20Coqueiro-purple?style=flat&logo=github" alt="Autor">
  </a>
  <a href="mailto:eduardocoqueiro@gmail.com">
    <img src="https://img.shields.io/badge/Email-eduardocoqueiro%40gmail.com-purple?style=flat&logo=gmail" alt="Email">
  </a>
  <a href="https://linkedin.com/in/eduardocoqueiro/">
    <img src="https://img.shields.io/badge/LinkedIn-Eduardo%20Coqueiro-purple?style=flat&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="https://kaggle.com/EduardoCoqueiro">
    <img src="https://img.shields.io/badge/Kaggle-Eduardo%20Coqueiro-blue?style=flat&logo=kaggle" alt="Kaggle">
  </a>
</p>

![CAPAS - PROJETOS](https://github.com/user-attachments/assets/df1f4625-03e5-4f76-9e0a-1428c3215b7d)

## Sumário 🎯

1. [Resumo 📄](#resumo-📄)
2. [Introdução 🌍](#introdução-🌍)
3. [Pipeline do Projeto 🛠️](#pipeline-do-projeto-🛠️)
4. [Métodos 🧪](#métodos-🧪)
5. [Resultados e Conclusões 📈](#resultados-e-conclusões-📈)
   - [Evolução do S&P 500](#1-evolução-do-sp-500)
   - [Taxas de Desemprego nos Estados Unidos](#2-taxas-de-desemprego-nos-estados-unidos)
   - [Comparação entre Desemprego e Participação na Força de Trabalho](#3-comparação-entre-desemprego-e-participação-na-força-de-trabalho)
   - [Correlação entre Taxa de Participação e Desemprego](#4-correlação-entre-taxa-de-participação-e-desemprego)
   - [Análise Regional: Estados Unidos](#5-análise-regional-estados-unidos)
   - [Tendências de Longo Prazo](#6-tendências-de-longo-prazo)
6. [Considerações Finais 📝](#considerações-finais-📝)
   - [Aprendizados-Chave](#aprendizados-chave)
   - [Reflexões](#reflexões)
   - [Próximos Passos](#próximos-passos)
7. [Referências 📚](#referências-📚)
8. [Documentação 📚](#documentação-📚)
9. [Agradecimentos 👏](#agradecimentos-👏)

## Resumo 📄

Este projeto utiliza dados econômicos da plataforma FRED (Federal Reserve Economic Data) para praticar habilidades de análise, desde a coleta e limpeza de dados até a criação de visualizações. Focado em indicadores como o S&P 500, taxas de desemprego e participação na força de trabalho, o projeto explora o impacto de eventos como a pandemia de COVID-19, fornecendo insights valiosos sobre padrões econômicos.


## Introdução 🌍

Este projeto foi inspirado no vídeo do canal [YouTube](https://www.youtube.com/watch?v=R67XuYc9NQ4&t=14s) e utiliza dados da plataforma americana [FRED (Federal Reserve Economic Data)](https://fred.stlouisfed.org/). O objetivo principal é praticar habilidades de coleta, limpeza e exploração de dados econômicos, aplicando técnicas modernas para extrair insights valiosos sobre indicadores econômicos.

Com o uso da API da FRED, os dados analisados incluem:
- O índice **S&P 500**, representando grandes empresas do mercado americano.
- **Taxas de desemprego estaduais** e variações regionais.
- **Taxas de participação na força de trabalho**, refletindo a inclusão da população no mercado de trabalho.

A análise explora o impacto de eventos econômicos como a pandemia de COVID-19, combinando visualizações e correlações para destacar padrões relevantes.

## Pipeline do Projeto 🛠️

1. **Coleta de Dados**: Extração de informações econômicas via API da FRED, incluindo indicadores como S&P 500, desemprego e participação no trabalho.
2. **Limpeza de Dados**: Tratamento de valores nulos e organização para análises consistentes.
3. **Análise Exploratória**: Criação de gráficos e visualizações para identificar padrões e tendências econômicas.
4. **Geração de Insights**: Avaliação do impacto de eventos econômicos, como a pandemia, sobre os indicadores.
5. **Conclusões**: Identificação de relações entre desemprego e participação, e interpretação de padrões regionais.

## Métodos 🧪

1. **Coleta de Dados:**
   - Uso da API da FRED para acessar dados históricos de indicadores econômicos.
   - Download de séries temporais como S&P 500, taxas de desemprego e participação na força de trabalho.
   - Organização inicial dos dados em DataFrames para processamento.

2. **Limpeza de Dados:**
   - Identificação e remoção de valores nulos e inconsistentes.
   - Padronização de colunas e formatação de datas.
   - Exclusão de dados irrelevantes, como séries redundantes ou incompletas.

3. **Análise Exploratória:**
   - Visualização de séries temporais para entender variações nos indicadores.
   - Comparação entre estados nos EUA, como taxas de desemprego e participação.
   - Identificação de eventos econômicos marcantes, como picos de desemprego.

4. **Criação de Visualizações:**
   - Gráficos de linha e dispersão para identificar tendências e correlações.
   - Análise regional com gráficos de barras e comparativos entre estados.
   - Uso de bibliotecas como `matplotlib` e `plotly` para personalizar gráficos.

5. **Cálculo de Correlações:**
   - Relação entre taxas de participação e desemprego por estado.
   - Criação de DataFrames combinados para facilitar a análise estatística.

6. **Geração de Insights:**
   - Avaliação do impacto da COVID-19 em diferentes estados e setores econômicos.
   - Identificação de padrões regionais que refletem variações econômicas estruturais.

## Resultados e Conclusões 📈

### 1. Evolução do S&P 500
- O gráfico do índice S&P 500 demonstra o desempenho de 2015 a 2024.
- **Observação principal**: Durante a pandemia de COVID-19, houve uma queda abrupta seguida por uma rápida recuperação. Isso evidencia a resiliência do mercado financeiro americano, impulsionado por políticas de estímulo econômico e avanços tecnológicos.

![g1](https://github.com/user-attachments/assets/a3ed8793-e1a1-488d-a09b-e4dbf2558185)

---

### 2. Taxas de Desemprego nos Estados Unidos
- **Análise temporal**: Em maio de 2020, o desemprego atingiu um pico devido à pandemia.
- **Destaques regionais**:
  - Estados como **Nevada** e **Hawaii** apresentaram taxas próximas de 25%, refletindo dependência de setores como turismo.
  - **Nebraska**, **South Dakota** e **North Dakota** tiveram taxas inferiores a 8%, indicando economias mais estáveis.

![g2](https://github.com/user-attachments/assets/9ed5ca1c-f5e7-4c3e-886f-af89ef4b32d7)

---

### 3. Comparação entre Desemprego e Participação na Força de Trabalho
- **Evolução entre 2020 e 2022**:
  - Estados como **California** e **New York** mostram recuperação consistente.
  - Estados como **Wyoming** e **South Dakota** mantiveram estabilidade, indicando menor volatilidade econômica.

![g3](https://github.com/user-attachments/assets/aa4b28bc-c8b3-41f6-90dc-aba81e05e090)

---

### 4. Correlação entre Taxa de Participação e Desemprego
- O gráfico de dispersão evidencia uma **correlação negativa**:
  - Estados com maior taxa de participação na força de trabalho tendem a apresentar taxas de desemprego mais baixas.
  - A correlação sugere que maior inclusão no mercado de trabalho está associada a economias mais robustas.

![g4](https://github.com/user-attachments/assets/1931a301-814b-4da7-bbf1-7c329a70b79d)

---

### 5. Análise Regional: Estados Unidos
- O comportamento dos indicadores varia significativamente por estado.
- **Impactos regionais**:
  - Estados com economia diversificada sofreram menos impactos da pandemia.
  - A recuperação pós-pandemia foi desigual, com setores como turismo e indústria enfrentando desafios específicos.

![g5](https://github.com/user-attachments/assets/a8437f2d-c1a1-4799-a6d7-9bdd30809a3a)

---

### 6. Tendências de Longo Prazo
- O comportamento de longo prazo das taxas de desemprego e participação reforça a importância de políticas econômicas regionais.
- As diferenças entre estados destacam desigualdades estruturais no mercado de trabalho americano.

![g6](https://github.com/user-attachments/assets/71114f0e-55e9-4ae7-a732-bf8761b202ae)

## Considerações Finais 📝

Este projeto forneceu uma visão abrangente sobre os impactos econômicos recentes nos Estados Unidos, utilizando dados confiáveis da plataforma FRED e ferramentas de análise de dados em Python. Abaixo estão os principais aprendizados e reflexões:

### Aprendizados-Chave
1. **Importância da Visualização de Dados**: 
   - Gráficos detalhados permitiram identificar padrões claros, como o impacto da pandemia de COVID-19 nas taxas de desemprego e na recuperação econômica regional.

2. **Análise Regional**:
   - Ficou evidente como diferentes estados enfrentaram os desafios econômicos de formas distintas, dependendo de fatores como dependência de setores específicos e diversificação econômica.

3. **Relações Econômicas**:
   - A correlação negativa entre a taxa de participação na força de trabalho e o desemprego destaca como o fortalecimento do mercado de trabalho pode contribuir para maior estabilidade econômica.

### Reflexões
- **Impactos da Pandemia**:
  - Eventos como a COVID-19 ressaltam a importância de dados em tempo real e análises rápidas para apoiar decisões políticas e econômicas.
  
- **Desigualdades Regionais**:
  - A recuperação econômica desigual aponta a necessidade de políticas regionais específicas para apoiar estados mais afetados.

### Próximos Passos
1. **Aprofundar Análises**:
   - Incorporar outros indicadores econômicos, como inflação e PIB, para enriquecer as conclusões.
2. **Automatização do Pipeline**:
   - Criar scripts automatizados para futuras atualizações de dados e análises contínuas.
3. **Exploração Global**:
   - Expandir a análise para incluir dados econômicos de outros países e identificar tendências globais.

Este projeto demonstra como dados econômicos podem ser explorados para gerar insights práticos e auxiliar na tomada de decisão. Ele também reforça a importância da ciência de dados como ferramenta essencial para analisar cenários complexos e em constante evolução.

## Referências 📚

1. **FRED - Federal Reserve Economic Data**  
   Plataforma oficial de dados econômicos utilizada no projeto para coleta de informações:
   [https://fred.stlouisfed.org/](https://fred.stlouisfed.org/)

2. **Vídeo de Referência no YouTube**  
   Vídeo inspirador que ajudou na concepção deste projeto:  
   [Como explorar dados econômicos com Python](https://www.youtube.com/watch?v=R67XuYc9NQ4&t=14s)

3. **Bibliotecas Utilizadas**  
   - [Pandas](https://pandas.pydata.org/): Manipulação e análise de dados.
   - [Matplotlib](https://matplotlib.org/): Visualização de dados.
   - [Plotly](https://plotly.com/): Gráficos interativos.
   - [FredAPI](https://github.com/mortada/fredapi): Conexão com a API da FRED.

4. **Artigos e Documentações Adicionais**  
   - Documentação oficial da FRED API: [https://fred.stlouisfed.org/docs/api/](https://fred.stlouisfed.org/docs/api/)
   - Estilo de gráficos `fivethirtyeight`: [https://matplotlib.org/stable/gallery/style_sheets/fivethirtyeight.html](https://matplotlib.org/stable/gallery/style_sheets/fivethirtyeight.html)

## Documentação 📚
- **[Notebook da Limpeza dos Dados](link_do_notebook_limpeza)**
- **[Notebook da Análise Exploratória dos Dados](link_do_notebook_eda)**
- **[Notebook das Previsões com Machine Learning](link_do_notebook_ml)**

## Agradecimentos 👏
Agradecimentos especiais ao Spotify por fornecer acesso à sua API e aos desenvolvedores de bibliotecas open-source que tornaram este projeto possível e também ao site Kagle por disponibiliza-los! 

<div align="center">
  <img src="https://github.com/user-attachments/assets/54afb33c-97be-40b6-8c96-0f12852e946f" alt="thank-you" width="500">
</div>

