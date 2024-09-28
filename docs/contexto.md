# Introdução

O diabetes é uma doença crônica de grande relevância para a saúde pública, afetando milhões de pessoas ao redor do mundo. No Brasil, a situação é alarmante: mais de 13 milhões de pessoas convivem com a condição, o que representa 6,9% da população nacional, de acordo com a Sociedade Brasileira de Diabetes (SBD). Embora frequentemente hereditário, o diabetes está fortemente associado a fatores como sobrepeso, sedentarismo, hipertensão e outros hábitos de vida inadequados. Aproximadamente 90% dos casos de diabetes no país são do tipo 2, conforme aponta o Ministério da Saúde, sendo predominantemente causados por estilos de vida não saudáveis.

As complicações decorrentes do diabetes constituem um problema significativo para o sistema de saúde brasileiro. Entre janeiro e agosto de 2023, o Sistema Único de Saúde (SUS) registrou 6.982 amputações de membros inferiores (pernas e pés) relacionadas à doença, resultando em uma média de mais de 28 ocorrências por dia. O diabetes é, segundo a SBD, a principal causa de amputações não traumáticas de membros inferiores no Brasil, superando aquelas causadas por acidentes de trânsito ou de trabalho.

Além disso, o problema do diagnóstico tardio agrava ainda mais a situação. Dados do Previva revelam que metade dos indivíduos diabéticos não adota medidas preventivas simplesmente porque ainda não foram diagnosticados. A falta de um diagnóstico precoce impede o controle eficaz da doença, aumentando o risco de complicações graves, como infarto, derrame cerebral e cegueira.

Diante desse cenário, propomos a análise de bases de dados para identificar fatores que possam indicar uma alta probabilidade de diagnóstico de diabetes, contribuindo para a formulação de estratégias de prevenção e intervenção mais eficazes.


## Problema

O aumento significativo dos casos de diabetes tipo 2 e suas complicações configura um grave problema de saúde pública no Brasil. Entre os desafios principais estão a falta de conscientização sobre a doença, o diagnóstico tardio e a prevalência de hábitos de vida não saudáveis. As amputações de membros inferiores relacionadas ao diabetes são uma consequência severa que reflete a inadequação no controle da condição.

A ausência de uma abordagem eficaz e preventiva, aliada ao diagnóstico tardio, compromete a capacidade de resposta do sistema de saúde, impactando a qualidade de vida dos pacientes e gerando altos custos para o sistema de saúde público.

## Questão de pesquisa

 Quais são os principais fatores que contribuem para o desenvolvimento de diabetes no Brasil, e como esses fatores podem ser identificados para melhorar as estratégias de prevenção e intervenção? Além disso, como um formulário que identifica hábitos e sintomas comuns entre portadores de diabetes tipo 2 pode ser utilizado como uma ferramenta de alerta, ajudando os indivíduos a reconhecerem comportamentos de risco e a buscarem orientação médica para um possível diagnóstico precoce da doença?


## Objetivos preliminares

Evidenciar os fatores de risco associados ao desenvolvimento de diabetes por meio da reunião e análise de bases de dados sobre sintomas e estilos de vida de portadores da doença. A partir dessa análise, buscar identificar pontos em comum e determinar quais fatores se repetem com maior frequência, bem como desenvolver uma escala de graus de risco para cada fator, de modo a auxiliar na formulação de estratégias de prevenção e diagnóstico precoce.

## Justificativa

O diabetes, especialmente o tipo 2, é um dos principais desafios de saúde pública no Brasil, afetando mais de 13 milhões de brasileiros, o que corresponde a 6,9% da população, segundo a Sociedade Brasileira de Diabetes (SBD). A doença está diretamente associada a complicações graves, como amputações de membros inferiores, com o Sistema Único de Saúde (SUS) registrando 6.982 amputações relacionadas ao diabetes entre janeiro e agosto de 2023. Esse número equivale a mais de 28 amputações diárias, representando um impacto significativo na vida dos pacientes e um enorme custo para o sistema de saúde.

Além disso, o Ministério da Saúde aponta que aproximadamente 90% dos casos de diabetes no Brasil são do tipo 2, que está fortemente ligado a estilos de vida inadequados, como sedentarismo e má alimentação. A falta de diagnóstico precoce agrava a situação, já que cerca de metade dos diabéticos no país desconhece sua condição, dificultando a prevenção e o tratamento efetivo.

