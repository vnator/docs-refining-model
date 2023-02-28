# Refining Backend User Profile

<!-- breve descrição da feature -->
tela do usuário para o aplicativo guild da VNATOR

## Data
A tela de usuários deverá apresentar as informações do usuário e da empresa a qual este presta serviços.

### tabela de usuário usuário.

| nome | origem | status |
| ---- | ------ | ------ |
| picture |	user_profile_api |	created | 
| userName |	user_profile_api |	created | 
| bio |	user_profile_api |	created | 
| gender |	user_profile_api |	created | 
| employ |	user_profile_api |	created | 
| age |	user_profile_api |	created | 
| companyId |	user_profile_api |	to_be_created | 

### informações da empresa.
| nome |	origem |	status |
| ---- | ------ | ------ |
| companyName |	company_profile_api |	to_be_created |
| companyAtivity |	company_profile_api |	to_be_created |
| description |	company_profile_api |	to_be_created |

## Steps

- definição da tabela Company.
- criação da model Company
- alteração da model User
- definição do endpoint company
    - tratamentos de exceções
        - companyName: maximo de 120 chars, not null.
        - companyAtivity: máximo de 240 chars, not nul.
        - description: máximo de 360 chars, not nul.
- migrations da tabela company.
- migrations da alteração de user.

## Tasks
- CRUD Company: desenvolvimento de company em models e alteração de model user,
- Migrations: aplicação de migrations em ambiente local.
- Endpoint: desenvolvimento de endpoint para interface de comunicação.

## Cases
- testar
- incluir company
- consutar company
- endpoint incluir company
    - excessões de companyName
    - excessões de companyAtivity
    - excessões de description
- endpoint consultar company company encontrada
- endpoint consultar company company nao encontrada
- incluir company em user quando company existe
- incluir company em user quando company nao existe