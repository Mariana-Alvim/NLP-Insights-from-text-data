# **Insights de dados de texto com NLP**
## Modelagem de tópicos, extração de keywords e recomendação de artigos
&nbsp;

Alguns recursos possibilitam acesso eficiente à informação e leitura rápida da abordagem de um texto. O objetivo desse estudo é propiciar acesso à informação focado aplicando técnicas de NLP em um banco de artigos. Para tal, o estudo foi separado em diferentes etapas:     

1. Classificação de artigos por tópicos
2. Extração de palavras chaves de um artigo
3. Recomendação artigos relacionados


&nbsp;

<u> Sobre o dataset: </u>

O conjunto de dados original nomeado "NIPS Paper" é do Kaggle, disponível pelo link:

https://www.kaggle.com/datasets/benhamner/nips-papers?resource=download&select=paper_authors.csv  


O Neural Information Processing Systems (NIPS) é uma das principais conferências de Machine Learning mundiais. 
O dataset contém os títulos, resumos, textos completos e anos de todos os artigos do NIPS publicados de 1987 a 2017. Ao todo são 7240 artigos.

Uma vez que o intuito é compreender o conceito das técnica e usar o texto completo do artigo para modelagem NLP poderia ser computacionalmente demandante, foram utilizados apenas 3500 caracteres de cada texto. Vale ressaltar que o mesmo código pode ser utilizado nos textos completos para aprimorar os modelos.

&nbsp;
