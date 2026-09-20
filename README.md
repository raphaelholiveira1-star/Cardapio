# Lanchonete Praça 12 | Cardápio digital com pagamento online (projeto de demonstração)

Cardápio digital fictício de uma lanchonete, em que o cliente monta o pedido, paga pelo próprio site e acompanha o andamento. Foi criado para demonstrar como um pequeno negócio pode vender sem app, sem cadastro e sem depender de conversas no WhatsApp. Não é uma lanchonete real e nenhum pagamento é processado.

## O que o projeto faz

- Cardápio organizado por categorias (lanches, porções, bebidas e sobremesas), com menu de navegação rápida
- Botões de adicionar e ajustar a quantidade de cada item, e barra fixa com o total no celular
- Pedido com nome, retirada ou entrega (com endereço e taxa) e observações
- Pagamento pelo site: **Pix** (QR Code e código copia e cola), **cartão** (com validação dos campos) ou **na entrega** (com campo de troco)
- Tela de acompanhamento do pedido, com as etapas: recebido, em preparo, pronto ou a caminho, e entregue
- Layout pensado primeiro para o celular, com tema claro e escuro conforme o aparelho

## Como abrir

1. Baixe ou clone esta pasta.
2. Abra o arquivo `index.html` no navegador.

Não precisa instalar nada. Mantenha o `index.html` e o `style.css` na mesma pasta.

## Como adaptar para um cliente

- **Cardápio:** os itens ficam na lista `M`, no `<script>` do `index.html`. Cada item tem número, ícone, nome, descrição e preço.
- **Taxa de entrega:** altere o valor de `FEE`.
- **Nome, cores e textos:** o nome está no `index.html`, e as cores no começo do `style.css`.

## Tecnologias

HTML, CSS e JavaScript puros, sem bibliotecas e sem imagens externas.

## Como seria em um projeto real

Nesta versão o cardápio está fixo no código, o Pix e o cartão são simulados e o andamento do pedido é acelerado para a demonstração. Em um projeto de verdade, o pagamento seria feito por um serviço como Mercado Pago ou Pagar.me, os pedidos chegariam a um painel para a cozinha e o dono poderia editar o cardápio e marcar itens como esgotados.
