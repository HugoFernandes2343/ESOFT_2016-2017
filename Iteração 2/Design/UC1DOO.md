# Design UC1 - Criar Evento

## Racional ##

| Cenário principal                                                                                                                                         | Questão: Que classe deve... | Resposta          | Justificação                                                      |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------|-------------------|-------------------------------------------------------------------|
| 1. O gestor de eventos inicia o registo do evento.                                                                                                        | n/a                         |                   |                                                                   |
| 2. O sistema solicita o tipo de evento(Congresso ou Exposição).                                                                                           | ...Instanciar o evento?     | Centro de Eventos | Creator                                                           |
| 3. O gestor de eventos seleciona o tipo de evento.                                                                                                        | n/a                         |                   |                                                                   |
| 4. O sistema solicita os dados do evento(titulo, descrição, data de inicio, data de fim, data limite de submissão de candidaturas e local de realização). | ...Armazenar os dados?      | Evento            | IE:classe responsável por armazenar os dados do evento            |
| 5. O gestor de eventos introduz os dados solicitados.                                                                                                     | n/a                         |                   |                                                                   |
| 6. O sistema solicita um organizador para o evento.                                                                                                       | n/a                         |                   |                                                                   |
| 7. O gestor de eventos insere um organizador.                                                                                                             | n/a                         |                   |                                                                   |
| 8. O sistema valida o organizador e adiciona-o ao evento.                                                                                                 | ..Armazenar os dados?       | Evento            | IE: classe que armazena os organizadores responsáveis pelo evento |
|                                                                                                                                                           | ...Valida o organizador?    | Centro de Eventos | IE: classe que armazena os utilizadores criados                   |
| 9. Os passos 6 a 8 repetem-se até que todos os organizadores tenham sido adicionados e no minimo tenham sido adicionados dois organizadores ao evento.    | n/a                         |                   |                                                                   |
| 10. O sistema apresenta todos os dados e solicita confirmação do gestor.                                                                                  | n/a                         |                   |                                                                   |
| 11. O gestor confirma os dados.                                                                                                                           | n/a                         |                   |                                                                   |
| 12. O sistema regista o novo evento e informa o gestor do sucesso da operação.                                                                            | ...Registar o evento?       | Centro de Eventos | IE: classe que armazena todos os eventos                          |                                                                            


##	Diagrama de Sequência ##
![UC1-Criar_Evento-SD.png](../Imagens/Desing/UC1-Cria_Evento-SD.png)


##	Diagrama de Classes ##
![UC1-Criar_Evento-ClassDiagram.png](../Imagens/Desing/UC1-Criar_Evento-ClassDiagram.png)
