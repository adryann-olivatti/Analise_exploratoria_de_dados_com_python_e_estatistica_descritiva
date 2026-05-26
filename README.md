# 📊 Análise Exploratória de Dados: Produtividade e Perfil de Funcionários

Este repositório contém o projeto prático desenvolvido para a disciplina de **Fundamentos de Estatística Descritiva**. O objetivo principal do estudo foi realizar uma análise exploratória de dados (AED) para investigar o perfil de 230 funcionários de uma organização e identificar quais fatores estão mais associados à alta produtividade no ambiente de trabalho.

---

## 🎯 Objetivos do Projeto

- **Binarização de Dados:** Classificar os colaboradores em grupos de "Alta" e "Baixa" produtividade com base na mediana geral do conjunto de dados.
- **Classificação de Variáveis:** Identificar e categorizar as variáveis do banco de dados em quantitativas (discretas/contínuas) e qualitativas (nominais/ordinais).
- **Análise Univariada:** Construir tabelas de frequência e gráficos para entender a distribuição demográfica e operacional dos funcionários.
- **Análise Bivariada (Associação):** Investigar cruzamentos entre produtividade e fatores como carga horária, satisfação, tempo de empresa, treinamentos e regime de trabalho (Home Office).

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

O projeto foi inteiramente desenvolvido em **Python** dentro do ambiente do Google Colab, utilizando as seguintes ferramentas:

* **Pandas:** Para manipulação, filtragem e tratamento da base de dados.
* **NumPy:** Para operações matemáticas e binarização de variáveis.
* **Matplotlib & Seaborn:** Para a criação de visualizações estatísticas (gráficos de barras e boxplots).

---

## 📈 Principais Descobertas da Análise

Com base nas evidências obtidas através dos gráficos e tabelas descritivas, destacam-se os seguintes pontos:
* **Horas Trabalhadas:** Apresentou a associação mais forte com a produtividade. Funcionários do grupo de alta produtividade registram uma jornada semanal consideravelmente maior.
* **Capacitação:** O grupo de alta produtividade possui maior concentração de cursos realizados, sugerindo o impacto positivo do treinamento técnico.
* **Satisfação e Tempo de Casa:** Curiosamente, estas variáveis apresentaram distribuições quase idênticas entre os grupos, indicando baixa associação direta com a produtividade nesta amostra.

---

## 📂 Estrutura do Repositório

* `TrabalhoFundamentos.ipynb`: Notebook Jupyter contendo todo o código-fonte desenvolvido, comentários explicativos e as respostas teóricas finais.

---

## 💡 Como Executar o Projeto

Você pode visualizar e rodar o código diretamente no seu navegador:

1. Clique no botão azul `Open in Colab` que aparece no topo do arquivo `.ipynb` deste repositório.
2. Certifique-se de executar todas as células (`Ambiente de execução > Executar tudo`) para carregar a base de dados pública e gerar as visualizações automaticamente.
