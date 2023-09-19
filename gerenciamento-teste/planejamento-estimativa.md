# Planejamento e estimativa de testes

### Objetivo e conteúdo de um plano de teste

O planejamento é influenciado pela política de teste e a estratégia de teste da organização, pelos ciclos de vida e métodos de desenvolvimento usados, pelo escopo dos testes, objetivos, riscos, restrições, criticidade, testabilidade e disponibilidade dos recursos. Conforme o andamento do projeto e do planejamento do teste, mais informações ficam disponíveis e mais detalhes podem ser incluídos no plano de teste. O planejamento do teste é uma atividade contínua e é executado durante todo o ciclo de vida do produto (observe que o ciclo de vida do produto pode se estender além do escopo de um projeto para incluir a fase de manutenção). O feedback das atividades de teste deve ser usado para reconhecer a alteração de riscos para que o planejamento possa ser ajustado. O planejamento pode ser documentado em um plano de teste principal e em planos de teste separados para cada nível de teste, como testes de sistema e testes de aceite, ou para cada tipo de teste, como teste de usabilidade e teste de performance. As atividades do planejamento do teste podem ser documentadas em um plano de teste e incluir:

> • Determinar o escopo, os objetivos e os riscos do teste.
> 
> • Definir a abordagem geral do teste.
> 
> • Integrar e coordenar as atividades de teste nas atividades do ciclo de vida do software.
> 
> • Tomar decisões sobre o que testar, as pessoas e outros recursos necessários para realizar asvárias atividades de teste e como essas atividades serão realizadas.
> 
> • Programar as atividades de análise, projeto, implementação, execução e avaliação de testes,
em datas específicas (p. ex., em desenvolvimento sequencial) ou no contexto de cada iteração (p. ex., no desenvolvimento iterativo).
>
> • Selecionar as métricas para monitoramento e controle de testes.
> 
> • Orçar as atividades de teste.
> 
> • Determinar o nível de detalhes e a estrutura da documentação de teste (p. ex., fornecendo modelos ou exemplos de documentos).

### Estratégia de teste e abordagem de teste

Uma estratégia de teste fornece uma descrição geral do processo de teste, comumente no nível do produto ou organizacional. Tipos comuns de estratégias de teste incluem:

> • Analítica: este tipo de estratégia de teste é baseado em uma análise de algum fator (p. ex., exigência ou risco). O teste baseado em risco é um exemplo de abordagem analítica, em que os testes são projetados e priorizados com base no nível de risco.
> 
>  • Baseada em modelo: neste tipo de estratégia de teste, os testes são projetados com base
em algum modelo de algum aspecto necessário do produto, como uma função, um processo
empresarial, uma estrutura interna ou uma característica não funcional (p. ex., confiabilidade). Exemplos de tais modelos incluem os modelos de processos de negócios, os modelos de estado e os modelos de crescimento de confiabilidade.
>
>  • Metódica: esse tipo de estratégia de teste depende do uso sistemático de um conjunto predefinido de testes ou condições de teste, como uma taxonomia de tipos comuns ou prováveis de falhas, uma lista de características de qualidade importantes, ou padrões de aparência e comportamento de aplicativos móveis ou páginas da web da empresa.
> 
>  • Compatível com processo (ou compatível com um padrão): esse tipo de estratégia envolve análise, projeto e implementação do teste baseado em regras e padrões externos, como aqueles determinados por padrões específicos do setor, pela documentação do processo, pela identificação e uso da base de teste, ou por qualquer processo ou padrão imposto pela organização.
> 
>  • Dirigida (ou consultivo): esse tipo de estratégia de teste é orientado principalmente pelo aconselhamento, orientação ou instruções dos stakeholders, especialistas no domínio do negócio ou especialistas em tecnologia, que podem estar fora da equipe de teste ou fora da própria organização.
> 
>  • Contra regressão: esse tipo de estratégia de teste é motivado pelo desejo de evitar a regressão de recursos existentes. Essa estratégia de teste inclui a reutilização do testware existente (especialmente casos de teste e dados de teste), da automação extensiva de testes de regressão e de conjuntos de teste padrão.
> 
>  • Reativa: Nesse tipo de estratégia de teste, o teste é reativo ao componente ou sistema que está sendo testado e aos eventos que ocorrem durante a execução do teste, em vez de serem pré-planejados (como as estratégias anteriores). Os testes são planejados e implementados e podem ser imediatamente executados em resposta ao conhecimento adquirido em resultados de testes anteriores. O teste exploratório é uma técnica comum empregada em estratégias reativas.

