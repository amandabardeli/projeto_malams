# projeto_malams
Projeto desenvolvido para trabalho de conclusão de curso (TCC) do curso de Análise e Desenvolvimento de Sistemas, da ETEC Professor Camargo Aranha, no ano letivo de 2025. O projeto tem como objetivo principal a automação de agendamento de serviços realizados em salões de beleza.

# Comandos Git para Gerenciamento de Branches

## Criando e Entrando em uma Branch no Git

No Git Bash, após clonar o repositório e entrar no projeto:

1. **Verificar as branches existentes:**
   git branch -a

2. **Criar uma nova branch e já entrar nela:**
   git checkout -b nome-da-branch
   
3. **Subir a branch para o GitHub:**
   git push -u origin nome-da-branch
     
4. **Sair da branch e voltar para a main (branch principal):**
   git checkout main
   
## Subindo Alterações na Branch

1. **Verificar o status das alterações:**
   git status
   
2. **Adicionar arquivos para commit:**
   git add .
   
3. **Criar um commit com uma descrição das alterações:**
   git commit -m "Descrição das alterações"
   
4. **Enviar a branch para o repositório remoto:**
   git push origin sua-branch

## Juntando as Alterações na main

1. **Mudar para a branch principal (main):**
   git checkout main
   
2. **Atualizar a main para garantir que está com as últimas alterações:**
   git pull origin main
   
4. **Mesclar as alterações da sua branch na main:**
   git merge sua-branch
   
5. **Se houver conflitos, resolva-os manualmente e finalize o merge com:**
   git commit -m "Resolvendo conflitos
   
7. **Subir a main atualizada para o repositório remoto:**
  git push origin main
   

