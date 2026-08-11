<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=700&lines=An%C3%A1lise+de+Livros+Mais+Vendidos+%F0%9F%93%9A;Explorando+dados+com+Python+%26+Pandas;EDA+%7C+Limpeza+de+Dados+%7C+Visualiza%C3%A7%C3%A3o;Transformando+dados+em+decis%C3%B5es)

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

---

## 📚 Sobre o projeto

Análise exploratória de dados (EDA) sobre os livros mais vendidos da história, cobrindo autoria, idioma original, ano de publicação, gênero e volume de vendas. O projeto passa pelas etapas principais de um fluxo de análise de dados: inspeção inicial, tratamento de valores ausentes e geração de visualizações para entender padrões de sucesso editorial ao longo do tempo.

**Dataset:** 174 registros, 6 variáveis (livro, autor(es), idioma original, ano de publicação, vendas aproximadas em milhões e gênero).

## 🎯 Objetivo

Responder perguntas como:
- Quais são os 10 livros mais vendidos da história?
- Existe relação entre o ano de publicação e o volume de vendas?
- Como as vendas se distribuem entre os diferentes gêneros literários?

## 🛠️ Tecnologias utilizadas

- **Python**
- **Pandas** — manipulação, limpeza e agregação dos dados
- **Matplotlib** e **Seaborn** — visualização de dados
- **Jupyter Notebook** — ambiente de desenvolvimento

## 🔍 Principais insights

- A coluna `Genre` apresentava valores ausentes em cerca de 32% dos registros, tratados com preenchimento (`fillna`) para não perder livros na análise
- O ranking dos 10 livros mais vendidos foi construído com `nlargest`, evidenciando os títulos com maior alcance editorial de todos os tempos
- A dispersão entre ano de publicação e vendas (colorida por gênero) ajuda a visualizar se best-sellers recentes vendem tanto quanto os clássicos mais antigos
- O dataset reúne obras em múltiplos idiomas originais, o que abriu espaço para investigar sucesso editorial além do mercado de língua inglesa

## ▶️ Como executar

```bash
# Clone o repositório
git clone https://github.com/DaviBaruch/Analise-livros.git

# Instale as dependências
pip install pandas matplotlib seaborn

# Execute o notebook
jupyter notebook analise_livros.ipynb
```

## 👤 Autor

**Davi Baruch Gutierrez Varas**
Estudante de Engenharia da Computação (FIAP) — foco em Data Science, Data Engineering e IA

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/davi-baruch-gutierrez-varas-451610272/)
