# Top 10 Scripts — Portfólio Progressivo

Os projetos crescem em dificuldade. Cada um deve ter README próprio, exemplos, testes e uma versão marcada por tag quando estiver estável.

| # | Projeto | Competências principais | Nível |
|---|---|---|---|
| 01 | CLI Logic Lab | tipos, fluxo, funções, validação | iniciante |
| 02 | Smart File Organizer | pathlib, regras, logs, dry-run | iniciante+ |
| 03 | CSV/JSON Data Profiler | coleções, parsing, estatística | intermediário |
| 04 | Log Triage Engine | regex, Counter, filtros, export | intermediário |
| 05 | Public API Collector | HTTP, JSON, paginação, retries | intermediário |
| 06 | Evidence Manifest | hashlib, pathlib, metadata | intermediário+ |
| 07 | IOC Normalizer | parsing, regex, dataclasses, typing | intermediário+ |
| 08 | Passive Domain Mapper | DNS/HTTP passivo, concorrência | avançado |
| 09 | Async Web Change Monitor | asyncio, hashing, SQLite | avançado |
| 10 | Python Intelligence Workbench | arquitetura modular completa | pro |

## 01 — CLI Logic Lab
Construa uma CLI com subcomandos para operações numéricas e textuais. Requisitos: validação, funções pequenas, mensagens de erro úteis e testes parametrizados.

**Upgrade:** transforme ifs repetidos em uma tabela de dispatch.

## 02 — Smart File Organizer
Organize arquivos por extensão, data ou regra configurável.

**Obrigatório:** `--dry-run`, prevenção de colisão, logging e testes com diretórios temporários.

## 03 — CSV/JSON Data Profiler
Leia datasets locais e informe schema inferido, nulos, duplicados, cardinalidade e estatísticas básicas.

**Upgrade:** exporte relatório JSON.

## 04 — Log Triage Engine
Parseie logs fornecidos pelo usuário, filtre intervalo temporal, agregue eventos e identifique padrões de frequência.

**Upgrade:** regras configuráveis em JSON/YAML.

## 05 — Public API Collector
Colete dados de APIs públicas documentadas.

**Obrigatório:** timeout, retries limitados, paginação, cache local e user-agent claro.

## 06 — Evidence Manifest
Gere manifesto de arquivos com hash SHA-256, tamanho, timestamps e caminho relativo.

**Objetivo:** aprender integridade, reprodutibilidade e processamento de filesystem.

## 07 — IOC Normalizer
Receba indicadores fornecidos pelo usuário e normalize IPs, domínios, URLs e hashes.

**Obrigatório:** nunca “inventar” enriquecimento; separar dado original, dado normalizado e validação.

## 08 — Passive Domain Mapper
Para domínios próprios ou autorizados, consolide DNS resolvido e metadados HTTP públicos, sem exploração ativa.

**Obrigatório:** limites de concorrência, timeout, provenance e export estruturado.

## 09 — Async Web Change Monitor
Monitore páginas públicas indicadas pelo usuário e registre alterações relevantes.

**Obrigatório:** asyncio, SQLite, hash de conteúdo, diff resumido e backoff.

## 10 — Python Intelligence Workbench
Projeto final: um workbench extensível para ingestão, normalização e análise de dados públicos.

### Arquitetura mínima
- CLI com subcomandos;
- camada de domínio;
- adaptadores de entrada;
- SQLite;
- sistema simples de plugins;
- async para coletores;
- logging estruturado;
- configuração por arquivo + ambiente;
- testes unitários e integração;
- CI;
- documentação de arquitetura.

### Critério de conclusão
Você deve conseguir explicar por que cada módulo existe e substituir uma implementação sem reescrever o sistema inteiro.
