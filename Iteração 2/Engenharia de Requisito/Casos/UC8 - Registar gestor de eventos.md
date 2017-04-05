# UC8 Registar gestor de eventos
##	Formato breve
O gestor de eventos inicia o registo de um novo gestor de eventos.
O sistema mostra a lista de utilizadores registados que ainda não são gestores.
O gestor de eventos insere o utilizador.
O sistema mostra os dados do novo gestor e pede confirmação.
O gestor confirma o gestor.
O sistema regista o utilizador como gestor de eventos e informa do sucesso da operação.

##	SSD de formato breve


##	Formato completo

### Ator principal
* Gestor de eventos

### Partes interessadas e seus interesses
+ Gestor de eventos: Pretende adicionar outros gestores para poderem aceder a funcionalidades específicas de gestor de eventos.
+ Centro de Eventos: Pretende criar e manter registo dos gestores de eventos.
+ Utilizador Registado: Pretende que seja declarado como gestor de eventos para poder aceder a funcionalidades específicas de gestor de eventos.

### Pré-condições
+ Utilizador está autenticado.

### Pós-condições
* O registo do gestor de eventos fica armazenado no sistema.

### Cenário de sucesso principal (ou fluxo básico)
1. O gestor de eventos inicia o registo de um novo gestor de eventos.
2. O sistema mostra a lista de utilizadores registados que ainda não são gestores.
3. O gestor de eventos insere o utilizador.
4. O sistema o sistema valida o utilizador e adiciona-o como gestor de eventos.
5. Os passos 2 a 4 repetem-se até que todos os gestores de eventos tenham sido adicionados.
6. O sistema apresenta todos os getores de eventos declarados e respetivos dados e solicita confirmação do gestor.
7. O gestor confirma os dados.
8. O sistema regista os utilizadores como gestores de eventos e informa o gestor do sucesso da operação.

### Extensões (ou fluxos alternativos)
\*a. O utilizador (não registado) solicita cancelamento do registo.

+ O caso de uso termina.

4a. Dados mínimos obrigatórios em falta.

1. O sistema informa quais os dados em falta.
2. O sistema permite a introdução dos dados em falta (passo 3)

    2.a O gestor de eventos não altera os dados. O caso de uso termina.


4b. O sistema detecta que os dados introduzidos (ou algum subconjunto dos dados) são inválidos.

1. O sistema alerta o gestor de eventos para o facto.
2. O sistema permite a sua alteração (passo 3)

    2a. O  gestor de eventos não altera os dados. O caso de uso termina.


## Requisitos especiais
*

## Lista de variações em tecnologias e dados
*

## Frequência de Ocorrência
*

## Questões em aberto
+ O registo de gestores de eventos deve estar sempre disponível?
+ É possivél o gestor anular a ação realizada?
+ O utilizador deve ser notificado do seu registo como gestor de eventos?
+ Qual a frequência de ocorrência deste caso de uso?
