# Técnicas de teste baseadas na experiência

Ao aplicar as técnicas de teste baseadas na experiência, os casos de teste são derivados da habilidade
e intuição do testador e de sua experiência com aplicativos e tecnologias semelhantes. Essas técnicas podem ser úteis na identificação de testes que não foram facilmente identificados por outras técnicas mais sistemáticas. Dependendo da abordagem e experiência do testador, essas técnicas podem alcançar graus de cobertura e eficácia amplamente variados. A cobertura pode ser difícil de avaliar e pode não ser mensurável com essas técnicas. Técnicas baseadas em experiência comumente usadas são discutidas nas seções seguintes.

### Suposição de erro

A suposição de erro é um técnica usada para prever a ocorrência de erros, defeitos e falhas, com base no conhecimento do testador, incluindo: 

• Como o aplicativo funcionou no passado;
• Que tipos de erro tendem a ser cometidos;
• Falhas ocorridas em outros aplicativos.

Uma abordagem metódica para a técnica de suposição de erro é criar uma lista de possíveis erros, defeitos e falhas e modelar os testes que exporão essas falhas e os defeitos que as causaram. Esses erros, defeitos, listas de falhas podem ser construídos com base na experiência, nos dados de defeitos e falhas ou no conhecimento comum sobre o motivo da falha do software.


### Teste exploratório

Nesta técnica, os testes informais (não pré-definidos) são modelados, executados, registrados e
avaliados dinamicamente durante a execução do teste. Os resultados do teste são usados para aprender mais sobre o componente ou sistema e para criar testes para as áreas que podem precisar
de mais testes. 

Às vezes, o teste exploratório é realizado usando testes baseados em sessão para estruturar as atividades de teste. No teste baseado em sessão, o teste exploratório é conduzido dentro de uma janela de tempo definida, e o testador usa um termo de teste contendo objetivos de teste para orientar o teste. O testador pode usar folhas de sessão de teste para documentar as etapas seguidas e as descobertas feitas.

O teste exploratório é mais útil quando há poucas ou inadequadas especificações ou pressão de tempo significativa nos testes. O teste exploratório também é útil para complementar outras técnicas de teste mais formais.

O teste exploratório está fortemente associado a estratégias de teste reativo (ver capítulo 5.2.2). O teste exploratório pode incorporar o uso de outras técnicas de caixa-preta, caixa-branca e experiência.