Uma estratégia de teste apropriada é frequentemente criada pela combinação de vários desses tipos de estratégias de teste. Por exemplo, testes baseados em risco (estratégia analítica) podem ser combinados com testes exploratórios (estratégia reativa), se complementando e podendo alcançar testes mais eficazes quando usados juntos.

Embora a estratégia de teste forneça uma descrição geral do processo de teste, a abordagem de teste adapta a estratégia de teste para um projeto ou lançamento específico. A abordagem de teste é o ponto de partida para selecionar as técnicas de teste, os níveis de teste e os tipos de teste, e para definir os critérios de entrada e saída (ou da definição de “pronto” ou “feito”, respectivamente). A adaptação da estratégia baseia-se em decisões tomadas em relação à complexidade e objetivos do projeto, do tipo de produto que está sendo desenvolvido e da análise de risco do produto. A abordagem selecionada depende do contexto e pode considerar fatores como riscos, segurança, recursos e habilidades disponíveis, tecnologia, natureza do sistema (p. ex., versão customizada ou software de prateleira), objetivos de teste e regulamentos

### Critérios de entrada e saída (definição de “pronto” e “feito”)

Para exercer o controle efetivo sobre a qualidade do software e dos testes, é aconselhável ter critérios que definam quando uma determinada atividade de teste deve iniciar e quando a atividade é concluída. Os critérios de entrada (chamado de “pronto” no desenvolvimento ágil) definem as condições prévias para a realização de uma determinada atividade de teste. Se os critérios de entrada não forem cumpridos, é provável que a atividade se mostre mais difícil, mais demorada, mais cara e mais arriscada. Os critérios de saída (chamado de “feito” no desenvolvimento ágil) definem quais condições devem ser atingidas para declarar que um nível de teste ou um conjunto de testes foram concluídos. Os critérios de entrada e saída devem ser definidos para cada nível e tipo de teste e serão diferentes com base nos objetivos do teste.

Critérios típicos de entrada incluem:

> • Disponibilidade dos requisitos testáveis, histórias de usuários e/ou modelos (p. ex., ao seguir uma estratégia de teste baseada em modelo).
> 
> • Disponibilidade dos itens de teste que atendam aos critérios de saída para quaisquer níveis de teste anteriores.
> 
> • Disponibilidade do ambiente de teste.
> 
>• Disponibilidade de ferramentas de teste necessárias.
> 
> • Disponibilidade de dados de teste e outros recursos necessários.

Os critérios típicos de saída incluem:

> • Que os testes planejados foram executados.
> 
> • Foi alcançado um nível definido de cobertura (p. ex., de requisitos, histórias de usuários, critérios de aceite, riscos, código).
> 
> • O número de defeitos não resolvidos está dentro de um limite acordado.
> 
> • O número de defeitos remanescentes estimados é suficientemente baixo.
> 
> • Os níveis avaliados de confiabilidade, eficiência de performance, usabilidade, segurança e outras características de qualidade relevantes são suficientes.

Mesmo sem que os critérios de saída sejam satisfeitos, também é comum que as atividades de teste sejam reduzidas devido ao orçamento gasto, à conclusão do prazo programado ou da pressão para levar o produto ao mercado. Pode ser aceitável encerrar os testes sob tais circunstâncias, se os stakeholders e os donos das empresas do projeto tiverem revisado e aceito o risco de entrar em vigor sem mais testes.

### Cronograma de execução de teste

