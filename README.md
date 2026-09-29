# 🐍 Python Zero → Pro

> Uma jornada prática para aprender lógica, Python e engenharia de software construindo projetos reais.

Este repositório deixou de ser uma coleção de explicações e passa a funcionar como um **sistema de treino**. A meta não é decorar sintaxe. É terminar a jornada sabendo transformar um problema em algoritmo, código legível, testes, CLI, automação e projetos publicáveis.

## 🎯 Objetivo final

Ao concluir a trilha, você terá:

- fundamentos sólidos de lógica e Python;
- domínio de coleções, funções, módulos, arquivos, exceções e orientação a objetos;
- código Pythonic com comprehensions, iteradores, generators, decorators e context managers;
- type hints, dataclasses e organização por pacotes;
- consumo de APIs e manipulação de JSON/CSV;
- SQLite e persistência;
- testes com pytest;
- lint e formatação com Ruff;
- CLI com argparse/Typer;
- logging e configuração;
- concorrência e async;
- automações e coleta passiva de dados;
- Git/GitHub + CI;
- **10 scripts de portfólio**, do iniciante ao projeto final.

## 🧠 Método: 5 lentes

Cada assunto deve ser estudado por cinco ângulos, sem imitar ninguém:

| Lente | Pergunta |
|---|---|
| 👀 Visual | O que está acontecendo no fluxo? |
| 🛠️ Prática | Como eu uso isso agora? |
| 🧠 Profunda | Por que isso funciona desse jeito? |
| 🐛 Debug | Como isso quebra e como diagnosticar? |
| 🔁 Transferência | Onde essa ideia aparece em problemas reais? |

## 🧪 Ciclo de cada missão

```text
ENTENDER → DIGITAR → QUEBRAR → CORRIGIR → EXPLICAR → TESTAR → REFATORAR → PUBLICAR
```

Nada de assistir vinte horas de conteúdo e depois descobrir que o cérebro terceirizou tudo para o tutorial.

## 🗺️ Trilha

| Nível | Tema | Entrega |
|---|---|---|
| 00 | Ambiente, terminal e Git | laboratório configurado |
| 01 | Lógica, tipos e operadores | Script #1 |
| 02 | Condicionais e loops | exercícios de fluxo |
| 03 | Strings e coleções | Script #2 |
| 04 | Funções, módulos e escopo | Script #3 |
| 05 | Arquivos, exceções e pathlib | Script #4 |
| 06 | OOP e dataclasses | Script #5 |
| 07 | Pythonic + typing | Script #6 |
| 08 | APIs, HTTP, JSON e SQLite | Script #7 |
| 09 | Testes, qualidade e packaging | elevar Scripts #1–#7 |
| 10 | Concorrência e async | Script #8 |
| 11 | Automação, OSINT e dados | Script #9 |
| 12 | Arquitetura e release | Script #10 |

➡️ [Roadmap completo](ROADMAP.md)

## 🏆 Top 10 Scripts

1. **CLI Logic Lab** — entrada, validação, funções e fluxo.
2. **Smart File Organizer** — pathlib, regras, dry-run e logs.
3. **CSV/JSON Data Profiler** — estatística descritiva e qualidade de dados.
4. **Log Triage Engine** — parsing, regex, Counter e exportação.
5. **Public API Collector** — requests/httpx, paginação, cache e tratamento de erros.
6. **Evidence Manifest** — hashing, metadados, inventário e integridade.
7. **IOC Normalizer** — normalização e classificação de indicadores em dados fornecidos pelo usuário.
8. **Passive Domain Mapper** — DNS e metadados HTTP passivos de domínios autorizados.
9. **Async Web Change Monitor** — coleta concorrente e comparação de mudanças em páginas públicas.
10. **Python Intelligence Workbench** — CLI modular + plugins + SQLite + async + testes + relatórios.

➡️ [Especificações do Top 10](projects/top10/README.md)

## 📚 Como estudar

Para cada nível:

1. leia o README do módulo;
2. faça as missões em ordem;
3. reescreva os exemplos sem copiar;
4. resolva os desafios antes de olhar qualquer solução;
5. crie testes;
6. registre no `LEARNING_LOG.md` o que aprendeu e onde travou;
7. só avance depois do checklist de domínio.

➡️ [Método detalhado](docs/METHOD.md)

## 📁 Estrutura

```text
.
├── levels/              # trilha zero → pro
├── projects/top10/      # 10 projetos progressivos
├── docs/                # método e referências
├── tests/               # testes dos exercícios/projetos
├── .github/workflows/   # CI
├── ROADMAP.md
├── LEARNING_LOG.md
└── pyproject.toml
```

## ✅ Regra de domínio

Você domina um tema quando consegue:

- explicar sem consultar;
- implementar sem copiar;
- prever pelo menos dois erros comuns;
- escrever um teste;
- refatorar uma versão ruim;
- aplicar o conceito em outro contexto.

## 🚦Comece aqui

Abra [levels/00-ambiente/README.md](levels/00-ambiente/README.md), configure o ambiente e avance em sequência.

> **Princípio do repositório:** código que funciona é o começo. Código compreensível, testado, observável e reutilizável é o objetivo.
