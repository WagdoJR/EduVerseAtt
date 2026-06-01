# ADR 0002 - Padrões de Resiliência

## Status

Aceito

## Contexto

O sistema precisa lidar com falhas de serviços externos e picos de carga.

## Decisão

Uso de:

* API Gateway
* Circuit Breaker
* Retry

## Justificativa

Evita falhas em cascata e melhora a disponibilidade.

## Trade-offs

* Vantagens:

  * Maior resiliência
  * Melhor experiência do usuário
* Desvantagens:

  * Maior complexidade
  * Overhead

## Referências

* Martin Fowler
* Richards & Ford
