# 🚀 OpenCEP Ultra

A API de CEP mais rápida e completa do Brasil. Construída sobre arquitetura **Jamstack**, utilizando **Cloudflare R2** para garantir alta disponibilidade e latência mínima.

## 📍 Diferenciais Únicos

Diferente de outras APIs de CEP, o **OpenCEP Ultra** permite consultas consolidadas que economizam centenas de chamadas:

- **Busca por CEP Individual**: Retorno instantâneo dos dados de um logradouro.
- **Filtro por Cidade**: Obtenha todos os CEPs de uma cidade em uma única chamada.
- **Filtro por Bairro**: Acesso detalhado a todos os códigos postais de um bairro específico.
- **Filtro por Estado**: Base completa de CEPs por UF.

## 🛠️ Como Usar

A API é RESTful e retorna dados no formato JSON.

### Exemplos de Endpoints

| Tipo | Endpoint |
| :--- | :--- |
| **CEP Individual** | `https://api-cep.kedllon.solutions/v1/01001000.json` |
| **Por Cidade** | `https://api-cep.kedllon.solutions/cidades/SP_高度_Sao_Paulo.json` |
| **Por Bairro** | `https://api-cep.kedllon.solutions/bairros/SP_高度_Sao_Paulo_高度_Se.json` |
| **Por Estado** | `https://api-cep.kedllon.solutions/estados/AC.json` |

## 🏗️ Arquitetura

Este projeto utiliza:
- **Hospedagem de Dados:** Cloudflare R2 (Object Storage).
- **Hospedagem de Docs:** GitHub Pages.
- **Processamento:** Scripts Python customizados para organização e normalização de dados baseados no projeto OpenCEP original.

## ⚖️ Licença e Ética

Este projeto é um derivado otimizado do projeto [OpenCEP](https://github.com/SeuAliado/OpenCEP). 
Mantemos a licença **MIT**, permitindo o uso livre e incentivando a colaboração.

---
Desenvolvido por **Kedllon Solutions**.
