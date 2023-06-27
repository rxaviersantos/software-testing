# O que é Processo de teste 

Não existe um processo universal de teste de software, mas há conjuntos comuns de atividades de teste sem as quais os testes terão menor probabilidade de atingir seus objetivos estabelecidos. 

## Processo de teste no contexto 

É muito útil se a base de teste tiver definidas critérios de cobertura mensuráveis (KPIs). 

Os critérios de coberturas podem exigir pelo menos um caso de teste para cada elemento da sua base de teste.

### Fatores que influenciam o processo de teste de uma organização:

Modelo do ciclo de vida de desenvolvimento de software;
Metodologia de projetos utilizados;
Níveis e tipos de testes;
Riscos de produto e projeto;
Domínio e conhecimento do negócio;
Restrições operacionais(Orçamento/tempo/Contratos)
Políticas, praticas, normas internas e externas


### Aspectos gerais dos processos de teste organizacionais:

Atividade e tarefas de teste;
Produtos de trabalho de teste;
Rastreabilidade entre a base de teste e os produtos de trabalho de teste.

## Atividades e tarefas de teste

Cada grupo de atividades é composto por atividades constituintes, que podem variar de um projeto ou lançamento para outro.

Atividades podem ser sobrepostas, podem acontecer simultaneamente, pode não conter etapa.

### Um processo de teste consiste nos seguintes grupos principais de atividades:

Planejamento do teste;
Monitoramento e controle do teste;
Análise do teste;
Modelagem do teste;
Implementação do teste;
Execução do teste;
Conclusão do teste.

### Planejamento do teste 

Envolve as atividades que definem os propósitos e a abordagem do teste para atender aos objetivos do teste dentro das restrições impostas pelo contexto.

Os planos de teste podem ser revisitados com base no feedback das atividades de monitoramento e controle.

### Monitoramento e controle 

Monitoramento: Comparação contínua do progresso real com o plano de teste usando qualquer métrica de monitoramento definida no plano de teste.

Controle: Tomada de açoes necessárias para atender aos objetivos do plano de teste.

### Análise do teste 

Determina "O que testar".

Analisa a base de teste apropriada ao nível de teste, como:

Especificações
Modelagem de informações (diagramas/fluxos)
Implementação dos componentes (código, metadados, banco de dados e intefaces)

Avalia a base de teste para identificar defeitos, como:

* Ambiguidades;
* Omissöes;
* Inconsistências;
* Imprecisöes;
* Contradições;
* Declarações supéfluas.

Identifica recursos a serem testados.
Define e prioriza as condições de teste para cada recurso.
Captura a rastreabilidade bidirecional entre a base de teste e condiçöes de teste.

A aplicaçao de técnicas de teste caixa-preta. caixa-branca e experiência pode ser útil no processo de análise do teste para reduzir a probabilidade de omitir as condições importantes de teste e definir as condições de teste mais corretas e precisas.


A identificação dos defeitos durante a análise do teste é um benefício importante, especialmente quando nenhum outro processo de revisäo está sendo usado.

Essas atividades de análise do teste não apenas verificam se os requisitos são consistentes, expressos adequadamente e completos, mas também validam se os requisitos capturam adequadamente as necessidades do cliente, do usuário e stakeholders.

### Modelagem do teste 

Determina "Como testar".

Durante a modelagem de teste, as condições de teste são elaboradas em casos de teste de alto nível. 

A modelagem de teste inclui as seguintes atividades principais: 

> - Projetar e priorizar casos de teste e conjuntos de casos de teste;
> - Identificar os dados de teste necessários para comportar as condições de teste e os casos de teste;
> - Projetar o ambiente de teste e identificar qualquer infraestrutura e ferramenta necessária;
> - Capturar a rastreabilidade bidirecional entre a base de teste, as condições de teste, os casos de teste e os procedimentos de teste.

A elaboradas condições de teste em casos de teste durante a modelagem do teste envolve muitas vezes o uso de técnicas de teste. 

A identificação dos defeitos durante a modelagem do teste também é um benefício importante. 

### Implementação do teste 

Temos tudo para executar os testes?

A implementação do teste inclui principalmente as seguintes atividades:

> - Desenvolver e priorizar os procedimentos de teste, criar os scripts automatizados;
> - Criar as suítes de teste a partir dos procedimentos; 
> - Organizar um cronograma;
> - Construir o ambiente;
> - Preparar os dados e garantir que sejam carregados no ambiente;
> - verificar e atualizar a rastreabilidade.

Nos testes exploratórios e em outros tipos de testes baseados na experiência, a modelagem e a implementação do teste podem ocorrer e serem documentadas como parte da execução do teste.

### Execução do teste 

Durante a execução do teste, os conjuntos de testes são executados de acordo com a programação da execução do teste.

A execução do teste inclui principalmente as seguintes atividades:

> - Gravar os identificadores e versões do teste ou do objeto de teste;
> - Executar os testes manualmente ou usando ferramentas de execução do teste;
> - Comparar resultados reais com os esperados;
> - Analisar anomalias para estabelecer prováveis causas; 
> - Comunicar os defeitos;
> - Registrar o resultado da execução do teste (p. ex., passar, falhar, bloquear);

### Conclusão do teste 

Coletam os dados das atividades de teste já concluídas para consolidar a experiência, o testeware e qualquer outra informação relevante. 
A conclusão do teste inclui principalmente as seguintes atividades:

> * Verificar se todos os defeitos estão fechados;
> * Criar um relatório de resumo de teste para ser comunicado aos stakeholders;
> * Finalizar e arquivar o ambiente de teste, os dados de teste, a infraestrutura de teste e outros testwares para posterior reutilização;
> * Entregar o testware para as equipes de manutenção, outras equipes de projeto ou stakeholders que poderiam se beneficiar de seu uso;
> * Analisar as lições aprendidas das atividades de teste concluídas; 
> * Usar as informações coletadas para melhorar a maturidade do processo do teste.

### Prodtos de trabalho do teste

Produtos de trabalho do teste são os entregáveis de cada atividade de teste, são eles:

Produtos de trabalho do planejamento do teste:

- *Planos de teste*
  
Produtos de trabalho de monitoramento e controle do teste:

- *Relatórios de progresso /  resumo / conclusão*
- *Relatórios de defeitos*
- *Relatórios de risco, alocação, recursos e esforço*

Produtos de trabalho da análise do teste:

- *Condições de teste definidas e priorizadas*
- *Defeitos na base de teste*

Produtos de trabalho da modelegem do teste:

- *Casos de teste de alto nível, derivados das condições identificadas na análise;*
- *Identificações identificadas na análise.*
  
Produtos de trabalho da implementação do teste:

- *Procedimentos de teste (passo a passo/detalhamento);*
- *Suíte de teste;*
- *Cronograma de execução;*

Produtos de trabalho da execução do teste:

- *Status dos casos de teste;*
- *Relatórios de defeitos;*
- *Documentação de quais itens estavam envolvidos no teste;* 


Produtos de trabalho de conclusão do teste 

- *Relatórios de teste;* 
- *Planos de ação para melhoria dos próximos projetos.*


### Rastreabilidade entre a base de teste e os produtos de trabalho de teste

- *Analisar o impacto das mudanças;*
- *Tornar o teste auditável;*
- *Atender aos critérios de governança de TI;*
- *Melhorar a compreensibilidade dos relatórios de progresso do teste;*
- *Relacionar os aspectos técnicos do teste com os stakeholders em termos que eles possam atender;*
- *Fornecer informações para avaliar a qualidade do produto, a capacidade do processo e o progresso do projeto em relação às metas de negócios.*
