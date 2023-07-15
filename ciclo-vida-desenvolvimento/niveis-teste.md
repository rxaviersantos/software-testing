# Níveis de teste 

Os níveis de teste são grupos de atividades de teste que são organizados e gerenciados juntos. Cada
nível de teste é uma instância do processo de teste, consistindo nas atividades descritas, executadas em relação ao software em um determinado nível de desenvolvimento, desde as unidades individuais ou componentes até os sistemas completos ou, quando aplicável, em sistemas de sistemas. Os níveis de teste estão relacionados com outras atividades dentro do ciclo de vida de desenvolvimento de software. 

<p align="center">
  <img alt="nivel de teste" src="https://github.com/rxaviersantos/software-testing/assets/85380530/10e79048-3725-46cc-aff1-1255708fa5e9" "height="400px" width="600px">
</p>



Os níveis de teste usados neste documento são:

```
• Teste de componentes;
• Teste de integração;
• Teste do sistema;
• Teste de aceite.
```

Os níveis de teste são caracterizados pelos seguintes atributos:

```
• Objetivos específicos;
• Base de teste, referenciada para derivar casos de teste;
• Objeto de teste (ou seja, o que está sendo testado);
• Defeitos e falhas típicas;
• Abordagens e responsabilidades específicas.
```

Para cada nível de teste, é necessário um ambiente de teste adequado. No teste de aceite, por
exemplo, um ambiente de teste com características mais próximas do ambiente de produção é ideal,
enquanto no teste de componentes os desenvolvedores normalmente usam seu próprio ambiente
de desenvolvimento.

## Teste de componente

Objetivos do teste de componente

O teste de componente (também conhecido como teste de unidade ou módulo) se concentra em
componentes que são testáveis separadamente. Os objetivos incluem:

• Reduzir o risco;
• Verificar os comportamentos funcional e não funcional do componente ao projetado e
especificado;
• Construir a confiança na qualidade do componente;
• Encontrar defeitos no componente;
• Evitar que os defeitos espalhem para níveis mais altos de teste.

Em alguns casos, especialmente em modelos de desenvolvimento incremental e iterativo (p. ex., Ágil),
em que as alterações de código estão em andamento, os testes de regressão de componentes
automatizados desempenham um papel fundamental na criação da confiança de que as alterações
não impactaram os componentes existentes.


O teste de componente geralmente é realizado isoladamente do resto do sistema, dependendo do modelo de ciclo de vida de desenvolvimento de software e de sistema, que pode exigir objetos simulados, virtualização de serviços, estrutura, simuladores e controladores. O teste de componente pode cobrir funcionalidade (p. ex., correção de cálculos), características não-funcionais (p. ex., busca
de vazamentos de memória) e propriedades estruturais (p. ex., teste de decisão).

<p align="center">
  <img alt="nivel de teste" src="https://github.com/rxaviersantos/software-testing/assets/85380530/e1ad9682-b0f5-4223-98d5-0fcc8f753849" "height="400px" width="600px">
</p>


### Base de teste

Exemplos de produtos de trabalho que podem ser usados como base de teste para testes de
componentes incluem:

````
• Projeto detalhado;
• Código;
• Modelo de dados;
• Especificações de componentes.
````
### Objetos de teste 

Objetos de teste típicos para testes de componentes incluem:

```
• Componentes, unidades ou módulos;
• Estruturas de código e dados;
• Classes;
• Módulos de banco de dados
```

### Defeitos típicos e falhas

Exemplos de defeitos e falhas típicas para o teste de componentes incluem:

> • Funcionalidade incorreta (p. ex., não conformidade descrita nas especificações do projeto);
> 
> • Problemas no fluxo de dados;
> 
> • Código e lógica incorretos.

Os defeitos geralmente são corrigidos assim que são encontrados, geralmente sem gerenciamento formal dos defeitos. No entanto, quando os desenvolvedores relatam defeitos, isso fornece informações importantes para análise de causa raiz e melhoria de processo.

### Abordagens e responsabilidades específicas

O teste de componente geralmente é executado pelo desenvolvedor que escreveu o código, mas obrigatoriamente requer acesso ao código que está sendo testado. Os desenvolvedores podem alternar o desenvolvimento de componentes com a localização e correção de defeitos. Os desenvolvedores geralmente escrevem e executam testes depois de codificarem um componente.

No entanto, especialmente no desenvolvimento ágil, escrever os casos de teste de componentes automatizados pode preceder a gravação do código do aplicativo.

Por exemplo, considere o desenvolvimento orientado por teste (TDD). Esse desenvolvimento é altamente iterativo e baseado em ciclos de desenvolvimento de casos de teste automatizados, em seguida, na criação e integração de pequenos trechos de código, executando os testes de componentes, corrigindo quaisquer problemas e regerando o código. Esse processo continua até que o componente tenha sido completamente construído e todos os testes de componentes tenham passado. O desenvolvimento orientado por teste é um exemplo de uma abordagem de teste inicial. 


