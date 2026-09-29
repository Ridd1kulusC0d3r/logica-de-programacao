# Python Field Notes

## Coleções
- `list`: ordem + mutabilidade.
- `tuple`: ordem + imutabilidade.
- `set`: unicidade + operações de conjunto.
- `dict`: chave → valor.

## Escolha de loop
- percorre coleção: `for`;
- repete enquanto condição: `while`;
- precisa índice e valor: `enumerate`;
- combina iteráveis: `zip`.

## Funções
Prefira funções pequenas, nomes explícitos, poucos efeitos colaterais e retorno previsível.

## Arquivos
Use `pathlib.Path`. Para abrir recursos, prefira context manager (`with`).

## Erros
Capture exceções específicas. Não use `except Exception: pass`.

## HTTP
Sempre use timeout. Trate status. Limite retries. Respeite políticas da fonte.

## Dados
Preserve raw. Normalize em outra camada. Registre provenance.

## Testes
Teste entrada → comportamento → saída. Casos-limite valem mais que dezenas de testes triviais.

## Debug
Leia o traceback de baixo para cima: exceção, mensagem, linha, contexto.

## Refatoração
Primeiro preserve comportamento com testes. Depois mude estrutura.
