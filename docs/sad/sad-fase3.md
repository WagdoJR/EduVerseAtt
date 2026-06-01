# Software Architecture Document - EduVerse (Fase 3)

## 1. Visão Geral

O EduVerse é uma plataforma educacional adaptativa que utiliza Inteligência Artificial para personalizar o aprendizado.

---

## 2. Arquitetura

A arquitetura segue o modelo de microsserviços, baseada em containers e hospedada em cloud (AWS).

### Componentes:

* Frontend
* API Gateway
* User Service
* Recommendation Service
* Content Service
* Banco de Dados
* Serviço de IA

---

## 3. Estratégia de Cloud

* Provedor: AWS
* Modelo: PaaS
* Serviços:

  * ECS (containers)
  * RDS (banco)
  * API Gateway

---

## 4. Escalabilidade

Escalabilidade horizontal baseada em containers.

---

## 5. Resiliência

* Circuit Breaker
* Retry
* API Gateway

---

## 6. Comunicação

* REST (síncrono)
* Mensageria (assíncrono)

---

## 7. Segurança

* Autenticação via token
* Controle de acesso

---

## 8. Considerações Finais

A arquitetura proposta garante escalabilidade, resiliência e flexibilidade, atendendo aos requisitos do sistema EduVerse.

---