Diante desse cenário, este trabalho propõe a realização de análises estatísticas aprofundadas sobre sintomas e estilos de vida de indivíduos com diabetes, com o objetivo de identificar padrões e fatores de risco recorrentes. O desenvolvimento de uma escala de graus de risco, com base em evidências, poderá auxiliar na criação de diretrizes de prevenção mais eficazes, direcionando políticas públicas que possam reduzir a incidência da doença e suas complicações, melhorar a qualidade de vida dos pacientes e otimizar o uso dos recursos no sistema de saúde público.

## Público-Alvo

Este estudo é voltado para grupos que podem se beneficiar da compreensão dos fatores de risco do diabetes tipo 2 e de estratégias de prevenção baseadas em dados. O público-alvo inclui a população em geral, que pode usar as informações sobre fatores de risco como práticas a serem evitadas no dia a dia ou como referência para identificar o momento de procurar um especialista para avaliar um possível diagnóstico. A pesquisa também é valiosa para profissionais de saúde, ao evidenciar numericamente os sintomas e comportamentos que podem ser indicativos de diabetes, auxiliando no diagnóstico precoce e no manejo da doença. Além disso, pesquisadores, formuladores de políticas públicas e organizações de saúde podem aplicar os resultados para melhorar as estratégias de prevenção e intervenção.

## Estado da arte

A diabetes é uma doença crônica que afeta milhões de pessoas no mundo todo, sendo caracterizada por níveis elevados de glicose no sangue devido à deficiência na produção ou ação da insulina. O aumento da prevalência dessa condição, associado a complicações sérias como doenças cardíacas, renais e danos aos nervos, destaca a importância de diagnósticos precoces e eficazes. No entanto, o diagnóstico de diabetes, muitas vezes, depende de exames laboratoriais que nem sempre estão prontamente disponíveis ou acessíveis para a população em geral, especialmente em áreas remotas ou menos desenvolvidas.

Com o avanço das técnicas de aprendizado de máquina e a crescente disponibilidade de grandes conjuntos de dados médicos, surge a oportunidade de desenvolver modelos preditivos que possam prever a ocorrência de diabetes de forma rápida e precisa, utilizando variáveis clínicas e demográficas acessíveis. Esses modelos têm o potencial de ajudar profissionais de saúde a identificar indivíduos com risco elevado antes que a doença se manifeste de forma mais severa, permitindo intervenções preventivas ou tratamentos mais eficazes.

Este trabalho se propõe a criar um modelo preditivo para a previsão de diabetes, utilizando um conjunto de dados clínicos previamente coletados. Para fundamentar o desenvolvimento desse modelo, será realizada uma revisão da literatura com o objetivo de identificar abordagens já utilizadas para resolver problemas similares. A partir dessa revisão, pretende-se analisar diferentes técnicas, algoritmos, e métricas de avaliação, além de comparar os resultados obtidos, fornecendo uma base sólida para o desenvolvimento e aprimoramento do modelo proposto.

### Predição de Óbitos em Pacientes com COVID-19 Utilizando Random Forest
**(a) Detalhamento e Contextualização do Problema:** O estudo foi realizado durante a pandemia de COVID-19, com o objetivo de prever óbitos em pacientes diagnosticados com a doença. A pandemia trouxe desafios significativos para a saúde pública global, destacando a necessidade urgente de ferramentas preditivas para identificar pacientes em risco de morte e, assim, priorizar cuidados médicos.

**(b) Descrição das Principais Características do Dataset Utilizado:** O estudo utilizou dados de 370.077 casos notificados no E-SUS VS do Espírito Santo, coletados entre janeiro de 2020 e outubro de 2022. O dataset foi dividido em dois conjuntos: 70% para treinamento e 30% para teste. Após o downsampling da classe majoritária (não óbito), o conjunto de treinamento foi reduzido para 7.766 amostras.

