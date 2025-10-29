# 📊 Análise Exploratória de Dados - Titanic

## Sobre o Projeto

Este projeto apresenta uma **Análise Exploratória de Dados (EDA)** do famoso conjunto de dados do desastre do Titanic, disponibilizado pelo Kaggle. O objetivo principal é explorar e compreender os fatores que influenciaram a sobrevivência dos passageiros através de visualizações, estatísticas descritivas e insights baseados em dados.[^5][^6][^7]

Como parte do meu portfólio de ciência de dados, este projeto demonstra habilidades em manipulação de dados, análise estatística e visualização utilizando Python.[^3][^1]

## Objetivos

- Realizar uma análise exploratória completa do dataset do Titanic
- Identificar padrões e correlações entre as variáveis disponíveis
- Tratar valores ausentes e inconsistências nos dados
- Visualizar distribuições e relações entre features
- Extrair insights sobre os fatores que impactaram a taxa de sobrevivência
- Preparar os dados para futuras etapas de modelagem de Machine Learning[^7][^3]


## Dataset

O dataset utilizado é proveniente da competição [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic) do Kaggle.[^6]

### Descrição das Variáveis

| Variável | Descrição |
| :-- | :-- |
| PassengerId | ID único do passageiro |
| Survived | Sobrevivência (0 = Não, 1 = Sim) |
| Pclass | Classe do ticket (1 = 1ª, 2 = 2ª, 3 = 3ª) |
| Name | Nome do passageiro |
| Sex | Sexo do passageiro |
| Age | Idade em anos |
| SibSp | Número de irmãos/cônjuges a bordo |
| Parch | Número de pais/filhos a bordo |
| Ticket | Número do ticket |
| Fare | Tarifa paga pelo passageiro |
| Cabin | Número da cabine |
| Embarked | Porto de embarque (C = Cherbourg, Q = Queenstown, S = Southampton) |

*Fonte: Kaggle Titanic Competition*[^8][^6]

## Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** - Manipulação e análise de dados
- **NumPy** - Operações numéricas
- **Matplotlib** - Visualizações básicas
- **Seaborn** - Visualizações estatísticas avançadas
- **Jupyter Notebook** - Ambiente de desenvolvimento interativo


## Estrutura do Projeto

```
titanic-eda/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── titanic_eda.ipynb
│
├── images/
│   └── (gráficos e visualizações)
│
├── README.md
└── requirements.txt
```


## Metodologia

O processo de EDA seguiu as seguintes etapas:[^1][^3]

### 1. Carregamento e Visão Geral dos Dados

- Importação do dataset
- Análise das dimensões e tipos de dados
- Verificação inicial da estrutura


### 2. Análise de Valores Ausentes

- Identificação de missing values
- Análise do impacto dos dados faltantes
- Estratégias de tratamento


### 3. Análise Descritiva

- Estatísticas resumidas das variáveis numéricas
- Análise de distribuições
- Identificação de outliers


### 4. Análise Univariada

- Distribuição de cada variável individualmente
- Visualizações com histogramas e gráficos de barras


### 5. Análise Bivariada

- Relação entre variáveis e a taxa de sobrevivência
- Correlações entre features
- Análise por grupos (classe, sexo, idade, etc.)


### 6. Insights e Conclusões

- Principais descobertas da análise
- Fatores determinantes para sobrevivência


## Principais Insights

*(Esta seção será preenchida após a conclusão da análise)*

Exemplos de perguntas respondidas:[^5][^7]

- Qual foi a taxa geral de sobrevivência?
- Como a classe social influenciou as chances de sobrevivência?
- Existe diferença significativa entre homens e mulheres?
- A idade foi um fator determinante?
- Quais portos de embarque tiveram maior taxa de sobrevivência?


## Como Executar o Projeto

### Pré-requisitos

- Python 3.7 ou superior instalado
- pip (gerenciador de pacotes Python)


### Instalação

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/titanic-eda.git
cd titanic-eda
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Execute o Jupyter Notebook:
```bash
jupyter notebook notebooks/titanic_eda.ipynb
```


## Aprendizados

Este projeto me permitiu desenvolver e praticar habilidades em:[^2][^4]

- Limpeza e preparação de dados reais
- Técnicas de análise exploratória
- Visualização de dados com diferentes bibliotecas Python
- Identificação de padrões e correlações em datasets
- Documentação e apresentação de projetos de dados


## Próximos Passos

- [ ] Implementar feature engineering
- [ ] Desenvolver modelos de Machine Learning para previsão de sobrevivência
- [ ] Comparar performance de diferentes algoritmos (Random Forest, Logistic Regression, SVM)
- [ ] Realizar otimização de hiperparâmetros
- [ ] Submeter previsões na competição do Kaggle[^3][^7]


## Autor

**Seu Nome**

- LinkedIn: [seu-perfil](https://linkedin.com/in/seu-perfil)
- GitHub: [@seu-usuario](https://github.com/seu-usuario)
- Email: seu.email@exemplo.com


## Referências

- [Kaggle - Titanic Competition](https://www.kaggle.com/c/titanic)[^6]
- Documentação Pandas
- Documentação Seaborn
- Documentação Matplotlib


## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

***

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!
<span style="display:none">[^10][^9]</span>

<div align="center">⁂</div>

[^1]: https://github.com/fabinhojorge/titanic_analysis

[^2]: https://medium.datadriveninvestor.com/how-to-write-a-good-readme-for-your-data-science-project-on-github-ebb023d4a50e?gi=8a4060ab4107

[^3]: https://github.com/Ruban2205/titanic-classification

[^4]: https://www.dataquest.io/blog/how-to-share-data-science-portfolio/

[^5]: https://www.kaggle.com/code/mjamilmoughal/eda-of-titanic-dataset-with-python-analysis

[^6]: https://www.kaggle.com/c/titanic/data

[^7]: https://www.geeksforgeeks.org/machine-learning/titanic-survival-prediction-using-ml/

[^8]: https://udaykiran.tech/solved-titanic-dataset-kaggle-competition

[^9]: https://www.reddit.com/r/learnmachinelearning/comments/93sq9g/about_to_go_solve_the_titanic_dataset_on_kaggle/

[^10]: https://www.youtube.com/watch?v=6IGx7ZZdS74

