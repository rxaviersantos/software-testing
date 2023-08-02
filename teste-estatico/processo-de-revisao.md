# Processo de revisão

As revisões variam de informal para formal. As revisões informais caracterizam-se por não seguir um processo definido e não ter um resultado formal documentado. Revisões formais são caracterizadas pela participação da equipe, com resultados documentados e procedimentos documentados para conduzir a revisão. A formalidade de um processo de revisão está relacionada a fatores como o modelo de ciclo de vida de desenvolvimento de software, a maturidade do processo de
desenvolvimento, a complexidade do produto a ser revisado, e quaisquer requisitos legais ou regulatórios ou a necessidade de uma trilha de auditoria.

O foco de uma revisão depende dos objetivos acordados da revisão (p. ex., encontrar defeitos, obter entendimento, treinar os participantes, como testadores e novos membros da equipe, ou discutir e decidir por consenso).

### Processo de revisão do produto de trabalho

O processo de revisão compreende as seguintes atividades principais:


*Planejar*

> * Definir o escopo, que inclui o propósito da revisão, quais documentos ou partes de documentos devem ser revisados e as características de qualidade a serem avaliadas;
>
> * Estimar o esforço e o prazo;
> 
> * Identificar as características de revisão, como o tipo de revisão, as atividades e checklists;
> 
> * Selecionar as pessoas para participar da revisão e alocar funções;
> 
> * Definir os critérios de entrada e saída para os tipos de revisão mais formais (p. ex., inspeções);
> 
> * Verificar se os critérios de entrada foram atendidos (para tipos de revisão mais formais).


*Iniciar revisão*

> * Distribuir o produto de trabalho (fisicamente ou por meios eletrônicos) e outros materiais, como formulários de registro de problemas, listas de verificação e produtos de trabalho relacionados;
> 
> * Explicar o escopo, os objetivos, o processo, as funções e os produtos de trabalho aos participantes;
> * Responder a quaisquer perguntas que os participantes possam ter sobre a revisão.

Revisão individual (ou seja, preparação individual)

> * Rever todo ou parte do produto de trabalho;
> * Observar possíveis defeitos, recomendações e questões


*Analisar e comunicar*

> * Comunicar possíveis defeitos identificados (p. ex., em uma reunião de revisão);
> 
> * Analisar possíveis defeitos, atribuindo responsável e status a eles;
> 
> * Avaliar e documentar características de qualidade;
> 
> * Avaliar as conclusões da revisão em relação aos critérios de saída para tomar uma decisão de revisão (“rejeitar” mudanças importantes necessárias, “aceitar” possivelmente com pequenas alterações).

*Corrigir e reportar*

> * Criar relatórios de defeitos para as descobertas que exigem mudanças;
> 
> * Corrigir os defeitos encontrados (normalmente feitos pelo autor) no produto de trabalho revisado;
> 
> * Comunicar os defeitos à pessoa ou equipe apropriada (quando encontrado em um produto de trabalho relacionado ao produto de trabalho revisado);
> 
> * Registrar o status atualizado dos defeitos (em revisões formais), principalmente incluindo o “de acordo” do autor do comentário;
> 
> * Métricas de coleta (para tipos de revisão mais formais);
> 
> * Verificar se os critérios de saída foram atendidos (para tipos de revisão mais formais);
> 
> * Aceitar o produto de trabalho quando os critérios de saída são atingidos.


Os resultados de uma revisão de produto de trabalho variam, dependendo do tipo de revisão e da formalidade.

### Funções e responsabilidades em uma revisão formal

Uma revisão formal típica incluirá as funções a seguir: 

Autor

> * Criar o produto de trabalho sob revisão;
> 
> * Corrigir os defeitos no produto de trabalho sob revisão (se necessário).

Gestor

> * Responsável pelo planejamento da revisão;
> * Decidir sobre a execução das revisões;
> * Atribuir pessoal, orçamento e tempo;
> * Monitorar a rentabilidade contínua.

Facilitador (geralmente chamado de moderador)

