# visualizacaoEstatistica

**Este Exercício tem como principal objetivo praticar os conceitos estatistico aprendidos em aula como média, mediana e desvio padrão em uma base de dados de um supermercado no chile**

## Dados Utilizados
**A base de dados contém as seguintes informações:**

* title: Nome do produto.

* Marca: Marca do fabricante.

* Preco_Normal: Preço base do produto sem descontos.

* Preco_Desconto: Preço final após aplicação de ofertas.

* Preco_Anterior: Preço de referência antes da promoção.

* Desconto: Valor total do desconto aplicado.

* Categoria: Categoria do produto (em espanhol).

## Tecnologias Utilizadas

| Tecnologia | Versão | Propósito |
|-----------|--------|----------|
| ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) | 3.7+ | Linguagem principal |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) | Latest | Manipulação de dados |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white) | Latest | Visualizações |
| ![Jupyter](https://img.shields.io/badge/Jupyter-F37726?logo=jupyter&logoColor=white) | Latest | Ambiente interativo |

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

##  Como Executar

### Pré-requisitos
- Python 3.7+
- pip ou conda

### Instalação

```bash
# Clone o repositório
git clone https://github.com/GrizzoHenrique/visualizacaoEstatistica.git
cd visualizacaoEstatistica

# Crie um ambiente virtual (recomendado)
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt
