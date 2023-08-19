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

Uma tabela de decisão completa tem colunas suficientes para abranger todas as combinações de
condições. A tabela pode ser reduzida excluindo-se as colunas contendo combinações impossíveis, colunas contendo possíveis combinações de condições, mas inviáveis, e colunas que testam as combinações de condições que não afetam o resultado. Para obter mais informações sobre como recolher as tabelas de decisão. 

O padrão comumente utilizado para a cobertura mínima para o teste de tabela de decisão é ter pelo
menos um caso de teste por regra de decisão na tabela. Isso normalmente envolve cobrir todas as combinações de condições. A cobertura é medida como o número de regras de decisão testadas por pelo menos um caso de teste, dividido pelo número total de regras de decisão, normalmente expressa como uma porcentagem.

O poder do teste por tabela de decisão é que ela ajuda a identificar todas as combinações importantes de condições, algumas das quais poderiam ser negligenciadas. Também ajuda a encontrar quaisquer lacunas nos requisitos. Pode ser aplicada a todas as situações em que o comportamento do software depende de uma combinação de condições, em qualquer nível de teste.