> * Garantir a execução eficaz das reuniões de revisão (quando realizada);
>   
> * Mediar, se necessário, entre os vários pontos de vista;
>   
> * É frequentemente a pessoa sobre quem o sucesso da revisão depende.

Líder de revisão

> * Assumir a responsabilidade geral pela revisão;
>   
> * Decidir quem será envolvido e organizar quando e onde acontecerá a revisão. 

Revisor

> * Podem ser especialistas no tema, pessoas trabalhando no projeto, stakeholders do produto de trabalho ou indivíduos com formação técnica ou profissional específica;
>   
> * Identificar possíveis defeitos no produto de trabalho sob revisão;
>   
> * Pode representar diferentes perspectivas (p. ex., testador, programador, usuário, operador, analista de negócios, especialista em usabilidade etc.).

Redator (ou registrador)

> * Coletar possíveis defeitos encontrados durante a atividade de revisão individual;
>   
> * Registrar novos defeitos em potencial, pontos em aberto e decisões da reunião de revisão (quando realizada).

Em alguns tipos de revisão, uma pessoa pode desempenhar mais de uma função e as ações associadas a cada função também podem variar com base no tipo de revisão. Além disso, com o advento de ferramentas para apoiar o processo de revisão, especialmente o registro de defeitos, os pontos em aberto e decisões, muitas vezes não há necessidade de um redator.

### Tipos de revisão

Embora as revisões possam ser usadas para vários propósitos, um dos principais objetivos é descobrir defeitos. Todos os tipos de revisão podem auxiliar na detecção de defeitos, e o tipo de revisão selecionado deve ser baseado nas necessidades do projeto, recursos disponíveis, tipo de produto e riscos, domínio do negócio e cultura da empresa, entre outros critérios de seleção.
Um único produto de trabalho pode ser objeto de mais de um tipo de revisão. Se mais de um tipo de revisão for usado, o pedido pode variar.
Os tipos de defeitos encontrados em uma revisão variam, dependendo especialmente do produto de trabalho que está sendo revisado. As revisões podem ser classificadas de acordo com vários atributos. A seguir, lista dos quatro tipos mais comuns de revisões e seus atributos associados.

Revisão informal

> • O objetivo principal é detectar defeitos potenciais;
> 
> • Outros objetivos seriam gerar novas ideias ou soluções, resolvendo rapidamente pequenos problemas;
> 
> • Não baseado em um processo formal (documentado);
> 
> • Não pode envolver uma reunião de revisão;
> 
> • Pode ser realizado por um colega do autor (verificação de parceiro) ou por mais pessoas;
> 
> • Os resultados podem ser documentados;
> 
> • Varia em utilidade dependendo dos revisores;
> 
> • O uso de checklists é opcional;
> 
> • Muito comumente usados no desenvolvimento ágil

Acompanhamento (walkthrough)

> • Os principais objetivos são encontrar defeitos, melhorar o produto de software, considerar implementações alternativas, avaliar a conformidade com padrões e especificações;
> • Objetivos adicionais seriam a troca de ideias sobre técnicas ou variações de estilo, treinamento de participantes, obtenção de consenso;
> 
> • A preparação individual antes da reunião de revisão é opcional;
> 
> • A reunião de revisão é normalmente liderada pelo autor do produto de trabalho;
> 
> • O redator é obrigatório;
> 
> • O uso de checklists é opcional;
> 
> • Pode assumir a forma de cenários, teste prático (dry run) ou simulações;
> 
> • Possíveis logs de defeitos e relatórios de revisão podem ser produzidos;
> 
> • Pode variar na prática de bastante informal para muito formal.

Revisão técnica

> • Os principais objetivos são a obtenção de consenso e a detecção de defeitos potenciais.
> 
> • Outros objetivos possíveis são: avaliar a qualidade e criar confiança no produto de trabalho, gerando novas ideias, motivando e capacitando os autores a melhorar os produtos de trabalho futuros, considerando implementações alternativas.
>
> Os revisores devem ser pares técnicos do autor e especialistas técnicos nas mesmas disciplinas ou em outras disciplinas.
> 
> • É necessária a preparação individual antes da reunião.
> 
> • A reunião de revisão é opcional, preferencialmente conduzida por um facilitador treinado (normalmente que não seja o autor).
> 
> • O redator é obrigatório e preferencialmente que não seja o autor.
> 
> • O uso de checklists é opcional.
> 
> • São produzidos registros de defeitos potenciais e o relatório de revisão

