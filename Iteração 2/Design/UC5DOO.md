# Design UC5 - Avaliar candidaturas

## Racional ##

| Cenário principal                                                                                          | Questão: Que classe deve...                                           | Resposta          | Justificação                                                                                              |
|------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|-------------------|-----------------------------------------------------------------------------------------------------------|
| 1. O FAE inicia a avaliação de candidaturas.                                                               | n/a                                                                   |                   |                                                                                                           |
| 2. O sistema apresenta os eventos do FAE com candidaturas por avaliar.                                     | ...procurar os eventos do FAE?                                        | Centro de eventos | IE: é a classe responsável por armazenar todos os eventos.                                                |
| 3. O FAE seleciona o evento.                                                                               | n/a                                                                   |                   |                                                                                                           |
| 4. O sistema apresenta as candidaturas que foram atribuidas ao FAE que ainda não foram avaliadas.          | ...procurar as atribuições de candidaturas feitas ao FAE por avaliar? | Evento            | IE: é a classe responsável por armazenar todas as atribuições de candidaturas a FAE.                      |
| 5. O FAE escolhe uma candidatura da lista para avaliar.                                                    | n/a                                                                   |                   |                                                                                                           |
| 6. O sistema apresenta a informação da candidatura e solicita a avaliação e justificação.                  | n/a                                                                   |                   |                                                                                                           |
| 7. O FAE aceita ou recusa a candidatura e justifica com um texto.                                          | n/a                                                                   |                   |                                                                                                           |
| 8. O sistema remove a candidatura da lista de candidaturas por avaliar.                                    | ...armazenar a avaliação da candidatura?                              | Avaliação         | Creator                                                                                                   |
|                                                                                                            | ...instanciar a avaliação da candidatura?                             | Atribuição        | IE: é a classe responsável por armazenar a candidatura, a avaliação e o respetivo FAE encarrega da mesma. |
| 9. Os passos 4 a 8 repetem-se até que todas as candidaturas do evento do FAE estejam avaliadas.            | n/a                                                                   |                   |                                                                                                           |
| 10. O sistema mostra todas as candidaturas avaliadas e respetiva avaliação e pede confirmação.             | n/a                                                                   |                   |                                                                                                           |
| 11. O FAE confirma.                                                                                        | n/a                                                                   |                   |                                                                                                           |
| 12. O sistema grava as avaliações das candidaturas e indica sucesso.                                       | ...gravar a avaliação da candidatura?                                 | Atribuição        | IE: é a classe responsável por armazenar a avaliação da candidatura.                                      |



##	Diagrama de Sequência ##
![UC5-Avaliar_Candidatura-SD.png](../Imagens/Design/UC5-Avaliar_Candidatura-SD.png)


##	Diagrama de Classes ##
![UC5-Avaliar_Candidatura-ClassDiagram.png](../Imagens/Design/UC5-Avaliar_Candidatura-ClassDiagram.png)