## Teste de integração

Objetivos do teste de integração

O teste de integração se concentra nas interações entre componentes ou sistemas. Os objetivos do teste de integração incluem:

> • Reduzir risco;
> 
> • Verificar se os comportamentos funcionais e não-funcionais das interfaces estão projetados e especificados;
> 
> • Construir confiança na qualidade das interfaces;
> 
> • Encontrar defeitos (que podem estar nas próprias interfaces ou nos componentes ou sistemas);
> 
> • Evitar que os defeitos espalhem para níveis mais altos de teste.


Assim como no teste de componentes, em alguns casos, o teste de regressão de integração automatizada garante que as alterações não interromperam as interfaces, os componentes ou sistemas existentes.

Existem dois níveis diferentes de teste de integração, que podem ser realizados em objetos de teste de tamanho variável, como segue:

> - O teste de integração de componentes foca nas interações e interfaces entre componentes integrados. O teste de integração de componentes é executado após o teste do componente e geralmente é automatizado. No desenvolvimento iterativo e incremental, os testes de integração de componentes geralmente fazem parte do processo de integração contínua;
>
> - O teste de integração do sistema concentra-se nas interações e interfaces entre sistemas, pacotes e micro serviços. O teste de integração do sistema também pode abranger interações e interfaces fornecidas por entidades externas (p. ex., serviços da Web). Nesse caso, a entidade em desenvolvimento não controla as interfaces externas, o que pode criar vários desafios para testes (p. ex., garantir que os defeitos de bloqueio de teste no código da organização externa sejam resolvidos, organizar ambientes de teste etc.). O teste de integração do sistema pode ser feito após o teste do sistema ou em paralelo com as atividades de teste do sistema em andamento (tanto no desenvolvimento sequencial quanto no desenvolvimento iterativo e incremental).


<p align="center">
  <img alt="nivel de teste" src="https://github.com/rxaviersantos/software-testing/assets/85380530/31a5bfe7-e552-4d25-895e-a3a9b8984ce4" "height="400px" width="600px">
</p>



Base de teste

Produtos de trabalho que podem ser usados como base de teste para testes de integração incluem:
```
• Software e modelagem do sistema;
• Diagramas de sequência;
• Especificações de interface e protocolo de comunicação;
• Casos de uso;
• Arquitetura no nível de componente ou sistema;
• Fluxos de trabalho;
• Definições de interface externa.
```

Objetos de teste

Objetos de teste típicos para testes de integração incluem:
```
• Subsistemas;
• Bancos de dados;
• Infraestrutura;
• Interfaces;
• APIs;
• Micro serviços.
```

Defeitos típicos e falhas

Defeitos e falhas típicos para testes de integração de componentes incluem:

> • Dados incorretos, dados ausentes ou codificação de dados incorreta;
> 
> • Sequenciamento ou temporização incorretos de chamadas de interface;
> 
> • Incompatibilidade de interface;
> 
> • Falhas na comunicação entre componentes;
> 
> • Falha de comunicação não manipulada ou tratada de forma errada entre componentes;
> 
> • Suposições incorretas sobre o significado, as unidades ou limites dos dados que estão sendo
transmitidos entre os componentes.

Os exemplos de defeitos e falhas típicos para testes de integração de sistemas incluem:

> • Estruturas de mensagens inconsistentes entre sistemas;
> 
> • Dados incorretos, dados ausentes ou codificação de dados incorreta;
> 
> • Incompatibilidade de interface;
> 
> • Falhas na comunicação entre sistemas;
> 
> • Falha de comunicação não manipulada ou tratada de forma errada entre sistemas;
> 
> • Suposições incorretas sobre o significado, unidades ou limites dos dados que estão sendo
transmitidos entre sistemas;
> 
> • Falha no cumprimento dos regulamentos de segurança obrigatórios.

### Abordagens e responsabilidades específicas

Os testes de integração de componentes e os testes de integração de sistemas devem se concentrar na própria integração. Por exemplo, se integrar o módulo A com o módulo B, os testes devem focar na comunicação entre ambos e não na funcionalidade dos módulos individualmente, como deveria ter sido coberto durante o teste de componentes. Se integrar o sistema X ao sistema Y, os testes devem focar na comunicação entre os sistemas, não na funcionalidade dos sistemas individualmente, como isso deveria ter sido coberto durante o teste do sistema. Tipos de testes funcionais, não-funcionais e estruturais são aplicáveis.

O teste de integração de componentes geralmente é de responsabilidade dos desenvolvedores, e o teste de integração do sistema geralmente é de responsabilidade dos testadores. No formato ideal, os testadores que realizam o teste de integração do sistema devem entender da arquitetura do sistema e devem ter influenciado no planejamento da integração.

