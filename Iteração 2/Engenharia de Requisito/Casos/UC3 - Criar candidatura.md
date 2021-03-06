# UC3 Criar Candidatura
## Formato breve
O Representante inicia o registo da candidatura.
O sistema mostra os eventos disponiveis.
O Representante escolhe um evento.
O sistema pede os dados.
O Representante introduz os dados.
O sistema valida e pede confirmação.
O Representante confirma.
O sistema guarda a candidatura e apresenta sucesso.
## SSD de formato breve
![SSD_UC3.png](../../Imagens/SSD_UC3.png)
## Formato completo

### Ator principal
* Representante do participante

### Partes interessadas e seus interesses
+ Representante do participante: Pretende criar uma candidatura  para que possa vir a participar num dos eventos registados na aplicação.
+ Centro de Eventos: Pretende que fique registado a candidatura para que possa ser avalida e se for aprovada atribuir um stand no evento ao participante candidato.

### Pré-condições
+ A candidatura não pode estar já efetuada.
+ O evento para o qual será feita a candidatura tem de estar criado na aplicação.
+ O evento para o qual será feita a candidatura tem de estar dentro do prazo de submissão.


### Pós-condições
* O registo da candidatura fica armezenado no sistema.

### Cenário de sucesso principal (ou fluxo básico)
1. O representante inicia o sistema.
2. O sistema procura e mostra a lista de eventos disponiveis cuja a data de submissão ainda não tenha expirado.
3. O representante seleciona o evento e inicia o registo da candidatura.
4. O sistema solicita os dados da candidatura.
5. O representante do participante (com a candidatura não registada) introduz os dados solicitados.
6. O sistema solicita que o representante do participante (com a candidatura não registada) confirme os dados inseridos.
7. O representante do participante (com a candidatura não registada) confirma a candidatura.
8. O sistema regista a candidatura e informa o representante do participante do sucesso da operação.

### Extensões (ou fluxos alternativos)
\*a. O representante do participante (com a candidatura não registada) solicita cancelamento do registo.

+ O caso de uso termina.


5a. Dados mínimos obrigatórios em falta.

1. O sistema informa quais os dados em falta.
2. O sistema permite a introdução dos dados em falta (passo 3)

    2.a O representante do participante (com a candidatura não registada) não altera os dados. O caso de uso termina.


5b. O sistema detecta que os dados (ou algum subconjunto dos dados) introduzidos devem ser únicos e que já existem no sistema.

1. O sistema alerta O representante do participante para o facto.
2. O sistema permite a sua alteração (passo 3)

    2a. O representante do participante (com a candidatura não registada) não altera os dados. O caso de uso termina.

5c. O sistema detecta que os dados introduzidos (ou algum subconjunto dos dados) são inválidos.

1. O sistema alerta o representante do participante para o facto.
2. O sistema permite a sua alteração (passo 3)

    2a. O representante do participante (com a candidatura não registada) não altera os dados. O caso de uso termina.

7a. O representante do participante não confirma.
1. Nada é guardado permanentemente e os registos temporarios sao apagados.

## Requisitos especiais
*

## Listas de variações em tecnologias e dados
*

## Frequência de Ocorrência
*

## Questões em aberto
+ Quais são os dados obrigatórios para o registo da candidatura?
+ Quais os dados que em conjunto permitem detectar a duplicação de candidaturas?
+ Como é que o representante poderá anular posteriormente a candidatura?
+ Qual a frequência de ocorrência deste caso de uso?