Inspeção

> Os principais objetivos são detectar os defeitos potenciais e avaliar a qualidade e criar confiança no produto de trabalho, evitando futuros defeitos semelhantes por meio do aprendizado do autor e da análise da causa-raiz.
> 
> • Outros possíveis objetivos são: motivar e capacitar os autores a melhorar os futuros produtos de trabalho e o processo de desenvolvimento de software, alcançando consenso.
> 
> • Segue um processo definido com saídas documentadas formais, com base em regras e checklists.
> 
> • Utiliza funções claramente definidas, como aquelas especificadas no capítulo 3.2.2, que são obrigatórias, e podem incluir um leitor dedicado (que lê o produto de trabalho em voz alta durante a reunião de revisão).
> 
> • É necessária a preparação individual antes da reunião.
> 
> • Os revisores são pares do autor ou especialistas em outras disciplinas relevantes para o produto de trabalho.
> 
> • São usados critérios de entrada e saída especificados.
> 
> • O redator é obrigatório.
> 
> • A reunião de revisão é liderada por um facilitador treinado (não pelo autor).
> 
> • O autor não pode atuar como líder de revisão, leitor ou redator.
> 
> • São produzidos registros de defeitos potenciais e o relatório de revisão.
> 
> • As métricas são coletadas e usadas para melhorar todo o processo de desenvolvimento de software, incluindo o processo de inspeção.

Aplicando técnicas de revisão

Há uma série de técnicas de revisão que podem ser aplicadas durante a atividade de revisão individual para descobrir defeitos. Essas técnicas podem ser usadas nos tipos de revisão descritos acima. A eficácia das técnicas pode variar dependendo do tipo da revisão utilizada. Abaixo são listados exemplos de diferentes técnicas de revisão individuais para vários tipos de revisão.

Revisão ad hoc

Em uma revisão ad hoc, os revisores recebem pouca ou nenhuma orientação sobre como essa tarefa deve ser executada. Os revisores geralmente leem o produto de trabalho sequencialmente, identificando e documentando os problemas à medida que os encontram. A revisão ad hoc é uma técnica comumente usada que requer pouca preparação. Essa técnica é altamente dependente das habilidades do revisor e pode levar a muitos problemas relatados em duplicidade por revisores diferentes.

Revisão baseada em checklist

Uma revisão baseada em checklist é uma técnica sistemática, na qual os revisores detectam os problemas com base em checklists que são distribuídos no início da revisão (p. ex., pelo facilitador). Um checklist de revisão consiste em um conjunto de perguntas baseadas em possíveis defeitos, que podem ser derivados da experiência. Os checklists devem ser específicos para o tipo de produto de trabalho sob teste e devem ser mantidos regularmente para cobrir os tipos de problemas perdidos nas revisões anteriores. A principal vantagem da técnica baseada em checklist é uma cobertura sistemática dos típicos tipos de defeitos. Deve-se tomar cuidado para não seguir simplesmente o checklist na revisão individual, mas também para procurar defeitos fora do checklist.

Revisão baseada em cenários

Em uma revisão baseada em cenário, os revisores recebem orientações estruturadas sobre como ler o produto de trabalho. Uma abordagem baseada no cenário dá suporte aos revisores na execução de "sequências" no produto de trabalho com base no uso esperado do produto de trabalho (se o produto de trabalho for documentado em um formato adequado, como casos de uso). Esses cenários fornecem aos revisores melhores diretrizes sobre como identificar tipos específicos de defeitos do que simples entradas no checklist. Assim como nas revisões baseadas em checklist, para não perder outros tipos de defeitos (p. ex., ausência de recursos), os revisores não devem ser restritos aos cenários documentados.

Revisão baseada na perspectiva

