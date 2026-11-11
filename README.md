# Traffic Analytics

Painéis de monitoramento SEO (multi-cliente) — V4 Export & Commerce.

- **Raiz:** landing com cards por cliente; abre o último visitado automaticamente.
- `/brasland/` · `/all-over/` — painéis completos (posicionamento, keywords, SERPs, concorrência, demanda).
- `/diamond/` — painel de rankings em **espanhol** (Ubersuggest, projeto US/en) · `/diamond/diagnostico/` painel de auditoria (diagnóstico, plano, projeção e indexação) · `/diamond/auditoria/` relatório completo.

Dados: Ubersuggest via MCP · atualizado via `refresh.py` (posicional semanal) · template + build no kit `_template-painel-rankings`.
Diamond: baseline Ubersuggest em 11/11/2026 (posições ainda `pending` no primeiro barrido; próxima leitura 18/11). Auditoria: Screaming Frog (crawl out/2026) + Google Search Console (cobertura 13/10/2026).
