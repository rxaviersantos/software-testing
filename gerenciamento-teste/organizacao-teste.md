# Organização do teste

### Teste independente

As tarefas de teste podem ser executadas por pessoas em um papel de teste específico ou por pessoas em outros papéis (p. ex., clientes). Um certo grau de independência geralmente torna o testador mais eficaz em encontrar os defeitos devido às diferenças entre os vieses cognitivos do autor e do testador. A independência não é, no entanto, um substituto para a familiaridade com o produto, e os desenvolvedores podem encontrar com eficiência muitos defeitos em seu próprio código.

Os graus de independência nos testes incluem (de baixo nível de independência a alto nível):

• Sem testadores independentes, a única forma de teste disponível são os desenvolvedores testando seu próprio código.

• Desenvolvedores independentes ou testadores dentro das equipes de desenvolvimento ou da equipe do projeto; isso poderiam ser desenvolvedores testando os produtos de seus colegas.

• Equipe de teste independente ou grupo dentro da organização, reportando-se ao gerenciamento de projetos ou ao gerenciamento executivo.

• Testadores independentes da organização empresarial ou da comunidade de usuários, ou com especializações em tipos de testes específicos, como usabilidade, segurança, performance, regulamentação, conformidade ou portabilidade.

• Testadores independentes externos à organização, trabalhando dentro ou fora do escritório.

Para a maioria dos tipos de projetos, geralmente é melhor ter vários níveis de teste, com alguns desses níveis gerenciados por testadores independentes. Os desenvolvedores devem participar dos testes, especialmente nos níveis mais baixos, para exercer controle sobre a qualidade de seu próprio trabalho.

A maneira pela qual a independência dos testes é implementada varia dependendo do modelo de ciclo de vida de desenvolvimento de software. Por exemplo, no desenvolvimento ágil, os testadores podem fazer parte de uma equipe de desenvolvimento. Em algumas organizações que usam métodos ágeis, esses testadores também podem ser considerados parte de uma equipe maior de testes independentes. Além disso, em tais organizações, os product owners podem realizar testes de aceite para validar as histórias de usuários ao final de cada iteração.

Os benefícios potenciais da independência do teste incluem:

> • Os testadores independentes provavelmente reconhecerão diferentes tipos de falhas em comparação a os desenvolvedores, devido a diferentes históricos, perspectivas técnicas e vieses.
> 
> • Um testador independente pode verificar, desafiar ou refutar as suposições feitas pelos stakeholders durante a especificação e a implementação do sistema.
> 

As desvantagens potenciais da independência do teste incluem:

> • Isolamento da equipe de desenvolvimento, levando a uma falta de colaboração, atrasos no fornecimento de feedback para a equipe de desenvolvimento ou um relacionamento adverso com a equipe de desenvolvimento.
> 
> • Os desenvolvedores podem perder o senso de responsabilidade pela qualidade.
> 
> • Testadores independentes podem ser vistos como gargalo ou culpados por atrasos na liberação.
> 
> • Testadores independentes podem não ter algumas informações importantes (p. ex., sobre o objeto de teste).
> 

Muitas organizações são capazes de alcançar com sucesso os benefícios da independência do teste, evitando todas as desvantagens

### Tarefas de um gerente de teste e do testador

As atividades e tarefas desempenhadas por esses dois papéis dependem do contexto do projeto e do produto, das habilidades das pessoas nas funções e da organização.

O gerente de teste tem a responsabilidade geral do processo de teste e da liderança das atividades bem-sucedidas de teste. O papel de gerente de teste pode ser executado por um gerente de teste profissional ou por um gerente de projeto, um gerente de desenvolvimento ou um gerente de qualidade. Em projetos ou organizações maiores, várias equipes de teste podem se reportar a um gerente de teste, um técnico de testes ou um coordenador de testes, cada equipe sendo liderada por um líder de teste ou um testador líder

As tarefas típicas do gerente de teste podem incluir:

