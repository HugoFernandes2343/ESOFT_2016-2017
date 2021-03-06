# Design UC3 - Criar candidatura

## Racional ##

| Cenário Principal                                                                                                                 | Questão: Que classe deve...        | Resposta           | Justificação                                                       |
|-----------------------------------------------------------------------------------------------------------------------------------|------------------------------------|--------------------|--------------------------------------------------------------------|
| 1. O representante inicia o sistema.                                                                                              | n/a                                |                    |                                                                    |
| 2. O sistema procura os eventos disponiveis e mostra a lista de eventos.                                                          | ...procurar os eventos existentes? | Centro de Eventos. | IE: é a classe responsável por armazenar todos os eventos criados. |
| 3. O representante seleciona o evento e inicia o registo da candidatura.                                                          | n/a                                |                    |                                                                    |
| 4. O sistema solicita os dados da candidatura.                                                                                    | ...armazenar os dados?             | Candidatura        | Creator                                                            |
|                                                                                                                                   | ...instanciar a candidatura?       | Evento             | IE: é a classe responsável por armazenar todas as candidaturas.    |
| 5. O representante do participante (com a candidatura não registada) introduz os dados solicitados.                               | n/a                                |                    |                                                                    |
| 6. O sistema solicita que o representante do participante (com a candidatura não registada) confirme os dados inseridos.   |                                     |                    |                                                                    |
| 7. O representante do participante (com a candidatura não registada) confirma a candidatura.                                      | n/a                                |                    |                                                                    |
| 8. O sistema regista a candidatura e informa o representante do participante do sucesso da operação.                              | ...guardar a candidatura?          | Evento             | IE: é a classe responsável por armazenar todas as candidaturas.    |




##	Diagrama de Sequência ##
![UC3-Criar_Candidatura-SD.png](../Imagens/Desing/UC3-Criar_Candidatura-SD.png)


##	Diagrama de Classes ##
![UC3-Criar_Candidatura-ClassDiagram.png](../Imagens/Desing/UC3-Criar_Candidatura-ClassDiagram.png)
