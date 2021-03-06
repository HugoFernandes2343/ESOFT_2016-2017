# Design UC1 - Criar Evento

## Racional ##

| Cenário principal                                                                                              | Questão: Que classe deve... | Resposta          | Justificação                                                                                                          |
|----------------------------------------------------------------------------------------------------------------|-----------------------------|-------------------|-----------------------------------------------------------------------------------------------------------------------|
| 1. O gestor de eventos inicia o registo do evento.                                                             | n/a                         |                   |                                                                                                                       |
| 2. O sistema solicita os dados do evento(titulo, descrição, data de inicio, data de fim, local de realização). | n/a                         |                   |                                                                                                                       |
| 3. O gestor de eventos introduz os dados solicitados.                                                          | ...criar evento?            | Evento            | Creator                                                                                                               |
|                                                                                                                | ...receber os dados?        | Evento       | IE:É a classe que recebe os dados para criar o evento(título, descrição, período de realização, local de realização). |
| 4. O sistema solicita um organizador para o evento.                                                            | n/a                         |                   |                                                                                                                       |
| 5. O gestor de eventos insere um organizador.                                                                  | n/a                         |                   |                                                                                                                       |
| 6. O sistema valida o organizador e adiciona-o ao evento.                                                      | ...armazenar o organizador? | Evento            | IE: É a classe que armazena os organizadores responsáveis pelo evento.                                                |
|                                                                                                                | ...validar o organizador?   | Centro de eventos | IE: É a classe que armazena os utilizadores criados, nomeadamente os organizadores.                                   |
| 7. Os passos 4 a 6 repetem-se até que todos os organizadores tenham sido adicionados ao evento.                | n/a                         |                   |                                                                                                                       |
| 8. O sistema apresenta todos os dados e solicita confirmação do gestor.                                        | n/a                         |                   |                                                                                                                       |
| 9. O gestor confirma os dados.                                                                                 | n/a                         |                   |                                                                                                                       |
| 10. O sistema regista o novo evento e informa o gestor do sucesso da operação.                                 | ...registar o evento?       | Centro de eventos | IE: É a classe responsável por armazenar os eventos                                                                  |                                                                              


##	Diagrama de Sequência ##
![UC1-Criar_Evento-SD.png](../Imagens/Desing/UC1-Cria_Evento-SD.png)


##	Diagrama de Classes ##
![UC1-Criar_Evento-ClassDiagram.png](../Imagens/Desing/UC1-Criar_Evento-ClassDiagram.png)
