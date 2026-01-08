# Curso TMW Git \& GitHub 2025



Este repositório acompanha o Curso TMW Git \& GitHub 2025, com foco na aprendizagem e aplicação prática de versionamento de código, controle de versões distribuído e colaboração em repositórios remotos utilizando Git e GitHub.



O curso aborda os principais componentes do ecossistema Git, incluindo:



* inicialização e organização de repositórios;
* uso consistente de commits e histórico de versões;
* criação e gerenciamento de branches;
* integração de alterações por meio de pull requests;
* aplicação do GitFlow como estratégia de organização do desenvolvimento;
* integração do Git ao Visual Studio Code como ambiente de trabalho.



Do ponto de vista metodológico, este repositório reflete a adoção de boas práticas para pesquisa orientada a dados, especialmente relevantes para Ciência Política e Ciências Sociais Aplicadas, onde código, dados e resultados analíticos precisam ser:



* **reprodutíveis**, permitindo a replicação de análises e a verificação de resultados;
* **transparentes**, com rastreabilidade clara das decisões técnicas e analíticas;
* **versionados**, garantindo controle sobre alterações em scripts, bases de dados e documentação;
* **colaborativos**, possibilitando revisões, auditorias e contribuições externas.



O uso do Git é tratado como parte integrante do pipeline analítico, desde a exploração de dados até a produção de resultados, relatórios e visualizações, alinhando práticas de desenvolvimento de software às exigências de rigor científico e pesquisa aplicada.



Este repositório funciona, portanto, como um registro técnico de aprendizagem, organização de código e consolidação de um fluxo de trabalho replicável, adequado a projetos de análise de dados, políticas públicas e pesquisa empírica baseada em evidências.





\## Fluxo de trabalho Git local



1. git checkout -b
2. cria ou atualiza arquivos
3. git status
4. git add arquivos
5. git status
6. git commit -m "minha mensagem"
7. git checkout main
8. git merge nova\_branch



\## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)



1. git clone
2. git checkout -b <nova\_branch>
3. alterações de arquivos
4. git status
5. git add arquivos
6. git status
7. git commit -m "nova mensagem"
8. git push origin <nova\_branch>
9. abrir Pull request no GitHub para main
10. excluir <nova\_branch> origin
11. git checkout main
12. git branch -D <nova\_branch>



\## Fluxo de trabalho GitHub <> Local (projetos open-source)



1. Fork do projeto para seu próprio github
2. git clone
3. git checkout -b <nova\_branch>
4. alterações de arquivos
5. git status
6. git add arquivos
7. git status
8. git commit -m "nova mensagem"
9. git push origin <nova\_branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova\_branch> origin
12. git checkout main
13. git branch -D <nova\_branch>
