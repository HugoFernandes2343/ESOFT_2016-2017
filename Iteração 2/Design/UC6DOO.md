# Realização do UC6 Registar Utilizador #

## Racional ##

| Cenário | Que classe... | Resposta | Justificação |
|---------|---------------|----------|--------------|
| 1.	O ator inicia no sistema o seu registo. | ... interage com o ator? | RegistarUtilizadorUI | Pure Fabrication. |
| | ... coordena o UC? | RegistarUtilizadorController | Controller. |  
| 2.	O sistema solicita os dados do utilizador (nome, e-mail, palavra-chave). | | | |
| 3.	O utilizador  introduz os dados solicitados. | ... guarda os dados do utilizador? | Utilizador | Information Expert |
| | ... instancia Utilizador? | CentrodeEventos | Creator (Regra 1) |
| 4.	O sistema valida e regista os dados do utilizador. | ... valida os dados de cada Utilizador (validação local)? | Utilizador | IE |
| | ...valida a lista de Utilizadores (validação global)? | CentrodeEventos | IE |
| | ... regista o Utilizador? | CentrodeEventos | IE. No MD o CentrodeEventos contém/agrega Utilizador(es) |
| 5.	O sistema notifica o utilizador do sucesso da operação e apresenta os dados inseridos no sistema. | | | |

##	Diagrama de Sequência ##
![TP_DOO_SD.png](https://bitbucket.org/repo/RXabA9/images/1008167083-TP_DOO_SD.png)

##	Diagrama de Classes ##
![TP_DOO_CD.png](https://bitbucket.org/repo/RXabA9/images/2694103138-TP_DOO_CD.png)