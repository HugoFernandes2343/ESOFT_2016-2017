# UC6 Registar Utilizador
##	Formato breve
O utilizador não registado introduz no sistema os seus dados (nome, username, e-mail, password, fusoHorario e idioma). O sistema valida os dados e pede confirmação. O utilizador confirma os dados inseridos. O sistema regista os dados e informa o utilizador do sucesso da operação.

##	SSD de formato breve
![SSD_UC6.png](https://bitbucket.org/repo/Lg4X4o/images/1326046318-SSD_UC6.png)

##	Formato completo

### Ator principal
* Utilizador não registado

### Partes interessadas e seus interesses
+ Utilizador não registado: Pretende obter credenciais para poder aceder a funcionalidades específicas de utilizador registado.
+ Centro de Eventos: Pretende criar e manter registo dos utilizadores de determinadas funcionalidades da aplicação.

### Pré-condições
+ Utilizador não está autenticado.

### Pós-condições
* O registo do utilizador fica armazenado no sistema.

### Cenário de sucesso principal (ou fluxo básico)
1. O utilizador (não registado) inicia no sistema o seu registo.
2. O sistema solicita os dados do utilizador (nome, username, e-mail, password, fusoHorario e idioma).
3. O utilizador (não registado) introduz os dados solicitados.
4. O sistema valida e solicita que o utilizador (não registado) confirme os dados inseridos.
5. O utilizador (não registado) confirma os dados.
6. O sistema regista os dados e informa o utilizador (não registado) do sucesso da operação.

### Extensões (ou fluxos alternativos)
\*a. O utilizador (não registado) solicita cancelamento do registo.

+ O caso de uso termina.

4a. Dados mínimos obrigatórios em falta.

1. O sistema informa quais os dados em falta.
2. O sistema permite a introdução dos dados em falta (passo 3)

    2.a O utilizador (não registado) não altera os dados. O caso de uso termina.


4b. O sistema detecta que os dados (ou algum subconjunto dos dados) introduzidos devem ser únicos e que já existem no sistema.

1. O sistema alerta o utilizador para o facto.
2. O sistema permite a sua alteração (passo 3)

    2a. O utilizador (não registado) não altera os dados. O caso de uso termina.

4c. O sistema detecta que os dados introduzidos (ou algum subconjunto dos dados) são inválidos.

1. O sistema alerta o utilizador para o facto.
2. O sistema permite a sua alteração (passo 3)

    2a. O utilizador (não registado) não altera os dados. O caso de uso termina.


## Requisitos especiais
*

## Lista de variações em tecnologias e dados
*

## Frequência de Ocorrência
*

## Questões em aberto
+ O registo de utilizadores deve estar sempre disponível, mesmo que não haja eventos registados no sistema?
+ Como é que os utilizadores podem recuperar as credenciais de acesso?
+ Alguém deve ser notificado do registo de utilizador no sistema como, por exemplo, os organizadores de eventos que irão decorrer brevemente?
+ Qual a frequência de ocorrência deste caso de uso?
+ Que tipo de encriptação deverá ser implementada?
