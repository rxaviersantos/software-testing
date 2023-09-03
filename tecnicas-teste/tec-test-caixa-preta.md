# Técnicas de teste caixa-preta


### Particionamento de equivalência

O particionamento de equivalência divide os dados em partições (também conhecidas como classes de equivalência), de tal forma que todos os membros de uma determinada partição deve ser processado da mesma maneira. Existem partições de
equivalência para valores válidos e inválidos.

> • Valores válidos são valores que devem ser aceitos pelo componente ou sistema. Uma partição de equivalência contendo este tipo de valores é chamada de "partição de equivalência válida".
> 
> • Valores inválidos são valores que devem ser rejeitados pelo componente ou sistema. Uma partição de equivalência contendo estes valores é chamada de "partição de equivalência inválida".
>
> • As partições podem ser identificadas para qualquer elemento de dados relacionado ao objeto de teste, incluindo entradas, saídas, valores internos, valores relacionados a tempo (p. ex., antes ou depois de um evento) e para parâmetros de interface (p. ex., componentes integrados sendo testados durante o teste de integração).
> 
> • Se necessário, qualquer partição pode ser dividida em subpartições.
> 
> • Cada valor deve pertencer a uma e apenas uma partição de equivalência.
> 
> • Quando partições de equivalência inválidas são usadas em casos de teste, elas devem ser testadas individualmente, ou seja, não podem ser combinadas com outras partições de equivalência inválidas, para garantir que as falhas não sejam mascaradas. Falhas podem ser mascaradas quando várias falhas ocorrem ao mesmo tempo, mas apenas uma é visível, fazendo com que as outras falhas não sejam detectadas.
>

Para obter uma cobertura de 100% com essa técnica, os casos de teste devem cobrir todas as partições identificadas (incluindo partições inválidas) usando no mínimo um valor de cada partição. A cobertura é medida como o número de partições de equivalência testadas por pelo menos um valor, dividido pelo número total de partições de equivalência identificadas, normalmente expresso como uma porcentagem. O particionamento de equivalência é aplicável em todos os níveis de teste.
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)
### Exemplo de aplicações das diretrizes 

<p align="">
  <img alt="" src="https://github.com/rxaviersantos/software-testing/assets/85380530/89baf17f-2874-4bf9-af0d-9580ed589f68" " height="400px" width="620px"> </p>

-------
### Partição de equivalência 

<p align="">
  <img alt="" src="https://github.com/rxaviersantos/software-testing/assets/85380530/566a1d68-8268-4bf6-9a9a-6f4bc0ba6cd6" " height="400px" width="620px"> </p>
  
### Exercício

<p align="">
  <img alt="" src="https://github.com/rxaviersantos/software-testing/assets/85380530/6788c167-44cd-41f9-9e85-e77fa0de17d7" " height="400px" width="620px"> </p>


# Análise de valor limite

A análise de valor limite é uma extensão do particionamento de equivalência, mas só pode ser usada quando a partição é ordenada, consistindo em dados numéricos ou sequenciais. Os valores mínimo e máximo (ou primeiro e último valores) de uma partição são seus valores limites.

Por exemplo, suponha que um campo de entrada aceite um único valor inteiro como uma entrada,
usando um teclado para limitar que entradas não inteiras sejam impossíveis.

O intervalo válido é de 1 a 5, inclusive. Portanto, existem três partições de equivalência: inválidas (muito baixas); válido; inválido (muito alto). 

Para a partição de equivalência válida, os valores limites são 1 e 5. Para a partição inválida (muito alta), os valores limites são 6 e 9. Para a partição inválida (muito baixa), existe apenas um valor limite, 0, porque esta é uma partição com apenas um membro.

No exemplo acima, identificamos dois valores limites por limite. O limite entre inválido (muito baixo) e válido fornece os valores de teste 0 e 1. A fronteira entre válido e inválido (muito alto) fornece os valores de teste 5 e 6. Algumas variações dessa técnica podem identificar três valores de limite por limite de dados: o valor anterior ao limite, o próprio valor limite e o imediatamente superior a ele. 

