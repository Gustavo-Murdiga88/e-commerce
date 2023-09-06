## Sistema de vendas

### Requisitos

 <br/>

#### Site de vendas

 <br/>

**RF**

---

  - Venda direcionado ao vendedor por zap
  - deve haver uma maneira de limitar o tempo que o produto fica no carrinho do cliente.
  -  Deve se possível cadastrar um cliente
  - Deve ser possível realizar uma venda pelo site
  - Deve haver uma forma de realizar pagamentos pelo site, tai como ->  Cartão de credito e Pix
  - deve haver uma configuração para formas de pagamento.
  - Deve ser possível redirecionar ao vendedor aleatoriamente
  - Deve ser possível criar um link para alteração da senha

<br/>

RNF
___

- Usar o Lexos para listar o produtos no sistema
- Usar o Whatsapp para realizar vendas sem intermediação do site.
- Deve ser possível realizar vendas pelo telefone.
- Ao gerar o link de troca de senha, gerar um token temporário para que assim seja possível acessar está rota.
- Será utilizado Next.js para criação do front-end
- O back end será montado em nodeJS ou PHP, iremos alinhar isso com o tempo.

___
<br/>

**RN**
___

  - Somente o usuário ADM poderá cadastrar clientes
  - Deve ser possível uma integração com hub Lexos
  - Deve ser possível cadastra categoria de produtos e imagens -Lexos
  - Controlar o estoque ao adicionar o carrinho
  - Log de ações do cliente
  - Controle do carrinho – dar um feedback ao cliente quando houver concorrência do produto.
