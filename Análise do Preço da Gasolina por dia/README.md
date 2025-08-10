# 📈 Análise do Preço da Gasolina por Dia

Este projeto realiza uma análise visual do preço da gasolina ao longo de diversos dias, utilizando poderosas bibliotecas de visualização em Python, como `matplotlib` e `seaborn`.

---

## 📂 Arquivos do Projeto

- **gasolina.csv**  
  Arquivo de entrada contendo os dados diários de venda da gasolina.

- **gasolina.png**  
  Gráfico gerado a partir dos dados do arquivo CSV, mostrando a evolução do preço.

- **gasolina.py**  
  Código Python completo que realiza a análise e gera o gráfico.

---

## 📊 Funcionalidades do Código

- Importa bibliotecas essenciais:  
  - `pandas` para manipulação e análise dos dados.  
  - `matplotlib.pyplot` e `seaborn` para criação e customização dos gráficos.

- Lê o arquivo `gasolina.csv`, que contém o preço da gasolina por dia.

- Gera um gráfico de linha:  
  - **Eixo X:** dias (coluna `dia`).  
  - **Eixo Y:** preço da gasolina (coluna `venda`).  
  - Pontos destacados com círculos para facilitar a visualização das variações pontuais.

- Personaliza o gráfico com:  
  - Título: "Preço da Gasolina por Dia".  
  - Estilo visual limpo usando `seaborn` no modo `whitegrid`.  
  - Layout ajustado automaticamente para melhor visualização.

- Exporta o gráfico como imagem (`gasolina.png`) para fácil compartilhamento e apresentação.

---

## 🧠 Insights e Aplicações

Este gráfico possibilita:

- **Identificar tendências** de aumento ou queda do preço da gasolina ao longo do tempo.  
- **Detectar anomalias ou picos**, indicando possíveis eventos externos, como variações de mercado ou alterações tributárias.  
- **Auxiliar na tomada de decisões** para motoristas, gestores de frota, analistas econômicos e demais interessados em acompanhar a evolução dos preços.

---
