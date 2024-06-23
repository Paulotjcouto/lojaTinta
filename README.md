# Sistema de Vendas em Java

Este é um projeto de implementação de um sistema de vendas de Tintas e matérias de construção relacionado com pintura em Java, com interface gráfica usando Swing. O sistema permite que os usuários visualizem uma vitrine de produtos, adicionem itens ao carrinho, visualizem o carrinho, realizem o pagamento e efetuem o logout tudo  isso com uma interface amigável e de fácil entendimento.

 



### Tela de Vitrine de Produtos 🛍️:
 
- Exibe uma variedade de produtos disponíveis para venda.
- Cada produto é representado por uma imagem, nome, preço e opção para adicionar ao carrinho.
- Os produtos são carregados a partir de um estoque pré-definido.

### Adição de Produtos ao Carrinho ➕:
- Os usuários podem selecionar produtos na vitrine e adicionar ao carrinho.
- Eles podem escolher o tamanho do produto, se aplicável.
 

### Tela do Carrinho 🛒:
- Exibe todos os itens atualmente no carrinho, incluindo imagem, nome, preço, quantidade e subtotal de cada item.
- Permite que os usuários visualizem o total do carrinho.
- Oferece opções para esvaziar o carrinho ou proceder para o pagamento.
 

### Pagamento 💳:
- Ao proceder para o pagamento, os usuários são redirecionados para uma tela de pagamento onde podem inserir suas informações de pagamento.
- Após o pagamento ser concluído com sucesso, o carrinho é esvaziado e uma mensagem de confirmação é exibida.
 

 

### Sair 🔐:
- Os usuários têm a opção de fazer logout do sistema a qualquer momento.
- Ao fazer logout, eles são redirecionados para a tela de login.

## Funcionamento do Código 💻:
O sistema é composto por várias classes Java que se comunicam para fornecer funcionalidades específicas. As classes principais incluem `TelaPrincipal`, `TelaCarrinho`, `TelaPagamento`, `TelaLogin`, `Carrinho`, `Estoque`, `Produto` e `ItemVenda`.

- O código faz uso extensivo do pacote `javax.swing` para criar a interface gráfica do usuário.
- O estoque de produtos é carregado a partir de um arquivo de dados.
- As interações do usuário são tratadas por meio de `ActionListeners` associados a botões e outros componentes de interface.

## Vídeo de Demonstração 🎥
Aguardando Gustavo mudar o front
## Diagrama de Classes 📊
