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



