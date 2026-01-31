Data Salary Dashboard 🎲

Este repositório contém uma aplicação interativa (Dashboard) desenvolvida para analisar a remuneração global na área de ciência de dados. O projeto utiliza os dados tratados durante a Imersão de Dados da Alura (2026) para fornecer insights visuais e dinâmicos.

🔗 Demonstração

O dashboard foi construído com a biblioteca Streamlit e permite filtrar informações em tempo real.

🛠️ Funcionalidades e Filtros

A aplicação permite que o usuário refine a busca através de:

• Ano: Comparação entre diferentes períodos.

• Senioridade: Níveis Junior (EN), Pleno (MI), Sênior (SE) e Executivo (EX).

• Tipo de Contrato: Full-time, Part-time, Freelance ou Contrato.

• Tamanho da Empresa: Pequena (S), Média (M) ou Grande (L).

📊 Visualizações Incluídas

O dashboard apresenta 4 indicadores principais (KPIs) e 4 gráficos dinâmicos:

• Métricas Gerais: Salário médio, valor máximo, total de registros e cargo mais frequente.

• Top 10 Cargos: Gráfico de barras horizontais com as maiores médias salariais.

• Distribuição Salarial: Histograma para entender a frequência das faixas de renda.

• Tipos de Trabalho: Gráfico de rosca mostrando a proporção entre Remoto, Híbrido e Presencial.

• Mapa Global: Mapa coroplético mostrando a média salarial especificamente para Data Scientists ao redor do mundo.

🗂️ Estrutura de Arquivos

• app.py: O código principal da aplicação Streamlit.

• dados-imersao-final.csv: Base de dados tratada e utilizada pelo dashboard.

• requirements.txt: Lista de bibliotecas necessárias para rodar o projeto.

🛠️ Tecnologias Utilizadas

• Python

• Streamlit (Interface do Dashboard)

• Pandas (Tratamento de Dados)

• Plotly Express (Gráficos Interativos)
