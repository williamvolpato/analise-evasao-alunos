# Análise de Evasão Acadêmica

Este repositório contém um projeto de análise e predição relacionado à evasão de alunos em uma instituição de ensino superior. O objetivo é identificar quais alunos têm maior probabilidade de evasão, permitindo que ações preventivas sejam tomadas para aumentar o engajamento acadêmico.

## Contexto

A evasão acadêmica é um dos maiores desafios enfrentados por instituições de ensino. Identificou-se que a falta de engajamento e a não participação em avaliações opcionais aplicadas no meio do semestre estão fortemente relacionadas à evasão de alunos. Este projeto visa analisar os dados acadêmicos e desenvolver um modelo de Machine Learning para prever a probabilidade de evasão, com base no comportamento dos alunos em diferentes disciplinas.

## Dados Utilizados

Os dados foram fornecidos pela instituição e incluem:

- **Alunos e Disciplinas:** Informações sobre matrículas dos alunos em disciplinas específicas.
- **Acessos ao Conteúdo Digital:** Logs de acessos a materiais de estudo.
- **Provas Realizadas:** Registros das provas realizadas pelos alunos.

⚠️ **Nota:** Por questões de privacidade, os arquivos de dados originais não estão incluídos neste repositório. Apenas o notebook com a solução é fornecido.

## Solução Desenvolvida

O projeto segue as etapas abaixo:

1. **Leitura dos Dados:** Carregamento das tabelas brutas para exploração inicial.
2. **Análise Exploratória de Dados (EDA):** Visualizações e estatísticas descritivas para compreender padrões nos dados. Por exemplo:
   - A maioria dos alunos que evadiram não realizou provas no meio do semestre.
   - A média de acessos ao conteúdo digital foi significativamente menor entre os alunos que evadiram.
3. **Criação de Features:** Transformação e agregação dos dados para criar variáveis relevantes para o modelo.
4. **União de Tabelas:** Integração das informações em uma única tabela por aluno-disciplina.
5. **Pré-Processamento:** Normalização e preparação dos dados para Machine Learning.
6. **Divisão dos Dados:** Separação em conjuntos de treino e teste.
7. **Modelagem:** Escolha de algoritmo, treinamento do modelo e definição de métricas de avaliação.
8. **Avaliação do Modelo:** Análise da performance e interpretação dos resultados.

## Resultados

- **Métrica de Performance:** O modelo apresentou uma acurácia de 87% no conjunto de teste.
- **Insights Relevantes:**
  - A ausência de realização de avaliações no meio do semestre é um forte indicador de evasão.
  - Alunos com menor engajamento em conteúdos digitais têm maior probabilidade de evadir.

Gráficos e estatísticas relevantes foram apresentados no notebook, destacando os padrões encontrados.

## Ferramentas Utilizadas

- **Linguagem:** Python
- **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
  
## Como Usar

1. Clone este repositório:
   ```bash
   https://github.com/williamvolpato/analise-evasao-alunos
   ```
2. Abra o arquivo `.ipynb` em sua ferramenta de preferência (como Jupyter Notebook ou Google Colab).
3. Siga as instruções no notebook para explorar e compreender a solução.

## Licença

Este projeto é disponibilizado apenas para fins educacionais e de demonstração. Dados e resultados são fictícios, criados para exemplificar uma solução técnica.

---

Sinta-se à vontade para contribuir com melhorias ou sugestões!
