# Plano do Projeto

## 1. Leitura do problema e enquadramento ✅
- Identificar os 3 objetivos do projeto:
  - O1: prever `Transported`.
  - O2: prever `FoodCourt`.
  - O3: prever a idade dos passageiros transportados.
- Definir o tipo de tarefa de cada objetivo:
  - O1: classificação.
  - O2: regressão.
  - O3: regressão condicionada aos passageiros transportados.
- Ler a descrição das variáveis e perceber quais são numéricas, categóricas e quais têm valores em falta.
- Estado: ✅ já colocado no notebook com a secção de enquadramento do problema.

## 2. Exploração inicial dos dados
- Fazer uma análise descritiva do dataset.
- Ver a distribuição das variáveis principais e da variável alvo de O1.
- Identificar missing values, outliers e possíveis inconsistências.
- Explorar relações simples entre atributos e variáveis alvo.
- Estado: ✅ secção de EDA inicial já adicionada ao notebook.

## 3. Pré-processamento
- Tratar valores em falta.
- Codificar variáveis categóricas.
- Normalizar ou padronizar variáveis numéricas quando fizer sentido.
- Criar um pipeline de pré-processamento reutilizável para os diferentes objetivos.

## 4. Objetivo O1: prever `Transported`
- Testar modelos simples de classificação.
- Comparar os modelos com métricas adequadas, como accuracy e/ou F1.
- Fazer tuning dos hiperparâmetros do melhor modelo.
- Gerar previsões para o ficheiro de exemplo `space_ex_o1.csv`.

## 5. Objetivo O2: prever `FoodCourt`
- Definir a estratégia de regressão para a variável `FoodCourt`.
- Testar vários modelos de regressão.
- Avaliar com métricas como MAE, RMSE e/ou R$^2$.
- Fazer tuning do melhor modelo.
- Gerar previsões para o ficheiro de exemplo `space_ex_o2.csv`.

## 6. Objetivo O3: prever a idade dos passageiros transportados
- Filtrar apenas os passageiros que foram transportados.
- Treinar modelos para prever a idade.
- Avaliar se a previsão é suficientemente fiável.
- Analisar o erro e a dispersão das previsões.
- Gerar previsões para o ficheiro de exemplo `space_ex_o3.csv`.

## 7. Importância das variáveis
- Extrair e comparar a importância das features nos melhores modelos.
- Identificar os atributos mais relevantes em cada objetivo.
- Criar gráficos de apoio para interpretar os resultados.

## 8. Discussão e conclusões
- Resumir os melhores modelos para cada objetivo.
- Explicar as decisões de pré-processamento e tuning.
- Discutir limitações, dificuldades e possíveis melhorias.
- Concluir se os objetivos foram atingidos de forma convincente.

## 9. Organização final do notebook
- Garantir que o notebook segue a estrutura pedida no enunciado.
- Incluir tabelas com resultados e gráficos auxiliares.
- Escrever comentários claros no código e texto explicativo nas células markdown.
- Validar que o notebook corre do início ao fim sem erros.
