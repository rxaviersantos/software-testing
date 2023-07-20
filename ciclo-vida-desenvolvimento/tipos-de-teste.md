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

<p align="center">
  <img alt="nivel de teste" src="https://github.com/rxaviersantos/software-testing/assets/85380530/6e2d1bda-340d-4b3d-bef1-382095ae0165" "height="400px" width="600px">
</p>



###  Teste relacionado à mudança

Quando são feitas alterações em um sistema, seja para corrigir um defeito ou por causa de uma funcionalidade nova ou variável, deve-se testar para confirmar se as alterações corrigiram o defeito ou implementaram a funcionalidade corretamente e não causaram consequências adversas imprevistas.

*Teste de confirmação:*

Depois que um defeito é corrigido, o software pode ser testado com todos os casos de teste que falharam devido ao defeito, que devem ser executados novamente na nova versão do software. O software também pode ser testado com novos testes se, por exemplo, para um defeito estiver faltando uma funcionalidade. No mínimo, as etapas para reproduzir as falhas causadas pelo defeito devem ser executadas novamente na nova versão do software. A finalidade de um teste de confirmação é confirmar se o defeito original foi corrigido com sucesso.

*Teste de regressão:*

É possível que uma alteração feita em uma parte do código, seja uma correção ou outro tipo de alteração, possa afetar acidentalmente o comportamento de outras partes do mesmo código, seja dentro do mesmo componente, em outros componentes do código, no mesmo sistema, ou em outros sistemas. As alterações podem incluir alterações no ambiente, como uma nova versão de um sistema operacional ou sistema de gerenciamento de banco de dados. Tais efeitos colaterais não intencionais são chamados de regressões. O teste de regressão envolve a execução de testes para detectar esses efeitos colaterais indesejados.

O teste de confirmação e o teste de regressão são realizados em todos os níveis de teste.

Especialmente em ciclo de vida de desenvolvimento iterativo e incremental (p. ex., Ágil), novos recursos, alterações nos recursos existentes e recompilação de código resultam em alterações frequentes no código, o que também requer testes relacionados a estas alterações. Devido à natureza evolutiva do sistema, os testes de confirmação e regressão são muito importantes. Isso é particularmente relevante para os sistemas da Internet das Coisas (IoT), nos quais objetos individuais (p. ex., dispositivos) são atualizados ou substituídos com frequência.

Os conjuntos de testes de regressão são executados muitas vezes e geralmente evoluem lentamente, portanto, o teste de regressão é um forte candidato à automação. A automação desses testes deve começar no início do projeto. 

<p align="center">
  <img alt="nivel de teste" src="https://github.com/rxaviersantos/software-testing/assets/85380530/bd52f983-77fc-4a02-81b8-41761ccfc1c0" "height="400px" width="600px">
</p>

### Tipos e níveis de teste

É possível executar qualquer um dos tipos de teste mencionados acima em qualquer nível de teste. Para ilustrar, exemplos de testes funcionais, não-funcionais, caixa-branca e relacionados a alterações serão fornecidos em todos os níveis de teste, para um aplicativo bancário, começando com testes funcionais:

> • No teste de componente, os testes são modelados com base em como um componente deve calcular os juros compostos;
>
> • No teste de integração de componentes, os testes são modelados com base em como os dados da conta capturada na interface do usuário são transmitidas para a lógica de negócios;
>
> • No teste de sistema, os testes são modelados com base em como os titulares de conta podem solicitar uma linha de crédito em suas contas correntes;
>
> • No teste de integração de sistemas, os testes são modelados com base em como o sistema usa um micro serviço externo para verificar a pontuação de crédito de um titular de conta;
>
> • No teste de aceite, os testes são modelados com base em como o banqueiro manipula a aprovação ou não de um pedido de crédito

Exemplos de testes não-funcionais:

> •  No teste de componente, os testes de performance são modelados para avaliar o número de ciclos de CPU necessários para realizar um cálculo complexo de juros total;
>
> •  No teste de integração de componentes, os testes de segurança são modelados para vulnerabilidades de estouro de buffer devido aos dados transmitidos da interface do usuário para a lógica de negócios;
>
> • No teste de sistema, os testes de portabilidade são modelados para verificar se a camada de apresentação funciona em todos os navegadores e dispositivos móveis suportados;
>
> • No teste de integração de sistemas, os testes de confiabilidade são modelados para avaliar a robustez do sistema se o micro serviço de pontuação de crédito não responder;
>
> • No teste de aceite, os testes de usabilidade são modelados para avaliar a acessibilidade da interface de processamento de crédito do banco para pessoas com deficiências

Exemplos de testes caixa-branca:

> • No teste de componentes, os testes são modelados para obter uma cobertura completa de instruções e decisões (capítulo 4.3) para todos os componentes que executam cálculos financeiros;
> 
> • No teste de integração de componentes, os testes são modelados para exercitar como cada tela na interface do navegador passa os dados para a próxima tela e para a lógica de negócios;
> 
> • No teste de sistema, os testes são modelados para cobrir sequências de páginas da web que podem ocorrer durante um aplicativo de linha de crédito;
> 
> • No teste de integração do sistema, os testes são modelados para exercer todos os possíveis tipos de consulta enviados ao micro serviço de pontuação de crédito;
> 
> • No teste de aceite, os testes são modelados para cobrir todas as estruturas de arquivos de dados financeiros suportados e intervalos de valores para transferências bancárias para bancos.

Exemplos de testes relacionados a mudanças:

> • No teste de componentes, os testes de regressão automatizados são modelados para cada componente e incluídos na estrutura de integração contínua;
> 
>  • No teste de integração de componentes, os testes são modelados para confirmar as correções dos defeitos relacionados à interface, à medida que as correções são verificadas no repositório de código;
> 
>  • No teste do sistema, todos os testes para um determinado fluxo de trabalho são executados novamente se qualquer tela desse fluxo de trabalho for alterada;
> 
>  • No teste de integração do sistema, os testes do aplicativo interagindo com o micro serviço de pontuação de crédito são executados diariamente como parte da implantação contínua desse micro serviço;
> 
>  • No teste de aceite, todos os testes com falhas anteriores são executados novamente após a correção de um defeito encontrado no teste de aceite.

Exemplos de tipos e níveis de teste

<p align="center">
  <img alt="nivel de teste" src="https://github.com/rxaviersantos/software-testing/assets/85380530/e7966aa9-f45f-41ec-aedf-3bfe18d38acf" "height="400px" width="600px">
</p>


Não é necessário, para todos os softwares, ter todos os tipos de testes representados em todos os níveis. No entanto, é importante executar os tipos de teste aplicáveis em cada nível, especialmente no nível mais antigo em que o tipo de teste ocorre.

<p align="center">
  <img alt="nivel de teste" src="https://github.com/rxaviersantos/software-testing/assets/85380530/88b9f4cc-6d4b-49fc-834b-bb8f89434853" "height="400px" width="600px">
</p>









