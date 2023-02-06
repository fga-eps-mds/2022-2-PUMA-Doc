# Qualidade

## Introdução

Este documento objetiva mostrar os critérios, ferramentas e o planejamento da qualidade de código do projeto, esclarecendo o como, quais e porquês das adoções de cada prática e tipos de teste durante o desenvolvimento do produto.

## Planejamento

### Teste Unitários

Os Testes unitários são testes automatizados de pequenas unidades de código, as quais são testadas de forma isolada do restante do sistema (VALENTE, 2020). 

Para a aplicação de testes unitários, a equipe utiliza o **Jest**, que é uma ferramenta de código aberto que permite realizar testes em aplicações baseadas em JavaScript de forma simples.

### SonarCloud

O **SonarCloud** é uma ferramenta utilizada para a captação de métricas e indicadores técnicos, ou seja, para o monitoramento da qualidade do projeto. Os dados coletados são utilizados para auxiliar no planejamento do aumento da qualidade do código.

### Testes Funcionais
A execução de testes funcionais baseia-se na aplicação da técnica de validação utilizada para avaliar um produto ou serviço. No projeto PUMA, os relatórios de testes funcionais são realizados pela equipe de PSP5 a partir de testes exploratórios.

## Modelo de Qualidade

De acordo com a ISO/IEC 25010, o modelo de qualidade determina quais características e subcaracterísticas de qualidade são analisadas ao avaliar as propriedades de um produto de software.

### Qualidade Interna e Externa

A norma NBR ISO/IEC 9126-1 propõe seis características principais da qualidade interna e externa, cada uma delas divididas em subcaracterísticas. A capacidade do software é determinada por um conjunto de atributos internos que podem ser medidos, para cada característica e subcaracterística.
<center>

| Característica      |  Subcaracterísticas | 
| :--------- | :----- | 
| Funcionalidade |  Adequação, Acurácia, Interoperabilidade, Segurança de Acesso, Conformidade |
| Confiabilidade  | Maturidade, Tolerância a, Falhas, Recuperabilidade, Conformidade |
| Usabilidade |Inteligibilidade, Apreensibilidade, Operacionalidade, Atratividade, Conformidade |
| Eficiência |  Comportamento em Relação ao Tempo, Comportamento em Relação aos Recursos, Conformidade|
| Manutenibilidade |  Analisabilidade, Modificabilidade, Estabilidade, Testabilidade, Conformidade|
| Portabilidade |  Adaptabilidade, Capacidade de Instalação, Coexistência, Capacidade de Substituição, Conformidade |

<figcaption>
Tabela 1 - Características e Subcaracterísticas do Modelo de Qualidade Interna e Externa
</figcaption>

</center>

### Qualidade Em Uso

De acordo com a norma NBR ISO/IEC 9126-1, os atributos de qualidade em uso são categorizados em quatro características: eficácia, produtividade, segurança e satisfação.

## Referências

ISO/IEC 25010. Disponível [aqui](https://iso25000.com/index.php/en/iso-25000-standards/iso-25010). Acesso em: 31 jan. 2023.


Jest. Disponível [aqui](https://jestjs.io/pt-BR/). Acesso em: 05 fev. 2023.

Norma NBR ISO/IEC 9126-1. Disponível [aqui](https://jkolb.com.br/wp-content/uploads/2014/02/NBR-ISO_IEC-9126-1.pdf). Acesso em: 31 jan. 2023.

SonarCloud. Disponível [aqui](https://www.sonarsource.com/products/sonarcloud/features/). Acesso em: 05 fev. 2023.

VALENTE, Marco. **Engenharia de Software Moderna**: Princípios e Práticas para Desenvolvimento de Software com Produtividade. 2020. Disponível [aqui](https://engsoftmoderna.info/cap8.html). Acesso em: 05 fev. 2023.


## Histórico de Revisão
| Data       | Versão | Modificação | Autor |
| :--------- | :----- | :---------- | :---- |
| 31/01/2023 | 0.1    | Criação do documento | Hérya |
| 05/02/2023 | 0.2    | Adição do tópico planejamento | Hérya |
| 05/02/2023 | 0.3    | Adição do tópico modelo de qualidade | Hérya |

