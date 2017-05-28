# Especificação suplementar

## Funcionalidades

*Especifica as funcionalidades que não se relacionam com os casos de uso.*

* __Segurança/Autenticação:__ a utilização do sistema pelos gestores de eventos, organizadores, representantes e FAE exige que estejam autenticados no sistema e com password encriptada.
* __Auditoria:__ as ações dos utilizadores devem ser registadas para posterior auditoria.
* __Licenciamento:__ n/a
* __Locais/línguas:__ dada a previsível diversidade cultural e geográfica dos vários utilizadores do sistema, este deve suportar nativamente, entre outras coisas, múltiplos fusos horários e idiomas. Nesse sentido, é necessário a recolha de informação relevante sobre o utilizador no momento do registo e da autenticação, e que essa informação seja tida em consideração durante as ações.
* __Correio (eletrónico):__ n/a
* __Ajuda:__ o sistema deve disponibilizar ajuda online para cada funcionalidade.
* __Impressão:__ n/a
* __Geração de relatório:__ n/a
* __Gestão do sistema:__ n/a
* __Workflow:__ n/a

## Usabilidade

*Avalia a interface com o utilizador. Possui diversas subcategorias, entre elas: prevenção de erros; estética e design; ajudas (Help) e documentação; consistência e padrões.*

* __Estética e design:__ Considerando os diversos intervenientes no sistema e a diversidade das suas características é fundamental que a interação entre os utilizadores e o sistema seja simples, intuitiva e completamente adaptada à ação em causa.

## Fiabilidade/Confiabilidade

*Refere-se a integridade, conformidade e interoperabilidade do software. Os requisitos a serem considerados são: frequência e gravidade de falha, possibilidade de recuperação, possibilidade de previsão, exatidão, tempo médio entre falhas.*

n/a

## Desempenho

*Avalia os requisitos de desempenho do software, nomeadamente: tempo de resposta, consumo de memória, utilização da CPU, capacidade de carga e disponibilidade da aplicação.*

n/a

## Suportabilidade

*Os requisitos de suportabilidade agrupam várias características, como: testabilidade, adaptabilidade, manutibilidade, compatibilidade, configurabilidade, instalabilidade, escalabilidade entre outros.*

* Os algoritmos a serem usados são baseados em diferentes critérios (e.g. número de FAE pretendidos por candidatura, distribuição de carga equitativa pelos FAE, experiência profissional na realização de eventos).
* __Manutenbilidade:__ devem ser adotadas boas práticas de análise e design de software OO.
* __Escalabilidade:__ perto das datas limites de submissão das candidaturas a um evento prevê-se uma sobrecarga maior do sistema, pelo que o sistema deve ser escalável.
* __Configurabilidade:__ deverá ser possível acrescentar novos algoritmos ao longo da vida do software, com o mínimo de esforço.
* Os algoritmos de atribuição tanto podem ser desenvolvidos pela própria empresa bem como por terceiros.

## Outras (+)
### Restrições de design

*Especifica ou restringe o processo de design do sistema. Exemplos podem incluir: linguagens de programação, processo de software, uso de ferramentas de desenvolvimento, biblioteca de classes, etc.*

* Deve ser adotado um processo de desenvolvimento de software iterativo e incremental
* Devem ser adotadas boas práticas de design (e.g. padrões GRASP, SOLID)
* Um novo utilizador é válido e único se ambas as condições se verificarem:
       - a. O seu endereço de _e-mail_ é válido e não é usado por mais nenhum utilizador;
       - b. O seu _username_ não é usado por mais nenhum utilizador.
* Todos os utilizadores do sistema são identificados pelo _e-mail_ ou _username_ do Utilizador.

### Restrições de implementação

*Especifica ou restringe o código ou a construção de um sistema tais como: padrões obrigatórios, linguagens de implementação, políticas de integridade de base de dados, limites de recursos, sistema operativo.*

* A aplicação deve ser desenvolvida em Java.
* Adoção de normas de codificação (e.g. Camel case).
* Adoção de controlo de versões.
* Os algoritmos de atribuição tanto podem ser desenvolvidos pela própria empresa bem como por terceiros.

### Restrições de interface

*Especifica ou restringe as funcionalidades inerentes a interface do sistema com o utilizador.*

n/a

### Restrições físicas

*Especifica uma limitação ou requisito físico do hardware utilizado, por exemplo: material, forma, tamanho ou peso.*

n/a
