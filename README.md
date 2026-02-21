# ✏️ Desafio Shakers Semana 2: Landing Page

<br>

Este repositório contém a solução para o Desafio da Semana 2 da Shakers. O objetivo foi desenvolver uma Landing Page promocional para a nova coleção de loções do cliente "Frederico Business", utilizando a arquitetura Online Store 2.0 da Shopify.

<br>

## 🚀 O que foi implementado

<br>

* **Textos dinâmicos:** O título e a descrição principal da página não estão no código. Eles vêm direto do que o lojista digitar na hora de criar a página no Admin da Shopify (usando o objeto `page`).
* **Produto em Destaque:** Criei um campo para o dono da loja escolher qual loção é a estrela da campanha. O código puxa a imagem, o preço e o link de compra desse produto automaticamente (usando o objeto `product`).
* **Vitrine de Loções:** Também dá para selecionar uma coleção inteira no painel, e a página monta uma listagem com esses produtos logo abaixo (usando o objeto `product_list`).

Para fazer isso funcionar, aprendi a conectar um **Template** (o esqueleto da página) a uma **Section** (o bloco visual) através de um **Schema** (que é o que cria aqueles botões de escolha no painel da Shopify).

## 💻 Como testar localmente

<br>

Para testar este tema no teu ambiente local, certifique-se de que tenha o [Shopify CLI](https://shopify.dev/docs/themes/tools/cli) instalado e siga estes passos:

1. Clone este repositório no seu computador.
2. Abra o terminal, entre na pasta do projeto e rode o comando do Shopify CLI:
   ```bash
   shopify theme dev

<br>

## 💻 Pull Requests 

Link para o pull request aberto:

[Pull Requests](https://github.com/pedrocalazans05/shakers-semana-2-lp-lotions/pull/5)

Made by Pedro Calazans 🤠