No exemplo anterior, usando valores limites de três pontos, os valores do limite inferior são 0, 1 e 2, e os valores dos limites superiores são 4, 5 e 6.
O comportamento nos limites das partições de equivalência é mais provável que seja incorreto do que o comportamento dentro das partições. É importante lembrar que os limites especificados e implementados podem ser deslocados para posições acima ou abaixo de suas posições pretendidas, podem ser omitidos por completo ou podem ser complementados com limites adicionais indesejados. A análise e o teste do valor-limite revelarão quase todos esses defeitos forçando o software a mostrar comportamentos de uma partição diferente daquela à qual o valor limite deveria pertencer.

A análise de valor limite pode ser aplicada em todos os níveis de teste. Essa técnica é geralmente usada para testar requisitos que exigem um intervalo de números (incluindo datas e horas). A cobertura de limite para uma partição é medida como o número de valores limites testados, dividido pelo número total de valores de teste de limite identificados, normalmente expressos como uma porcentagem.

### Exemplo Analise de valor limite 

<p align="">
  <img alt="" src="https://github.com/rxaviersantos/software-testing/assets/85380530/faee09e3-2d38-43e8-950d-ed31b903dbed" " height="400px" width="620px"> </p>

<p align="">
  <img alt="" src="https://github.com/rxaviersantos/software-testing/assets/85380530/cdc949ee-502a-4729-83dc-0a8c9cb46534" " height="400px" width="620px"> </p>

<p align="">
  <img alt="" src="https://github.com/rxaviersantos/software-testing/assets/85380530/152edcac-869e-444f-be4e-4941aba3b855" " height="400px" width="620px"> </p>

 
# Teste de tabela de decisão

Técnicas de teste combinatórias são úteis para testar a implementação de requisitos do sistema que especificam como diferentes condições de combinações levam à resultados diferentes. Uma abordagem para esse teste é o teste de tabela de decisão.

As tabelas de decisão são uma boa maneira de registrar regras de negócios complexas que um
sistema deve implementar. Ao criar tabelas de decisão, o testador identifica as condições
(geralmente entradas) e as ações resultantes (geralmente saídas) do sistema. Estes formam as linhas da tabela, geralmente com as condições no topo e as ações na parte inferior. Cada coluna
corresponde a uma regra de decisão que define uma combinação exclusiva de condições que resultam na execução das ações associadas a essa regra. Os valores das condições e ações são geralmente mostrados como valores booleanos (verdadeiro ou falso) ou valores discretos (p. ex., vermelho, verde, azul), mas também podem ser números ou intervalos numéricos. Esses diferentes tipos de condições e ações podem ser encontrados juntos na mesma tabela.

A notação comum nas tabelas de decisão é a seguinte:

    • “S”: significa que a condição seja verdadeira (também pode ser mostrada como “V” ou “1”)
    
    • “N”: significa que a condição seja falsa (também pode ser mostrada como “F” ou “0”)
    
    • “-“: significa que o valor da condição não importa (também pode ser mostrado como “N/A”)

Para ações:


    • “X” significa que a ação deve ocorrer (também pode ser mostrada como “S” ou “V” ou “1”)
    
    • Em branco significa que a ação não deve ocorrer (também pode ser mostrada como “-“ ou “N” ou “F” ou “0”)

Uma tabela de decisão completa tem colunas suficientes para abranger todas as combinações de condições. A tabela pode ser reduzida excluindo-se as colunas contendo combinações impossíveis, colunas contendo possíveis combinações de condições, mas inviáveis, e colunas que testam as combinações de condições que não afetam o resultado.  

O padrão comumente utilizado para a cobertura mínima para o teste de tabela de decisão é ter pelo menos um caso de teste por regra de decisão na tabela. Isso normalmente envolve cobrir todas as combinações de condições. A cobertura é medida como o número de regras de decisão testadas por pelo menos um caso de teste, dividido pelo número total de regras de decisão, normalmente expressa como uma porcentagem.

O poder do teste por tabela de decisão é que ela ajuda a identificar todas as combinações importantes de condições, algumas das quais poderiam ser negligenciadas. Também ajuda a encontrar quaisquer lacunas nos requisitos. Pode ser aplicada a todas as situações em que o comportamento do software depende de uma combinação de condições, em qualquer nível de teste.

