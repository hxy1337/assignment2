# About this assignment
## Introduction

With continued economic growth and rising living standards, automobiles have become an increasingly important means of transportation for many households (Dargay, Gately and Sommer, 2007). A higher employment rate typically suggests increased household incomes and greater purchasing power, which may further stimulate the consumption of durable goods such as automobiles (McCarthy, 1996).

However, automobile ownership is not only influenced by economic and employment factors, but also by the specific urban environment, such as the development of city infrastructure and legal or regulatory restrictions. Although it is widely believed that there is a certain correlation between employment rate and automobile ownership, the specific relationship still requires further analysis and validation(Ingram and Liu, 1999).

This study aims to analyse the relationship between employment rate and automobile ownership. By collecting data and applying programming-based statistical methods, we seek to reveal whether there is a significant correlation between the two, thereby providing data-driven references for urban planning and economic policy-making(Zhao, Lu and De Roo, 2011).

## Data

In this study, Leeds, UK, is selected as the sample area. The data used in this research are divided into two categories. The first category is statistical data in CSV format, which were obtained from https://www.nomisweb.co.uk/. From this website, two datasets from the 2021 Census were collected: economic activity status and household car ownership. Among these, data based on LSOA (Lower Layer Super Output Area) will be used for data analysis and for generating non-spatial charts, while data based on MSOA (Middle Layer Super Output Area) will be used for producing spatial maps. In total, there are four CSV files. The reason for using MSOA data for spatial mapping is that there are too many LSOA data points, which would negatively impact visual clarity and interpretation. Therefore, MSOA is selected instead for spatial visualization.

The second category consists of geographic data, which is obtained from https://geoportal.statistics.gov.uk/. Since the MSOA geographic data covers the whole of the UK and the dataset is very large, it was processed to include only the Leeds area and then converted to the GeoJSON format before being uploaded to GitHub.

Economic data：https://www.nomisweb.co.uk/query/construct/summary.asp?mode=construct&version=0&dataset=2083

Car data：https://www.nomisweb.co.uk/query/construct/summary.asp?mode=construct&version=0&dataset=2063

GEO data：https://geoportal.statistics.gov.uk/datasets/12baf1e6a44441208ffe5ba5ed063a68_0/explore

## About code

The main programming technologies used in this study include Python for data processing and analysis, with libraries such as Pandas for data manipulation, NumPy for numerical operations, and Matplotlib and Seaborn for data visualization. For spatial data processing and mapping, GeoPandas was utilised. Additionally, Jupyter Notebook served as the primary environment for code development, documentation, and presentation.

The purpose of the programming in this study is to identify the most suitable variables from the two datasets—employment status and car ownership—that effectively address the research question. The main steps of the programming process include: combining, visualizing, and cleaning the data, followed by data integration and correlation analysis of the variables. Based on this process, the appropriate variables are selected to explain the relationship under investigation. Furthermore, both non-spatial and spatial visualizations are created for the two selected variables.

## Before running

All steps in this study are relatively rigorous, though not highly flexible. Readers do not need to add any extra code—simply clicking “Run” is sufficient to understand the content of this research. Numerous Markdown cells are included, providing the author’s reasoning behind each step, such as specific findings, explanations for data cleaning decisions, or choices made in the visualisation process. However, even without reading these Markdown explanations, the code and its comments are sufficient to convey the overall logic of the workflow.

If readers are interested in exploring similar or other datasets, they can simply follow this template, modifying the file names or variable names as needed, and repeat the entire process to carry out research with different data.

## Acknowledgment
I acknowledge the use of ChatGPT-3.5 and GPT-4.1-mini (OpenAI, https://chat.openai.com/) for learning coding, translating my draft from Chinese to English, and correcting my grammar.

## reference


Ingram, G.K. & Liu, Z. (1999) ‘Determinants of motorization and road provision’. *The World Bank Research Observer.* [online]. 14(2), pp. 287–303. [Accessed 10 May 2025]. Available from:
https://doi.org/10.1093/wbro/14.2.287


McCarthy, P.S. (1996) ‘Market price and income elasticities of new vehicle demand’. *The Review of Economics and Statistics.* [online]. 78(3), pp. 543–547. [Accessed 10 May 2025]. Available from:
https://www.jstor.org/stable/2109793


Zhao, P., Lu, B. & De Roo, G. (2011) ‘The impact of urban growth on travel demand and urban mobility: A case study of Beijing’. *Transportation Research Record.* [online]. 2243(1), pp. 1–8. [Accessed 10 May 2025]. Available from: https://journals.sagepub.com/doi/10.3141/2243-01
