# Enunciado PT-PT

Um centro de eventos do norte do país pretende desenvolver uma aplicação (de software) de apoio à organização e gestão destes eventos.

Entre outras coisas, este software deve permitir registar os vários eventos que irão realizar-se ao longo do ano, bem como facilitar o processo de atribuição de ocupação dos espaços (stands) aos participantes (empresas) que irão estar presentes nos vários eventos.

Ao criar um evento, o gestor de eventos define o seu título, um texto descritivo sobre o âmbito do mesmo, o período e o local de realização, e um conjunto de pessoas responsáveis pela sua realização (os organizadores).

Numa fase posterior à criação do evento no sistema, um dos organizadores define quais os funcionários de apoio ao evento (FAE). Os FAE são as pessoas que, além de outras tarefas, decidirão quais os participantes selecionados para o evento.

O representante do participante fará candidatura a evento.

Um dos organizadores atribui aos FAE as candidaturas para decisão. Para cada candidatura, os FAE indicam no sistema se esta foi aceite ou recusada, juntamente com um breve texto justificativo.
É necessário que todos os gestores de eventos, organizadores, FAE e participantes estejam registados no sistema como utilizadores. Para tal, o utilizador não registado cria o seu perfil de utilizador indicando o nome, endereço de email e credenciais de acesso (password é armazenada cifrada). Um gestor de eventos confirma posteriormente o registo.

O núcleo principal do software deve ser implementado em Java. Com o intuito de aumentar a manutenibilidade do software, devem ser adotadas boas práticas de análise e design de software OO.