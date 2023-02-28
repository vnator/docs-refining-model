# Feature Login
<!-- breve descrição da feature -->
tela de login para o aplicativo guild da VNATOR.

## informações da tela

### respostas do servidor.
| nome | descrição | origem | observações |
| ---- | --------- | ------ | ----------- |
| error message | mensagem de erro que retorna da requisição de login | [api_login](https://link-exemplo-api-login) |  |

## Eventos
Definições dos eventos e suas exceções para login do usuário e validação dos inputs.

### validações do input email.
| validação | descrição | mensagem de erro |
| --------- | --------- | ---------------- |
| required | obrigatório inserir valor | need's email |
| e mail | verificação de email | type a valid email |


### mostrar senha
**DADO QUE** o usuário clica no botão com ícone `visibility`, no input do password,
**E** sua senha está escondida pelo padrão de input do tipo `password`.
**ENTÃO** sua senha deve ser exposta e o ícone deve ser alterado para o ícone `visibility hidden` disponível no layout
**CASO** clique novamente a senha deve ser escondida como antes do primeiro clique no ícone também deve retornar a ser o `visibility`.

### login
**DADO QUE** o usuário preencheu corretamente os campos de input email e password
**E** clica no botão `login`.
**ENTÃO** o título do login deve ser substituído pela palavra `await`
**CASO** a resposta da requisição seja com status `200` deve ser redirecionado para a [tela de perfil do usuário](https://www.figma.com/file/WtMpi3eZqmUSEqZY4hDRAk/refining-example?node-id=0%3A1).
**CASO** a resposta do servidor seja diferente de `200`, deve utilizar a mensagem de resposta e apresentar na informação de `mensagem de erro`.

### recuperar senha
**DADO QUE** usuário clica no link `forgot your password?`
**ENTÃO** este deve ser redirecionado para a tela de [recuperação de senha](https://link-de-exemplo-para-recuperação-de-senha).


## Anexos
- [tela de login](https://www.figma.com/file/WtMpi3eZqmUSEqZY4hDRAk/refining-example?node-id=0%3A1)
- [api_login](https://hackmd.io/TepmNZDoREqzRAr_5hC7-A)