# Tipos de teste

Um tipo de teste é um grupo de atividades de teste destinado a testar características específicas de um sistema de software, ou parte de um sistema, com base em objetivos de teste específicos. Tais
objetivos podem incluir:

> • Avaliar as características de qualidade funcional, tais como integridade, correção e adequação;
>
> • Avaliar as características de qualidade não-funcionais, como confiabilidade, eficiência de performance, segurança, compatibilidade e usabilidade;
>
> • Avaliar se a estrutura ou arquitetura do componente ou sistema está correta, completa e especificada;
>
> • Avaliar os efeitos das alterações, como a confirmação da correção dos defeitos (teste de confirmação) e procurar alterações não intencionais no comportamento como resultado de alterações no software ou no ambiente (teste de regressão).

### Teste funcional

O teste funcional de um sistema envolve testes que avaliam as funções que o sistema deve executar. Os requisitos funcionais podem ser descritos em produtos de trabalho, como especificações de requisitos, de negócios, épicos, histórias de usuários, casos de uso ou especificações funcionais, podendo ainda não estarem documentados. As funções são “o que” o sistema deve fazer.
Os testes funcionais devem ser realizados em todos os níveis de teste (p.e, testes para componentes podem ser baseados em uma especificação de componente), embora o foco possa ser diferente em cada nível,

O teste funcional considera o comportamento do software, portanto, técnicas caixa-preta podem ser usadas para derivar condições de teste e casos de teste para a funcionalidade do componente ou sistema. 

### Teste não funcional

Os testes não-funcionais de um sistema avaliam as características de sistemas e de softwares, como usabilidade, eficiência de performance ou segurança. O teste não funcional é o teste de "quão bem" o sistema se comporta.

Ao contrário das percepções errôneas comuns, o teste não-funcional pode e geralmente deve ser realizado em todos os níveis de teste, e feito o mais cedo possível. A descoberta tardia de defeitos não-funcionais pode ser extremamente perigosa para o sucesso de um projeto.

As técnicas caixa-preta podem ser usadas para derivar condições de teste e casos de teste para testes não-funcionais. Por exemplo, a análise do valor limite pode ser usada para definir as condições de tensão para testes de performance.

A eficácia dos testes não-funcionais pode ser medida por meio de cobertura não funcional. A cobertura não funcional é a medida em que algum tipo de elemento não funcional foi exercido por testes e é expressa como uma porcentagem do tipo de elemento a ser coberto. Usando a rastreabilidade entre testes e dispositivos suportados para um aplicativo móvel, a porcentagem de dispositivos que são abordados pelo teste de compatibilidade pode ser calculada, identificando potencialmente as lacunas de cobertura.

A modelagem e execução de testes não-funcionais podem envolver habilidades ou conhecimentos especiais, como o conhecimento das fraquezas inerentes a um projeto ou tecnologia ou a uma base de usuários específica.
 
### Teste caixa-branca

O teste caixa-branca é derivado de testes com base na estrutura interna ou na implementação do sistema. A estrutura interna pode incluir código, arquitetura, fluxos de trabalho e fluxos de dados dentro do sistema.

A eficácia dos testes caixa-branca pode ser medida através da cobertura estrutural. A cobertura estrutural é a extensão em que algum tipo de elemento estrutural foi testado e é expresso como uma porcentagem do tipo de elemento a ser coberto.

No nível de teste de componente, a cobertura de código é baseada na porcentagem do código do componente que foi testado e pode ser medida em termos de aspectos diferentes do código (itens de cobertura), como a porcentagem de instruções executáveis que foram testadas no componente ou a porcentagem dos resultados da decisão que foram testados. Esses tipos de cobertura são chamados coletivamente de cobertura de código. No nível de teste de integração de componentes, o teste caixa-branca pode ser baseado na arquitetura do sistema, como interfaces entre componentes, e a cobertura estrutural pode ser medida em termos da porcentagem de interfaces exercidas pelos testes.

A modelagem e a execução do teste caixa-branca podem envolver habilidades ou conhecimentos especiais, como a maneira como o código é construído como os dados são armazenados e como usar ferramentas de cobertura interpretando corretamente seus resultados.










