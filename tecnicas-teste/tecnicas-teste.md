# Categorias de técnicas de teste

O objetivo de uma técnica de teste, incluindo as discutidas nesse capítulo, é ajudar a identificar as
condições de teste, os casos de teste e os dados de teste.

A escolha de quais técnicas de teste usar depende de vários fatores, incluindo:

> • Complexidade do componente ou do sistema;
> 
> • Normas regulatórias;
> 
> • Requisitos contratuais ou do cliente;
> 
> • Níveis e tipos de risco;
> 
> • Documentação disponível;
> 
> • Conhecimento e habilidades do testador;
> 
> • Ferramentas disponíveis;
> 
> • Tempo e orçamento;
> 
> • Modelo de ciclo de vida de desenvolvimento de software.
> 
> • Os tipos de defeitos esperados no componente ou sistema.


Algumas técnicas são mais aplicáveis em determinadas situações e níveis de teste, outras são aplicáveis em todos os níveis de teste. Ao criar casos de teste, os testadores geralmente usam uma combinação de técnicas de teste para obter os melhores resultados do esforço de teste. O uso de técnicas de teste nas atividades de análise do teste, modelagem de teste e implementação do teste pode variar de muito informal (pouca ou nenhuma documentação) a muito formal. O nível adequado da formalidade depende do contexto dos testes, incluindo a maturidade dos processos de teste e de desenvolvimento, das restrições de tempo, dos requisitos normativos ou de segurança, do conhecimento e das habilidades das pessoas envolvidas e do modelo de ciclo de vida de desenvolvimento de software que está sendo seguido. 

### Categorias de técnicas de teste e suas características

As técnicas de teste caixa-preta (também chamadas de técnicas comportamentais ou baseadas no comportamento) são fundamentadas em uma análise da base de teste apropriada (p. ex., documentos de requisitos formais, especificações, casos de uso, histórias de usuários ou processos de negócios). Essas técnicas são aplicáveis a testes funcionais e não-funcionais. As técnicas de teste caixa-preta se concentram nas entradas e saídas do objeto de teste sem referência a sua estrutura interna.

As técnicas de teste caixa-branca (também chamadas de técnicas estruturais ou baseadas na estrutura) são baseadas em uma análise da arquitetura, do detalhamento do projeto, da estrutura interna ou o código do objeto de teste. Ao contrário das técnicas de teste caixa-preta, as técnicas de teste caixa-branca concentram-se na estrutura e no processamento dentro do objeto de teste.

As técnicas de teste baseadas na experiência aproveitam a conhecimento dos desenvolvedores, testadores e usuários para projetar, implementar e executar os testes. Estas técnicas são frequentemente combinadas com técnicas de teste caixa-preta e caixa-branca.

As características comuns das técnicas de teste caixa-preta incluem o seguinte:

> • As condições de teste, os casos de teste e os dados de teste são derivados de uma base de teste que pode incluir requisitos de software, especificações, casos de uso e histórias de usuários;
> 
> • Os casos de teste podem ser usados para detectar lacunas entre os requisitos e as suas implementações, bem como desvios nos requisitos;
> 
> • A cobertura é medida com base nos itens testados na base de teste e na técnica aplicada nesta base.

As características comuns das técnicas de teste caixa-branca incluem o seguinte:

> • As condições de teste, os casos de teste e os dados de teste são derivados de uma base de teste que pode incluir código, arquitetura de software, o detalhamento do projeto ou qualquer outra fonte de informação relacionada à estrutura do software;
> 
> • A cobertura é medida com base nos itens testados em uma estrutura selecionada (p.ex., o código ou interfaces) e a técnica aplicada à base de teste.

As características comuns das técnicas de teste baseadas na experiência incluem o seguinte:

As condições de teste, os casos de teste e os dados de teste são derivados de uma base de teste que pode incluir conhecimento e a experiência de testadores, desenvolvedores,
usuários e stakeholders.

Esse conhecimento e experiência inclui o uso esperado do software, seu ambiente, possíveis defeitos e a distribuição desses defeitos




<p align="center">
  <img alt="nivel de teste" src="https://github.com/rxaviersantos/software-testing/assets/85380530/8689f5fe-db85-4bd9-bcd3-a045cdcdb09a" "height="300px" width="700px">
</p>


