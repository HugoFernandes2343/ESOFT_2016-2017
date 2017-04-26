## UC7: Confirmar Registo de Utilizador
## Formato breve
Um gestor de eventos solicita ao sistema o conjunto de utilizadores que efetuaram o registo e que ainda não foram confirmados no sistema. O sistema apresenta os dados solicitados ao gestor de eventos. O gestor de eventos seleciona os utilizadores pretendidos e submete-os ao sistema que, lhe solicita a confirmação dessa sua seleção. O utilizador confirma os dados e o sistema regista os utilizadores selecionados como confirmados e informa o Gestor de eventos do sucesso da operação.
## SSD - Formato breve
![SSD_Confirma_Registo_Utilizador.jpg](https://bitbucket.org/repo/RXabA9/images/728009425-SSD_Confirma_Registo_Utilizador.jpg)

## Formato completo

### Ator principal
* Gestor de eventos
### Partes interessadas e seus interesses
Gestor de eventos: confirmar os utilizadores que se registaram
Participante: ser confirmado pelo gestor de forma a passar
### Pré-condições
+ Há utilizadores por confirmar.
### Pós-condições
+ Os utilizadores foram confirmados no sistema.
### Cenário de sucesso principal (ou fluxo básico)
1. O gestor inicia a confirmação de registo de utilizador.
2. O sistema apresenta a lista de utilizadores não confirmados.
3. O gestor seleciona o utilizador.
4. O sistema remove o utilizador da lista de utilizadores não registados.
5. Os passos 2 a 6 repetem-se até os utilizadores estarem confirmados.
6. O sistema mostra todos os utilizadores que foram avaliados e solicita confirmação.
7. O gestor confirma.
8. O sistema guarda os utilizadores como registados e indica sucesso.

### Extensões (ou fluxos alternativos)
\*a O gestor de eventos solicita cancelamento do processo.

+ O caso de uso termina.

7a. O gestor não confirma.
1. Nada é guardado permanentemente e os registos temporarios sao apagados.
## Requisitos especiais
*
## Listas de variações em tecnologias e dados
*
## Frequência de Ocorrência
*
## Questões em aberto
+ Quão frequente é este caso de uso?
+ O gestor pode recusar utilizadores?
