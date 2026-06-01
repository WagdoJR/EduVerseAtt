# ADR 0001 - Estratégia de Nuvem e Escalabilidade

## Status

Aceito

## Contexto

A plataforma EduVerse precisa suportar milhares de usuários simultâneos, garantindo alta disponibilidade e escalabilidade.

## Opções consideradas

* IaaS: maior controle, porém maior complexidade operacional
* PaaS: facilidade de gerenciamento e escalabilidade automática
* Serverless: alta escalabilidade, porém maior complexidade e custo

## Decisão

Foi adotado o modelo PaaS utilizando AWS com containers.

## Justificativa

O modelo PaaS permite foco no desenvolvimento, reduzindo esforço operacional.

## Trade-offs

* Vantagens:

  * Escalabilidade automática
  * Menor complexidade operacional
* Desvantagens:

  * Menor controle da infraestrutura
  * Dependência do provedor

## Referências

* Pressman (2021)
* Richards & Ford (2020)
