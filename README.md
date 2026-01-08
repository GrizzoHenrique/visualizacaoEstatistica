# visualizacaoEstatistica

Projeto: Fundamentos da Descoberta de Dados (Módulo 13)
Este projeto faz parte do curso de Ciência de Dados e tem como foco a aplicação de conceitos estatísticos e visualização de dados em um cenário real de varejo.

📋 Visão Geral
O objetivo principal deste projeto é explorar e analisar uma base de dados de produtos de um supermercado no Chile. Através da análise exploratória, buscamos entender o comportamento dos preços, identificar padrões de descontos e aplicar medidas de tendência central e dispersão para extrair insights valiosos sobre as categorias de produtos.

📊 Dados Utilizados
A base de dados contém as seguintes informações:

title: Nome do produto.

Marca: Marca do fabricante.

Preco_Normal: Preço base do produto sem descontos.

Preco_Desconto: Preço final após aplicação de ofertas.

Preco_Anterior: Preço de referência antes da promoção.

Desconto: Valor total do desconto aplicado.

Categoria: Categoria do produto (em espanhol).

🛠️ Tecnologias e Bibliotecas
As seguintes ferramentas foram utilizadas no desenvolvimento deste projeto:

Python 3

Pandas: Manipulação e tratamento de dados.

Matplotlib: Criação de gráficos estáticos.

Plotly Express: Visualizações interativas e dinâmicas.

🔍 Principais Análises Realizadas
1. Estatísticas por Categoria
Foi realizada a análise da Média e Mediana dos preços normais por categoria.

Destaque Positivo: A categoria comidas-preparadas apresentou média e mediana acima do padrão geral.

Destaque Negativo: A categoria instantaneos-y-sopas apresentou os menores valores médios.

2. Análise de Dispersão e Variabilidade
Cálculo do Desvio Padrão para identificar quais categorias possuem maior variação de preços.

Identificou-se que em categorias com alto desvio, como lacteos, a média sofre forte influência de outliers (valores atípicos), tornando a mediana uma medida mais robusta para representar o centro dos dados.

3. Visualização com Boxplots
Utilização de gráficos de caixa (Boxplot) para visualizar a distribuição dos dados e identificar visualmente a presença de outliers nas categorias mais críticas.

🚀 Como executar o projeto
Clone este repositório.

Certifique-se de ter as bibliotecas instaladas:

Bash

pip install pandas matplotlib plotly
Abra o arquivo Profissao Cientista de Dados M13 Projeto.ipynb em um ambiente Jupyter ou Google Colab.

Certifique-se de que o arquivo CSV da base de dados está no mesmo diretório.
