# 📘 Aprendizados — Ciclo 14 (Git e GitHub)

Neste ciclo, aprendi os conceitos fundamentais de **linhas de comando, Git e GitHub**, além de práticas de versionamento e colaboração em projetos.  
A importância de boas práticas e de como contribuir de maneira eficaz e "limpa" em futuros projetos.
---

## 💻 Linhas de Comando

Descobri que posso interagir com o computador apenas por texto, o que muitas vezes é mais rápido e direto do que usar o mouse.  
Usei principalmente o **Git Bash**, mas também conheci o **CMD**, o **PowerShell** e o **Bash** via **VS Code**.

| Comando                | Função                                                                 |
|------------------------|------------------------------------------------------------------------|
| `pwd`                  | Mostra o diretório atual                                                |
| `ls`                   | Lista os arquivos e pastas do diretório atual                           |
| `cd nome-da-pasta`     | Entra em uma pasta                                                      |
| `cd ..`                | Volta uma pasta                                                         |
| `cd ~`                 | Volta para a pasta raiz do usuário                                      |
| `mkdir nome-da-pasta`  | Cria uma nova pasta                                                     |
| `rm nome-do-arquivo`   | Remove um arquivo                                                       |
| `rm -r nome-da-pasta`  | Remove uma pasta                                                        |
| `whoami`               | Mostra o usuário logado                                                 |
| `touch meu_arquivo.md` | Cria um novo arquivo no diretório                                       |


---

## 🛠️ Git — Controle de Versão

Aprendi que o Git é um sistema que registra todas as alterações feitas em arquivos de um projeto.  
Isso permite voltar para versões anteriores, saber quem fez cada mudança e trabalhar em equipe de forma segura.

| Comando                          | Função                                                                 |
|---------------------------------|-------------------------------------------------------------------------|
| `git init`                      | Inicia um repositório Git                                               |
| `git add nome-do-arquivo`       | Adiciona um arquivo específico à área de staging                        |
| `git add arquivo1 arquivo2`     | Adiciona arquivos específicos à área de staging                         |
| `git add *`                     | Adiciona todos os arquivos criados/modificados à área de staging        |
| `git status`                    | Mostra o estado atual dos arquivos                                      |
| `git commit -m "mensagem"`      | Registra as alterações no histórico do projeto                          |
| `git pull`                      | Atualiza o repositório local com alterações do remoto                   |
| `git push`                      | Envia alterações locais para o repositório remoto                       |
| `git push origin main`          | Envia alterações locais para o repositório remoto pela primeira vez     | 
| `git remote add origin URL`     | Conecta o repositório local a um remoto                                 |
| `git checkout nome-do-arquivo`  | Descarta alterações locais em um arquivo específico                     |
| `git log`                       | Exibe o histórico de commits de um repositório                          |         

---

## 🌿 Branches — Ramificações no Git

Com branches, entendi que posso desenvolver novas funcionalidades ou corrigir erros sem mexer diretamente na linha principal do projeto (**main**).  
Isso evita conflitos e deixa o fluxo de trabalho bem organizado. É uma boa prática não fazer alterações na Main.

| Comando                                | Função                                                               |
|---------------------------------------|----------------------------------------------------------------------|
| `git branch`                           | Lista todas as branches                                              |
| `git checkout -b nome-da-branch`       | Cria e acessa uma nova branch                                        |
| `git checkout nome-da-branch`          | Alterna entre branches                                               |
| `git merge nome-da-branch`             | Mescla alterações de uma branch na atual                             |
| `git branch -d nome-da-branch`         | Exclui uma branch local já mesclada                                  |
| `git branch -m nome-novo_da-branch`    | Renomeia a branch atual                                              |
| `git push origin --delete nome-branch` | Exclui uma branch do repositório remoto                              |

---

## 🍴 Forks — Trabalhando com Projetos de Terceiros

Aprendi que o **fork** cria uma cópia de um repositório na minha conta, permitindo que eu contribua sem alterar o projeto original.  
Depois, posso propor as mudanças por meio de um **pull request**.

| Comando                                   | Função                                                                 |
|-------------------------------------------|------------------------------------------------------------------------|
| `git clone URL-do-fork`                   | Clona o fork para meu computador                                       |
| `git remote add upstream URL-do-original` | Conecta meu repositório local ao original                              |
| `git fetch upstream`                      | Busca alterações do repositório original                               |
| `git merge upstream/main`                 | Mescla as alterações do repositório original na minha branch           |
| `git rebase upstream/main`                | Reorganiza meu histórico aplicando minhas mudanças sobre as mais novas |

---

## 🤖 GitHub Copilot

Também conheci o **GitHub Copilot**, uma ferramenta de inteligência artificial que sugere código enquanto escrevo.  
Ele me ajuda a economizar tempo, evita erros e ainda me dá ideias de como resolver problemas de forma mais eficiente.  
Apesar disso, aprendi que sempre preciso revisar o código sugerido antes de usá-lo.

---

## ✅ Conclusão

Esse módulo me deu uma base sólida para versionar meus projetos com Git e GitHub e trabalhar de forma colaborativa com outras pessoas, tanto em projetos pessoais como em projetos profissionais.  
Agora consigo criar, gerenciar e atualizar repositórios, organizar meu trabalho com branches e até contribuir com projetos de terceiros usando forks.  
Também passei a enxergar como o Copilot pode potencializar minha produtividade e aprendizado.
Estou muito feliz com esses aprendizados!
