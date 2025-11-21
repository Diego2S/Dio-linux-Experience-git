# 📌 Principais Comandos Git

## 🔹 Configuração Inicial
- `git init` Inicializa um repositório Git na pasta atual  
- `git config --global user.name "Seu Nome"` Define o nome do usuário  
- `git config --global user.email "seu@email.com"`  Define o e-mail do usuário  

---

## 🔹 Fluxo Básico de Versionamento
- `git status` Mostra o estado dos arquivos  
- `git add .` Adiciona todos os arquivos ao stage  
- `git add arquivo.ext` Adiciona um arquivo específico ao stage  
- `git commit -m "mensagem"`  Salva o snapshot das alterações  
- `git log`  Mostra histórico de commits  
- `git diff` Mostra as diferenças entre arquivos alterados  

---

## 🔹 Branches
- `git branch`  Lista as branches existentes  
- `git branch nome-da-branch`  Cria uma nova branch  
- `git checkout nome-da-branch`  Troca para outra branch  
- `git checkout -b nova-branch`  Cria e já acessa uma nova branch  
- `git merge nome-da-branch`  Mescla a branch especificada na branch atual  

---

## 🔹 Repositórios Remotos
- `git remote add origin URL`  Adiciona o repositório remoto  
- `git push -u origin main` Envia a branch `main` para o repositório remoto  
- `git push`  Envia commits para o servidor  
- `git pull`  Atualiza o repositório local com o remoto  
- `git clone URL` Clona um repositório remoto  

---

## 🔹 Corrigindo Erros / Ajustes
- `git reset arquivo` Remove arquivo do stage  
- `git reset --hard` Desfaz tudo e volta ao último commit  
- `git revert <id-do-commit>`  Cria um commit que desfaz outro  
- `git stash`  Guarda temporariamente as alterações  
- `git stash pop` Restaura as alterações guardadas  

---

## 🔹 Informações e Ajuda
- `git show` Mostra detalhes de um commit  
- `git help` Mostra ajuda do Git  

---
