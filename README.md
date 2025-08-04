# Projeto Zs - Visualizador RC, Validação e Gasto v3.0

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)  
[LinkedIn](https://www.linkedin.com/in/josé-wesllen)

---

## Visão Geral

O **Visualizador RC, Validação e Gasto v3.0** é uma aplicação web interna desenvolvida em Google Apps Script para otimizar e centralizar processos de suprimentos e operações. A ferramenta integra-se a uma planilha Google que funciona como banco de dados, fornecendo uma interface intuitiva e segura para:

- Criação automatizada de Requisições de Compra (RCs);
- Validação e aprovação das compras pelos gestores;
- Monitoramento e análise de dados de gastos e status.

---

## Objetivos

- Automatizar a criação de RCs evitando duplicidade;
- Facilitar a validação e ajuste de compras conforme a demanda real;
- Oferecer dashboards para acompanhamento em tempo real da operação;
- Centralizar informações e otimizar o fluxo de suprimentos.

---

## Público-Alvo

- **Gestores de Unidade:** Para validação e criação de RCs;
- **Equipe de Suprimentos/Compras:** Para acompanhamento das requisições e status;
- **Gestores de Operações:** Para visão geral dos gastos e conformidade.

---

## Tecnologias Utilizadas

- **Backend:** Google Apps Script (Code.gs)  
- **Frontend:** HTML, CSS, JavaScript (Single Page Application - SPA)  
- **Banco de Dados:** Google Sheets  
- **Bibliotecas:** Google Charts para visualização gráfica dos dados  

---

## Arquitetura do Sistema

### Backend (Code.gs)

- Serve a interface principal via `doGet(e)`.
- API de funções acessadas via `google.script.run`.
- Implementa a lógica de negócios, regras de validação, leitura e escrita na planilha.

### Frontend (HTML, CSS, JS)

- Single Page Application que gerencia telas via manipulação dinâmica do DOM.
- Design responsivo e moderno.
- Comunicação assíncrona com o backend para operações em tempo real.

### Fonte de Dados

- Dados armazenados e gerenciados em Google Sheets que funcionam como banco de dados.

---

## Funcionalidades Principais

- **Criação automática de RCs:** Identificação e registro de itens aptos para compra.  
- **Validação de Compras:** Interface para gestores aprovarem ou ajustarem quantidades.  
- **Dashboards:** Visualização do status de validação, estimativas de gastos e prazos.  
- **Controle de Acesso:** Interface segura para diferentes perfis de usuário.

---

## Como Executar Localmente

1. Abra o Google Apps Script (https://script.google.com) e crie um novo projeto.  
2. Importe os arquivos do backend (`Code.gs`) e do frontend (HTML, CSS, JS).  
3. Vincule o script à planilha Google que será usada como banco de dados.  
4. Publique o projeto como aplicativo web para acesso interno.

---

## Contato

**José Wesllen**  
[LinkedIn](https://www.linkedin.com/in/josé-wesllen)  
Email: wesllenmanoel@live.com

---

## Licença

Este projeto está sob a licença MIT — veja o arquivo [LICENSE](LICENSE) para detalhes.

---

*Alguns códigos foram otimizados com o auxílio de Inteligência Artificial para melhores práticas.*

