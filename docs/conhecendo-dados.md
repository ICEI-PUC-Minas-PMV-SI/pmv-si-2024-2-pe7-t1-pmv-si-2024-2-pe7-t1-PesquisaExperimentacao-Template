# Conhecendo os dados

A análise descritiva dos dados se baseia em uma amostra de 520 pessoas, composta por 63% homens (328) e 37% mulheres (192). Entre os participantes, 61% testaram positivo para diabetes, distribuídos entre 147 homens e 173 mulheres, enquanto 39% testaram negativo, com 181 homens e 19 mulheres. A idade foi dividida em três grupos: menos de 30 anos (45 pessoas), entre 30 e 60 anos (420 pessoas), e mais de 60 anos (80 pessoas). O conjunto de dados também inclui variáveis relacionadas a sintomas clínicos associados à diabetes, como Polyuria, Polydipsia, coceira, cicatrização tardia, perda de peso repentina e visão embaçada. Essas variáveis foram analisadas em busca de correlações, especialmente com a presença de diabetes, e indicaram interações entre diferentes sintomas. A distribuição de obesidade na amostra também foi destacada, com foco nas relações entre obesidade e diabetes.

## Descrição dos achados

A análise dos dados fornecidos revela informações importantes sobre a distribuição e as correlações associadas à presença de diabetes em uma amostra de 520 pessoas. Dentre os pesquisados, 320 pessoas (61%) são positivas para diabetes, sendo 147 homens e 173 mulheres. Em contraste, 200 pessoas (39%) testaram negativo para diabetes, das quais 181 são homens e 19 são mulheres. Essa distribuição, no universo analisado, aponta uma assimetria significativa entre os gêneros, com mais mulheres diagnosticadas com diabetes, enquanto a maioria dos homens na amostra são negativos para a doença. Isso sugere uma possível relação entre gênero e a prevalência de diabetes, mas é importante destacar que a literatura[^1] indica que no geral, a prevalência global de diabetes é maior em homens, mas há mais mulheres com diabetes tipo 2 do que homens.

### Análises Gráficas

#### Distribuição por Faixa Etária

Ao analisar as faixas etárias, observa-se que a incidência de diabetes aumenta consideravelmente com o avanço da idade. Entre os menores de 30 anos, apenas 33% têm diabetes, enquanto entre os indivíduos com idade entre 30 e 60 anos, essa proporção sobe para 61%, e, entre os maiores de 60 anos, atinge 70%. Esse padrão é consistente com a literatura médica, que sugere um aumento da prevalência de diabetes à medida que as pessoas envelhecem.

![Gráfico de distribuição por faixa etária](https://github.com/user-attachments/assets/c64e3068-caff-4d0a-a197-db108b0db2bc)

#### Correlações Clínicas

Em termos de correlações clínicas, a análise por meio de um heatmap sugere que Polyuria (micção excessiva) e Polydipsia (sede excessiva) estão fortemente associadas tanto entre si quanto com a presença de diabetes, o que é esperado, já que esses sintomas são comumente observados em pacientes com a doença [^2]. A idade também parece se correlacionar com vários dos parâmetros clínicos, reforçando a ideia de que o risco de diabetes aumenta com o envelhecimento [^3].

![Heatmap das correlações clínicas](https://github.com/user-attachments/assets/2b003015-b134-47d1-89ed-ea3a1bc34247)

Curiosamente, a associação entre obesidade e diabetes na amostra analisada é menor do que o esperado. Apenas 19,06% das pessoas com diabetes também apresentam obesidade, um número inferior ao que se observa em muitas populações, onde a obesidade é um fator de risco importante para o desenvolvimento de diabetes tipo 2. Esse resultado pode indicar a presença de outros fatores, como predisposição genética ou hábitos de vida específicos, que não foram capturados pelos dados.

Além dos sintomas clássicos como Polydipsia, presente em 70,31% das pessoas com diabetes, outros sinais notáveis incluem coceira (48,13%), cicatrização tardia (47,81%), perda de peso repentina (58,75%) e visão embaçada (54,69%). A análise também revelou que 57,50% das pessoas com diabetes apresentam, simultaneamente, obesidade e Polydipsia, sugerindo uma interação relevante entre esses dois fatores.

#### Análises Multivaloradas de Sintomas

A análise multivalorada revela insights adicionais sobre a associação entre sintomas específicos e diabetes:

- **Polidipsia:** 70,31% das pessoas com diabetes apresentaram Polidipsia.

  ![Gráfico de correlação com Polidipsia](https://github.com/user-attachments/assets/b1608371-9804-4f69-971b-87d0795de231)

  ![Gráfico de correlação com Polidipsia](https://github.com/user-attachments/assets/6bf4f5fd-cf2f-47a1-8d5b-96b5f5fc93e1)

- **Coceira:** 48,13% das pessoas com diabetes apresentaram coceira.

  ![Gráfico de correlação com Coceira](https://github.com/user-attachments/assets/d2217a27-9d4b-4b13-8ea2-192c60eb3a48)

- **Cicatrização Tardia:** 47,81% das pessoas com diabetes apresentaram cicatrização tardia.

  ![Gráfico de correlação com Cicatrização Tardia](https://github.com/user-attachments/assets/4bd960a6-257f-452a-9d5f-ae019036049a)

- **Perda de Peso Repentina:** 58,75% das pessoas com diabetes apresentaram perda de peso repentina.

  ![Gráfico de correlação com Perda de Peso Repentina](https://github.com/user-attachments/assets/d11f6fcc-d399-4b78-aec1-1e05c3926548)

- **Visão Embaçada:** 54,69% das pessoas com diabetes apresentaram visão embaçada.

  ![Gráfico de correlação com Visão Embaçada](https://github.com/user-attachments/assets/e875da58-3100-4e87-9c5e-9f4942f8632e)

- **Obesidade e Polidipsia:** 57,50% das pessoas com diabetes apresentavam concomitantemente obesidade e Polidipsia.
  - O número total de pessoas que testaram positivo para diabetes e apresentaram concomitantemente obesidade e Polidipsia é de 184 pessoas.
  - O número total de pessoas com obesidade que fazem parte do universo analisado é de 320 pessoas.
  
  ![Gráfico de correlação com Obesidade e Polidipsia](https://github.com/user-attachments/assets/37d745dd-e9c8-4681-8106-1edbbe4d3b0a)

## Ferramentas utilizadas

- Notebook Jupyter: Empregado para a análise exploratória e a criação de visualizações, como o heatmap das correlações entre os sintomas e a presença de diabetes.
- Google Sheets: Utilizado para organizar e manipular os dados de forma estruturada, facilitando a preparação para as análises subsequentes.
- Google Looker Studio (antigo Google Data Studio): Ferramenta utilizada para criar dashboards e visualizações gráficas mais avançadas, incluindo gráficos de distribuição etária e análise de correlação multivalorada.

[^1]: [Influence of Gender in Diabetes Mellitus and Its Complication](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9408508/)
[^2]: ["What Are the 3 P’s of Diabetes?" - Healthline](https://www.healthline.com/health/diabetes/3-ps-of-diabetes)
[^3]: [The Interaction Between Age and Risk Factors for Diabetes and Prediabetes: A Community-Based Cross-Sectional Study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9843502/)

