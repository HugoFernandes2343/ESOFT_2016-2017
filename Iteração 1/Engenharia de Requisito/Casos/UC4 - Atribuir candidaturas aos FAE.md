# UC4 Atribuir candidaturas
## Formato breve
O Organizador inicia o sistema.
O sistema mostra a lista de eventos.
O Organizador escolhe o evento.
O sistema mostra as candidaturas para o evento.
O organizador escolhe as candidaturas.
O sistema mostra a lista dos FAE.
O Organizador escolhe os FAE.
O sistema pede confirmação.
O Organizador confirma.
O sistema indica sucesso.

## SSD de formato breve
![SSD_UC4.png](../../Imagens/SSD_UC4.png)
## Formato completo

### Ator principal
* Organizador

### Partes interessadas e seus interesses
+ Organizador: apos atribuir candidaturas pode prosseguir com o seu trabalho de organizar o evento.
+ FAE: é lhes atribuida uma candidatura para avaliarem e decidirem se essa pode participar no evento.
+ Centro de eventos: atribuir candidaturas permite que a organização dos eventos prossiga.

### Pré-condições
+ Ainda não estão atribuidas todas as candidaturas de um determinado evento.

### Pós-condições
+ Ficam atribuidas candidaturas aos FAE

### Cenário de sucesso principal (ou fluxo básico)
1. O organizador inicia a atribuição de candidaturas a FAE.
2. O sistema fornece a sua lista de eventos com candidaturas por atribuir e solicita a selecção de um evento.
3. O organizador escolhe um evento.
4. O sistema apresenta uma lista das candidaturas por atribuir aos FAE desse evento.
5. O organizador escolhe uma candidatura.
6. O sistema fornece a lista de FAE responsáveis por esse evento.
7. O organizador escolhe um FAE para avaliar a candidatura.
8. O sistema atribui a candidatura ao FAE.
9. Os passos 4 a 8 repetem-se até todas as candidaturas do evento terem sido atribuidas.
10. O sistema apresenta as atribuições definidas e solicita confirmação.
11. O organizador confirma.
12. O sistema regista as atribuições de candidaturas a FAE e indica sucesso.

### Extensões (ou fluxos alternativos)
\*a. O utilizador (não registado) solicita cancelamento do registo.

+ O caso de uso termina.

## Requisitos especiais
*
## Listas de variações em tecnologias e dados
*
## Frequência de Ocorrência
*
## Questões em aberto
+ O organizador pode deixar candidaturas por atribuir?
+ Quão frequente é a ocurrencia deste caso de uso?
+ O organizador tem que atribuir todas as candidaturas de uma vez ou pode parar e continuar posteriormente?
