## Jogada 3 - 16/08/2025

### Posição Escolhida
A1 (Superior esquerda)

### Estratégia
Após Felipe bloquear C2, escolhi A1 para:
- Controlar a linha superior A1-A2-A3
- Tentar criar nova ameaça ofensiva
- Manter pressão no jogo

### Estado do Tabuleiro Antes
```
   1   2   3
A  . | ❌ | ⚫
  ---+---+---
B  . | ❌ | .
  ---+---+---
C  . | ⚫ | .
```

### Estado do Tabuleiro Depois
```
   1   2   3
A  ❌ | ❌ | ⚫
  ---+---+---
B  . | ❌ | .
  ---+---+---
C  . | ⚫ | .
```

### Comandos Git Utilizados
```bash
git add learning-git.txt docs/estrategias/ryan-estrategia.md
git commit -m "feat: jogada Ryan 3 - posição A1"
git push origin master
```

### Análise Técnica
- Controle da linha superior estabelecido (A1-A2)
- Felipe ainda possui ameaça potencial na coluna 3
- Necessário monitorar movimentos defensivos

### Observações
Felipe mantém vantagem tática. Próxima jogada será decisiva.

---

## Jogada 4 - 16/08/2025

### Posição Escolhida
C1 (Inferior esquerda)

### Estratégia
Jogada defensiva tardía. Tentativa de bloquear expansão do Felipe, mas já era tarde demais.
Felipe completou a vitória na coluna 3.

### Estado do Tabuleiro Antes
```
   1   2   3
A  ❌ | ❌ | ⚫
  ---+---+---
B  . | ❌ | ⚫
  ---+---+---
C  . | ⚫ | ⚫
```

### Estado do Tabuleiro Final
```
   1   2   3
A  ❌ | ❌ | ⚫
  ---+---+---
B  . | ❌ | ⚫
  ---+---+---
C  ❌ | ⚫ | ⚫
```

### Comandos Git Utilizados
```bash
git add learning-git.txt docs/estrategias/ryan-estrategia.md
git commit -m "feat: jogada Ryan final - C1 - Felipe venceu"
git push origin master
```

### Análise Técnica
- Felipe venceu na coluna 3 (A3-B3-C3)
- Erro estratégico: não identifiquei a ameaça de Felipe na coluna 3
- Deveria ter jogado B3 para bloquear, porem mesmo assim eu acabaria perdendo

### Observações
**RESULTADO FINAL: FELIPE VENCEU**
