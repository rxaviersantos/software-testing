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
