EPI-MISU — SITE V1.2
===================

ALTERAÇÕES DA V1.2
-------------------
1. Páginas técnicas (A MISU, Pontas com Engate Rápido, Ligação de Pressão, Conexões Irrigação, Tubulação de Sucção e Catálogos): botão central inferior “Tela Cheia”, com Fullscreen API e fallback compatível com navegadores que não permitem fullscreen nativo.
2. Lista de Preços com área própria de rolagem, tarja de pesquisa/grupo fixa e cabeçalho fixo: Imagem, Código, Peso (Kg), Descrição, Preço Unit., Quant. Disponível e Prazo.
3. Cada produto da Lista de Preços possui botão “Comprar”, que abre o mesmo item no Pedido de Compra.
4. Lista de Preços e Pedido de Compra possuem “Limpar Pesquisa”.
5. “Produtos disponíveis” foi renomeado para “Pedido de Compra”.
6. Pedido de Compra passou a usar a mesma estrutura tabular da Lista de Preços, com Quant. Pedido e ADICIONAR ao Carrinho.
7. Cadastro do comprador ganhou: Código do Cliente, Inscrição Estadual, Telef. Fixo, Pessoa de Contato, Representante Legal e Transportadora Indicada.
8. Ao digitar um Código do Cliente já cadastrado neste navegador, os dados são carregados automaticamente. O cadastro é salvo/atualizado ao finalizar pedido com código informado.
9. Forma de Entrega: Retirar na MISU, Transportadora, Via Aérea e Rodoviária.
10. Resumo do Pedido ganhou seleção de Frete: Calcular, CIF e Retirar na MISU. Até definição da cobrança, o valor permanece R$ 0,00 e a regra padrão é FRETE GRÁTIS-CIF.
11. Controle de Vendas local exibe os novos campos do comprador.

OBSERVAÇÃO SOBRE CLIENTES
-------------------------
Nesta V1.2 sem Worker/D1, a ficha do cliente é gravada no localStorage do navegador. Para funcionar de forma compartilhada entre vários computadores/celulares, a próxima etapa deve criar a tabela CLIENTES no Worker/D1 exclusivo EPI-MISU.

PUBLICAÇÃO NO GITHUB PAGES
---------------------------
1. Envie TODO o conteúdo da pasta EPI_MISU_V1_2 para o repositório.
2. Mantenha index.html e representantes.html na raiz e preserve assets/ e data/.
3. Settings > Pages > Deploy from a branch > main / root.
4. Teste em computador e celular: Tela Cheia, pesquisas, Comprar da Lista de Preços, Pedido de Compra, Carrinho, Cadastro por Código de Cliente, Formas de Entrega, Frete, PIX, Meus Pedidos e ADM.
