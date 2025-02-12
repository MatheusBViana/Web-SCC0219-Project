# Projeto de Web - Loja de Plantas

- Luísa Balleroni Shimabucoro - 11832385
- Matheus Bermudes Viana - 11849797
- Wictor Dalbosco Silva - 11871027

## Requerimentos
- O sistema deve ter dois tipos de usuário:
  - *Administradores*: São responsáveis por gerenciar administradores, clientes e podutos. Para utilizar a conta de administrador, utilize as credenciais admin@admin.com:admin no formato (email:senha)
  - *Clientes*: São usuários que acessam o sistema para comprar produtos

- Para armazenar os dados é preciso ter os seguintes registros:
  - *admin*: id, nome, telefone e email
  - *cliente*: id, nome, endereço, telefone e email
  - *produto*: id, nome, foto, descrição, preço, quantidade em estoque e quantidade vendida

- Venda de produtos (ou serviços): produtos são selecionados, suas quantidades definidas e por fim são colocados no carrinho. Produtos são comprados usando um número de cartão de crédito (qualquer número é aceito pelo sistema). A quantidade do produto vendida é subtraída da quantidade do estoque e acrescida a quantidade de produtos vendidos. Carrinhos são esvaziados apenas após o pagamento ou por uma ação direta do usuário.

- Gerenciamento de produtos/serviços: administradores podem criar/atualizar/ler/deletar (CRUD) novos produtos e serviços. Por exemplo, eles podem alterar a quantidade de produtos no estoque.

- **Funcionalidade específica:** o cliente pode selecionar o tipo de residência (casa ou apartamento) e características como iluminação do cômodo, temperatura e tempo disponível para manutenção. Com isso, a aplicação oferece sugestões de plantas que cumprem pelo menos 3 dos 4 critérios.

- O sistema deve atender os requisitos de acessibilidade e prover boa usabilidade. Além disso, o sistema deve ser responsivo.


## Descrição do Projeto
Esse projeto consiste no desenvolvimento de uma aplicação online para uma loja de plantas, a qual terá as seguintes funcionalidades:
- Cadastro e Login
- Adicionar ou remover produtos/serviços do carrinho
- Processo de finalizar compra (checkout)
- Filtros de busca de produtos
- Opções para gerenciamento de clientes, produtos e serviços exclusivas para administradores do sistema
- **Funcionalidade específica:** o cliente pode selecionar o tipo de residência (casa ou apartamento) e características como iluminação do cômodo, temperatura e tempo disponível para manutenção. Com isso, a aplicação oferece sugestões de plantas que cumprem pelo menos 3 dos 4 critérios

Para que essas funcionalidades possuam um funcionamento adequado será necessário armazenar as seguintes informações:
  - *admin*: id, nome, telefone e email
  - *cliente*: id, nome, endereço, telefone e email
  - *produto geral*: id, nome, foto, descrição, preço, quantidade em estoque e quantidade vendida
    - *planta*: além dos atributos padrões, elas possuem tamanho, nível de iluminação, temperatura e manutenção ideais

### Diagrama de Navegação
<img src="Mockups/nav_diagram.png" alt="navigation diagram" width="700"/>

<a href="https://www.figma.com/file/3dgTdFB6VzP9HX0n41i1g5/Plant-Shop-Website-(Practice-%23001)-(Community)-(Copy)?node-id=0%3A1">Projeto no Figma</a>
## Comentários Sobre o Código
## Plano de Testagem
## Resultado dos Testes
## Procedimentos de Construção
## Problemas
## Comentários