**(c) Abordagens/Algoritmos Utilizados (e seus Parâmetros):** Foi utilizado o algoritmo Random Forest, uma técnica que combina várias árvores de decisão para melhorar a precisão preditiva. O downsampling foi aplicado ao conjunto de dados de treinamento para lidar com o desbalanceamento de classes. Parâmetros específicos do modelo, como o número de árvores, profundidade máxima e critérios de divisão, não foram detalhados no resumo.

**(d) Métricas de Avaliação Empregadas:** As previsões foram avaliadas utilizando uma tabela de contingência 2×2, com ênfase na sensibilidade, especificidade, acurácia, valor preditivo positivo (VPP) e valor preditivo negativo (VPN). A sensibilidade foi de 82,5%, a especificidade de 82,9%, e a acurácia geral de 83,9%. O VPP foi de 6,9% e o VPN foi de 99,7%.

**(e) Resultados Obtidos:** O modelo apresentou um bom desempenho geral, com alta sensibilidade e especificidade, sendo eficaz na identificação de casos de não óbito. No entanto, o VPP foi baixo, indicando que a proporção de previsões corretas de óbito foi pequena, provavelmente devido ao desequilíbrio de classes. O VPN alto demonstrou que as previsões de não óbito eram altamente confiáveis. Apesar dos resultados positivos, o estudo sugere a necessidade de aprimoramento na precisão da previsão dos casos de óbito.


### Avaliação dos Parâmetros Hematológicos e Bioquímicos em Pacientes com Mieloma Múltiplo de Alto Risco
**(a) Detalhamento e Contextualização do Problema:** O mieloma múltiplo (MM) é a segunda neoplasia hematológica mais frequente no mundo, caracterizada por sintomas como anemia e disfunção renal. Este estudo visa avaliar os dados laboratoriais de pacientes com MM de alto risco e comparar estatisticamente as diferenças entre os gêneros. A análise da relação entre gênero e alterações laboratoriais em pacientes com MM é crucial, pois pode fornecer insights sobre diferenças na progressão da doença e na resposta ao tratamento.

**(b) Descrição das Principais Características do Dataset Utilizado:** O estudo é retrospectivo, descritivo e observacional, com dados laboratoriais coletados de 17 prontuários de pacientes diagnosticados com MM de alto risco, atendidos no Hospital Geral de Fortaleza entre 2022 e 2023. Os pacientes foram classificados como de alto risco segundo o International Staging System Revised (R-ISS). O dataset inclui parâmetros hematológicos (hemoglobina, contagem total de leucócitos, contagem de plaquetas, VCM, HCM e RDW) e bioquímicos (ureia e creatinina). A média de idade dos pacientes foi de 62,47 anos.

**(c) Abordagens/Algoritmos Utilizados (e seus Parâmetros):** Foi utilizado o teste estatístico de Fisher para avaliar a associação entre a normalidade e anormalidade dos valores de referência e o gênero dos pacientes. Esse teste é apropriado para amostras pequenas e foi escolhido para verificar se há uma correlação significativa entre gênero e alterações nos parâmetros laboratoriais.

**(d) Métricas de Avaliação Empregadas:** O estudo utilizou valores para determinar a significância estatística das associações entre gênero e parâmetros laboratoriais. Valores gerados maiores que 0,05 indicaram que não houve correlação significativa entre o gênero e os parâmetros analisados.

**(e) Resultados Obtidos:** Os resultados mostraram que não houve correlação significativa entre o gênero dos pacientes e as alterações nos parâmetros hematológicos e bioquímicos. As principais alterações incluíram uma diminuição na hemoglobina (94,12%) e um aumento no RDW (88,24%), com todos os pacientes apresentando níveis elevados de ureia e 82,36% com níveis elevados de creatinina. Esses achados sugerem que, apesar das diferenças conhecidas na prevalência e resposta ao tratamento entre homens e mulheres, as alterações laboratoriais não diferem significativamente entre os gêneros em pacientes com MM de alto risco.


### Predição de baixo peso ao nascer utilizando modelos de machine learning
**(a) Detalhamento e Contextualização do Problema:** Dentre as principais causas de morte de recém-nascidos, a World Health Organization(WHO) destaca o Baixo Peso ao Nascer (BPN) como o fator isolado de predominância para a indução desse resultado negativo. A literatura apresenta modelos de machine learning como potenciais ferramentas para auxiliar os profissionais de saúde no prognóstico de diversas doençasda área materno-infantil.

