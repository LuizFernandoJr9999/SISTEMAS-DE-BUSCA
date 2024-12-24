# SISTEMAS-DE-BUSCA

1. Introdução e Conteúdo do Curso
 
O QUE TEM DENTRO DE UM SISTEMA DE BUSCA 

  ETAPA 1

- Coletar os documentos.
- Crawler: inicia com um conjupequeno de textos e em seguida se seguem os links contidos neles para obter outros.

  ETAPA 2

  - Os textos coletados precisam ser indexados.
  - Tabela de documentos e as localizações para todas as palavras diferentes.
  - O índice é uma lits de todas as palavras diferentes, juntamente com os documentos nos quais ela aparece e suas posições nesses docuemntos.
  - Baixar páginas, passá-las pelo indexador e analisá-las para encontrar todos os links para outras páginas.

  ETAPA 3

  - Retornar uma lista de documentos classificados por relevância.
  - Relevância do documento e inter-relação entre as palavras do documento.Retornar os documentos que contém asd palavras é simples, a inteligência está em como os resultados são ordenados.

  ALGORITMOS PARA CLASSIFICAÇÃO DOS TEXTOS

  - Consulta com uma palavra.
  - Consulta com múltiplas palavras.
  - Classificação baseada em conteúdo
      - Frequência de palavras.
      - Posição das palavras no documento.
      - Distância entre as palvras no documento.
  - Classificação pelo texto do link.
  - Links externos (algoritmo PageRank).
 
  PRÉ-REQUISITOS

  - Lógica de programação, principalmente estruturas condicionais e de repetição (if e for).
  - Comandos básicos em Python é desejável, embora seja possível acompanhar o curso sem saber essa linguagem com profundidade.
  - É necessário conhecer comandos SQL básicos (select e insert) - Mysql.
  - Modelo entidade-relacionamento para a construção de base de dados (chaves primárias e estrangeiras).
  - É recomendável que você saiba as principais tags HTML existentes em páginas web, embora seja possível acompanhar o curso sem esse conhecimento.
  - Não sãp necessários conhecimentos prévios sobre Inteligência Artificial.

 O QUE NÃO VEREMOS

 - Bibliotecas para indexação:
   - Whoosh
   - Python Search API
   - PyLucene (Apache Lucene)
 - Interface web para pesquisa

3. INSTALAÇÃO DO ANACONDA

4. CARREGAMENTO DE PÁGINAS WEB COM URLLIB3

Instalar urllib3

- Ir em Anaconda - Anaconda propmpt - instalar: conda install urllib3

- Instalado em c:\Users\LuizF\
 - Abrir a IDE do Spider.
 - Criar pasta - C:\Usuarios\LuizF\Busca em Textos com Python

5. EXTRAÇÃO DE DADOS DE HTML COM BEAUTIFULSOAP

6. CRAWLER - BUSCA DE DOCUMENTOS - PARTE 1

   Está apenas lendo a página e listando todos os links da página.

7. CRAWLER - BUSCA DE DOCUMENTOS - PARTE 2    

  Foi feito o tratamento dos links das páginas relacionadas.
  
8. CRAWLER - BUSCA DE DOCUMENTOS - PARTE 3

9. CRAWLER - BUSCA DE DOCUMENTOS - PARTE 4

10. PRÉ-PROCESSAMENTO DOS TEXTOS - REMOÇÃO DE TAGS HTML

11. INSTALAÇÃO DO MYSQL

12. INDEXAÇÃO - CRIAÇÃO DA BASE DE DADOS

13. INDEXAÇÃO - ENTENDIMENTO DAS TABELAS

14. PRÉ-PROCESSAMENTO DOS TEXTOS - SEPARAÇÃO DAS PALAVRAS

15. 
