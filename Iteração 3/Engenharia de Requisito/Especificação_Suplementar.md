# Especificação suplementar

## Funcionalidades

*Especifica as funcionalidades que não se relacionam com os casos de
uso, nomeadamente: Auditoria, Reporte e Segurança.*

-   *Segurança/Autenticação*: a utilização do sistema pelo gestor de
    eventos, organizadores, representante e FAE’s exige autenticação e
    com password cifrada

-   Auditoria: as ações dos utilizadores devem ser registadas para posterior auditoria.


## Usabilidade

*Avalia a interface com o utilizador. Possui diversas subcategorias,
entre elas: prevenção de erros; estética e design; ajudas (Help) e
documentação; consistência e padrões.*

-   O sistema deve disponibilizar ajuda online para cada funcionalidade.

-   Dada a previsível diversidade cultural e geográfica dos vários utilizadores do sistema, este deve suportar nativamente, entre outras coisas, múltiplos fusos horários e idiomas.

## Fiabilidade/Confiabilidade
*Refere-se a integridade, conformidade e interoperabilidade do software. Os requisitos a serem considerados são: frequência e gravidade de falha, possibilidade de recuperação, possibilidade de previsão, exatidão, tempo médio entre falhas.*

n/a

## Desempenho
*Avalia os requisitos de desempenho do software, nomeadamente: tempo de resposta, consumo de memória, utilização da CPU, capacidade de carga e disponibilidade da aplicação.*

-  Perto das datas limites de submissão das candidaturas a um evento prevê-se uma sobrecarga maior do sistema, pelo que o sistema deve ser escalável.

## Suportabilidade
*Os requisitos de suportabilidade agrupam várias características, como:
testabilidade, adaptabilidade, manutibilidade, compatibilidade,
configurabilidade, instalabilidade, escalabilidade entre outros.*

-   Manutibilidade: devem ser adotadas boas práticas de análise e design de software OO


##

### Restrições de design

*Especifica ou restringe o processo de design do sistema. Exemplos podem incluir: linguagens de programação, processo de software, uso de ferramentas de desenvolvimento, biblioteca de classes, etc.*

-   Adoção de boas práticas de design(e.g. padrões GRASP, SOLID)

-   Deve ser adotado um processo de desenvolvimento de software
    iterativo e incremental, normas de codificação (e.g. Camel case) e de controlo de versões.

### Restrições de implementação

*Especifica ou restringe o código ou a construção de um sistema tais
como: padrões obrigatórios, linguagens de implementação, políticas de
integridade de base de dados, limites de recursos, sistema operativo.*

-   *A* aplicação deve ser desenvolvida em Java.

### Restrições de interface

*Especifica ou restringe as funcionalidades inerentes a interface do
sistema com o utilizador.*
n/A

### Restrições físicas

*Especifica uma limitação ou requisito físico do hardware utilizado, por
exemplo: material, forma, tamanho ou peso.*

n/a
