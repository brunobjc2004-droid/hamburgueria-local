# hamburgueria-local
Projeto frontend (SENAI) de uma hamburgueria de bairro, criado com IA e com integração de chatbot via Easy-Peasy.ai.

# 🍔 Nossa Esquina — Hamburgueria de Bairro

Este repositório contém o código-fonte de uma landing page institucional para a hamburgueria fictícia **Nossa Esquina**. O projeto foi desenvolvido como uma atividade prática no **SENAI**, focando no desenvolvimento frontend auxiliado por Inteligência Artificial (IA) e na integração de assistentes virtuais de atendimento.

---

## 🌐 O Site

Uma página única (Single Page Application) responsiva que apresenta a identidade visual, a história e o cardápio da hamburgueria.

* **Tecnologias:** HTML5 estrutural, CSS3 (variáveis nativas e layout responsivo) e JavaScript Vanilla.
* **Scroll Suave Customizado:** Implementação de script JS com curva de *easing* para garantir uma transição de rolagem lenta e fluida (1.2 segundos) entre as seções do menu.
* **Mascote:** Integração da identidade visual do personagem "Léo" no layout da página.

---

## 🤖 Implementação do Chatbot

O grande foco da atividade foi a integração de um assistente virtual dinâmico para simular o atendimento automatizado e anotação de pedidos dos clientes.

* **Plataforma:** [Easy-Peasy.ai](https://easy-peasy.ai/)
* **Método de Integração:** Inserção de script assíncrono diretamente no escopo global (`<body>`) do documento HTML.
* **Customização:** Botão flutuante configurado nativamente no canto inferior direito (`bottom-right`) utilizando a paleta de cores correspondente à identidade visual proposta (`#6366f1`).

```html
<script 
    src="[https://bots.easy-peasy.ai/chat.min.js](https://bots.easy-peasy.ai/chat.min.js)" 
    data-chat-url="[https://bots.easy-peasy.ai/bot/7820ff6c-8330-4873-b3dd-c421cdf6458e](https://bots.easy-peasy.ai/bot/7820ff6c-8330-4873-b3dd-c421cdf6458e)" 
    data-btn-position="bottom-right" 
    data-widget-btn-color="#6366f1" 
    defer>
</script>
