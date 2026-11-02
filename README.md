# Ciência de Dados — Repositório de Atividades Práticas

Repositório oficial para registro de atividades práticas, estudos de caso, exercícios e projetos desenvolvidos ao longo da disciplina de **Ciência de Dados**, ministrada pelo **Prof. Dr. André Fonseca**.

---

## 👤 Identificação do Aluno

- **Nome Completo:** Esdras Felipe
- **Matrícula:** `[Insira sua matrícula aqui]`
- **Curso:** Tecnologia da Informação / Ciência de Dados
- **Docente:** Prof. Dr. André Fonseca
- **Material Oficial da Disciplina:** [Ciência de Dados (oandrefonseca.github.io/data-science)](https://oandrefonseca.github.io/data-science/)

---

## 🧭 Sumário Geral

1. [Identificação do Aluno](#-identificação-do-aluno)
2. [Tabela de Navegação Rápida (Sumário das Aulas)](#-tabela-de-navegação-rápida)
3. [Estrutura do Repositório](#️-estrutura-do-repositório)
4. [Unidade 01 — Fundamentos, Manipulação e Análise Exploratória](#-unidade-01--fundamentos-manipulação-e-análise-exploratória)
   - [Aula 01: Ferramentas, Ambiente e Versionamento](#aula-01--ferramentas-ambiente-e-versionamento)
   - [Aula 02: Introdução aos Dados Tabulares](#aula-02--introdução-aos-dados-tabulares)
   - [Aula 03: Trabalho Final: Análise de Vendas](#aula-03--trabalho-final-análise-de-vendas)
   - [Aula 04: Análise de Vendas em R](#aula-04--análise-de-vendas-em-r)
   - [Tarefa Unidade 1: Projeto de Avaliação](#tarefa-unidade-1--projeto-de-avaliação)
5. [Unidade 02 — Estatística Descritiva e Pré-processamento](#-unidade-02--estatística-descritiva-e-pré-processamento)
   - [Aula 05: Estatística Descritiva](#aula-05--estatística-descritiva)
   - [Aula 06: Imputação e Normalização de Dados](#aula-06--imputação-e-normalização-de-dados)
   - [Tarefa Unidade 2: Projeto de Avaliação](#tarefa-unidade-2--projeto-de-avaliação)
6. [Unidade 03 — Inferência Estatística e Testes de Hipóteses](#-unidade-03--inferência-estatística-e-testes-de-hipóteses)
   - [Aula 07: Estatística Inferencial](#aula-07--estatística-inferencial)
   - [Aula 08: Testes Paramétricos](#aula-08--testes-paramétricos)
   - [Aula 09: Testes Não Paramétricos](#aula-09--testes-não-paramétricos)
   - [Tarefa Unidade 3: Projeto de Avaliação](#tarefa-unidade-3--projeto-de-avaliação)
7. [Bases de Dados Utilizadas](#-bases-de-dados-utilizadas)
8. [Ambiente, Instalação e Reprodutibilidade](#-ambiente-instalação-e-reprodutibilidade)
9. [Diretrizes de Desenvolvimento e Boas Práticas](#-diretrizes-de-desenvolvimento-e-boas-práticas)

---

## 📊 Tabela de Navegação Rápida

A tabela abaixo sintetiza o mapeamento completo das aulas com os roteiros oficiais do professor e os respectivos arquivos de exercícios neste repositório:

| Unidade | Aula / Item | Tema / Conteúdo | Roteiro Oficial do Professor | Arquivo no Repositório | Padrão / Formato |
| :---: | :---: | :--- | :---: | :---: | :--- |
| **01** | Aula 01 | Ferramentas, Ambiente e Versionamento | [Roteiro 01](https://oandrefonseca.github.io/data-science/aulas/01-ferramentas-ambiente-versionamento.html) | [exercicio_aula01.ipynb](./Unidade_01/Aula_01/exercicio_aula01.ipynb) | Código + Análise |
| **01** | Aula 02 | Introdução aos Dados Tabulares | [Roteiro 02](https://oandrefonseca.github.io/data-science/aulas/02-introducao-dados-tabulares.html) | [exercicio_aula02.ipynb](./Unidade_01/Aula_02/exercicio_aula02.ipynb) \| [.qmd](./Unidade_01/Aula_02/exercicio_aula02.qmd) | Código + Análise |
| **01** | Aula 03 | Trabalho Final: Análise de Vendas | [Roteiro 03](https://oandrefonseca.github.io/data-science/aulas/03-analise-vendas.html) | [exercicio_aula03.ipynb](./Unidade_01/Aula_03/exercicio_aula03.ipynb) | Estudo de Caso |
| **01** | Aula 04 | Análise de Vendas em R (tidyverse) | [Roteiro 04](https://oandrefonseca.github.io/data-science/aulas/04-analise-vendas-r.html) | [exercicio_aula04.ipynb](./Unidade_01/Aula_04/exercicio_aula04.ipynb) \| [.qmd](./Unidade_01/Aula_04/exercicio_aula04.qmd) | R / Tidyverse |
| **01** | Projeto 1 | Avaliação Prática — Unidade 01 | [Roteiro 03](https://oandrefonseca.github.io/data-science/aulas/03-analise-vendas.html) | [projeto_unidade1.ipynb](./Unidade_01/Tarefa_Unidade_1/projeto_unidade1.ipynb) | Projeto Avaliativo |
| **02** | Aula 05 | Estatística Descritiva | [Roteiro 05](https://oandrefonseca.github.io/data-science/aulas/05-estatistica-descritiva.html) | [exercicio_aula05.ipynb](./Unidade_02/Aula_05/exercicio_aula05.ipynb) | Código + Análise |
| **02** | Aula 06 | Imputação e Normalização de Dados | [Roteiro 06](https://oandrefonseca.github.io/data-science/aulas/06-imputacao-normalizacao-dados.html) | [exercicio_aula06.ipynb](./Unidade_02/Aula_06/exercicio_aula06.ipynb) \| [.qmd](./Unidade_02/Aula_06/exercicio_aula06.qmd) | Pipeline de Dados |
| **02** | Projeto 2 | Avaliação Prática — Unidade 02 | [Roteiro 06](https://oandrefonseca.github.io/data-science/aulas/06-imputacao-normalizacao-dados.html) | [projeto_unidade2.ipynb](./Unidade_02/Tarefa_Unidade_2/projeto_unidade2.ipynb) | Projeto Avaliativo |
| **03** | Aula 07 | Estatística Inferencial | [Roteiro 07](https://oandrefonseca.github.io/data-science/aulas/07-inferencia-estatistica.html) | [exercicio_aula07.ipynb](./Unidade_03/Aula_07/exercicio_aula07.ipynb) | Código + Análise |
| **03** | Aula 08 | Testes Paramétricos | [Roteiro 08](https://oandrefonseca.github.io/data-science/aulas/08-testes-parametricos.html) | [exercicio_aula08.ipynb](./Unidade_03/Aula_08/exercicio_aula08.ipynb) | Código + Análise |
| **03** | Aula 09 | Testes Não Paramétricos | [Roteiro 09](https://oandrefonseca.github.io/data-science/aulas/09-testes-nao-parametricos.html) | [exercicio_aula09.ipynb](./Unidade_03/Aula_09/exercicio_aula09.ipynb) | Código + Análise |
| **03** | Projeto 3 | Avaliação Prática — Unidade 03 | [Roteiro 09](https://oandrefonseca.github.io/data-science/aulas/09-testes-nao-parametricos.html) | [projeto_unidade3.ipynb](./Unidade_03/Tarefa_Unidade_3/projeto_unidade3.ipynb) | Projeto Avaliativo |

---

## 🗂️ Estrutura do Repositório

A hierarquia de pastas segue rigorosamente as recomendações de padronização (sem espaços, sem acentuação, nomes descritivos em `Unidade_XX`, `Aula_YY` e `Tarefa_Unidade_X`):

```text
repositorio-ciencias-dados/
├── README.md                                 # Documento principal de apresentação e sumário
├── .gitignore                                # Exclusão de caches, .venv e dados pesados
├── requirements.txt                          # Especificação de dependências reproduzíveis
│
├── Unidade_01/
│   ├── Aula_01/
│   │   └── exercicio_aula01.ipynb            # Ferramentas, Ambiente e Versionamento
│   ├── Aula_02/
│   │   ├── exercicio_aula02.ipynb            # Introdução aos Dados Tabulares
│   │   └── exercicio_aula02.qmd
│   ├── Aula_03/
│   │   └── exercicio_aula03.ipynb            # Análise de Vendas (Estudo de Caso)
│   ├── Aula_04/
│   │   ├── exercicio_aula04.ipynb            # Análise de Vendas em R (tidyverse)
│   │   └── exercicio_aula04.qmd
│   └── Tarefa_Unidade_1/
│       └── projeto_unidade1.ipynb            # Projeto avaliativo da Unidade 01
│
├── Unidade_02/
│   ├── Aula_05/
│   │   └── exercicio_aula05.ipynb            # Estatística Descritiva
│   ├── Aula_06/
│   │   ├── exercicio_aula06.ipynb            # Imputação e Normalização de Dados
│   │   └── exercicio_aula06.qmd
│   └── Tarefa_Unidade_2/
│       └── projeto_unidade2.ipynb            # Projeto avaliativo da Unidade 02
│
└── Unidade_03/
    ├── Aula_07/
    │   └── exercicio_aula07.ipynb            # Estatística Inferencial
    ├── Aula_08/
    │   └── exercicio_aula08.ipynb            # Testes Paramétricos
    ├── Aula_09/
    │   └── exercicio_aula09.ipynb            # Testes Não Paramétricos
    └── Tarefa_Unidade_3/
        └── projeto_unidade3.ipynb            # Projeto avaliativo da Unidade 03
```

---

## 📘 Unidade 01 — Fundamentos, Manipulação e Análise Exploratória

### [Aula 01: Ferramentas, Ambiente e Versionamento](./Unidade_01/Aula_01/)
- **Roteiro Oficial:** [Aula 1 — Ferramentas, Ambiente e Versionamento](https://oandrefonseca.github.io/data-science/aulas/01-ferramentas-ambiente-versionamento.html)
- **Arquivo Prático:** [exercicio_aula01.ipynb](./Unidade_01/Aula_01/exercicio_aula01.ipynb)
- **Tópicos Abordados:** Estrutura profissional de pastas de projetos de dados, comandos essenciais de terminal (`cd`, `ls`, `mkdir`), fundamentos de Git local (área de trabalho, staging area e repositório com `git init`, `status`, `add`, `commit`), gerenciamento de ambientes virtuais (`uv`, `venv`, `pip`), o papel do `.gitignore` para proteção contra vazamento de credenciais e integridade de dados, e especificação de reprodutibilidade via `requirements.txt`.
- **Perguntas de Consolidação:** O colega cético (isolamento de ambientes), Ignorar não é proteger (estratégias de backup vs versionamento), e o Teste definitivo de reprodutibilidade ao clonar o projeto.

### [Aula 02: Introdução aos Dados Tabulares](./Unidade_01/Aula_02/)
- **Roteiro Oficial:** [Aula 2 — Introdução aos Dados Tabulares](https://oandrefonseca.github.io/data-science/aulas/02-introducao-dados-tabulares.html)
- **Arquivos Práticos:** [exercicio_aula02.ipynb](./Unidade_01/Aula_02/exercicio_aula02.ipynb) \| [exercicio_aula02.qmd](./Unidade_01/Aula_02/exercicio_aula02.qmd)
- **Tópicos Abordados:** Estrutura fundamental de dados tabulares (observações e variáveis), pandas (`Series` e `DataFrame`), e o **Ritual de Inspeção Inicial em 5 Passos**:
  1. *Dimensões da base:* `shape` (linhas × colunas);
  2. *Tipos primitivos:* `dtypes` e detecção de coerções inadequadas;
  3. *Valores ausentes:* `isna().sum()` e diagnóstico de completude;
  4. *Duplicatas:* `duplicated().sum()` e verificação de chaves primárias;
  5. *Estatística sumária:* `describe()` para identificar mínimos, máximos e indícios de anomalias (ex.: quantidades negativas e preços unitários zerados).
- **Perguntas de Consolidação:** `CustomerID` float e valores `NaN`, a documentação oficial contra os dados reais, e o repositório sem os dados brutos.

### [Aula 03: Trabalho Final: Análise de Vendas](./Unidade_01/Aula_03/)
- **Roteiro Oficial:** [Aula 3 — Trabalho Final: Análise de Vendas](https://oandrefonseca.github.io/data-science/aulas/03-analise-vendas.html)
- **Arquivo Prático:** [exercicio_aula03.ipynb](./Unidade_01/Aula_03/exercicio_aula03.ipynb)
- **Tópicos Abordados:** Formulação e resposta a perguntas de negócio orientadas por dados reais (dataset Online Retail):
  - Definição do recorte analítico de **vendas válidas** (exclusão criteriosa de cancelamentos prefixados com `C`, itens com preço zerado e ajustes de inventário);
  - Indicadores-chave: faturamento total, ticket médio por transação, clientes mais valiosos e produtos líderes em volume e receita;
  - Quantificação do impacto de devoluções e cancelamentos;
  - Evolução mensal do faturamento e identificação de sazonalidade.

### [Aula 04: Análise de Vendas em R](./Unidade_01/Aula_04/)
- **Roteiro Oficial:** [Aula 4 — Análise de Vendas em R](https://oandrefonseca.github.io/data-science/aulas/04-analise-vendas-r.html)
- **Arquivos Práticos:** [exercicio_aula04.ipynb](./Unidade_01/Aula_04/exercicio_aula04.ipynb) \| [exercicio_aula04.qmd](./Unidade_01/Aula_04/exercicio_aula04.qmd)
- **Tópicos Abordados:** Reprodução das transformações e métricas da Aula 03 utilizando o ecossistema R e `tidyverse` (`readxl`, `dplyr`, `ggplot2`). Análise comparativa entre os paradigmas de programação funcional e encadeamento com *pipe* (`|>`) versus a abordagem orientada a objetos do pandas.

### [Tarefa Unidade 1: Projeto de Avaliação](./Unidade_01/Tarefa_Unidade_1/)
- **Arquivo de Entrega:** [projeto_unidade1.ipynb](./Unidade_01/Tarefa_Unidade_1/projeto_unidade1.ipynb)
- **Descrição:** Relatório analítico completo consolidando os indicadores de vendas, diagnóstico de qualidade dos dados, fundamentação escrita das escolhas de exclusão/recorte e formulação de recomendações práticas para a tomada de decisão gerencial.

---

## 📗 Unidade 02 — Estatística Descritiva e Pré-processamento

### [Aula 05: Estatística Descritiva](./Unidade_02/Aula_05/)
- **Roteiro Oficial:** [Aula 5 — Estatística Descritiva](https://oandrefonseca.github.io/data-science/aulas/05-estatistica-descritiva.html)
- **Arquivo Prático:** [exercicio_aula05.ipynb](./Unidade_02/Aula_05/exercicio_aula05.ipynb)
- **Tópicos Abordados:**
  - Medidas de tendência central: média aritmética simples, média ponderada por volume, mediana e moda;
  - Medidas de dispersão: variância amostral, desvio-padrão e amplitude interquartil ($IQR = Q_3 - Q_1$);
  - Assimetria (*skewness*): distribuições simétricas, assimétricas positivas (cauda longa à direita) e negativas;
  - Curtose (*kurtosis*): formas leptocúrtica (caudas pesadas), mesocúrtica (normal) e platicúrtica (caudas leves);
  - Diagnóstico de *outliers* via critério de Tukey ($1{,}5 \times IQR$).
- **Perguntas de Consolidação:** Escolha do ticket médio representativo diante de assimetria severa; limites da regra mecânica do IQR na presença de clientes atacadistas; distinção entre população observada e processo gerador contínuo (amostra).

### [Aula 06: Imputação e Normalização de Dados](./Unidade_02/Aula_06/)
- **Roteiro Oficial:** [Aula 6 — Imputação e Normalização de Dados](https://oandrefonseca.github.io/data-science/aulas/06-imputacao-normalizacao-dados.html)
- **Arquivos Práticos:** [exercicio_aula06.ipynb](./Unidade_02/Aula_06/exercicio_aula06.ipynb) \| [exercicio_aula06.qmd](./Unidade_02/Aula_06/exercicio_aula06.qmd)
- **Tópicos Abordados:**
  - Taxonomia de ausência: MCAR (*Missing Completely at Random*), MAR (*Missing at Random*) e MNAR (*Missing Not at Random*);
  - Técnicas de imputação: exclusão listwise, imputação por mediana e abordagens multivariadas (KNN / IterativeImputer);
  - Escalonamento: `StandardScaler` (z-score), `MinMaxScaler` e `RobustScaler` (baseado em mediana e IQR para resistir a outliers);
  - Transformações não-lineares: logarítmica ($\log(1+x)$), Box-Cox e Yeo-Johnson para estabilização de variância e aproximação da normalidade no dataset imobiliário.

### [Tarefa Unidade 2: Projeto de Avaliação](./Unidade_02/Tarefa_Unidade_2/)
- **Arquivo de Entrega:** [projeto_unidade2.ipynb](./Unidade_02/Tarefa_Unidade_2/projeto_unidade2.ipynb)
- **Descrição:** Construção de pipeline robusto de pré-processamento, engenharia de atributos, tratamento de ausentes, mitigação de assimetria extrema e documentação das transformações sem induzir vazamento de dados (*data leakage*).

---

## 📙 Unidade 03 — Inferência Estatística e Testes de Hipóteses

### [Aula 07: Estatística Inferencial](./Unidade_03/Aula_07/)
- **Roteiro Oficial:** [Aula 7 — Estatística Inferencial](https://oandrefonseca.github.io/data-science/aulas/07-inferencia-estatistica.html)
- **Arquivo Prático:** [exercicio_aula07.ipynb](./Unidade_03/Aula_07/exercicio_aula07.ipynb)
- **Tópicos Abordados:**
  - Formulação de hipótese nula ($H_0$) e hipótese alternativa ($H_1$);
  - Distribuição amostral da média e Teorema Central do Limite;
  - Teste de permutação (abordagem exata por reamostragem computacional);
  - Teste $t$ de Student, estatística de teste, graus de liberdade e $p$-valor;
  - Erros do Tipo I ($\alpha$) e Tipo II ($\beta$), poder estatístico ($1 - \beta$);
  - Tamanho do efeito com $d$ de Cohen e controle de variáveis confundidoras.
- **Perguntas de Consolidação:** O que o $p$-valor realmente informa e o que ele não mede; diferença entre significância estatística e relevância prática; cenários de divergência entre teste $t$ e teste de permutação.

### [Aula 08: Testes Paramétricos](./Unidade_03/Aula_08/)
- **Roteiro Oficial:** [Aula 8 — Testes Paramétricos](https://oandrefonseca.github.io/data-science/aulas/08-testes-parametricos.html)
- **Arquivo Prático:** [exercicio_aula08.ipynb](./Unidade_03/Aula_08/exercicio_aula08.ipynb)
- **Tópicos Abordados:**
  - Premissas: normalidade dos resíduos (Shapiro-Wilk, Q-Q Plot), homocedasticidade (Levene) e independência das observações;
  - Aplicação dos 7 casos clássicos de decisão:
    1. *Teste $t$ para uma amostra* (comparação contra valor de referência);
    2. *Teste $t$ de Welch* (duas amostras independentes com variâncias heterogêneas);
    3. *Teste $t$ pareado* (mesma unidade amostral em momentos distintos);
    4. *ANOVA One-Way* (comparação de médias entre 3 ou mais grupos);
    5. *Coeficiente de Correlação linear de Pearson*;
    6. *Teste Z para duas proporções*;
    7. *Teste Qui-quadrado de Independência* ($\chi^2$).

### [Aula 09: Testes Não Paramétricos](./Unidade_03/Aula_09/)
- **Roteiro Oficial:** [Aula 9 — Testes Não Paramétricos](https://oandrefonseca.github.io/data-science/aulas/09-testes-nao-parametricos.html)
- **Arquivo Prático:** [exercicio_aula09.ipynb](./Unidade_03/Aula_09/exercicio_aula09.ipynb)
- **Tópicos Abordados:**
  - Transformação de observações em postos (*ranks*) e tratamento de empates;
  - Teste $U$ de Mann-Whitney (Wilcoxon Rank-Sum) para dominância estocástica;
  - Aproximação normal com distribuição $Z$ para amostras moderadas e grandes;
  - Tamanho do efeito não paramétrico: $\delta$ de Cliff;
  - Correlação monotônica de postos de Spearman vs Correlação linear de Pearson em distribuições com caudas pesadas e observações alavancadas.

### [Tarefa Unidade 3: Projeto de Avaliação](./Unidade_03/Tarefa_Unidade_3/)
- **Arquivo de Entrega:** [projeto_unidade3.ipynb](./Unidade_03/Tarefa_Unidade_3/projeto_unidade3.ipynb)
- **Descrição:** Aplicação completa de testes de hipótese a um problema empírico de dados, justificando a escolha metodológica (paramétrica vs não paramétrica), validando premissas, calculando tamanho de efeito e convertendo achados estatísticos em recomendações acionáveis.

---

## 📦 Bases de Dados Utilizadas

Em consonância com as instruções de reprodutibilidade da disciplina, os arquivos de dados brutos não são versionados no Git (conforme regras em `.gitignore`). As instruções de obtenção e citação encontram-se abaixo:

1. **Online Retail Dataset (Aulas 02, 03, 04, 05):**
   - *Origem:* UCI Machine Learning Repository (ID 352).
   - *Licença:* Creative Commons Attribution 4.0 International (CC BY 4.0).
   - *Citação:* Chen, D. (2015). Online Retail [Dataset]. UCI Machine Learning Repository. [https://doi.org/10.24432/C5BW33](https://doi.org/10.24432/C5BW33).
   - *Instruções:* Baixar do repositório UCI e salvar como `online_retail.xlsx`.

2. **Mercado Imobiliário de São Paulo (Aula 06):**
   - *Arquivo:* `imoveis_sao_paulo.csv`.
   - *Conteúdo:* Dados cadastrais e valores de aluguel para análise de imputação e escalonamento.

3. **Datasets Clássicos de Benchmark (Aulas 07, 08, 09):**
   - `mtcars.csv`: Consumo e atributos mecânicos de automóveis.
   - `sleep.csv`: Estudo clínico de fármacos para aumento do tempo de sono (Student, 1908).
   - `iris.csv`: Medições morfométricas de sépalas e pétalas (Fisher, 1936).
   - `penguins.csv`: Dados biométricos de pinguins do arquipélago Palmer.
   - `titanic.csv`: Demografia e sobrevivência de passageiros.

---

## 🛠️ Ambiente, Instalação e Reprodutibilidade

Para recriar o ambiente de desenvolvimento idêntico em qualquer máquina:

```bash
# 1. Clone o repositório
git clone https://github.com/esdrasfelipe/repositorio-ciencias-dados.git
cd repositorio-ciencias-dados

# 2. Crie e ative um ambiente virtual isolado
python3 -m venv .venv
source .venv/bin/activate    # No Linux/macOS
# .venv\Scripts\activate     # No Windows

# 3. Instale as dependências com versões especificadas
pip install -r requirements.txt
```

---

## 📋 Diretrizes de Desenvolvimento e Boas Práticas

- **Código + Análise:** Todo bloco de código relevante deve ser imediatamente acompanhado de um bloco de texto (Markdown) com interpretação crítica dos resultados numéricos e gráficos.
- **Padronização:** Respeitar a nomenclatura de diretórios (`Unidade_XX`, `Aula_YY`, `exercicio_aulaYY`), sem caracteres especiais ou espaços.
- **Commits Frequentes:** Registrar o progresso do desenvolvimento com commits atômicos, claros e descritivos no Git à medida que as tarefas forem concluídas.
- **Reprodutibilidade:** Garantir que todos os notebooks possam ser executados de cima a baixo com *Kernel -> Restart & Run All* sem interrupções.