**(b) Descrição das Principais Características do Dataset Utilizado:** O estudo utilizou um conjunto de dados abertos do Sistema de Informações sobre Nascidos Vivos (SINASC), composto por 61 atributos e 400.157 registros, abrangendo os anos de 2018 a 2020, especificamente do estado de Pernambuco. Os atributos do dataset incluem uma variedade de informações relacionadas ao histórico materno, dados sociodemográficos materno-infantil, informações sobre o pré-natal, dados de residência da gestante, detalhes sobre a unidade de saúde, dados de atendimento, informações do recém-nascido, e datas informativas pessoais.

**(c) Abordagens/Algoritmos Utilizados (e seus Parâmetros):** Foram utilizados três modelos baseados em árvores: Decision Tree, Adaboost e RandomForest. Antes do treinamento dos modelos, foi realizado o balanceamento dos dados devido à desproporção nas classes, onde 11% dos registros pertenciam à classe minoritária (baixo peso ao nascer, BPN) e 89% à classe majoritária (peso normal ao nascer, PNN). A técnica de Random Undersampling foi aplicada, que consiste em selecionar registros aleatórios da classe majoritária sem reposição, reduzindo-a para a mesma quantidade de dados da classe minoritária. Após o balanceamento, o conjunto de dados foi dividido em 70% para treinamento e 30% para teste.

**(d) Métricas de Avaliação Empregadas:** A avaliação dos modelos preditivos foi realizada com base nas seguintes métricas:
- Acurácia: Medida geral da capacidade do modelo em classificar corretamente os casos de BPN e PNN.
- Precisão: Avalia a proporção de verdadeiros positivos entre todas as previsões positivas realizadas pelo modelo.
- Sensibilidade: Mede a capacidade do modelo de identificar corretamente os casos de BPN, ou seja, a proporção de verdadeiros positivos em relação ao total de casos positivos reais.
- Especificidade: Avalia a capacidade do modelo de identificar corretamente os casos de PNN, ou seja, a proporção de verdadeiros negativos em relação ao total de casos negativos reais.
- f1-score: Métrica que combina precisão e sensibilidade em um único valor, útil para avaliar o desempenho do modelo especialmente em datasets desbalanceados.
- _Area Under the Receiver Operating Characteristic Curve_ (ROC AUC): Representa a habilidade do modelo em distinguir entre as classes BPN e PNN, com uma área maior indicando melhor desempenho na separação das classes.
Essas métricas proporcionaram uma visão abrangente do desempenho dos modelos na predição de baixo peso ao nascer, ajudando a identificar quais abordagens apresentaram melhor eficácia no contexto analisado.

**(e) Resultados Obtidos:** Os resultados dos modelos baseados em árvores mostraram desempenhos distintos na predição de baixo peso ao nascer (BPN).
- Decision Tree: Este modelo conseguiu capturar algumas das relações importantes entre os atributos, mas apresentou limitações em termos de generalização para dados novos. A importância dos atributos foi bem destacada, com a idade materna e a gestação única ou múltipla mostrando-se como os principais fatores influentes na predição de BPN.
- Adaboost: O modelo Adaboost melhorou o desempenho em comparação com a Decision Tree, ajustando-se melhor aos dados balanceados. Este modelo também destacou a idade materna e o tipo de gestação como fatores cruciais, e apresentou uma capacidade aprimorada de identificar casos de BPN.
- RandomForest: O modelo RandomForest foi o mais eficaz entre os três, com um desempenho robusto na predição de BPN. Os atributos sociodemográficos e de pré-natal foram identificados como os mais influentes na aprendizagem do modelo. A idade materna foi consistentemente destacada como o atributo mais importante, com um nível de importância acima de 0.8. Outros atributos, como o tipo de gestação e a escolaridade materna, também apresentaram altos níveis de importância, acima de 0.3.
A análise dos resultados revelou que a gestação múltipla (gêmeos ou mais) e a idade materna avançada foram fortemente associadas a maiores taxas de BPN. Gestantes adolescentes e aquelas com baixa escolaridade também apresentaram maior frequência de BPN. Os resultados corroboraram a literatura existente, indicando que a idade avançada pode estar associada a complicações durante a gestação, enquanto a gestação múltipla aumenta o risco de complicações obstétricas.

