# Enunciado PT-PT

## Respostas a perguntas em aberto

* Um novo utilizador é válido e único se ambas as condições se verificarem:
       - a. O seu endereço de _e-mail_ é válido e não é usado por mais nenhum utilizador,
       - b. O seu _username_ não é usado por mais nenhum utilizador.
- Todos os utilizadores do sistema são identificados pelo _e-mail_ ou _username_ do Utilizador.
- Os gestores de eventos são criados por outros gestores de eventos. No início do sistema, há pelo menos um gestor de eventos.
- Aquando da criação de um evento é obrigatório definir pelo menos 2 organizadores.
- No mesmo evento, o mesmo utilizador não pode desempenhar o papel de organizador e de FAE.
- O processo de atribuição de candidaturas consiste na atribuição de cada candidatura submetida ao evento a um ou mais FAE para avaliação das candidaturas.


## Novos requisitos

Existem 2 tipos de eventos:

- Exposições, em que é suposto os expositores realizarem transações comerciais entre si e com os visitantes;
- Congressos, em que não é suposto serem realizadas transações comerciais, mas ser antes um evento de troca de conhecimento e competências.

Os organizadores desejam poder organizar workshops nos congressos.

Perto das datas limites de submissão das candidaturas a um evento prevê-se uma sobrecarga maior do sistema, pelo que o sistema deve ser escalável.

Findo o período da submissão de candidaturas (data definida), os organizadores despoletam o processo de atribuição de candidaturas para revisão, após o qual se inicia o processo de avaliação de candidaturas.

Como forma de automatizar o processo de atribuição de candidaturas são disponibilizados vários algoritmos de apoio à decisão dos organizadores, considerando as caraterísticas do evento e dos FAE (e.g. número de FAE pretendidos por candidatura, número máximo de candidaturas por FAE, distribuição de carga equitativa pelos FAE, experiência do FAE na organização de eventos no centro, número de candidaturas revistas pelo FAE no centro).

Todos os algoritmos são capazes de lidar com eventos, mas alguns são específicos de exposições e outros de congressos. O resultado da atribuição pode ser alterado através da escolha de diferentes algoritmos de apoio à decisão até que o resultado seja confirmado como definitivo pelo organizador.
Deverá ser possível acrescentar novos algoritmos ao longo da vida do software, com o mínimo de esforço.

O software deve ser desenvolvido de forma iterativa e incremental, bem como adotar boas práticas de design (e.g. padrões GRASP, SOLID) e normas de codificação (e.g. Camel case) e de controlo de versões.