Se os testes de integração e a estratégia de integração forem planejados antes de componentes ou sistemas serem construídos, esses componentes ou sistemas podem ser construídos na ordem exigida para a maioria dos testes eficientes.

Quanto maior o escopo da integração, mais difícil se torna isolar os defeitos em um componente ou sistema específico, o que pode levar a um aumento do risco e a um tempo adicional para a solução de problemas. Esse é um dos motivos pelos quais a integração contínua, onde o software é integrado componente por componente (ou seja, integração funcional), tornou-se prática comum. Essa integração contínua geralmente inclui testes de regressão automatizados, preferencialmente em vários níveis de teste.


## Teste de sistema

Objetivos do teste de sistema

O teste de sistema se concentra no comportamento e nas capacidades de todo um sistema ou produto, geralmente considerando as execuções das tarefas de ponta a ponta do sistema e os comportamentos não-funcionais exibidos ao executar tais tarefas. 

Os objetivos do teste do sistema incluem:
```
•  Reduzir o risco;

• Verificar se os comportamentos funcionais e não-funcionais do sistema estão como projetados e especificados;

• Validar se o sistema está completo e funcionará como esperado;

• Criar confiança na qualidade do sistema como um todo;

• Encontrar defeitos;

• Evitar que os defeitos espalhem para níveis mais altos de teste ou produção
```


Para determinados sistemas, a verificação da qualidade dos dados pode ser um objetivo. Assim como no teste de componente e no teste de integração, e em alguns casos os testes automatizados de regressão do sistema fornecem a confiabilidade de que as alterações não quebraram os recursos existentes ou a execução dos recursos de ponta a ponta.

O teste do sistema geralmente produz informações que são usadas pelos stakeholders para tomar decisões de liberação. O teste do sistema também pode satisfazer requisitos ou padrões legais e regulatórios. O ambiente de teste deve preferencialmente corresponder ao seu destino, ou ao ambiente de produção.

<p align="center">
  <img alt="nivel de teste" src="https://github.com/rxaviersantos/software-testing/assets/85380530/2b8813c8-f8f5-49fd-bd9a-4b2a29472acd" "height="400px" width="600px">
</p>


Base de teste

Produtos de trabalho que podem ser usados como base de teste para teste de sistema incluem:
```
• Especificações de requisitos de sistema e software (funcionais e não-funcionais);

• Relatórios de análise de risco;

• Casos de uso;

• Épicos e histórias de usuários;

• Modelos de comportamento do sistema;

• Diagramas de estado;

• Sistema e manuais do usuário;
```

Objetos de teste

Os objetos de teste típicos para teste de sistema incluem:
```
• Aplicações;

• Sistemas de hardware e software;

• Sistemas operacionais;

• Sistema sob teste (SUT);

• Configuração do sistema e dados de configuração.

```

Defeitos típicos e falhas

Os defeitos e falhas típicas para o teste de sistema incluem:
```
• Cálculos incorretos;

• Comportamento funcional ou não funcional do sistema incorreto ou inesperado;

• Controle e/ou fluxos de dados dentro do sistema incorretos;

• Falha na execução correta e completa de tarefas funcionais de ponta a ponta;

• Falha do sistema em funcionar adequadamente no(s) ambiente(s) de produção;

• Falha do sistema para funcionar conforme descrito nos manuais do sistema e do usuário.
```
Abordagens e responsabilidades específicas

O teste de sistema deve focar no comportamento geral, funcional ou não, de ponta a ponta do sistema como um todo. O teste de sistema deve usar as técnicas mais apropriadas do sistema a ser testado. Testadores independentes geralmente realizam testes no sistema. Defeitos nas especificações podem levar a uma falta de compreensão ou desacordo sobre o comportamento esperado do sistema. Tais situações podem causar falsos positivos e falsos negativos, que perdem tempo e reduzem a eficácia da detecção de defeitos, respectivamente. O envolvimento precoce de testadores no refinamento da história do usuário ou em atividades de testes estáticos, como revisões, ajuda a reduzir a incidência de tais situações.


### Teste de aceite

O teste de aceite, como o teste do sistema, geralmente se concentra no comportamento e na capacidade de todo um sistema ou produto. 

Os objetivos do teste de aceite incluem:
```
• Estabelecer confiança na qualidade do sistema como um todo;

• Validar que o sistema está completo e funcionará como esperado;

• Verificar se os comportamentos funcionais e não-funcionais do sistema são os especificados.
```

O teste de aceite pode produzir informações para avaliar a situação do sistema para implantação e uso pelo cliente (usuário final). Os defeitos podem ser encontrados durante o teste de aceite, mas encontrar defeitos muitas vezes não é um objetivo, e encontrar um número significativo de defeitos durante o teste de aceite pode, em alguns casos, ser considerado um grande risco de projeto. O teste de aceite também pode satisfazer requisitos ou padrões legais ou regulatórios.

