# Níveis de teste 

Os níveis de teste são grupos de atividades de teste que são organizados e gerenciados juntos. Cada
nível de teste é uma instância do processo de teste, consistindo nas atividades descritas, executadas em relação ao software em um determinado nível de desenvolvimento, desde as
unidades individuais ou componentes até os sistemas completos ou, quando aplicável, em sistemas
de sistemas. Os níveis de teste estão relacionados com outras atividades dentro do ciclo de vida de
desenvolvimento de software. Os níveis de teste usados neste documento são:

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






