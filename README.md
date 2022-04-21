# Habilidades

Nesse projeto, você deverá ser capaz de:

- Manter aderência do código à especificação. Seu programa deve se comportar como especificado no repositório, no [protótipo](https://www.figma.com/file/cNKu41RhnPIgNqrbMTzmUI/Delivery-App-new-trybeer?node-id=0%3A1) e no [Diagrama de ER](./assets/readme/eer.png);
- Manter a organização do seu código e a arquitetura geral da aplicação (tanto da API quando do front-end);
- Manter aderência ao padrão REST na API;
- Respeitar a estrutura do banco de dados. Sua implementação não deve adicionar ou remover tabelas, campos ou relacionamentos e sua API deve estar preparada para aproveitar essa estrutura por completo;
- Manter uma cobertura de testes. Seu código deve ser testável e possuir uma suíte de testes unitários e/ou de integração robusta e com alta cobertura.
- Implementar a funcionalidade de comunicação em tempo real, utilizando o socket.io.
- Manter aderência aos princípios SOLID;

## O que deverá ser desenvolvido

Esse será o projeto mais desafiador até agora! Nessa aplicação, vocês serão responsáveis por criar e integrar tanto o back-end quanto o front-end!

O projeto em si é super divertido! Como dado no contexto, você vai criar uma plataforma de delivery de cerveja. 🍻

Para facilitar o entendimento, podemos dividir a aplicação em ** 4 fluxos principais**, **uma validação de status entre cliente e pessoa vendedora** e **cobertura de testes (`front-end` e `back-end`)**:

- **Fluxo Comum** que compreende: 
  - (1) Tela de Login (`01login.test`); 
  - (2) Tela de Registro (`02register.test`).

- **Fluxo do Cliente** que compreende: : 
  - (3) Tela de Produtos (`03customer_products.test`); 
  - (4) Tela de Checkout (`04customer_checkout.test`); 
  - (5) Tela de Pedidos (`05customer_orders.test`); 
  - (6) Tela de Detalhes do Pedido (`06customer_order_details.test`).

- **Fluxo da Pessoa Vendedora** que compreende: 
  - (7) Tela de Pedidos (`07seller_orders.test`); 
  - (8) Tela de Detalhes/Controle do Pedido (`08seller_order_details.test`).

- **Validação do Status do Pedido** que compreende: 
  - (9) Teste de status sem atualização em tempo real (`09customer_seller_status_sync.test`); 
  - (10) Teste de status com atualização em tempo real (`10customer_seller_socket_status_sync.test`).

- **Fluxo da Pessoa Administradora** que compreende: 
  - (11) Tela de gerenciamento de usuários (`11admin_manage_users.test`).

- **Testes da aplicação** que compreende: 
  - (12) Testes de cobertura (`12coverage_tests.test`).
