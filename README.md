# Get Start the Quest
Esta documentação indica a forma que deve ser descrita uma funcionalidade, esta será dividida em Feature com 3 seções específicas, e Refining que será dividido em 4 seções.

## Features
- **informações**: indica os dados presentes na funcionalidade com detalhes sobre origem e aplicação, ou qualquer outra informação relevante para ser indexada.
- **eventos**: define ações, reações, suas possibilidades e exceções.
- **anexos**: anexos necessários para desenvolvimento da funcionalidade, ex: telas, documentação de determinada API, endpoints ou especificações definidas em algum outro documento.

        obs: segue abaixo dois modelos para definição de features
        buscando ilustrar vários cenários de possibilidade.


## Refining
- **consulta**: consulta indica de onde vem a informação, é adequando `tipificar(definir origem)` se está vem de uma interface para consumo por um cliente ou acesso a uma `base de dados(interface/database)`, a consulta ainda pode ser `definida(estado)` em existente ou não existente ou a ser `modificada(created/to_be_create/to_be_modified)`.
- **steps**: sequencia de ações a serem descritas dos eventos que serão realizados no desenvolvimento da funcionalidade. é indicado que quem estiver descrevendo pautar suas decisões baseados na tecnologia que será utilizada com escrotineo técnico.
= **tasks**: fragmentação do refining no número de tarefas necessárias para completar a funcionalidade, é indicado fragmentar o maximo possível sem perder a responsabilidade da tarefa e sem reescrever funcionalidades recem escritas do conjunto de tarefas anteriormente realizadas na mesma funcionalidade.
- **cases**: descrição dos casos de testes que deverão ser contemplados, de forma lógica e se necessário de forma técnica caso algum detalhe importante relacionado a ambiente, dependencia ou técnologia seja necessário.

        obs: segue abaixo dois modelos para definição de refining
        buscando ilustrar vários cenários de possibilidade.