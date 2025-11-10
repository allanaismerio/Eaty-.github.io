#  Eaty - Landing Page de Delivery de Comida

Este projeto é uma landing page (página única) para um serviço fictício de delivery de comida chamado "Eaty". A página foi projetada para atrair clientes, exibir restaurantes e facilitar o contato.

O site é totalmente estático e responsivo, construído com foco em técnicas modernas de HTML5 e CSS3.

## 💻 Seções da Página

A página é dividida nas seguintes seções:

* **Navegação (`<nav>`):** Um menu fixo ("sticky") que acompanha o usuário durante a rolagem, com links âncora para as outras seções e botões de "Entrar" e "Cadastrar".
* **Hero (`<header>`):** A seção principal de boas-vindas com o slogan e campos de busca por endereço e tipo de comida.
* **Restaurantes em Destaque (`#restaurantes`):** Um grid responsivo de cards que exibe os restaurantes parceiros.
* **Como Funciona (`#como-funciona`):** Uma explicação simples em três passos de como usar o serviço.
* **Depoimentos (`#depoimentos`):** Uma seção de prova social com feedback de clientes.
* **Contato (`#contato`):** Uma seção final com informações de contato e um formulário para envio de mensagens.
* **Rodapé (`<footer>`):** Informações de copyright.

## ✨ Recursos Técnicos Implementados

Este projeto utiliza apenas HTML e CSS, sem JavaScript, e foca em recursos nativos do navegador:

* **CSS Moderno:** O layout é construído primariamente com **CSS Flexbox** (para alinhamento) e **CSS Grid** (para a galeria de restaurantes).
* **Grid Responsivo:** A seção de restaurantes usa `grid-template-columns: repeat(auto-fit, ...)` para que os cards se ajustem automaticamente ao tamanho da tela, sem a necessidade de *media queries*.
* **Navegação "Sticky":** O menu principal usa `position: sticky` para permanecer visível no topo da página.
* **Rolagem Suave:** A propriedade `scroll-behavior: smooth;` no CSS permite que a navegação interna entre as seções seja suave.
* **Formulário HTML5:** O formulário de contato utiliza validação nativa do HTML (atributos `required`).

## 🚀 Tecnologias Utilizadas

* **HTML5:** Para toda a estrutura e semântica do conteúdo.
* **CSS3:** Para toda a estilização, layout, responsividade e interações (como `:hover` e `scroll-behavior`). O CSS está incorporado no arquivo HTML.

## Como Visualizar

1.  Clone este repositório para sua máquina local.
2.  Abra o arquivo `index.html` (ou o nome do seu arquivo HTML) em qualquer navegador web.

---
*&copy; 2025 Eaty - Sua fome, nossa entrega.*