Na revisão baseada na perspectiva, semelhante a uma revisão baseada em papéis, os revisores assumem os pontos de vista de diferentes stakeholders na revisão individual. Os pontos de vista comuns dos stakeholders incluem o usuário final, marketing, designer, testador ou operador. Usar esses diferentes pontos de vista leva a uma maior profundidade na revisão individual, com menos duplicidade de problemas entre os revisores.

Além disso, esse modelo também exige que os revisores tentem usar o produto de trabalho sob revisão para gerar o produto que eles obteriam. Por exemplo, um testador tentaria gerar testes de aceite de rascunho ao executar uma revisão baseada na perspectiva em uma especificação de requisitos para ver se todas as informações necessárias foram incluídas. Além disso, nesse modelo, espera-se que os checklists sejam usados.

Estudos empíricos mostraram que essa revisão é a técnica mais eficaz para revisar os requisitos e os produtos de trabalho técnico. Um fator-chave para o sucesso é incluir e ponderar adequadamente os diferentes pontos de vista dos stakeholders, baseando-se nos riscos. 

Revisão baseada em papéis

Uma revisão baseada em papéis é uma técnica na qual os revisores avaliam o produto de trabalho na perspectiva dos papéis individuais dos stakeholders. Os papéis típicos incluem tipos específicos de usuário final (experiente, inexperiente, sênior, jovem etc.) e papéis específicos na organização (administrador do usuário, administrador do sistema, testador de performance etc.).


### Fatores de sucesso para revisões

Para ter uma revisão bem-sucedida, devem ser considerados o tipo e as técnicas apropriadas de revisão. Além disso, há vários outros fatores que afetarão o resultado.

Fatores organizacionais de sucesso para revisões incluem:

> • Cada revisão tem objetivos claros, definidos durante o seu planejamento e usados como critérios mensuráveis de saída.
> 
> • São aplicados tipos de revisão que são adequados para alcançar os objetivos e são apropriados ao tipo e nível de produtos de trabalho de software e participantes.
> 
> • Quaisquer técnicas usadas de revisão, como baseada em checklist ou baseada em papéis, são adequadas para a identificação efetiva de defeitos no produto de trabalho a ser revisado.
> 
> • Todos os checklists utilizados abordam os principais riscos e deverão estar atualizados.
> 
> • Documentos grandes são escritos e revisados em pequenos pedaços, para que o controle de qualidade seja exercido através do fornecimento de feedback antecipado e frequente aos autores sobre os defeitos.
> 
> • Os participantes devem ter tempo suficiente para se preparar.
> 
> • As revisões são agendadas com aviso adequado.
> 
> • A gerência apóia o processo de revisão (p. ex., incorporando tempo adequado para atividades de revisão nos cronogramas do projeto).

Os fatores de sucesso relacionados às pessoas para revisões incluem:

> • As pessoas certas estão envolvidas para atender aos objetivos de revisão, por exemplo, pessoas com diferentes conjuntos de habilidades ou perspectivas, que podem usar o documento como uma entrada de trabalho.
> 
> • Os testadores são vistos como revisores valiosos que contribuem para a revisão e aprendem sobre o produto de trabalho, o que permite que eles preparem testes mais eficazes e preparem esses testes antes.
> 
> • Os participantes dedicam tempo e atenção adequados aos detalhes.
> 
> • As revisões são realizadas em pequenos trechos, para que os revisores não percam a concentração durante a revisão individual ou na reunião de revisão (quando realizada).
> 
> • Os defeitos encontrados são reconhecidos, apreciados e manipulados objetivamente.
> 
> • A reunião é bem administrada, para que os participantes considerem um uso valioso do seu tempo.
> 
> • A revisão é conduzida em uma atmosfera de confiança; o resultado não será usado para a avaliação dos participantes.
>
> • Os participantes evitam linguagem corporal e comportamentos que possam indicar tédio, exasperação ou hostilidade a outros participantes.
> 
> • O treinamento adequado é fornecido, especialmente para os tipos de revisão mais formais, como as inspeções.
> 
> • Uma cultura de aprendizado e melhoria de processos é promovida.
















