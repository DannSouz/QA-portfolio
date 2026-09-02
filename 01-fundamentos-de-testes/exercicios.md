# Exercício — Regra de Frete

## Requisito

Compras de R$ 200,00 ou mais devem receber frete grátis.

## Resultados observados

| Valor da compra | Resultado |
|---|---|
| R$ 199,99 | Frete de R$ 15 |
| R$ 200,00 | Frete de R$ 15 |
| R$ 200,01 | Frete grátis |
| R$ 250,00 | Frete grátis |

## Análise

### Falha identificada

Uma compra de exatamente R$ 200,00 recebeu cobrança de frete, contrariando o requisito especificado.

### Possível defeito

A condição pode ter sido implementada utilizando:

`valor > 200`

quando deveria considerar:

`valor >= 200`

### Resultado esperado

Compras com valor igual ou superior a R$ 200,00 devem receber frete grátis.

### Verificação ou validação?

**Verificação**, pois o comportamento observado está sendo comparado diretamente com um requisito especificado.
