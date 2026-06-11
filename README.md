# Real-Time Chat App com Spring Boot & WebSockets

Este repositório contém uma aplicação full-stack de chat em tempo real. O objetivo principal deste projeto é explorar e aprofundar conhecimentos na integração de sistemas backend em Java com interfaces web, com foco na implementação do protocolo WebSockets para estabelecer uma comunicação bidirecional contínua.

## 🎯 Objetivo de Aprendizagem
Este projeto foi desenvolvido como um exercício prático para compreender a fundo o funcionamento dos WebSockets, substituindo o paradigma tradicional de *request-response* do HTTP por conexões persistentes. A exploração abrange desde a configuração do `MessageBroker` no backend até à gestão de eventos, payloads e subscrições via STOMP no cliente.

## 🚀 Funcionalidades
* **Comunicação em Tempo Real:** Envio e receção instantânea de mensagens entre múltiplos utilizadores conectados simultaneamente na sala de chat.
* **Notificações de Estado:** Alertas automáticos no ecrã quando um utilizador entra ou abandona a sessão (escutando o evento `SessionDisconnectEvent`).
* **Avatares Dinâmicos:** Geração automática de avatares baseados na inicial do nome e atribuição de cores de forma aleatória.
* **Frontend Nativo:** Interface de utilizador desenhada apenas com HTML, CSS e Vanilla JavaScript, garantindo uma manipulação direta e fluida do DOM.

## 🛠️ Tecnologias Utilizadas
**Backend:**
* Java
* Spring Boot 3
* Spring WebSockets
* Lombok (redução de *boilerplate* code)

**Frontend:**
* HTML5 / CSS3
* Vanilla JavaScript
* SockJS (gestão da conexão websocket e fallbacks)
* StompJS (mensageria orientada a texto simples)

## 📺 Créditos e Atribuição
O código presente neste repositório foi escrito e acompanhado com base no excelente tutorial criado por **Ali Bouali**:
* **Vídeo Original:** [Spring boot & WebSockets: Build a Real-Time Chat App From Scratch](https://www.youtube.com/watch?v=TywlS9iAZCM) [00:00:00]
* **Canal:** Ali Bouali

Esta implementação foi feita com um intuito puramente educativo, servindo como uma base estrutural sólida para a futura criação e integração de arquiteturas *real-time* noutros projetos e plataformas.