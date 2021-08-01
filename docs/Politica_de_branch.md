# Políticas de Branch
## Histórico de versão

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
| 31/07/2021 | 1.0 | Criação da primeira versão do documento | Francisco Emanoel |

## 1. Introdução

Documento destinado a organizar e padronizar as políticas de contribuição para o projeto.

Aqui se encontram:

- Política de Branch

## 2. Políticas de Branch

<p align = "justify"> &emsp;&emsp; As branches do projeto serão dividas de acordo com a sua finalidade principal para manter uma organização no padrão do projeto. A seguir estão as regras de classificação das branches: </p>


### 2.1 Branch master

<p align = "justify"> &emsp;&emsp; A branch <b>master</b> representa uma versão estável do produto, contendo código já testado e versionado, pronto para ser entregue ao usuário final ou cliente. Essa branch parte das branches <b>feature</b> através de pull requests aprovados. </p>

Regras:

1. Existe apenas uma branch **master**.
2. **Não** são permitidos commits feitos diretamente na **master**.


### 2.2 Branches Feature

<p align = "justify"> &emsp;&emsp; As branches <b>feature</b> representam as funcionalidades do sistema a serem desenvolvidas, elas devem ter a branch <b>master</b> como sua origem e fim. </p>

Regras:

1. Essa branch sempre é criada a partir da branch **master**.
2. Antes da abertura de pull request a branch deve ser mesclada à branch **master**.

Regras de nomenclatura:

`feature/issueID-titulo-da-issue`


### 2.3 Branches Release
<p align = "justify"> &emsp;&emsp; A branch <b>release</b> representa o conjunto de funcionalidades provenientes de um ponto específico da branch <b>master</b>. Essa branch contém funcionalidades prontas que, provavelmente, estarão presentes na próxima versão estável do produto. Apenas issues de <b>bug fixes</b> são permitidos nessa branch. </p>

Regras:

1. Essa branch sempre é criada a partir da branch **master**.
2. Essa branch sempre é mesclada à branch **master**.
3. Essa branch aceita apenas mesclagens de branches do tipo **bugfix**.

Regras de nomenclatura:

`release/vNúmero-da-versão`


### 2.4 Branches Bugfix

<p align = "justify"> &emsp;&emsp; As branches do tipo <b>bugfix</b> são utilizadas para implementar soluções para bugs, encontrados através de testes realizados em releases específicas, na branch <b>release</b>. Isso significa que a branch <b>bugfix</b> deve ter a branch <b>release</b> como sua origem e fim. </p>

Regras:

1. Essa branch sempre é criada a partir da branch **release**.
2. Essa branch sempre é mesclada na branch **release**.

Regras de nomenclatura:

`bugfix/issueID-titulo-da-issue`


### 2.5 Branches Hotfix

<p align = "justify"> &emsp;&emsp; A branch <b>hotfix</b> é utilizada para implementar soluções para problemas urgentes encontrados no ambiente de produção. Isso significa que essa branch deve ter a branch <b>master</b> como sua origem e fim. </p>

Regras:

1. Essa branch sempre é criada a partir da branch **master**.
2. Essa branch sempre é mesclada à branch **master**.

Regras de nomenclatura:

`hotfix/issueID-titulo-da-issue`


### 2.6 Branches Docs

<p align = "justify"> &emsp;&emsp; As branches <b>docs</b> representam a geração ou alteração dos documentos do projeto, elas devem ter a branch <b>master</b> como sua origem e fim. </p>

Regras:

1. Essa branch sempre é criada a partir da branch **master**.
2. Antes da abertura de pull request a branch deve ser mesclada à branch **master**. 

Regras de nomenclatura:

`docs/issueID-documento`


## Referências

> Politica de Contribuição Hortum. Disponivel em [https://github.com/fga-eps-mds/2020.2-Hortum/blob/main/docs/Politica_de_Contribuicao.md](https://github.com/fga-eps-mds/2020.2-Hortum/blob/main/docs/Politica_de_Contribuicao.md)
