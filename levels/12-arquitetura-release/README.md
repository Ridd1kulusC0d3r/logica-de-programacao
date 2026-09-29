# Arquitetura, CLI e release

## Resultado esperado
Sair de “um script grande” para um projeto que outra pessoa consegue entender, testar e estender.

## Conteúdo
- separação de responsabilidades
- domain / services / adapters
- configuração
- CLI e subcomandos
- interfaces e plugins
- SQLite e repositories
- logging estruturado
- versionamento semântico
- changelog
- documentação arquitetural
- releases

## Missões
1. Desenhe componentes antes de codar.
2. Separe I/O da lógica de domínio.
3. Extraia configuração do código.
4. Crie uma interface simples de plugin.
5. Adicione banco sem contaminar regras de negócio.
6. Instrumente logs.
7. Publique uma release reproduzível.

## Entrega
Implemente o **Script #10 — Python Intelligence Workbench**.

## Definition of Done
- [ ] CLI modular;
- [ ] persistência SQLite;
- [ ] plugins;
- [ ] async onde agrega valor;
- [ ] logs;
- [ ] type hints;
- [ ] testes unitários e integração;
- [ ] CI verde;
- [ ] documentação de arquitetura;
- [ ] release versionada.
