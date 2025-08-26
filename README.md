# gRPC Demo: Microsserviços com Go e Spring Boot

Este projeto é uma demonstração de como utilizar gRPC para uma comunicação rápida e eficiente entre microsserviços. O cenário simula um sistema de e-commerce simples com dois serviços principais:

- **Orders Service (Go)**: Responsável por receber e processar pedidos.
- **Inventory Service (Spring Boot)**: Responsável por controlar o estoque dos produtos.

O desafio principal é garantir que um pedido só seja confirmado se houver estoque disponível, exigindo uma comunicação confiável e de baixa latência entre os dois serviços.