> • Desenvolver ou revisar uma política de teste e uma estratégia de teste para a organização.
> 
> • Planejar as atividades de teste considerando o contexto e entendendo os objetivos e riscos do teste. Isso pode incluir a seleção de abordagens de teste, a estimativa do tempo, o esforço e o custo, a aquisição de recursos, a definição de níveis e ciclos de teste e o planejamento da gestão dos defeitos.
> 
> • Escrever e atualizar o(s) plano(s) de teste.
> 
> • Coordenar o(s) plano(s) de teste com gerentes de projeto, proprietários dos produtos e outros.
> 
> • Compartilhar as perspectivas de teste com outras atividades do projeto, como planejamento da integração.
> 
> • Iniciar a análise, o projeto, a implementação e a execução dos testes, monitorar o progresso e os resultados obtidos e verificar o status dos critérios de saída (ou definição de feito).
> 
> • Preparar e entregar os relatórios de progresso do teste e resumo com base nas informações coletadas.
> 
> • Adaptar o planejamento com base nos resultados e no progresso dos testes (às vezes documentados em relatórios de andamento de testes ou em relatórios de resumo de teste para outros testes já concluídos no projeto) e tomar as ações necessárias para o controle de testes.
> 
> • Suporte para configurar o sistema de gerenciamento de defeitos e o gerenciamento de configuração adequado do testware.
> 
> • Introduzir as métricas adequadas para medir o progresso do teste e avaliar a qualidade do teste e do produto.
> 
> • Apoiar a seleção e implementação de ferramentas para apoiar o processo de teste, incluindo a recomendação orçamentária para seleção de ferramentas (e possivelmente compra ou suporte), alocando tempo e esforço para projetos-piloto e fornecendo suporte contínuo no uso de ferramenta.
> 
> • Decidir sobre a implementação do(s) ambiente(s) de teste.
> 
> • Promover e defender os testadores, a equipe de teste e a profissão de teste dentro da organização.
> 
> • Desenvolver as habilidades e carreiras dos testadores (p. ex., através de planos de treinamento, avaliações de performance, treinamento etc.).
> 

A maneira como a função de gerente de teste é executada varia de acordo com o ciclo de vida de desenvolvimento de software. Por exemplo, no desenvolvimento ágil, algumas das tarefas mencionadas acima são tratadas pela equipe do Ágil, especialmente aquelas relacionadas ao teste diário feito dentro da equipe, geralmente por um testador que trabalha na equipe. Algumas das tarefas que abrangem várias equipes ou toda a organização, ou que têm a ver com gerenciamento de pessoal, podem ser executadas por gerentes de teste fora da equipe de desenvolvimento, que às vezes são chamados de treinadores de teste. Veja Black (2009) para mais informações sobre como gerenciar o processo de teste.

As tarefas típicas do testador podem incluir:

> • Revisar e contribuir para os planos de teste.
> 
> • Analisar, revisar e avaliar os requisitos, as histórias de usuários e os critérios de aceite, as especificações e modelos para testabilidade (ou seja, a base de teste).
> 
> • Identificar e documentar as condições de teste e capturar a rastreabilidade entre casos de teste, as condições de teste e a base de teste.
> 
> • Projetar, configurar e verificar o(s) ambiente(s) de teste, geralmente coordenando com a administração do sistema e gerenciamento da rede.
> 
> • Projetar e implementar casos de teste e procedimentos de teste.
> 
> • Preparar e adquirir os dados de teste.
> 
> • Criar o cronograma detalhado de execução dos testes.
> 
> • Executar os testes, avaliar os resultados e documentar os desvios dos resultados esperados.
> 
> • Usar ferramentas apropriadas para facilitar o processo de teste.
> 
> • Automatizar os testes conforme necessário (pode ser suportado por um desenvolvedor ou por um especialista em automação de testes).
> 
> • Avaliar as características não-funcionais, como eficiência de performance, confiabilidade, usabilidade, segurança, compatibilidade e portabilidade.
> 
> • Revisar os testes desenvolvidos por outros.

As pessoas que trabalham em análise de teste, projeto de teste, tipos de teste específicos ou automação de teste podem ser especialistas nessas funções. Dependendo dos riscos relacionados ao produto e ao projeto, e o modelo de ciclo de vida de desenvolvimento de software selecionado, pessoas diferentes podem assumir o papel de testador em diferentes níveis de teste. Por exemplo, no nível de teste de componente e no nível de teste de integração de componente, o papel de um testador é geralmente executado por desenvolvedores. No nível de teste de aceite, o papel de um testador geralmente é feito por analistas de negócios, especialistas no assunto e usuários. No nível de teste do sistema e no nível de teste de integração do sistema, o papel de um testador é geralmente executado por uma equipe de teste independente. No nível de teste de aceite operacional, o papel de um testador geralmente é executado pelas equipes de administração de operações ou sistemas.




