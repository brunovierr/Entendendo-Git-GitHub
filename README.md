
# Entendendo o Curso de Git e GitHub para Versionamento

Me chamo [**Bruno**](https://www.linkedin.com/in/bruno-de-fran%C3%A7a-6987ab356/) e esse repositório foi criado com o objetivo de armazenar conteúdos e testes do curso de versionamento de Código com Git e GitHub da [DIO](https://www.dio.me/) para futuras consultas e estudos sobre códigos no Git Bash e para auxiliar futuros estudantes. 

### Links Úteis
[Curso da DIO](https://web.dio.me/track/ri-happy-front-end-do-zero)  
[IA para git](https://www.gitfluence.com/)  
[Repositório com aulas de git](https://github.com/digitalinnovationone/github-quickstart)  
[Documentação do GitHub](https://docs.github.com/)  



## 📌 O que o curso possui?
- [x] Salvando Alterações no Repositório Local
- [x] Desfazendo Alterações no Repositório Local
- [x] Enviando e Baixando Alterações com o Repositório Remoto
- [x] Trabalhando com Branches - Criando, Mesclando, Deletando e Tratando Conflitos
- [x] Trabalhando com Branches - Comandos Úteis no Dia a Dia


## 🔶 Comandos das Aulas **git**
| Command | Description |
| --- | --- |
|```git init```| **inicia** um repositório local.|
|```git pull``` |**puxa** (Baixa e mescla as alterações no repositório local).|
|```git push```| **empurra** (envia as alterações para o repositório remoto).|
|```git add .```| **Adiciona** todos os arquivos não rastreados ao ambiente de preparação.|
|```git status``` |**status do repositório.**|
|```git log```| ver **histórico** dos seus commits.|

##
🟢↩**Salvando e Desfazendo Alterações no Repositório Local**
| Command | Description |
| --- | --- |
|```git commit -m "nome do commit"``` |**salva** as alterações no repositório local.|
|```git commit --amend -m "novo nome"```| **renomeia** o seu ultimo commit.|
|```rm -rf .git```| **remove** à força o repositório onde está o diretorio.|
|```git restore <arquivo>```| **descarta** todas as mudanças que foi feita antes do commit.|
|```git reset --<soft/mixed/hard> <hash do commit>```| **volta o commit** da hash indicada da forma que solicitada (soft/mixed/hard).|
|```git reset <nomeDoArquivo>```| **retira** o arquivo da área de preparação.|

##

⬆⬇**Enviando e Baixando Alterações com o Repositório Remoto**
| Command | Description |
| --- | --- |
|```git remote add origin <https repositório remoto>```| **conecta** o repositório local com o remoto por meio do https.|
|```git branch -m Main``` |força renomeação para a branch main. |
|```git push -u origin main```| **envia** o repositório local para o remoto ja estabelecendo uma conexão para os proximos push/pull.|
|```git pull``` |**puxa** (baixa e mescla as alterações no repositório local).|

## 
🌿 **Trabalhando com Branches**

- **Branch** -> é uma ramificação do repositório para teste de novas funcionalidades

| Command | Description |
| --- | --- |
| `git checkout -b <nome>` | **cria** e **troca** a branch para a nova criada. |
| `git checkout <nome>` | **troca** a branch para indicada. |
| `git branch` | **mostra todas** as branchs existentes. |
| `git branch -v` | **mostra os últimos commits** para cada branch existente. |
| `git merge <nome>` | **mescla** a branch indicada com a branch main. |
| `git branch -d <nome>` | **deleta** a branch indicada. |
##
🔨**Úteis no dia a dia**

| Command | Description |
| --- | --- |
|`git fetch origin main`| **apenas baixa** as alterações que teve no repositório remoto sem mesclar com o local.|
|`git diff main origin/main`| **exibe a diferença** do repositório remoto baixado para o repositório local.|
|```git merge origin/main``` | **mescla** os repositório, Local e Remoto localmente.|
| ```git clone <https repositório> --branch <nome da branch> --single branch```| **clona** apenas a branch remota indicada.
|```git stash```| **armazena** as mudanças feitas na branch temporiaramente para continuar trabalhando nela, porém sem perde as alterações já feitas.|
- ```git stash pop``` **aplica** a alteração sem a mudança armazenada no stash.

- ```git stash apply``` **mantém** a alteração que estava armazenada no stash .

##
 Espero que de alguma maneira eu tenha ajudado!

## 👨‍💻 Autor

**Bruno de França Vieira**

[![E-mail](https://img.shields.io/badge/Email-000?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bruno.fv.08@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=0E76A8)](https://www.linkedin.com/in/brunovierr/)
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/brunovierr)



