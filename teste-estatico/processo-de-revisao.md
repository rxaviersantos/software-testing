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













