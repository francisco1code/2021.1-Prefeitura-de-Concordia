# Documento de Metodologia e Processos

## Histórico
|Data|Versão|Descrição|Autor(es)
|--|--|--|--|
|31/07|1.0|Adição do documento de metodologia|Francisco Emanoel e Eliseu Kadesh|  
|07/08|2.0|Refatoração completa por suspeita de plágio|João Pedro|
|07/08|2.1|Junção do documento de branchs e commits|João Pedro|

## 1. Introdução
<p align = "justify"> &emsp;&emsp; Esse documento representa a explicação e os motivos das metodologias que estarão sendo utilizadas no projeto. Com isso, cada metodologia terá uma breve explicação, seu motivo para ser utilizada e quais documentos/artefatos e rituais serão feitos durante a duração desse projeto [1].</p>

## 2. Metodologias
### 2.1 Scrum
<p align = "justify"> &emsp;&emsp; O SCRUM é uma metodologia ágil voltada para a gestão e planejamento de projetos de software. Pelas sua rapidez e versatilidade, o projeto estará fazendo o uso de uma das suas técnicas mais famosas, as <b>Sprints</b>, que permitirão o desenvolvimento em Time Box eficiente. Para então realizar os planejamentos necessários para cada sprint, será utilizada outra metodologia prevista pelo SCRUM, as conhecidas <b>Sprint Plannings</b> [2].</p>

### 2.2 Extreme Programming (XP)
<p align = "justify"> &emsp;&emsp; O Extreme Programming assim como o SCRUM, é uma técnica ágil e que permite respostas rápidas às mudanças. Porém, sua utilização será limitada apenas a alguns conceitos que são definidos pelo XP, em decorrencia da produção apenas de documentos e não de códigos em sí, sendo eles os seus <b>cinco principais valores</b> e as técnicas de <b>Pareamento</b>. Os cinco principais valores são: <b>Simplicidade</b>, <b>Feedback</b>, <b>Coragem</b>, <b>Respeito</b> e <b>Comunicação</b>, que permitem à equipe e ao projeto, feedback rápido, simplicidade, mudanças incrementais, abraço a mudanças e trabalho de qualidade [3].</p>

<p align = "justify"> &emsp;&emsp; E por fim, a técnica de <b>Pareamento</b>, que será utilizada em alguns documentos. Essa metodologia é representada pela junção de dois desenvolvedores que irão trabalhar em uma mesma máquina de forma que, um estará escrevendo a documentação/artefato enquanto outro estará observando, de forma a previnir erros e caso eles aconteçam corrigindo antes de passarem pelo processo de revisão [3].</p>

### 2.3 Política de Commits
<p align = "justify"> &emsp;&emsp; Pela utilização do ambiente de versionamento git, será necessário definir uma política de commits que estará prevendo como os mesmos deverão ser feitos. Essa política então, prevê que os commits deverão ser feitos de forma clara e breve, em português e descrevendo as alterações feitas. O seguinte padrão, portanto, será utilizado:</p>
```
(#NúmeroDaIssue): Comentário do commit
Exemplo: (#5): Adição do documento de metodologias
```

<p align = "justify"> &emsp;&emsp; E para ocasiões onde o commit foi realizado por duas pessoas, a mensagem deverá ser alterada para o seguinte formato:</p>
```
(#NúmeroDaIssue): Commentário do commit
>>
>>
Co-authored-by: Nome do Github <Email utilizado no Github>
```
```
Exemplo: (#5): Adição do documento de metodologias


Co-authored-by: Fábio-Roger<fabioroger@gmail.com>
```
<p align = "justify"> &emsp;&emsp; <b>Observações</b>: Para o funcionamento do Co-authored, é necessário pular duas linhas entre o comentário e a função de co-authored (representado pelos >>). Além disso, também é obrigatório a utilização dos caractéres '<' e '>' entre o email.</p>

### 2.4 Política de Branchs
<p align = "justify"> &emsp;&emsp; Pelo fato do projeto estar utilizando metodologias ágeis a utilização de branchs se faz necessária, principalmente para a organização. Para isso, as branchs deverão seguir um padrão único de nomeclatura, devido a produção apenas de documentos, e que obrigatoriamente sempre se originarão da <b>main</b>. Segue o padrão a ser seguido:</p>
```
X-Nome_do_Documento
Exemplo: 5-Documento_de_Metodologias
```
<p align = "justify"> &emsp;&emsp; <b>Observações</b>: O caractér 'X' deverá ser trocado pelo número da issue que a branch está relacionada. Caso esse número não exista, será utilizado o nome da issue.</p>

## 4. Referências
<p style="text-align: justify; text-indent: 20px">[1] Hortum. <b>Documento de Metodologias e Processos</b>. Disponível em: <a href="https://fga-eps-mds.github.io/2020.2-Hortum/Documento_metodologia/" target="_blank">https://fga-eps-mds.github.io/2020.2-Hortum/Documento_metodologia/</a>. Acesso em: 07 de agosto de 2021</p>
<p style="text-align: justify; text-indent: 20px">[2] SCRUM. Disponível em: <a href="https://www.desenvolvimentoagil.com.br/scrum" target="_blank">https://www.desenvolvimentoagil.com.br/scrum</a>. Acesso em: 07 de agosto de 2021</p>
<p style="text-align: justify; text-indent: 20px">[3] Higor. <b>Introdução ao Extreme Programming (XP)</b>. 2013. Disponível em: <a href="https://www.devmedia.com.br/introducao-ao-extreme-programming-xp/29249" target="_blank">https://www.devmedia.com.br/introducao-ao-extreme-programming-xp/29249</a>. Acesso em: 07 de agosto de 2021</p>