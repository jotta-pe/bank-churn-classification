# O projeto - Visão Geral
O Projeto "Bank Churn Classification" é voltado para a classificação da rotatividade de clientes em bancos. Ele visa classificar se um determinado cliente irá ou não encerrar sua conta no banco.
Link no kaggle: https://www.kaggle.com/competitions/playground-series-s4e1

A identificação previa de clientes que podem potencialmente encerrar suas contas possibilita aos bancos identificar e atacar as causas da evasão de clientes, mantendo sua fidelidade. Além disso, uma análide aprofundada dos dados podem revelar pontos de fragilidade na estrutura de comunicação do banco com os clientes, levando a ações direcionadas.

# Metodologia
A metodologia utilizada vai ser a CRISP-DM (Cross-Industry Standard Process for Data Mining), a metodologia padrão mais utilizada para projetos desse tipo, Ela consiste em organizar o projeto em 6 fases cíclicas: Entendimento do Negócio, Entendimento dos Dados, Preparação dos Dados, Modelagem, Avaliação e Implantação. OBS: Para esse projeto não vai haver a fase de implantação pois é apenas um case que não vai para produção. 

Uma breve descrição das fases do CRISP-DM:
- Entendimento do Negócio:
  - Definir o problema real a ser resolvido.
  - Estabelecer metas claras de sucesso para a empresa.

- Entendimento dos Dados:
  - Coletar a base de dados inicial.
  - Analisar a estrutura, o tamanho e a qualidade das informações.
  
- Preparação dos Dados:
  - Limpar valores nulos ou errados.
  - Selecionar e transformar as variáveis relevantes (Feature Engineering).

- Modelagem:
  - Escolher e aplicar algoritmos de aprendizado de máquina (Machine Learning).
  - Treinar e ajustar os modelos matemáticos.

- Avaliação:
  - Testar o desempenho do modelo com métricas estatísticas.
  - Garantir que o resultado atende aos objetivos do negócio antes do lançamento.
  
- Implantação:
  - Colocar o modelo em produção para uso real por usuários ou sistemas.
  - Monitorar o desempenho contínuo do sistema.

# Entendimento do Negócio:

# Entendimento dos Dados:

# Preparação dos dados:

# Modelagem:

# Avaliação:


## A Fazer
- [ ] Definição do problema
- [ ] Carga e EDA
- [ ] Limpeza e preparação dos dados
- [ ] Selecionar e Criar features para o modelo
- [ ] Treinar modelo (separando os dados de treino e teste)
- [ ] Avaliar modelo
- [ ] Realizar teste para seleção de variáveis como Hold-out
- [ ] Fazer análise de hiperparêmtros
- [ ] Gerar as predições finais

---

# Fontes consultadas

- [pandas — operações de merge](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.merge.html)
- [scikit-learn — Pipeline](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html)
- [scikit-learn — ColumnTransformer](https://scikit-learn.org/stable/modules/generated/sklearn.compose.ColumnTransformer.html)
- [scikit-learn — RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
- [scikit-learn — métricas de classificação](https://scikit-learn.org/stable/modules/model_evaluation.html)
- [scikit-learn — importância por permutação](https://scikit-learn.org/stable/modules/permutation_importance.html)

## Livros

- GÉRON, Aurélien. *Hands-On Machine Learning with
  Scikit-Learn, Keras, and TensorFlow*. 3. ed.
  O'Reilly Media, 2022.

