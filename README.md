Análise de Emissões de Gases de Efeito Estufa (GEE) no Brasil
Este projeto consiste em uma análise exploratória de dados sobre as emissões de gases de efeito estufa no Brasil, abrangendo o período de 1970 a 2021. Utilizando a base de dados do SEEG (Sistema de Estimativas de Emissões e Remoções de Gases de Efeito Estufa), o estudo identifica os principais setores, gases e estados responsáveis pelas emissões no país.
📂 Base de Dados
O ficheiro de dados é demasiado grande para o GitHub. Pode descarregá-lo aqui: [Download Dataset (Google Drive)](https://docs.google.com/spreadsheets/d/1SKkSazDZJSU1HzifAt_jclvQ59Rtl-vN/edit?usp=sharing&ouid=101592218707252029913&rtpof=true&sd=true)

Arquivo referente aos municipios, para a visualização per capita:[Download Dataset (Google Drive)](https://docs.google.com/spreadsheets/d/1CJ1GJgNZw1QF5YYwgS4AJWRbrUcwdiXU/edit?usp=sharing&ouid=101592218707252029913&rtpof=true&sd=true)

📋 Conteúdo do Projeto
O notebook realiza o processamento de uma base de dados complexa e gera visualizações para responder a perguntas fundamentais sobre o impacto ambiental das atividades econômicas:

Limpeza e Tratamento de Dados: Filtragem de tipos de emissão (excluindo remoções e bunkers para análises específicas) e transformação de dados para formato tidy (longo).

Análise Setorial: Divisão das emissões por setores como Agropecuária, Energia, Processos Industriais, Resíduos e Mudança de Uso da Terra.

Evolução Temporal: Visualização da média e soma das emissões ao longo das décadas (1970-2021).

Análise Geográfica: Identificação dos estados brasileiros com maiores índices de emissão.

Emissões Per Capita: Cruzamento de dados de emissão com dados populacionais para entender o impacto por habitante.

🛠️ Tecnologias Utilizadas
Python 3

Pandas: Para manipulação e análise de dados tabulares.

Matplotlib/Plotly: Para criação de gráficos estáticos e interativos.

Google Colab: Ambiente de desenvolvimento utilizado para a execução das análises.

📊 Principais Insights
A partir das visualizações geradas no notebook, é possível observar:

A variação das emissões em setores críticos como "Mudança de Uso da Terra e Floresta".

O ranking de gases (CO2, CH4, N2O, etc.) e seu peso equivalente (CO2e).

A correlação entre atividade econômica estadual e o volume de gases expelidos.

🚀 Como Executar
Dados: O projeto utiliza o arquivo Excel do SEEG (ex: 1-SEEG10_GERAL-BR_UF_2022.10.27-FINAL-SITE.xlsx). Certifique-se de ter o arquivo ou acesso ao link da fonte.

Ambiente: Recomenda-se abrir o arquivo .ipynb no Google Colab.

Dependências: Instale as bibliotecas necessárias caso execute localmente:

Bash

pip install pandas openpyxl matplotlib plotly
📂 Estrutura do Arquivo
EmissõesGases.ipynb: Notebook principal com todo o código de análise e gráficos.

Analysis of Greenhouse Gas (GHG) Emissions in Brazil
This project consists of an exploratory data analysis of greenhouse gas emissions in Brazil, covering the period from 1970 to 2021. Using the SEEG (System for Estimating Greenhouse Gas Emissions and Removals) database, the study identifies the main sectors, gases, and states responsible for emissions in the country.

📋 Project Content
The notebook processes a complex database and generates visualizations to answer fundamental questions about the environmental impact of economic activities:

Data Cleaning and Processing: Filtering emission types (excluding removals and bunkers for specific analyses) and transforming data into a tidy (long) format.

Sectoral Analysis: Breakdown of emissions by sectors such as Agriculture and Livestock, Energy, Industrial Processes, Waste, and Land Use Change.

Temporal Evolution: Visualization of the average and total emissions over the decades (1970-2021).

Geographic Analysis: Identification of Brazilian states with the highest emission levels.

Per Capita Emissions: Merging emission data with population data to understand the impact per inhabitant.

🛠️ Technologies Used
Python 3

Pandas: For tabular data manipulation and analysis.

Matplotlib/Plotly: For creating static and interactive charts.

Google Colab: The development environment used to run the analyses.

📊 Key Insights
From the visualizations generated in the notebook, it is possible to observe:

Fluctuations in emissions within critical sectors like "Land Use Change and Forestry."

Ranking of gases (CO2, CH4, N2O, etc.) and their global warming potential (CO2e).

The correlation between state economic activity and the volume of gas emissions.

🚀 How to Run
Data: The project uses the SEEG Excel file (e.g., 1-SEEG10_GERAL-BR_UF_2022.10.27-FINAL-SITE.xlsx). Ensure you have the file or access to the source link.

Environment: It is recommended to open the .ipynb file in Google Colab.

Dependencies: Install the required libraries if running locally:

Bash

pip install pandas openpyxl matplotlib plotly
📂 File Structure
EmissõesGases.ipynb: Main notebook containing all analysis code and charts.
