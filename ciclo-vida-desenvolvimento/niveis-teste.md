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


O teste de componente geralmente é realizado isoladamente do resto do sistema, dependendo do
modelo de ciclo de vida de desenvolvimento de software e de sistema, que pode exigir objetos
simulados, virtualização de serviços, estrutura, simuladores e controladores. O teste de componente
pode cobrir funcionalidade (p. ex., correção de cálculos), características não-funcionais (p. ex., busca
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
