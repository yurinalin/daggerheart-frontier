# Daggerheart Frontier Campaign

Bootstrap kit para campanha em **Daggerheart** com fluxo **Markdown-first** e publicação seletiva para **FoundryVTT**.

## Estrutura

- `lore/` — verdade do cenário e wiki do mestre
- `factions/` — facções, expedições e organizações
- `locations/` — locais importantes
- `npcs/` — fichas rápidas de NPCs
- `sessions/` — preparação, notas ao vivo e resumos
- `sandbox/` — tabelas e ferramentas de improviso
- `handouts/` — material para jogadores
- `templates/` — modelos reutilizáveis
- `foundry-publish/` — arquivos limpos para sincronizar com o Foundry
- `.vscode/` — configuração do workspace

## Fluxo recomendado

1. Escrever e atualizar conteúdo nas pastas principais.
2. Copiar ou adaptar apenas o que for útil em jogo para `foundry-publish/`.
3. Sincronizar `foundry-publish/` com o Foundry usando seu fluxo de importação.
4. Após a sessão, atualizar `sessions/` e fazer commit.

## Regras do projeto

- **Foundry não é a fonte de verdade.**
- **Markdown primeiro, Foundry depois.**
- Toda sessão gera:
  - notas ao vivo
  - resumo pós-sessão
  - hooks para a próxima

## Primeiros passos

1. Abra esta pasta no VS Code.
2. Instale as extensões:
   - Continue
   - Markdown All in One
   - GitLens (opcional)
3. Revise `.vscode/settings.json` e `.vscode/tasks.json`.
4. Ajuste os documentos em `lore/`, `sessions/` e `foundry-publish/`.
5. Faça o primeiro teste publicando `foundry-publish/Camp Halcyon.md`.

## Mapa rápido do conteúdo atual

- Pitch para jogadores: `handouts/campaign-pitch.md`
- Wiki do mestre: `lore/world-overview.md`
- Cheat sheet: `sandbox/gm-cheat-sheet.md`
- Mini-arco inicial: `sessions/starter-arc-echoes-of-the-storm.md`
- Toolkit de improviso: `sandbox/frontier-sandbox-toolkit.md`
- Notas de sessão zero: `sessions/session-00.md`