Depois que vários casos de teste e procedimentos de teste são produzidos (com alguns procedimentos de teste potencialmente automatizados) e montados em suítes de testes, os
conjuntos de testes podem ser organizados em um cronograma da execução do teste que define a ordem em que devem ser executados. O cronograma deve levar em consideração fatores como priorização, dependências, testes de confirmação, testes de regressão e a sequência mais eficiente para se executar os testes.

O ideal seria que os casos de teste fossem ordenados para serem executados com base em seus níveis de prioridade, geralmente executando os casos de teste com a prioridade mais alta primeiro. No entanto, essa prática pode não funcionar se os casos de teste tiverem dependências ou os recursos que estão sendo testados tiverem dependências. Se um caso de teste com prioridade mais alta depender de um caso de teste com prioridade mais baixa, o caso de teste de prioridade mais baixa deverá ser executado primeiro. Da mesma forma, se houver dependências entre os casos de teste, elas devem ser ordenadas adequadamente, independentemente de suas prioridades relativas. Os testes de confirmação e regressão também devem ser priorizados, com base na importância de feedback rápido sobre as mudanças, mas aqui novamente as dependências podem ser aplicadas.

Em alguns casos, várias sequências de testes são possíveis, com diferentes níveis de eficiência associados a essas sequências. Nesses casos, as compensações entre a eficiência da execução do teste e a aderência à priorização devem ser feitas.

### Fatores que influenciam o esforço do teste

A estimativa de esforço do teste envolve a previsão da quantidade de trabalho relacionado ao teste que será necessário para atender aos objetivos do teste de um projeto, release ou iteração em particular. Os fatores que influenciam o esforço de teste podem incluir características do produto, características do processo de desenvolvimento, características das pessoas e resultados do teste.

Características do produto

> • Riscos associados com o produto
> 
>  • Qualidade da base de teste
> 
>  • Tamanho do produto
> 
>  • Complexidade do domínio do produto
> 
>  • Requisitos das características de qualidade (p. ex., segurança, confiabilidade)
> 
>  • Nível necessário de detalhes para documentação de teste
> 
>  • Requisitos para conformidade legal e regulatória

Características do processo de desenvolvimento

> • Estabilidade e maturidade da organização.
> 
> • O modelo de desenvolvimento em uso.
> 
> • A abordagem de teste.
> 
> • As ferramentas usadas.
> 
> • O processo de teste.
> 
> • A pressão sobre o tempo de finalização.

Características das pessoas

> • As habilidades e a experiência das pessoas envolvidas, especialmente com projetos e produtos semelhantes (p. ex., conhecimento de domínio).
> 
> • Coesão e liderança da equipe.

Resultados dos testes

> • O número e a gravidade dos defeitos encontrados.
> 
> • A quantidade de retrabalho necessário.

### Técnicas de estimativa de teste

Existem várias técnicas de estimativa usadas para determinar o esforço necessário adequado para os testes. Duas das mais utilizadas são:

> • *Técnica baseada em métricas:* estimar o esforço do teste com base nas métricas de projetos anteriores, ou com base em valores típicos.
> 
> • *Técnica baseada em especialistas:* estimar o esforço do teste com base na experiência dos responsáveis pelas tarefas de teste ou por especialistas.

Por exemplo, no desenvolvimento ágil, os gráficos burndown são exemplos da técnica baseada em métricas à medida que o esforço é capturado e relatado e, em seguida, usado para alimentar a velocidade da equipe para determinar a quantidade de trabalho que ela pode realizar na próxima iteração; considerando que o planning poker é um exemplo da técnica baseada em especialistas, já que os membros da equipe estão estimando o esforço para entregar um recurso com base em sua experiência.

Em projetos sequenciais, os modelos de remoção de defeitos são exemplos da técnica baseada em métricas, onde o volume de defeitos e o tempo para removê-los são capturados e relatados, o que fornece uma base para estimar projetos futuros de natureza semelhante. Considerando que a técnica de estimativa Wideband Delphi é um exemplo da técnica baseada em especialistas, na qual grupos de especialistas fornecem estimativas com base em sua experiência.













