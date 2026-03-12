
# ECS–BRKGA Research

Repositório oficial do projeto de pesquisa sobre **Evolutionary Clustering Search (ECS)** e **Biased Random-Key Genetic Algorithm (BRKGA)**.

O objetivo deste repositório é centralizar **documentação técnica, reuniões, experimentos computacionais e referências científicas** relacionadas ao desenvolvimento e avaliação de algoritmos evolutivos híbridos.

---

## Visão geral do projeto

Este projeto investiga estratégias de **otimização combinatória e metaheurísticas evolutivas**, com foco especial em:

- **Evolutionary Clustering Search (ECS)**
- **Clustering Search (CS)**
- **Biased Random-Key Genetic Algorithm (BRKGA)**
- técnicas de **transfer learning em otimização**
- aplicações em problemas clássicos de otimização

O projeto também busca desenvolver **infraestrutura experimental reproduzível**, permitindo que a equipe execute e compare algoritmos de forma organizada.

---

## Base científica

Este trabalho é fundamentado principalmente nos seguintes artigos:

**Detecting Promising Areas by Evolutionary Clustering Search**

Oliveira, A.C.M.; Lorena, L.A.N.  
Brazilian Symposium on Artificial Intelligence – SBIA (2004)  
Springer

Introduz o método **Evolutionary Clustering Search (ECS)**, no qual um algoritmo evolucionário gera soluções enquanto um processo de clustering identifica regiões promissoras do espaço de busca.

---

**Hybrid Evolutionary Algorithms and Clustering Search**

Oliveira, A.C.M.; Lorena, L.A.N.  
Hybrid Evolutionary Algorithms (2007)  
Springer

Generaliza a abordagem para **Clustering Search (*CS)**, permitindo integração com diferentes metaheurísticas.

---

## Objetivos do repositório

Este repositório foi criado para:

- organizar a **documentação do projeto**
- registrar **atas e relatórios de reuniões**
- versionar **notebooks e experimentos**
- centralizar **referências científicas**
- facilitar **colaboração da equipe**
- manter **reprodutibilidade dos experimentos**

---

## Estrutura do projeto

```text

ecs-brkga-research
│
├── docs/
│   ├── index.html
│   │
│   ├── meetings/
│   │   ├── 2026-03-10-relatorio-reuniao/
│   │   │   └── index.html
│   │   └── README.md
│   │
│   ├── reports/
│   ├── papers/
│   └── references/
│
├── experiments/
│   └── transfer-learning-brkga/
│       ├── TransferOptimizationLearning_BRKGA_Compartilhado.ipynb
│       └── README.md
│
├── src/
│
├── data/
│
├── assets/
│
├── pyproject.toml
├── .python-version
├── .gitignore
└── README.md

```

---

## Organização das pastas

### docs/

Documentação do projeto e conteúdo publicado no **GitHub Pages**.

Inclui:

- relatórios de reuniões
- documentação técnica
- relatórios executivos
- páginas HTML navegáveis

---

### docs/meetings/

Registros formais das reuniões do projeto.

Cada reunião deve seguir a convenção:

```

YYYY-MM-DD-nome-da-reuniao

```

Exemplo:

```

2026-03-10-relatorio-reuniao

```

Conteúdo possível:

- relatório HTML
- PDF exportado
- imagens e anexos

---

### experiments/

Contém **notebooks e experimentos exploratórios**.

Exemplos:

- testes de algoritmos
- protótipos
- experimentos preliminares
- análise de resultados

---

### src/

Código consolidado do projeto.

Esta pasta deve conter implementações estáveis dos algoritmos estudados.

---

### data/

Dados utilizados nos experimentos:

- instâncias de problemas
- datasets
- arquivos auxiliares

---

### assets/

Imagens, diagramas e recursos visuais utilizados na documentação.

---

## Ambiente de desenvolvimento

Este projeto utiliza:

- **Python**
- **pyenv** para controle da versão do Python
- **uv** para gerenciamento de dependências e ambientes virtuais

---

## Configuração do ambiente

### 1 — Selecionar versão do Python

```

pyenv local 3.12.8

```

---

### 2 — Criar ambiente virtual

```

uv venv

```

---

### 3 — Ativar ambiente

Linux / Mac:

```

source .venv/bin/activate

```

Windows (Git Bash):

```

source .venv/Scripts/activate

```

---

### 4 — Sincronizar dependências

```

uv sync

```

---

## GitHub Pages

A documentação do projeto é publicada via **GitHub Pages** utilizando a pasta:

```

docs/

```

Configuração recomendada:

```

Branch: main
Folder: /docs

```

Após ativação, o site ficará disponível em:

```

[https://fredericmenezes.github.io/ecs-brkga-research/](https://fredericmenezes.github.io/ecs-brkga-research/)

```

---

## Primeira reunião registrada

Relatório disponível em:

```

docs/meetings/2026-03-10-relatorio-reuniao/

```

Tema:

**Planejamento da implementação e experimentação de ECS vs BRKGA**

Data:

10/03/2026

---

## Boas práticas do projeto

Para manter a organização do repositório:

- registrar reuniões na pasta `docs/meetings`
- manter experimentos em `experiments`
- mover código consolidado para `src`
- documentar decisões importantes
- manter experimentos reproduzíveis

---

## Equipe

Projeto conduzido por:

**Prof. Alexandre**

Colaboração de:

- Dadilton
- Frederic Menezes Ferreira
- estudantes e colaboradores vinculados ao projeto

---

## Licença

Este repositório é destinado a **pesquisa acadêmica**.

A licença será definida conforme a evolução do projeto e futuras publicações.

---

## Contato

Para informações sobre o projeto ou colaboração:

Frederic Menezes Ferreira