Uma tabela de decisão é composta de:
```
- Uma área de condições, onde são relacionadas as condições que devem ser verificadas para que seja executado um conjunto de ações;
- Uma área de ações, que exibe o conjunto de ações que deve ser executado caso um determinado conjunto de condições ocorra;
- Regras de decisão, representadas pelas colunas, que apresentam a combinação das condições com as ações a serem executadas.
```
<p align="">
  <img alt="" src="https://github.com/rxaviersantos/software-testing/assets/85380530/16998cfb-2ae4-453e-b43a-51fb6476b3e6" " height="280px" width="480px"> </p>

 Na tabela acima, definimos que para ser considerado exame especial, o avaliado teria que ter mais de 40 anos ou cargo de chefia com mais de 2 anos no cargo.

Para que seja definida a quantidade de regras da tabela, basta que multipliquemos a quantidade de respostas possíveis de cada condição.

```
Exemplo:

Condição 1 sim/não:     = 2

Condição 2 sim/não:     = 2

Condição 3 sim/não:     = 2

Quantidade de Regras:   = 2 x 2 x 2 = 8
```

# Teste de transição de estado

Componentes ou sistemas podem responder de maneira diferente a um evento, dependendo das
condições atuais ou do histórico anterior (p. ex., os eventos que ocorreram desde que o sistema foi inicializado). O histórico anterior pode ser resumido usando o conceito de estados. Um diagrama de transição de estado mostra os possíveis estados do software, bem como a forma como o software entra, sai e transita entre os estados. Uma transição é iniciada por um evento (p. ex., entrada do usuário de um valor em um campo). O evento resulta em uma transição. Se o mesmo evento pode resultar em duas ou mais transições diferentes do mesmo estado, esse evento pode ser qualificado por uma condição de proteção. A mudança de estado pode fazer com que o software execute uma ação (p. ex., gerar uma mensagem de cálculo ou de erro).

Uma tabela de transição de estado mostra todas as transições válidas e potencialmente inválidas entre estados, bem como os eventos, condições de proteção e ações resultantes para transições válidas. Os diagramas de transição de estado normalmente mostram apenas as transições válidas e excluem as transições inválidas.

Os testes podem ser projetados para cobrir uma sequência típica de estados, para exercitar todos os estados, para exercitar cada transição, para executar sequências específicas de transições ou para testar transições inválidas.

O teste de transição de estado é usado em aplicativos baseados em menus e é amplamente usado na indústria de software de prateleira. A técnica também é adequada para modelar um cenário de negócios com estados específicos ou para testar a navegação na tela. O conceito de um estado é abstrato - pode representar algumas linhas de código ou um processo de negócios inteiro.

A cobertura é geralmente medida como o número de estados identificados ou transições testadas, dividido pelo número total de estados ou transições identificadas no objeto de teste, normalmente expresso como uma porcentagem. Para obter mais informações sobre os critérios de cobertura para testes de transição de estado.


<p align="center">
  <img alt="nivel de teste" src="https://github.com/rxaviersantos/software-testing/assets/85380530/b353a6b0-7b4d-49c0-bc8d-87266ffec08c" "height="300px" width="700px">
</p>

# Teste de caso de uso

Os testes podem ser derivados de casos de uso, que são uma maneira específica de projetar interações com itens de software, incorporando requisitos para as funções de software representadas pelos casos de uso. Os casos de uso estão associados a atores (usuários humanos, hardware externo ou outros componentes ou sistemas) e assuntos (o componente ou sistema ao qual o caso de uso é aplicado).

Cada caso de uso especifica algum comportamento que um assunto pode realizar em colaboração com um ou mais atores. Um caso de uso pode ser descrito por interações e atividades, bem como condições prévias, pós-condições e linguagem natural, quando apropriado.  Interações entre os atores e o sujeito podem resultar em mudanças no estado do sujeito. As interações podem ser representadas graficamente por fluxos de trabalho, diagramas de atividades ou modelos de processos de negócios.

Um caso de uso pode incluir possíveis variações de seu comportamento básico, incluindo comportamento excepcional e tratamento de erros (resposta do sistema e recuperação de erros de desenvolvimento, aplicação e comunicação, p.e., resultando em uma mensagem de erro). Os testes são projetados para exercitar os comportamentos definidos (básico, excepcional ou alternativo e tratamento de erros). A cobertura pode ser medida pela porcentagem de comportamentos de casos de uso testados dividida pelo número total de comportamentos de casos de uso, normalmente expressos como uma porcentagem.



