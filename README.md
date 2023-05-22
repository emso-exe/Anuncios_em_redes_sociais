# :mag_right: Análise de dados: Anúncios em redes sociais 📰

Este é um projeto de machine learning para análise de dados de usuários que efetuaram ou não uma compra, os dados foram disponibilizados na plataforma [Kaggle](https://www.kaggle.com/datasets/dragonheir/logistic-regression).

Não estão definidos no dataset o caso proposto e o problema a ser solucionado, então baseados nos dados serem de compras efetuadas ou não por usuários e arquivo de dados ser nomeado como "anúncios de redes sociais", será adotada a seguinte interpretação: *O arquivo Social_Network_Ads.csv contém dados de usuários de uma rede social que tiveram alguma interação com um anúncio e foram incentivados ou não a efetuar uma compra, sendo assim o objetivo do desenvolvimento do modelo será em prever quais clientes estimulados pelo(s) anúncio(s) realizará ou não uma compra.*

## 📃 Demanda da análise

- Analisar a correlação dos dados dos usuários.
- Gerar um modelo preditivo de compra ou não por um usuário.
- Simular novas entradas de dados e previsões.
  
## 📋 Tópicos da análise

1. Análise das medidas estatísticas dos dados
2. Distribuição dos dados entre as variáveis independentes (features) e dependente (target)
3. Correlação entre as variáveis
4. Criação do modelo de regressão logística
   1. Separação dos dados de treino e teste
   2. Treinamento e predições do modelo
   3. Métricas do modelo
   4. Previsões com novos dados
5. Conclusão
   
## :gem: Resultados do modelo

╒════╤═════════╤═════════════╤════════════╤════════════════════╤════════════╕
│    │   idade │   masculino │   feminino │   salario_estimado │   comprado │
╞════╪═════════╪═════════════╪════════════╪════════════════════╪════════════╡
│  0 │      19 │           0 │          1 │          130754.00 │          0 │
├────┼─────────┼─────────────┼────────────┼────────────────────┼────────────┤
│  1 │      26 │           0 │          1 │          148398.00 │          0 │
├────┼─────────┼─────────────┼────────────┼────────────────────┼────────────┤
│  2 │      19 │           1 │          0 │           42037.00 │          0 │
├────┼─────────┼─────────────┼────────────┼────────────────────┼────────────┤
│  3 │      35 │           1 │          0 │          102935.00 │          1 │
├────┼─────────┼─────────────┼────────────┼────────────────────┼────────────┤
│  4 │      41 │           1 │          0 │          102119.00 │          1 │
├────┼─────────┼─────────────┼────────────┼────────────────────┼────────────┤
│  5 │      33 │           0 │          1 │           43919.00 │          0 │
├────┼─────────┼─────────────┼────────────┼────────────────────┼────────────┤
│  6 │      58 │           0 │          1 │          141094.00 │          1 │
├────┼─────────┼─────────────┼────────────┼────────────────────┼────────────┤
│  7 │      34 │           0 │          1 │          111118.00 │          0 │
├────┼─────────┼─────────────┼────────────┼────────────────────┼────────────┤
│  8 │      36 │           0 │          1 │          114059.00 │          0 │
├────┼─────────┼─────────────┼────────────┼────────────────────┼────────────┤
│  9 │      50 │           0 │          1 │          133254.00 │          1 │
╘════╧═════════╧═════════════╧════════════╧════════════════════╧════════════╛


Após efetuar ajustes nos dados, a fim de identificar padrões e correlações que auxiliaram na interpretação das informações sobre usuários que realizaram uma compra ou não, foi construído um modelo com **acurácia de 90%** e **pontuação média de 84,5%**. Foram executados testes com novas entradas de dados indicando clientes que potencialmente efetuariam uma compra (comprado: 1) estimulados por um anúncio específico, assim o modelo também irá permitir traçar perfis, baseado nas variáveis independentes, com maior probabilidade de efetuar uma compra e assim direcionar os anúncios para esse público específico.


## 💻 Tecnologias

- Python
    - Biblioteca GC
    - Biblioteca Pandas
    - Biblioteca Matplotlib
    - Biblioteca Seaborn
    - Biblioteca Numpy
    - Biblioteca Warnings
    - Biblioteca Tabulate
    - Biblioteca SciKit-learn
    - Biblioteca Imbalanced-learn

## 💳 Créditos

- [Estênio Mariano](https://github.com/emso-exe)

## 🔖 Licença

Licença MIT (MIT). Por favor leia o [arquivo da licença](LICENSE.md) para mais informações.