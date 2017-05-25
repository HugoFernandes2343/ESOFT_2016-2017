# UC11  - Alterar lista de peritos de workshop
## Formato breve
O organizador inicia no sistema a alteração da lista de peritos de uma workshop. O sistema apresenta os congressos organizados pelo Organizador que possuem workshops e solicita a escolha de um. Após realizar a sua escolha, o sistema apresenta os workshops a tomarem lugar no congresso escolhido e solicita a escolha de um. O Organizador escolhe um. O sistema questiona o Organizador o que pretende alterar em relação à lista de peritos do workshop escolhido. O organizador escolhe entre adicionar um novo perito ou remover um perito e procede de acordo com a escolha efetuada. O sistema solicita a confirmação da alteração realizada à lista de peritos do workshop escolhido. O organizador confirma. O sistema ou regista um novo perito do workshop ou remove o perito indicado e apresenta uma mensagem de sucesso.

<ou regista o novo perito a ser adicionado, ou guarda as alterações realizadas ao perito selecionado ou remove o perito indicado.>

<O sistema solicita a confirmação ou dos dados alterados do perito escolhido, ou do novo perito a ser adicionado ao workshop, ou dos peritos escolhidos a serem eliminados do workshop.>

<Processa as alterações realizadas à lista de peritos do workshop escolhido, realizando as ações necessárias e apresenta mensagem de operação concluída com sucesso>

## SSD de formato breve
![SSD do UC11](../../SSDs/UC11.png)

## Formato completo
### Ator primário
+ Organizador

### Partes interessadas e seus interesses
+ __Organizador:__ Deseja poder alterar a lista de peritos de um workshop de um dado congresso a qualquer altura sem ter a necessidade de requisitar a um administrador do sistema para manualmente inserir novos peritos ao workshop ou remover peritos.

### Pré-condições
+ Utilizador registado em sistema como Organizador.
+ Existirem congressos organizados pelo Organizador com workshops criadas.

### Pós-condições
+ A lista de peritos ter sofrido algum tipo de alteração seja os dados de um perito terem sido alterados, um perito ter sido removido ou um perito ter adicionado.

### Cenário de sucesso principal (ou fluxo básico)
1. O organizador inicia no sistema a alteração da lista de peritos de um workshop.
2. O sistema apresenta os congressos organizados pelo Organizador que possuem workshops e solicita a escolha de um.
3. O organizador escolhe um congresso.
4. O sistema apresenta os workshops a serem organizados no congresso escolhido e solicita a escolha de um.
5. O organizador escolhe um workshop dos apresentados.
6. O sistema questiona o Organizador o que pretende alterar em relação à lista de peritos do workshop escolhido.
7. O organizador ou escolhe adicionar um novo perito inexistente em sistema sendo este posteriormente validado ou escolhe eliminar um perito do workshop.
8. O sistema solicita confirmação das alterações realizadas à lista de peritos do workshop escolhido.
9. O organizador confirma.
10. O sistema ou regista o novo perito a ser adicionado, ou guarda as alterações realizadas ao perito selecionado ou remove o perito indicado.

### Extensões (ou fluxos alternativos)
\*a. O Gestor de Eventos solicita o cancelamento da alateração da lista de peritos.
> 1. O caso de uso termina.

## Requisitos especiais
*

## Lista de variações em tecnologias e dados
*

## Frequência de Ocorrência
*

## Questões em aberto
*