Formas comuns de testes de aceite incluem o seguinte:
```
• Teste de aceite do usuário;

• Teste de aceite operacional;

• Teste de aceite contratual e regulatório;

• Alfa teste e Beta
```
Teste de aceite do usuário (UAT)

O teste de aceite do sistema pelos usuários é tipicamente focado em validar a adequação do uso do sistema pelos usuários pretendidos em um ambiente operacional real ou simulado. O objetivo principal é desenvolver a confiança de que os usuários podem usar o sistema para atender às suas necessidades, atender aos requisitos e executar processos de negócios com o mínimo de dificuldade, custo e risco.

Teste de aceite operacional

O teste de aceite do sistema pelas operações ou pela equipe de administração de sistemas geralmente é realizado em um ambiente de produção (simulado).
Os testes se concentram em aspectos operacionais e podem incluir:

```
• Teste de backup e restauração;

• Instalar, desinstalar e atualizar;

• Recuperação de desastres;

• Gerenciamento de usuários;

• tarefas de manutenção;

• Carregamento de dados e tarefas de migração;

• Verifica vulnerabilidades
```
O principal objetivo do teste de aceite operacional é criar confiança de que os operadores ou administradores do sistema possam manter o sistema funcionando adequadamente para os usuários no ambiente operacional, mesmo sob condições excepcionais ou difíceis.

Teste de aceite contratual e regulatório

O teste de aceite contratual é realizado com base nos critérios de aceite de um contrato para desenvolver softwares específicos. Os critérios de aceite devem ser definidos quando as partes concordam com o contrato. O teste de aceite contratual é frequentemente realizado por usuários ou por testadores independentes.

O teste de aceite regulatório é realizado em relação a quaisquer regulamentos que devem ser seguidos, como governamentais, legais ou de segurança. O teste de aceite regulatório é frequentemente realizado por usuários ou por testadores independentes, às vezes com os resultados sendo testemunhados ou auditados por agências reguladoras.
O principal objetivo do teste de aceite contratual e regulatório é a criação de confiança de que a conformidade contratual ou regulatória foi alcançada.

Alfa teste e beta teste

Os “alfa” e “beta” teste são normalmente usados por desenvolvedores de software comercial de prateleira (COTS) que desejam obter feedback de usuários, clientes ou operadores em potencial ou existentes antes que o produto de software seja colocado no mercado. O alfa teste é realizado no site da organização em desenvolvimento, não pela equipe de desenvolvimento, mas por clientes em potencial, existentes, operadores, ou por uma equipe de teste independente. O beta teste é realizado
por clientes em potencial, existentes, operadores em seus próprios locais. O beta teste pode ocorrer após o alfa teste ou sem que este seja realizado.

Um objetivo dos testes alfa e beta é a construção da confiança entre os clientes ou operadores de que podem usar o sistema em condições normais no dia a dia para atingir seus objetivos com o mínimo de dificuldade, custo e risco. Outro objetivo pode ser a detecção dos defeitos relacionados às condições e ambiente(s) em que o sistema será utilizado, especialmente quando essas são difíceis de replicar pela equipe de desenvolvimento. 

<p align="center">
  <img alt="nivel de teste" src="https://github.com/rxaviersantos/software-testing/assets/85380530/f0705d03-fc84-4d1e-b1ce-eaa385b3412d" "height="400px" width="600px">
</p>

Base de teste

Os exemplos de produtos de trabalho que podem ser usados como base de teste para qualquer forma de teste de aceite incluem:

```
• Processos de negócios;

• Requisitos do usuário ou de negócios;

• Regulamentos, contratos legais e normas;

• Casos de uso;

• Requisitos de sistema;

• Documentação do sistema ou usuário;

• Procedimentos de instalação;

• Relatórios de análise de risco.
```

Além disso, como base de teste para derivar casos de teste para testes de aceite operacional, um ou mais dos seguintes produtos de trabalho podem ser usados:

```
• Procedimentos de backup e restauração;

• Procedimentos de recuperação de desastres;

• Requisitos não-funcionais;

• Documentação de operações;

• Instruções de implantação e instalação;

• Metas de performance;

• Pacotes de banco de dados;

• Normas ou regulamentos de segurança.
```

Objetos de teste típicos

Os objetos de teste típicos para qualquer forma de teste de aceite incluem:

```
• Sistema sob teste;

• Configuração do sistema e dados de configuração;

• Processos de negócios para um sistema totalmente integrado;

• Sistemas de recuperação e hot sites (para continuidade de negócios e testes de recuperação de desastres);

• Processos operacionais e de manutenção;

• Formulários;

• Relatórios;

• Dados de produção existentes e convertidos.
```


