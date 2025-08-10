# 📈 Análise do Preço da Gasolina por Dia
Este projeto realiza uma análise visual do preço da gasolina ao longo de diversos dias, utilizando bibliotecas poderosas de visualização em Python, como matplotlib e seaborn.

📂 Arquivos
gasolina.csv: Arquivo de entrada contendo os dados de venda da gasolina.

gasolina.png: Gráfico gerado com os dados do arquivo CSV.

gasolina.py: Arquivo Python com o código completo que realiza a análise.

📊 O que o código faz
Importa bibliotecas:

pandas para manipulação de dados.

matplotlib.pyplot e seaborn para visualização gráfica.

Lê o arquivo gasolina.csv com os dados de vendas por dia.

Gera um gráfico de linha:

Eixo X: dias (coluna dia).

Eixo Y: preço da gasolina (coluna venda).

Os pontos são marcados com círculos para facilitar a visualização de variações pontuais.

Personaliza o gráfico:

Título: "Preço da Gasolina por Dia".

Estilo visual limpo usando whitegrid.

Layout ajustado automaticamente com tight_layout().

Exporta a imagem do gráfico (gasolina.png) e salva o código usado em um arquivo .py (gasolina.py).

🧠 Insight gerado pelo gráfico
A visualização do preço da gasolina por dia permite:

Identificar tendências: aumento ou queda do preço ao longo do tempo.

Detectar anomalias ou picos: variações bruscas que podem indicar eventos externos (ex: mudanças no mercado, impostos, etc).

Facilitar a tomada de decisões: útil para motoristas, gestores de frota, ou análises econômicas.
