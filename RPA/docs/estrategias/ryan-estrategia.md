# Estratégia do Ryan (❌)

## Jogada 1 - 16/08/2025

### Posição Escolhida
B2 (Centro)

### Estratégia
Escolhi o centro do tabuleiro como primeira jogada porque:
- O centro oferece o maior número de possibilidades de vitória (4 linhas: horizontal, vertical e 2 diagonais)
- É uma posição defensiva e ofensiva ao mesmo tempo
- Força o oponente a reagir à minha posição central

### Estado do Tabuleiro Antes
```
   1   2   3
A  . | . | .
  ---+---+---
B  . | . | .
  ---+---+---
C  . | . | .
```

### Estado do Tabuleiro Depois
```
   1   2   3
A  . | . | .
  ---+---+---
B  . | ❌ | .
  ---+---+---
C  . | . | .
```

### Comandos Git Utilizados
```bash
git checkout -b jogada-ryan-1
# [editar arquivo learning-git.txt]
git add learning-git.txt docs/estrategias/ryan-estrategia.md
git commit -m "feat: jogada Ryan - posição B2 (centro)"
git push origin jogada-ryan-1
```

### Observações
Esta é uma jogada clássica de abertura. Agora Felipe precisa decidir se vai para um canto ou uma lateral.

---


## Jogada 2 - 16/08/2025

### Posição Escolhida
A2 (Superior centro)

### Estratégia
Posicionamento em A2 visa:
- Controle da linha superior A1-A2-A3
- Domínio da coluna central A2-B2-C2
- Criação de ameaça de vitória vertical
- Bloqueio de possível expansão horizontal do adversário

### Estado do Tabuleiro Antes
```
   1   2   3
A  . | . | ⚫
  ---+---+---
B  . | ❌ | .
  ---+---+---
C  . | . | .
```

### Estado do Tabuleiro Depois
```
   1   2   3
A  . | ❌ | ⚫
  ---+---+---
B  . | ❌ | .
  ---+---+---
C  . | . | .
```

### Comandos Git Utilizados
```bash
git add learning-git.txt
git commit -m "feat: jogada Ryan 2 - posição A2"
git push origin main
```

### Análise Técnica
- Ameaça criada: Sequência A2-B2, necessita C2 para vitória
- Pressão sobre adversário: Felipe deve bloquear C2 obrigatoriamente
- Alternativas do adversário: Criar contra-ameaça para forçar defesa

### Observações
Jogada estabelece vantagem tática significativa. Próxima movimentação do adversário determinará estratégia subsequente.

// ...existing code...

---

## Jogada 3 - 16/08/2025

### Posição Escolhida
[Informar a posição escolhida após verificar learning-git.txt]

### Estratégia
[Análise da jogada após Felipe ter bloqueado C2]

### Estado do Tabuleiro Antes
```
   1   2   3
A  . | ❌ | ⚫
  ---+---+---
B  ❌ | ❌ | .
  ---+---+---
C  . | ⚫ | .
```

### Estado do Tabuleiro Depois
```
[Tabuleiro após sua jogada]
```

### Comandos Git Utilizados
```bash
git checkout -b jogada-ryan-3
git add learning-git.txt docs/estrategias/ryan-estrategia.md
git commit -m "feat: jogada Ryan 3 - posição [B1]"
git push origin jogada-ryan-3
git checkout master
git merge jogada-ryan-3
git push origin master
```

### Análise Técnica
possivelmente a proxima jogada define o jogo...

### Observações
aguardo o proximo movimento de felipe
