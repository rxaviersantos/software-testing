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