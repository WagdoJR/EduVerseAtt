# ADR 0003 - Modelo de Comunicação

## Status

Aceito

## Contexto

Necessidade de comunicação eficiente entre microsserviços.

## Opções

* Síncrono (REST)
* Assíncrono (mensageria)

## Decisão

Uso híbrido:

* REST para comunicação direta
* Mensageria para eventos

## Justificativa

Equilíbrio entre performance e escalabilidade.

## Trade-offs

* Vantagens:

  * Desacoplamento
  * Escalabilidade
* Desvantagens:

  * Complexidade
  * Debug mais difícil

## Referências

* C4 Model
* ADR Docs