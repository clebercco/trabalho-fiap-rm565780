🌱 Análise Preditiva de Rendimento Agrícola
📋 Sobre o Projeto
Este projeto foi desenvolvido para a FarmTech Solutions como parte de um serviço de consultoria em IA para uma fazenda de médio porte (200 hectares) que produz diversas culturas. O objetivo principal é analisar dados de condições ambientais e prever o rendimento das safras, identificando tendências e padrões para otimizar a produção agrícola.

🎯 Objetivos
Realizar análise exploratória dos dados de condições ambientais e rendimento

Identificar padrões e tendências através de técnicas de clusterização

Desenvolver e comparar cinco modelos preditivos diferentes para prever rendimento agrícola

Avaliar os modelos com métricas apropriadas (MSE, MAE, R²)

Fornecer insights acionáveis para melhorar a produtividade agrícola

📊 Dataset
O dataset crop_yield.csv contém informações sobre quatro culturas diferentes:

Cocoa beans

Oil palm fruit

Rice paddy

Rubber natural

Variáveis incluídas:

Crop: Nome da cultura

Precipitation (mm day-1): Precipitação em mm por dia

Specific Humidity at 2 Meters (g/kg): Umidade específica a 2 metros

Relative Humidity at 2 Meters (%): Umidade relativa a 2 metros

Temperature at 2 Meters (C): Temperatura a 2 metros em Celsius

Yield: Rendimento em toneladas por hectare

🛠️ Tecnologias Utilizadas
Python 3

Pandas: Manipulação e análise de dados

NumPy: Computação científica

Matplotlib/Seaborn: Visualização de dados

Scikit-learn: Machine Learning e pré-processamento

Jupyter Notebook: Ambiente de desenvolvimento

📁 Estrutura do Projeto
text
📂 crop-yield-analysis/
│
├── 📄 crop_yield.csv              # Dataset original
├── 📄 Analise_Preditiva_Rendimento_Agricola.ipynb  # Jupyter Notebook completo
├── 📄 README.md                   # Este arquivo
└── 📂 images/                     # Pasta para imagens (geradas pelo notebook)
🚀 Como Executar

-Clone o repositório:

bash
git clone https://github.com/seu-usuario/crop-yield-analysis.git
cd crop-yield-analysis

-Instale as dependências:

bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

-Execute o Jupyter Notebook:

bash
jupyter notebook

-Abra o notebook Analise_Preditiva_Rendimento_Agricola.ipynb e execute as células sequencialmente

📈 Metodologia
O projeto segue uma abordagem completa de ciência de dados:

Análise Exploratória: Compreensão inicial dos dados e identificação de padrões

Pré-processamento: Limpeza, codificação e normalização dos dados

Clusterização: Identificação de grupos naturais nos dados usando K-means

Detecção de Outliers: Identificação de valores atípicos com Isolation Forest

Modelagem Preditiva: Desenvolvimento de 5 modelos de machine learning diferentes

Avaliação: Comparação dos modelos usando MSE, MAE e R²

Interpretação: Análise de importância de features e insights do negócio

🤖 Modelos Implementados
Regressão Linear

Ridge Regression

Random Forest Regressor

Gradient Boosting Regressor

Support Vector Regression (SVR)

📋 Resultados
Os modelos foram avaliados usando três métricas:

MSE (Mean Squared Error): Erro quadrático médio

MAE (Mean Absolute Error): Erro absoluto médio

R² (Coefficient of Determination): Coeficiente de determinação

→ Acesse o Jupyter Notebook para ver os resultados completos e comparações detalhadas!
################################################################################################
Meta de Etnrega 2:
  
1)  Configuração da Instância
•	Tipo de instância: t4g.micro (2 vCPUs, 1 GiB RAM, até 5 Gigabit de rede)
•	Sistema operacional: Linux
•	Modelo de preço: Sob demanda 
•	Armazenamento EBS: 50 GB 

<img width="886" height="162" alt="image" src="https://github.com/user-attachments/assets/6f528464-09b3-4718-8def-68ce50c73041" />

•A região da Virgínia do Norte (EUA) apresenta uma solução mais econômica, em relação à região de São Paulo. 


2) Suponha também que você precisa acessar rapidamente os dados dos sensores e que há restrições legais para armazenamento no exterior. Qual opção você escolheria? Justifique.
•	a) Os sensores provavelmente estão localizados no Brasil. hospedar a API na mesma região reduz significativamente a latência na comunicação, Isso garante que os dados dos sensores sejam processados quase em tempo real.
•	b) Segue link do vídeo https://youtu.be/9JrP-KTMyzI
 
  
