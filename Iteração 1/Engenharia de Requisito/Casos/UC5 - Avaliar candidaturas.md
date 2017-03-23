# UC5 Avaliar candidaturas
## Formato breve
O FAE inicia o sistema.
O sistema apresenta candidaturas por avaliar.
O FAE escolhe candidatura.
O sistema apresenta detalhes de candidatura.
O FAE avalia a candidatura e justifica a avaliação.
O sistema pede confirmação.
O FAE confirma.
O sistema indica sucesso e remove a candidatura da lista.

## SSD de formato breve
![SSD_UC5.png](../../Imagens/SSD_UC5.png)
## Formato completo

### Ator principal
* FAE

### Partes interessadas e seus interesses
+ FAE: avalia a candidatura para atribuir o espaço no evento.
+ Participante: ser aceite no evento.
+ Centro de eventos: poder prosseguir com a organização sabendo quem serão os participantes.

### Pré-condições
+ Há candidaturas por avaliar.

### Pós-condições
+ As candidaturas encontram-se avaliadas e aceites/recusadas no sistema.

### Cenário de sucesso principal (ou fluxo básico)
1. O FAE inicia a avaliação de candidaturas.
2. O sistema apresenta os eventos do FAE com candidaturas por avaliar.
3. O FAE seleciona o evento.
4. O sistema apresenta as candidaturas que foram atribuidas ao FAE que ainda não foram avaliadas.
5. O FAE escolhe uma candidatura da lista para avaliar.
6. O sistema apresenta a informação da candidatura e solicita a avaliação e justificação.
7. O FAE aceita ou recusa a candidatura e justifica com um texto.
8. O sistema remove a candidatura da lista de candidaturas por avaliar.
9. Os passos 4 a 8 repetem-se até que todas as candidaturas do evento do FAE estejam avaliadas.
10. O sistema mostra todas as candidaturas avaliadas e pede confirmação.
11. O FAE confirma.
12. O sistema grava as avaliações das candidaturas e indica sucesso.

### Extensões (ou fluxos alternativos)
\*a. O FAE solicita cancelamento do registo.

+ O caso de uso termina.

4a. O evento não possuí nenhuma candidatura para ser avaliada pelo FAE atual.

1. O sistema informa que aquele evento não tem nenhuma candidatura para ser avaliada pelo FAE.
2. O sistema permite a introdução de um novo evento (passo 3)

    2.a O FAE não insere outro evento. O caso de uso termina.


## Requisitos especiais
*

## Listas de variações em tecnologias e dados
*

## Frequência de Ocorrência
*

## Questões em aberto
+ Qual é a frequência de ocorrência este UC?
+ Os FAE tem que avaliar todas as candidaturas de uma vez?
+ A justificação é obrigatória?
+ É possivel cancelar candidaturas e que impacto é que tem se ja tiverem sido aprovadas?
