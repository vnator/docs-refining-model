# Refining Frontend Tela de Login 
<!-- breve descrição da feature -->
Desenvolvimento da parte visual da tela de login

### respostas do servidor.
| nome | descrição | origem | observações |
| ---- | --------- | ------ | ----------- |
| error message | mensagem de erro que retorna da requisição de login | [api_login](https://link-exemplo-api-login) |  |

## Steps

- importar imagens externas para aplicação.
- incluir ícones visiblity e visibility hidden
- incluir componentes
    - elementos e componentes
    - estilos dos elementos existentes
    - alterações de estado local possíveis 
- incluir ícone que leva para recuperação de senha
- incluir validações de formulários
    - email: required, email valido
    - password: required, min 6 chars
- definir funçao de submit com payload
    - wait response: desenvolver estado de loading enquanto login é processado
    - resolved: redirecionar para página inicial
    - rejectec: tratar respostas e incluir em elemento de feedback do usuário
- definir evento após tratamento de ret

## tasks
- Componente Visual: Desenvolvimento de componente sem eventos que causam alteração visual.
- Models para requisições: task focado em desenvolver interação com API.
- Integração: integração entre componente visual re requisições e alterações de estado necessárias.

## Cases
- testar
    - renderização do componente
    - se click em forgot password leva a tela de esqueci minha senha
    - validação de obrigatório no email
    - validação de email valido no email
    - validação de obrigatório do password
    - submit wait response: enviar com alteraçao de estado enviando
    - submit resolved: redirecionar para página inicial
    - submit jected: alteração de estado visual apresentando mensagem de erro