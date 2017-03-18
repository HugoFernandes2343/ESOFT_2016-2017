# Design UC2 - Atribuir FAE a evento 

| Cenário principal                                                          | Questão: Que classe deve...               | Resposta          | Justificação                                                     |
|----------------------------------------------------------------------------|-------------------------------------------|-------------------|------------------------------------------------------------------|
| 1. O organizador inicia o sistema.                                         | n/a                                       |                   |                                                                  |
| 2. O sistema procura os eventos do organizador e mostra a lista de eventos.| ...procurar os eventos do organizador?    | Centro de Eventos | IE: é a classe reponsável por armazenar todos os eventos criados.|
| 3. O organizador selecciona o evento.                                      | n/a                                       |                   |                                                                  |
| 4. O sistema pede a identificação do utilizador.                           | n/a                                       |                   |                                                                  |
| 5. O organizador introduz o utilizador.                                    | n/a                                       |                   |                                                                  |
| 6. O sistema valida o utilizador e adiciona-o como FAE do evento.          | ...procurar o utilizador?                 | Centro de Eventos | IE: é a classe que armazena todos os utilizadores criados.       |
|                                                                            | ...guardar o utilizador?                  |        FAE        | Creator                                                          |
|                                                                            | ...instanciar o FAE?                      |       Evento      | IE: é a classe que armazena os FAE responáveis pelo evento.      |
| 7. Os passos 4 a 6 repetem-se até todos os FAE estarem introduzidos.       | n/a                                       |                   |                                                                  |
| 8. O sistema pede confirmação dos dados introduzidos.                      | n/a                                       |                   |                                                                  |
| 9. O utilizador confirma os utilizadores introduzidos.                     | n/a                                       |                   |                                                                  |
| 10. O sistema regista os utilizadores como FAE do evento e indica sucesso. | ...armazenar os FAE atribuídos ao evento? |       Evento      | IE: é a classe que armazena todos os FAE atribuidos ao evento.   |
