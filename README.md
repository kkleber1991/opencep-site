# 🚀 OpenCEP Ultra

<p align="center">
  <img src="logo.png" alt="OpenCEP Ultra Logo" width="200"/>
</p>

<p align="center">
  <b>A API de CEP mais rápida, robusta e escalável do Brasil.</b><br>
  Construída com arquitetura Jamstack sobre Cloudflare R2 e Workers para performance de nível global.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License MIT">
  <img src="https://img.shields.io/badge/Cloudflare-Workers-FF4A03?logo=cloudflare&logoColor=white" alt="Cloudflare Workers">
  <img src="https://img.shields.io/badge/Jamstack-000000?logo=jamstack&logoColor=white" alt="Jamstack">
  <img src="https://img.shields.io/badge/SLA-99.99%25-brightgreen" alt="SLA High">
</p>

---

## 🌟 O que é o OpenCEP Ultra?

O **OpenCEP Ultra** redefine como desenvolvedores brasileiros consomem dados postais. Utilizando uma arquitetura de **Dados Estáticos em Borda (Edge Storage)**, eliminamos a necessidade de bancos de dados tradicionais lentos, entregando respostas em milissegundos com custo operacional zero.

### ✨ Diferenciais de Elite
- **Performance Extrema:** Servido diretamente da rede de borda da Cloudflare.
- **Filtros Inteligentes:** Única API gratuita com suporte nativo a filtros por Bairro, Cidade e Estado.
- **SLA de Elite:** Sem quedas por sobrecarga de banco de dados.
- **Ética Open Source:** Baseado nos dados do projeto OpenCEP com melhorias contínuas.

---

## 🛠️ Guia de Uso (API Reference)

A API é acessível via qualquer cliente HTTP (Fetch, Axios, cURL).

### 1. Consulta por CEP Individual
Retorna os dados completos de um logradouro específico.
- **Endpoint:** `GET /v1/{CEP}.json`
- **Exemplo:** `https://api-cep.kedllon.solutions/v1/01001000.json`

### 2. Consulta Consolidada por Estado
Obtenha a base completa de uma UF em uma única chamada de alta velocidade.
- **Endpoint:** `GET /estados/{UF}.json`
- **Exemplo:** `https://api-cep.kedllon.solutions/estados/AC.json`

### 3. Filtros por Cidade e Bairro
Ideal para preenchimento de formulários e dashboards de logística.
- **Cidades:** `GET /cidades/{UF}_{CIDADE}.json`
- **Bairros:** `GET /bairros/{UF}_{CIDADE}_{BAIRRO}.json`

---

## 🏗️ Arquitetura Técnica

O projeto é mantido por três pilares tecnológicos:

1.  **Storage (Cloudflare R2):** 1.2 milhões de arquivos JSON servidos com latência ultra-baixa.
2.  **Routing (Cloudflare Workers):** Um "cérebro" inteligente que gerencia rotas e fornece respostas amigáveis para desenvolvedores.
3.  **Docs (GitHub Pages):** Documentação técnica e vitrine visual hospedada de forma perene.

---

## 🤝 Contribuição e Comunidade

Este é um projeto aberto! Se você deseja reportar erros, sugerir melhorias ou contribuir com o código:

1.  Veja nosso [Guia de Contribuição](CONTRIBUTING.md).
2.  Respeite nosso [Código de Conduta](CODE_OF_CONDUCT.md).
3.  Reporte falhas em nossa seção de [Segurança](SECURITY.md).

---

## ⚖️ Licença

Distribuído sob a licença **MIT**. Veja o arquivo `LICENSE` para mais detalhes.

---
<p align="center">
  Desenvolvido com ❤️ por <b>Kedllon Solutions</b>
</p>
