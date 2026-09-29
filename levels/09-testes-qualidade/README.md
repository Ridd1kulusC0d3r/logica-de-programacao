# Testes, qualidade e packaging

## Resultado esperado
Transformar scripts que “funcionam na minha máquina” em software verificável.

## Conteúdo
- pytest, assert e organização de testes
- fixtures e parametrização
- mocks apenas quando necessários
- Ruff e higiene estática
- type checking com mypy
- pyproject.toml
- pacotes e imports
- GitHub Actions / CI

## Missões
1. Escreva testes para uma função antiga antes de refatorá-la.
2. Converta cinco casos repetidos em `pytest.mark.parametrize`.
3. Teste uma falha esperada com `pytest.raises`.
4. Faça o Ruff apontar um problema e corrija-o entendendo a regra.
5. Adicione type hints a um módulo.
6. Rode a suíte localmente.
7. Faça o CI executar lint + testes a cada PR.

## Entrega
Leve os Scripts #1–#7 para **CI verde**.

## Gate
- [ ] testes cobrem comportamento, não implementação;
- [ ] erros esperados são testados;
- [ ] lint passa;
- [ ] imports estão organizados;
- [ ] projeto instala em ambiente limpo;
- [ ] PR demonstra CI funcionando.
