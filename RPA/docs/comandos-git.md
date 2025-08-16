# Comandos Git Utilizados no Projeto 📚

Este arquivo documenta todos os comandos Git utilizados durante o desenvolvimento do jogo da velha.

## Configuração Inicial do Repositório

### 1. Inicialização do Repositório
```bash
git init
```
**Objetivo**: Inicializar um novo repositório Git na pasta do projeto.

### 2. Configuração do Usuário
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu.email@exemplo.com"
```
**Objetivo**: Configurar as informações do usuário para os commits.

### 3. Adicionar Arquivos ao Stage
```bash
git add .
# ou para arquivos específicos:
git add README.md
git add learning-git.txt
```
**Objetivo**: Preparar arquivos para commit.

### 4. Primeiro Commit
```bash
git commit -m "feat: configuração inicial do projeto jogo da velha"
```
**Objetivo**: Criar o primeiro commit com a estrutura básica.

## Trabalhando com Branches

### 5. Criar e Mudar para Nova Branch
```bash
git checkout -b jogada-ryan-1
# ou usando git switch (mais moderno):
git switch -c jogada-ryan-1
```
**Objetivo**: Criar uma branch para a primeira jogada do Ryan.

### 6. Listar Branches
```bash
git branch
```
**Objetivo**: Ver todas as branches disponíveis.

### 7. Mudar entre Branches
```bash
git checkout main
git switch main
```
**Objetivo**: Voltar para a branch principal.

## Fazendo Jogadas

### 8. Fazer uma Jogada
```bash
# Editar o arquivo learning-git.txt
git add learning-git.txt
git commit -m "feat: jogada Ryan - posição A1"
```
**Objetivo**: Registrar uma nova jogada no tabuleiro.

### 9. Merge da Jogada
```bash
git checkout main
git merge jogada-ryan-1
```
**Objetivo**: Integrar a jogada na branch principal.

## Conectando com GitHub

### 10. Adicionar Repositório Remoto
```bash
git remote add origin https://github.com/seu-usuario/jogo-da-velha-git.git
```
**Objetivo**: Conectar o repositório local com o GitHub.

### 11. Enviar para GitHub
```bash
git push -u origin main
```
**Objetivo**: Enviar o código para o repositório remoto.

### 12. Push de Branches
```bash
git push origin jogada-ryan-1
```
**Objetivo**: Enviar uma branch específica para o GitHub.

## Comandos de Consulta

### 13. Ver Status
```bash
git status
```
**Objetivo**: Verificar o estado atual do repositório.

### 14. Ver Histórico
```bash
git log --oneline
git log --graph --oneline --all
```
**Objetivo**: Visualizar o histórico de commits.

### 15. Ver Diferenças
```bash
git diff
git diff --staged
```
**Objetivo**: Ver as mudanças feitas nos arquivos.

## Comandos Avançados

### 16. Pull Request (via GitHub)
```bash
# Após push da branch, criar PR no GitHub interface
```
**Objetivo**: Propor mudanças para revisão antes do merge.

### 17. Atualizar Repositório Local
```bash
git pull origin main
```
**Objetivo**: Baixar as últimas mudanças do repositório remoto.

### 18. Reverter Commits (se necessário)
```bash
git revert HEAD
```
**Objetivo**: Desfazer um commit específico.

---

## 📝 Convenções de Commit

Utilizamos as seguintes convenções para mensagens de commit:

- `feat:` - Nova funcionalidade/jogada
- `fix:` - Correção de erro
- `docs:` - Atualização de documentação
- `style:` - Formatação (sem mudança de código)
- `refactor:` - Refatoração de código
- `test:` - Adição de testes

### Exemplos:
```bash
git commit -m "feat: jogada Ryan posição B2"
git commit -m "docs: atualização do README com regras"
git commit -m "fix: correção do tabuleiro após jogada inválida"
```
