# Automação, OSINT e engenharia de dados

## Resultado esperado
Construir pipelines pequenos, auditáveis e reproduzíveis para dados públicos.

## Conteúdo
- ingestão → normalização → análise → exportação
- provenance e timestamp
- schemas
- deduplicação
- hashing
- qualidade de dados
- coleta responsável
- cache e reprodutibilidade
- separação entre fato, inferência e hipótese

## Missões
1. Normalize um dataset heterogêneo.
2. Preserve sempre o dado bruto.
3. Crie identificadores determinísticos.
4. Registre origem e horário de coleta.
5. Faça deduplicação sem destruir a evidência original.
6. Exporte JSON estruturado.
7. Gere um resumo derivado sem misturá-lo ao dado-fonte.

## Entrega
Implemente o **Script #9 — Async Web Change Monitor** para páginas públicas indicadas pelo usuário.

## Gate
- [ ] consigo reconstruir de onde veio cada registro;
- [ ] não misturo raw e derived;
- [ ] tenho limites de requisição;
- [ ] erros e lacunas ficam explícitos;
- [ ] resultados podem ser reproduzidos.
