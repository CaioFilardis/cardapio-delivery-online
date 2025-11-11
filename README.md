# 🍔 Cardápio Online

> Um sistema prático e intuitivo para digitalizar o cardápio de restaurantes, bares e estabelecimentos similares, permitindo que clientes façam pedidos diretamente pelo WhatsApp.

[![GitHub](https://img.shields.io/badge/GitHub-CaioFilardis-blue?style=flat-square&logo=github)](https://github.com/CaioFilardis)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)]()

---

## 📋 Sumário

- [🍔 Cardápio Online](#-cardápio-online)
  - [📋 Sumário](#-sumário)
  - [🎯 Visão Geral](#-visão-geral)
  - [✨ Funcionalidades](#-funcionalidades)
    - [✅ Implementadas](#-implementadas)
  - [🛠 Tecnologias](#-tecnologias)
    - [Frontend](#frontend)
    - [Bibliotecas](#bibliotecas)
    - [Serviços Externos](#serviços-externos)
  - [📦 Instalação](#-instalação)
    - [Pré-requisitos](#pré-requisitos)
    - [Opção 1: Clone o Repositório](#opção-1-clone-o-repositório)

---

## 🎯 Visão Geral

O **Cardápio Online** é uma solução web frontend que permite pequenos e médios estabelecimentos de alimentação oferecerem uma experiência moderna de compra digital. O sistema foi desenvolvido com foco em:

- **Simplicidade**: Interface intuitiva e fácil de navegar
- **Responsividade**: Funciona perfeitamente em desktop, tablet e mobile
- **Integração WhatsApp**: Pedidos são enviados diretamente via WhatsApp Business
- **Customização Fácil**: Estrutura modular e bem documentada

**Demo ao vivo**: [caiofilardis.github.io/Cardapio-Online/](https://caiofilardis.github.io/Cardapio-Online/)

---

## ✨ Funcionalidades

### ✅ Implementadas

- **📱 Visualização Responsiva**
  - Design mobile-first
  - Totalmente adaptável a qualquer tamanho de tela
  - Navegação intuitiva

- **🛒 Carrinho de Compras**
  - Adicionar/remover produtos
  - Aumentar/diminuir quantidade
  - Cálculo automático de total
  - Badge com quantidade total
  - Botão flutuante persistente

- **📂 Categorias de Produtos**
  - 6 categorias: Burgers, Pizzas, Churrasco, Steaks, Bebidas, Sobremesas
  - Aproximadamente 72 produtos
  - Paginação (8 iniciais + 4 com "Ver mais")
  - Filtro rápido por categoria

- **📍 Fluxo de Pedido (3 Etapas)**
  - **Etapa 1**: Revisão do carrinho com controle de quantidade
  - **Etapa 2**: Preenchimento de endereço com busca automática por CEP
  - **Etapa 3**: Resumo final antes do envio

- **🔗 Integração WhatsApp**
  - Link direto para conversa
  - Mensagem pré-formatada com:
    - Nome do cliente
    - Items com quantidade e preço
    - Endereço de entrega completo
    - Total (incluindo taxa de entrega)

- **⭐ Depoimentos**
  - 3 depoimentos com avaliação em estrelas
  - Navegação entre depoimentos
  - Layout responsivo

- **📞 Canais de Contato**
  - Botão para ligação telefônica
  - Link para reserva via WhatsApp
  - Links para redes sociais (Instagram, Facebook, WhatsApp)

- **🎨 Animações e Efeitos**
  - Animações ao scroll
  - Transições suaves
  - Efeitos hover nos elementos interativos

---

## 🛠 Tecnologias

### Frontend

| Tecnologia | Versão | Descrição |
|------------|--------|-----------|
| **HTML5** | - | Estrutura semântica |
| **CSS3** | - | Estilização responsiva |
| **JavaScript** | ES6+ | Interatividade |
| **jQuery** | 1.12.4 | Manipulação DOM |
| **Bootstrap** | 4.x | Framework responsivo |

### Bibliotecas

| Biblioteca | Versão | Uso |
|-----------|--------|-----|
| **FontAwesome** | 5.x | Ícones |
| **Animate.css** | - | Animações CSS |
| **WOW.js** | - | Trigger de animações ao scroll |
| **Modernizr** | 3.5.0 | Detecção de recursos |
| **Popper.js** | - | Posicionamento de elementos |

### Serviços Externos

| Serviço | Descrição |
|---------|-----------|
| **ViaCEP API** | Busca de endereços por CEP |
| **WhatsApp API** | Integração para envio de pedidos |
| **GitHub Pages** | Hospedagem |

---

## 📦 Instalação

### Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet

### Opção 1: Clone o Repositório

