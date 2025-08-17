## Histórico Completo das Jogadas

## Resumo do Jogo
- **Jogadores**: Ryan (❌) vs Felipe (⚫)
- **Data de Início**: 16/08/2025
- **Status**: Finalizado
- **Vencedor**: Felipe
- **Repositório**: https://github.com/Ryanditko/atividade-devops-git

## Cronologia das Jogadas

### Jogada #1 - 16/08/2025
- **Jogador**: Ryan
- **Marca**: ❌
- **Posição**: B2 (Centro)
- **Branch**: `jogada-ryan-1`
- **Estratégia**: Posicionamento central para máximas possibilidades de vitória

### Jogada #2 - 16/08/2025
- **Jogador**: Felipe
- **Marca**: ⚫
- **Posição**: A3 (Canto superior direito)
- **Branch**: `jogada-felipe-1`
- **Estratégia**: Defesa em canto para múltiplas opções futuras

### Jogada #3 - 16/08/2025
- **Jogador**: Ryan
- **Marca**: ❌
- **Posição**: A2 (Superior centro)
- **Branch**: `jogada-ryan-2`
- **Estratégia**: Criação de ameaça na coluna 2 (A2-B2, necessita C2)

### Jogada #4 - 16/08/2025
- **Jogador**: Felipe
- **Marca**: ⚫
- **Posição**: C2 (Inferior centro)
- **Branch**: `jogada-felipe-2`
- **Estratégia**: Bloqueio obrigatório da ameaça de Ryan

### Jogada #5 - 16/08/2025
- **Jogador**: Ryan
- **Marca**: ❌
- **Posição**: A1 (Superior esquerda)
- **Branch**: `jogada-ryan-3`
- **Estratégia**: Tentativa de fechar pela diagonal (A1-B2, necessita C3)

### Jogada #6 - 16/08/2025
- **Jogador**: Felipe
- **Marca**: ⚫
- **Posição**: C3 (Centro direita)
- **Branch**: `jogada-felipe-3`
- **Estratégia**: Bloqueio da diagonal

### Jogada #7 - 16/08/2025
- **Jogador**: Ryan
- **Marca**: ❌
- **Posição**: C1 (Inferior esquerda)
- **Branch**: `jogada-ryan-4`
- **Estratégia**: Bloqueio da linha C

### Jogada #8 - 16/08/2025
- **Jogador**: Felipe
- **Marca**: ⚫
- **Posição**: B2 (Centro esquerda)
- **Branch**: `jogada-felipe-4`
- **Estratégia**: Jogada final para vencer completando a coluna 3

## Estados do Tabuleiro

### Estado Inicial
```
   1   2   3
A  . | . | .
  ---+---+---
B  . | . | .
  ---+---+---
C  . | . | .
```

### Após Jogada #1 (Ryan B2)
```
   1   2   3
A  . | . | .
  ---+---+---
B  . | ❌ | .
  ---+---+---
C  . | . | .
```

### Após Jogada #2 (Felipe A3)
```
   1   2   3
A  . | . | ⚫
  ---+---+---
B  . | ❌ | .
  ---+---+---
C  . | . | .
```

### Após Jogada #3 (Ryan A2)
```
   1   2   3
A  . | ❌ | ⚫
  ---+---+---
B  . | ❌ | .
  ---+---+---
C  . | . | .
```

### Após Jogada #4 (Felipe C2)
```
   1   2   3
A  . | ❌ | ⚫
  ---+---+---
B  . | ❌ | .
  ---+---+---
C  . | ⚫ | .
```

### Após Jogada #5 - (Ryan A1 )
```
   1   2   3
A  ❌ | ❌ | ⚫
  ---+---+---
B  . | ❌ | .
  ---+---+---
C  . | ⚫ | .
```

### Após Jogada #6 - (Felipe C3 )
```
   1   2   3
A  ❌ | ❌ | ⚫
  ---+---+---
B  . | ❌ | .
  ---+---+---
C  . | ⚫ | ⚫
```

### Após Jogada #7 - (Ryan C1 )
```
   1   2   3
A  ❌ | ❌ | ⚫
  ---+---+---
B  . | ❌ | .
  ---+---+---
C  ❌ | ⚫ | ⚫
```

### Estado Final (Após Jogada #8 - (Felipe C2 ))
```
   1   2   3
A  ❌ | ❌ | ⚫
  ---+---+---
B  . | ❌ | ⚫
  ---+---+---
C  ❌ | ⚫ | ⚫
```

## Análise Técnica Git

### Branches Utilizadas
- `master` - Branch de desenvolvimento
- `main` - Branch principal (consolidação final)
- `jogada-ryan-1` - Primeira jogada do Ryan (B2)
- `jogada-felipe-1` - Primeira jogada do Felipe (A3)
- `jogada-ryan-2` - Segunda jogada do Ryan (A2)
- `jogada-felipe-2` - Segunda jogada do Felipe (C2)
- `jogada-ryan-3` - Terceira jogada do Ryan (B1)
- `docs-ryan-jogada-2` - Documentação posterior
- `jogada-felipe-3` - Terceira jogada do Felipe (C3)
- `jogada-ryan-4` - Quarta jogada do Ryan (C1)
- `jogada-felipe-4` - Quarta jogada do Felipe

