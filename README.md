# Análise e diagnóstico das arboviroses dengue e chikungunya

#### IMPORTÂNCIA DO PROJETO
No Brasil, as arboviroses dengue e chikungunya são graves problemas de saúde pública, transmitidas pelo mosquito *Aedes aegypti* e endêmicas em muitas regiões do país. Ambas apresentam sintomas semelhantes, mas a chikungunya pode causar dores articulares intensas e a dengue pode, muitas vezes, ser fatal. <br>
O desenvolvimento e implementação de modelos de diagnóstico baseados em Machine Learning pode ser muito útil. Ao identificar padrões nos sintomas dos pacientes, esses modelos podem mostrar a probabilidade de diagnósticos dessas doenças de forma mais ágil e rápida. Dessa forma, podem agilizar o diagnóstico, alertar os profissionais da saúde antecipadamente sobre surtos e otimizar a alocação de recursos. 

-----------------------------------------------------------------------------------------------------------------------------------------

#### LÓGICA DA ANÁLISE
O projeto foi estruturado da seguinte forma:

1. INTRODUÇÃO
2. IMPORTANDO BIBLIOTECAS
3. DATASET
   - 3.1 DICIONÁRIO
   - 3.2 DIVISÃO DO DATASET EM TREINO E TESTE
   - 3.3 TRATAMENTO DO DATASET
4. ANÁLISE DESCRITIVA
5. MODELAGEM
   - 5.1 ÁRVORE DE DECISÃO
   - 5.2 REGRESSÃO LOGÍSTICA
6. CONCLUSÃO

-----------------------------------------------------------------------------------------------------------------------------------------

#### COLETA DE DADOS

Os dados foram coletados em MendeleyData (https://data.mendeley.com/datasets/bv26kznkjs/1)

-----------------------------------------------------------------------------------------------------------------------------------------

#### MODELAGEM

Foram utilizadas duas técnicas para a modelagem: árvore de decisão e regressão logística.

-----------------------------------------------------------------------------------------------------------------------------------------

#### CONCLUSÃO

- Os modelos de árvore de decisão e regressão logística apresentaram performance parecida ao tentar classificar os dados.
- Ambos foram capazes de classificar chikungunya e outras doenças de forma razoavelmente bem, porém não foram eficientes em classificar pacientes com dengue.
- A dificuldade de classificação pode ser devido à similaridade dos sintomas ou aos dados propriamente ditos; talvez com uma base maior e mais variada (de outras regiões do Brasil ou abrangendo outros anos, por exemplo) os modelos possam ser aperfeiçoados.

