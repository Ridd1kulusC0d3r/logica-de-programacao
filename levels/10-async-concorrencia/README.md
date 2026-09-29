# Concorrência e async

## Resultado esperado
Entender quando concorrência melhora throughput e quando apenas cria bugs mais rápidos, um talento humano tradicional.

## Conteúdo
- blocking vs non-blocking
- threads e I/O
- processos e CPU
- event loop
- async / await
- tasks e gather
- semáforos
- filas
- timeouts
- cancelamento e backpressure

## Missões
1. Meça uma versão sequencial.
2. Refaça o mesmo laboratório com threads.
3. Refaça um caso I/O-bound com asyncio.
4. Limite concorrência com Semaphore.
5. Adicione timeout.
6. Trate cancelamento.
7. Compare tempo, complexidade e legibilidade.

## Entrega
Implemente o **Script #8 — Passive Domain Mapper** apenas para domínios próprios ou autorizados, usando fontes e metadados passivos.

## Gate
- [ ] sei explicar I/O-bound vs CPU-bound;
- [ ] não crio concorrência ilimitada;
- [ ] tenho timeout;
- [ ] erros de uma tarefa não derrubam silenciosamente o lote;
- [ ] medi antes e depois.