### Merges Realizados
1. **Merge #1**: `jogada-ryan-1` → `master`
   - Primeira jogada documentada
   - Conflitos: Não
   
2. **Merge #2**: `jogada-felipe-1` → `master`
   - Sincronização remota necessária
   - Conflitos: Não

3. **Merge #3**: `jogada-ryan-2` → `master`
   - Criação de ameaça tática
   - Conflitos: Não

4. **Merge #4**: `jogada-felipe-2` → `master`
   - Defesa obrigatória
   - Conflitos: Resolução necessária

5. **Merge #5**: `jogada-ryan-3` → `master`
   - Nova estratégia ofensiva
   - Conflitos: Pull necessário antes do push

6. **Merge #6**: `jogada-felipe-3` → `master`
   - Defesa obrigatória
   - Conflitos: Não

7. **Merge #7**: `jogada-ryan-4` → `master`
   - Defesa obrigatória
   - Conflitos: Não

8. **Merge #8**: `jogada-felipe-4` → `master`
   - Jogada final
   - Conflitos: Não

### Comandos Git Destacados
```bash
# Inicialização
git init
git remote add origin https://github.com/Ryanditko/atividade-devops-git.git

# Workflow padrão das jogadas
git checkout -b jogada-[jogador]-[numero]
git add learning-git.txt docs/estrategias/[jogador]-estrategia.md
git commit -m "feat: jogada [jogador] [numero] - posição [posição]"
git push origin jogada-[jogador]-[numero]
git checkout master
git merge jogada-[jogador]-[numero]
git push origin master

# Sincronização
git fetch origin
git pull origin master
git push origin master
```

## Análise Estratégica

### Situação Final do Jogo
- **Felipe**: Vencedor usando estratégias defensivas

### Padrões Identificados
1. **Ryan**: Estratégia agressiva, busca ameaças constantes
2. **Felipe**: Estratégia defensiva, bloqueia ameaças do adversário
3. **Workflow Git**: Branches individuais para cada jogada, merge sistemático

## Conceitos Git Praticados

### Funcionalidades Utilizadas
- [x] Inicialização de repositório
- [x] Commits com convenções semânticas
- [x] Branches para features/jogadas
- [x] Merges entre branches
- [x] Push/Pull para sincronização
- [x] Resolução de conflitos
- [x] Fetch de branches remotas
- [x] Documentação técnica
- [x] Trabalho colaborativo

### Convenções Estabelecidas
- **Commits**: `feat:`, `docs:`, `fix:`, `merge:`
- **Branches**: `jogada-[jogador]-[numero]`
- **Documentação**: Estratégias individuais + histórico completo
- **Sincronização**: Pull antes de push, fetch regular

## Dificuldades Encontradas e Soluções

### 1. Erro non-fast-forward
**Problema**: Push rejeitado por mudanças remotas
**Solução**: `git pull origin master` antes do push

### 2. Documentação Posterior
**Problema**: Commit sem documentação
**Solução**: Branch específica para documentação

### 3. Sincronização de Branches
**Problema**: Colaborador criou branch não sincronizada
**Solução**: `git fetch origin` + checkout na branch remota

### 4. Conflitos de Merge
**Problema**: Mudanças simultâneas no mesmo arquivo
**Solução**: Resolução manual + commit de merge

## Estrutura Final do Projeto

```
RPA/
├── learning-git.txt              # Tabuleiro do jogo
├── README.md                     # Documentação principal
├── docs/
│   ├── comandos-git.md          # Referência de comandos
│   ├── estrategias/
│   │   ├── ryan-estrategia.md   # Estratégias do Ryan
│   │   └── felipe-estrategia.md # Estratégias do Felipe
│   └── historico-jogadas/
│       └── historico-completo.md # Este arquivo
└── .git/                        # Controle de versão
```

## Lições Aprendidas

### Workflow Eficiente
1. **Planejamento**: Estrutura de pastas bem definida
2. **Convenções**: Padronização de commits e branches
3. **Documentação**: Registro detalhado de cada etapa
4. **Colaboração**: Sincronização constante entre desenvolvedores

### Boas Práticas Git
1. **Commits atômicos**: Uma jogada por commit
2. **Mensagens descritivas**: Convenção semântica
3. **Branches por feature**: Isolamento de mudanças
4. **Documentação contínua**: Registros técnicos completos

### Aplicação Educacional
Este projeto demonstra efetivamente o uso prático do Git em um contexto colaborativo, simulando um ambiente de desenvolvimento real através de um jogo simples mas estratégico.**