# Descrição do _dataset_ selecionado

O [dataset](https://www.kaggle.com/datasets/tanshihjen/early-stage-diabetes-risk-prediction) compreende dados essenciais sobre sinais e sintomas de indivíduos que apresentam sinais iniciais de diabetes ou estão em risco de desenvolvê-la. As variáveis incluídas no dataset oferecem insights valiosos sobre potenciais indicadores do início da diabetes. O dataset abrange informações diversas, desde detalhes demográficos até sintomas específicos associados à diabetes.

Descrição dos Atributos:

- Age (1-20 a 65): Faixa etária dos indivíduos.
- Sex (1. Male, 2. Female): Informação de gênero.
- Polyuria (1. Yes, 2. No): Presença de micção excessiva.
- Polydipsia (1. Yes, 2. No): Sede excessiva.
- Sudden Weight Loss (1. Yes, 2. No): Perda de peso abrupta.
- Weakness (1. Yes, 2. No): Fraqueza generalizada.
- Polyphagia (1. Yes, 2. No): Fome excessiva.
- Genital Thrush (1. Yes, 2. No): Presença de candidíase genital.
- Visual Blurring (1. Yes, 2. No): Visão embaçada.
- Itching (1. Yes, 2. No): Presença de coceira.
- Irritability (1. Yes, 2. No): Manifestação de irritabilidade.
- Delayed Healing (1. Yes, 2. No): Cicatrização lenta.
- Partial Paresis (1. Yes, 2. No): Perda parcial de movimento voluntário.
- Muscle Stiffness (1. Yes, 2. No): Presença de rigidez muscular.
- Alopecia (1. Yes, 2. No): Queda de cabelo.
- Obesity (1. Yes, 2. No): Presença de obesidade.
- Class (1. Positive, 2. Negative): Classificação de diabetes.


# Canvas analítico

O [modelo do Canvas Analítico](https://github.com/ICEI-PUC-Minas-PMV-SI/PesquisaExperimentacao-Template/blob/main/help/Software-Analtics-Canvas-v1.0.pdf) segue esse formato de quadro, para simplicidade da documentação iremos listar cada parte em formato de lista numerada.

1. **Question:** Quais fatores clínicos são mais indicativos do risco de desenvolvimento de diabetes, e como podemos prever o risco de diabetes em indivíduos usando esses fatores?
2. **Datasource:** O conjunto de dados "early_stage_diabetes_risk_prediction" é proveniente do Repositório de Aprendizado de Máquina UCSI, possúi muito parâmetros e a classificação se o paciente possui ou não diabetes, é um bom lugar para começar.
3. **Heuristic:** Aplicação de modelos de machine learning para identificação dos atributos mais importantes para predição de risco de diabetes.
  * Suspeita 1: A adesão ao tratamento é maior em pacientes com acompanhamento familiar frequente.
  * Suspeita 2: A falta de adesão está associada à dificuldade de acesso aos medicamentos prescritos.
  * Suspeita 3: Intervenções de suporte psicológico e educacional tendem a aumentar a adesão ao tratamento.
5. **Validation:** Esperamos como resultado um modelo capaz de realizar previsão com base na base de dados já catalogada, será feito o treinamento em 70% da base e 30% será reservada para validação.
6. **Implementation:** O trabalho será conduzido em etapas que envolvem  tratamento e análise de um dataset contendo informações sobre pacientes com diabetes. O dataset utilizado será composto por dados demográficos, clínicos e socioeconômicos, além de informações sobre frequência de consultas, adesão ao tratamento e resultados clínicos (como níveis de glicemia, pressão arterial, etc.).

  Inicialmente, será feita uma limpeza e preparação dos dados para garantir sua qualidade e integridade. Em seguida, serão    aplicadas técnicas de análise exploratória de dados (EDA) para identificar padrões de comportamento e possíveis             correlações entre variáveis que possam influenciar a adesão ao tratamento.
  
  Modelos preditivos, como regressão logística e random forest, serão utilizados para avaliar quais fatores possuem maior     peso na adesão ou abandono do tratamento. Além disso, será realizada uma análise de clusters para segmentar os pacientes    com características similares, o que permitirá uma compreensão mais aprofundada dos diferentes perfis de adesão.
7. **Results:**
Com a análise dos dados, espera-se:

Identificação dos principais fatores que influenciam a adesão: A análise de correlação e modelos preditivos devem revelar quais variáveis (como idade, região de residência, condições socioeconômicas e acesso a recursos de saúde) possuem maior impacto na adesão ao tratamento.

Segmentação de perfis de pacientes: A análise de clusters possibilitará agrupar pacientes em segmentos distintos, possibilitando intervenções mais direcionadas e personalizadas para cada grupo.

Modelagem preditiva de risco de abandono: Espera-se criar um modelo capaz de prever com precisão os casos de possível abandono do tratamento com base no perfil dos pacientes e na análise histórica do dataset. A meta é alcançar uma acurácia superior a 85% na predição.

8. **Next Steps:** O Aprimoramento do Modelo, considerando novos algoritmos, ajuste fino dos hiperparâmetros e inclusão de dados adicionais para melhorar a precisão e a robustez do modelo.

# Referências

- MORAIS, Flávio Leandro de; NERI, Ana Beatriz Torres; ROCHA, Elisson da Silva; MELLO, Maria Eduarda Ferro de; TEXEIRA, Igor Vitor; LYNN, Theo; ENDO, Patricia Takako. Predição de baixo peso ao nascer utilizando modelos de machine learning. Universidade de Pernambuco (UPE). Disponível em: https://research.ebsco.com/c/6hyen5/viewer/pdf/ch27syuvyz. Acesso em: 28 ago. 2024.
- BARRETO, I. V.; NOGUEIRA, B. M. D.; PESSOA, F. M. C. P.; GADELHA, R. B.; MACHADO, A. K. C.; RIBEIRO, R. M.; MOREIRA, A. P. L.; MORAES, M. E. A.; FILHO, M. O. M.; MOREIRA-NUNES, C. S. Análise de dados hematológicos e bioquímicos em pacientes com mieloma múltiplo de alto risco atendidos no Hospital Geral de Fortaleza, Ceará. Journal of Hematology & Oncology, v. 2, n. 6, p. 1-11, 2023. Disponível em: https://www.sciencedirect.com/science/article/pii/S2531137923009707. Acesso em: 28 ago. 2024.
- MARCHETTI, Victor Hugo Ovani; DALMASCHIO, Maria Eugênia Pedruzzi; SANTOS, Tatiani Bellettini dos; PANDINI, Eduardo Toffoli. Capacidade preditiva do modelo random forest para óbito em pacientes com COVID-19: Uma análise de dados no contexto da pandemia. Journal of Data Science and Epidemiology, v. 4, n. 2, p. 123-135, 2023. Disponível em: https://www.sciencedirect.com/science/article/pii/S1413867023001605. Acesso em: 28 ago. 2024.
- PREVIVA. Diagnóstico Precoce do Diabetes. Disponível em: https://www.previva.com.br/novosite/diagnosticoprecocedodiabetes/. Acesso em: 1 set. 2024.
- AGÊNCIA BRASIL. Diabetes é responsável por mais de 28 amputações por dia no Brasil. Disponível em: https://agenciabrasil.ebc.com.br/saude/noticia/2023-11/diabetes-e-responsavel-por-mais-de-28-amputacoes-por-dia-no-brasil. Acesso em: 1 set. 2024.
- BRASIL. Ministério da Saúde. Diabetes. Disponível em: https://www.gov.br/saude/pt-br/assuntos/saude-de-a-a-z/d/diabetes. Acesso em: 1 set. 2024.

<!-- https://www.sciencedirect.com/science/article/pii/S1413867023001605 -->
<!-- https://www.sciencedirect.com/science/article/pii/S2531137923009707 -->
<!-- https://research.ebsco.com/c/6hyen5/viewer/pdf/ch27syuvyz -->
<!-- https://www.previva.com.br/novosite/diagnosticoprecocedodiabetes/ -->
<!-- https://agenciabrasil.ebc.com.br/saude/noticia/2023-11/diabetes-e-responsavel-por-mais-de-28-amputacoes-por-dia-no-brasil -->
<!-- https://www.gov.br/saude/pt-br/assuntos/saude-de-a-a-z/d/diabetes -->

