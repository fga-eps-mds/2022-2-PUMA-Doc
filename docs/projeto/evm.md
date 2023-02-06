
# Análise de Valor Agregado (EVM)

## Introdução

A Análise do Valor Agregado (Earned Value Management - EVM) é um método de mensuração do desempenho desenvolvido pelo departamento de defesa dos EUA. É usado para estabelecer padrões de análise de contratos que considerem não somente os custos e prazos mas também a performance e eficiência do projeto [[1]](#ref1), [[2]](#ref2).

## Detalhamento EVM - PUMA

A Análise do Valor Agregado tem como foco integrar as medições de Cronograma, Escopo e Custo estabelecendo uma relação entre o produto obtido e os custos reais incorridos.

No desenvolvimento do diagrama foram utilizadas informações sobre o projeto como:

- Quantidade de Sprints ou Iterações do projeto ou release;  
- Quantidade de Sprints ou Iterações concluídas até o momento;  
- Total de esforço para concluir o projeto ou release (seja em horas, seja em pontos ou outra métrica);  
- Esforço concluído (Done) até o momento;  
- Orçamento do projeto ou release;  
- Valor gasto até o momento.  


Estes cálculos são obtidos através dos parâmetros para EVM, dentro do projeto e de suas releases, e cada release possui dados das sprints. O detalhamento dos cálculos está explicado abaixo.

**Parâmetros EVM**  
- BAC – Orçamento estimado para a Release, detalhado na tabela de custos  
- AC = EV / BAC – Custo até o momento  
- PV = BAC * (TSC / TSE) – Valor Planejado  
- EV = BAC * (RPC / PRP) – Valor Agregado  
- CPI = EV / AC – Índice de Desempenho de Custos  
- CPV = EV - AC – Variação de Desempenho de Custo  
- SPI = EV / PV – Índice de Desempenho de Prazo  
- SPV = EV - PV – Variação de Desempenho de Prazo  

**Parâmetros Gerais do Projeto**  
- CPI – Índice de Desempenho de Custos  
- SPI – Índice de Desempenho de Prazo  
- CPV – Variação de Desempenho de Custo  
- SPV – Variação de Desempenho de Prazo  
 
**Parâmetros das Releases**  
- PRP – Pontos Planejados por Release  
- RPC – Pontos Concluídos por Release  
- BAC – Orçamento estimado por Release  
- AC – Custo até o momento  
- PV – Valor Planejado por Release  
- EV – Valor Agregado por Release  

**Parâmetros das Sprints**  
- PP - Pontos Planejados por Sprint  
- PC - Pontos Concluídos por Sprint  
- PI - Pontos Incompletos por Sprint  
- AP - Pontos Adicionados por Sprint  
- SC - Orçamento gasto por Sprint  
- TSC - Total de Sprints Concluídas  
- TSE - Total de Sprints Estimadas  

Os resultados da estimativa de custos para o projeto estão consolidados na planilha:
<iframe width="700" height="500" frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/1JX57gR8_53dbSimfpn0yJvfqQPuwrfU01bsiqr05fYs/edit?usp=sharing&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

<br/>

<p  align="justify">Para visualizar a planilha completa <a href="https://docs.google.com/spreadsheets/d/1JX57gR8_53dbSimfpn0yJvfqQPuwrfU01bsiqr05fYs/edit?usp=sharing">clique aqui</a>.</p>

## Referência

<a id="ref1"></a>
[1] Análise de Valor Agregado (EVM) em Projetos: Conheça e aprenda a calcular. Disponível em: <http://valorecompetencia.com.br/gestao_de_projetos/analise-de-valor-agregado-evm-em-projetos-conheca-e-aprenda-a-calcular>. Acesso em: jan, 2023. 

<a id="ref2"></a>
[2] Hiflex consultoria. Gerenciamento De Valor Agregado (EVM) Em Projetos Ágeis. Disponível em: https://hiflexconsultoria.com.br/gerenciamento-de-valor-agregado-evm-em-projetos-ageis/. Acesso em: jan. 2023. 

## Histórico de Revisão

| Data       | Versão | Modificação | Autor |
| :--------- | :----- | :---------- | :---- |
| 17/01/2023 | 1.0    | Criação do documento | Ailamar Alves |
| 04/02/2023 | 0.2    | Atualização da planilha.| Ailamar, Matheus |
