# Feature User Profile

<!-- breve descrição da feature -->
tela de perfil do usuário focada em apresentar informações gerais do usuário para o aplicativo guild da VNATOR.

## informações da tela
A tela de usuários deverá apresentar as informações do usuário e da empresa a qual este presta serviços.

### informações do usuário.
| nome | descrição | origem | observações |
| ---- | --------- | ------ | ----------- |
| picture | foto de usuário | user_profile_api | atributo de resposta da requisição `data.pictureUrl` |
| userName | nome de usuário | user_profile_api | atributo de resposta da requisição `data.userName` |
| bio | biografia do usuário | user_profile_api | atributo de resposta da requisição `data.bio` |
| gender | gênero do usuário | user_profile_api | atributo de resposta da requisição `data.gender` |
| employ | ocupação do usuário | user_profile_api | atributo de resposta da requisição `data.employ` |
| age | ocupação do usuário | user_profile_api | atributo de resposta da requisição `data.age` |


### informações da empresa.
| nome | descrição | origem | observações |
| ---- | --------- | ------ | ----------- |
| companyName | nome fantasia da empresa | user_profile_api | atributo de resposta da requisição `data.company.publicName` |
| companyAtivity | ramo de atividade da empresa | user_profile_api | atributo de resposta da requisição `data.company.employ` |
| description | resumo da descrição sobre a empresa | user_profile_api | atributo de resposta da requisição `data.company.resume` |

### Logout
**DADO QUE** o usuário clica no botão de ícone `logout`
**ENTÃO** o aplicativo deve utilizar a [api_login_endpoint_logout](https://hackmd.io/TepmNZDoREqzRAr_5hC7-A) e após receber uma resposta com status `200` deve redirecionar para a [tela de login](https://www.figma.com/file/WtMpi3eZqmUSEqZY4hDRAk/refining-example?node-id=0%3A1)


### Anexos
- [Tela de User Profile](https://www.figma.com/file/WtMpi3eZqmUSEqZY4hDRAk/refining-example?node-id=3%3A103)