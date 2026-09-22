# Claude Opus 5.5 — Pesquisa e Plano de Atualização

Pesquisa sobre o **Claude Opus 5.5** (Anthropic, lançado em 22/09/2026) com gráficos de preço, benchmarks e effort × custo, as mudanças de API e o plano de atualização dos sistemas INEMA.

🔗 **Página:** https://inematds.github.io/opus55/

| | |
|---|---|
| **API ID** | `claude-opus-5-5` (Bedrock: `anthropic.claude-opus-5-5`) |
| **Contexto / saída** | 1M / 128K tokens |
| **Preço** | US$ 4 entrada · US$ 20 saída · cache read US$ 0,20 (por milhão) |
| **Effort padrão** | `medium` (no Opus 5 era `high`) |
| **Breaking changes** | thinking não desliga · sem `tool_choice` forçado · preserved thinking · computer use só via `computer_toolset_20260801` |

## Conteúdo

- Resumo, preços e comparativo com Opus 5, Opus 4.8, Fable 5.1, Sonnet 5 e Haiku 4.5
- Benchmarks do system card e o ranking independente da Artificial Analysis
- Curva de effort × custo por tarefa
- Mudanças de API, com exemplo antes/depois
- Inventário dos sistemas INEMA que usam Claude e o plano de atualização por prioridade

## Metodologia

Documentação oficial da Anthropic (anúncio, docs, preços, guia de migração, system card), cobertura de terceiros e um inventário local somente leitura, tudo em 22/09/2026. Cada gráfico usa uma única tabela-fonte. Benchmarks oficiais são auto-reportados. As fontes estão no fim da página.

Página única (`index.html`), sem build. Capa em `capa/capa.png` e imagem de destaque em `assets/hero.jpg`, geradas com o image_gen do Codex.
