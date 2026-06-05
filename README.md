# Biblioteca GEPAEd

Biblioteca digital da produção científica em periódicos do **GEPAEd — Grupo de Estudo e Pesquisa em Argumentação na Educação**.

Página web navegável: explore os artigos por tema, autor, ano ou área, refine com filtros e acesse cada trabalho na fonte.

## Como funciona

Site estático (HTML/CSS/JS), sem servidor. Os dados ficam em `data.js`, gerados a partir dos currículos Lattes dos pesquisadores (extração via QLattes) e enriquecidos com DOI/link via CrossRef e OpenAlex.

- `index.html` — aplicação
- `data.js` — base de dados (115 artigos)
- `img/` — identidade visual
- `biblioteca_gepaed_offline.html` — versão de arquivo único (abre offline)

## Atualização

A base é mantida por um pipeline em R que unifica os CSVs do QLattes, deduplica, reconstrói co-autorias e recupera links. Para atualizar, basta regenerar `data.js`.

---
Grupo de Estudo e Pesquisa em Argumentação na Educação — GEPAEd
