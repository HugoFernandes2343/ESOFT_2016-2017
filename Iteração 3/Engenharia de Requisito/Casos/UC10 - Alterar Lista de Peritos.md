# UC10 Alterar Lista de Peritos
##	Formato breve
O Organizador inicia a edição da lista de peritos de um Workshop.
O sistema mostra os congressos com workshops organizados pelo Organizador.
O Organizador escolhe um evento.
O sistema mostra os workshops do evento.
O Organizador escolhe um workshop.
O sistema solicita a operação a pretendida pelo Organizador.
O Organizador seleciona a operação.
O sistema mostra os passos a serem efetuados.
O Organizador efetua os passos solicitados.
O sistema apresenta o resultado final e solicita confirmação.
O Organizador confirma.
O sistema regista as alterções efetuadas e indica sucesso.

##	SSD de formato breve
![SSD_UC10.png](../../Imagens/SSD_UC10.png)

##	Formato completo

### Ator principal
* Organizador

### Partes interessadas e seus interesses
+ Organizador: Pretende alterar a lista de peritos de um dos Workshops dos seus Congressos.
+ Workshop: Pretende manter atualizada a sua lista de peritos.

### Pré-condições
+ Tem de ser Organizador de congressos e estes têm de ter Workshops com peritos.

### Pós-condições
* A lista de peritos fica alterada.

### Cenário de sucesso principal (ou fluxo básico)
1. O Organizador inicia a edição da lista de peritos de um Workshop.
2. O sistema mostra os congressos com workshops organizados pelo Organizador.
3. O Organizador escolhe um evento.
4. O sistema mostra os workshops do evento.
5. O Organizador escolhe um workshop.
6. O sistema solicita a operação a pretendida pelo Organizador.
7. O Organizador seleciona a operação.
8. O sistema mostra os passos a serem efetuados.
9. O Organizador efetua os passos solicitados.
10. O sistema apresenta o resultado final e solicita confirmação.
11. O Organizador confirma.
12. O sistema regista as alterções efetuadas e indica sucesso.

### Extensões (ou fluxos alternativos)
\*a. O utilizador (não registado) solicita cancelamento do registo.

+ O caso de uso termina.

3a. Dados mínimos obrigatórios em falta.

1. O sistema informa quais os dados em falta.
2. O sistema permite a introdução dos dados em falta (passo 3)

    2.a O gestor de eventos não altera os dados. O caso de uso termina.


3b. O sistema detecta que os dados introduzidos (ou algum subconjunto dos dados) são inválidos.

1. O sistema alerta o gestor de eventos para o facto.
2. O sistema permite a sua alteração (passo 3)

    2a. O  gestor de eventos não altera os dados. O caso de uso termina.

    3a. Dados mínimos obrigatórios em falta.

    1. O sistema informa quais os dados em falta.
    2. O sistema permite a introdução dos dados em falta (passo 3)

        2.a O gestor de eventos não altera os dados. O caso de uso termina.


5a. Dados mínimos obrigatórios em falta.

1. O sistema informa quais os dados em falta.
2. O sistema permite a introdução dos dados em falta (passo 3)

    2.a O gestor de eventos não altera os dados. O caso de uso termina.


5b. O sistema detecta que os dados introduzidos (ou algum subconjunto dos dados) são inválidos.

1. O sistema alerta o gestor de eventos para o facto.
2. O sistema permite a sua alteração (passo 3)

    2a. O  gestor de eventos não altera os dados. O caso de uso termina.     

11a. O Organizador não confirma.

1. O caso de uso termina.

## Requisitos especiais
*

## Lista de variações em tecnologias e dados
*

## Frequência de Ocorrência
*

## Questões em aberto
+ Qual a frequência de ocorrência deste caso de uso?
