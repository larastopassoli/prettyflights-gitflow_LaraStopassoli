\# Diretrizes GitFlow - PrettyFlights



\## Objetivo



Aplicar a estratégia GitFlow no projeto do Totem de Check-in da PrettyFlights, simulando o fluxo de desenvolvimento da versão 1.0.0.



\---



\## Etapas Realizadas



\### 1. Criação do Repositório



Foi criado um repositório público no GitHub chamado:



prettyflights-gitflow\_LaraStopassoli



\---



\### 2. Inicialização do Projeto



O repositório foi clonado localmente e foi criado o arquivo README.md para iniciar o projeto.



Commit realizado:



chore: initial project setup



\---



\### 3. Criação da Branch Develop



Foi criada a branch permanente develop para centralizar o desenvolvimento das funcionalidades.



Comandos utilizados:



git checkout -b develop

git push origin develop



\---



\### 4. Desenvolvimento da Feature



Foi criada a branch temporária:



feature/checkin-validacao



Nessa branch foi adicionada uma funcionalidade de validação do check-in do totem.



Commit realizado:



feat: implement check-in validation rules



Após o desenvolvimento, a feature foi integrada na branch develop.



\---



\### 5. Criação da Release 1.0.0



Foi criada a branch:



release/1.0.0



Nela foram adicionadas as notas da versão.



Commit realizado:



release: prepare version 1.0.0



A release foi integrada na branch main e também na develop.



Foi criada a tag:



v1.0.0



\---



\### 6. Correção Emergencial com Hotfix



Foi criado um hotfix a partir da branch main:



hotfix/correcao-login



Nessa branch foi realizada uma correção emergencial relacionada ao login do totem.



Commit realizado:



fix: correct login validation bug



O hotfix foi integrado tanto na branch main quanto na branch develop.



Foi criada a tag:



v1.0.1



\---



\## Conclusão



A estratégia GitFlow permite organizar o fluxo de desenvolvimento do software de forma estruturada, separando funcionalidades, releases e correções emergenciais em branches específicas.



Também foram utilizadas boas práticas como Semantic Versioning e Conventional Commits para padronização do versionamento e do histórico do projeto.

