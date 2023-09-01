# Técnicas de teste caixa-branca

O teste caixa-branca é baseado na estrutura interna do objeto de teste. As técnicas de teste caixabranca podem ser usadas em todos os níveis de teste, mas as duas técnicas relacionadas a códigos discutidas neste capítulo são as mais comumente usadas no nível de teste de componente. Existem técnicas mais avançadas que são usadas em alguns ambientes de segurança crítica, de missão crítica ou de alta integridade para obter uma cobertura mais completa, mas essas não são discutidas aqui. 

### Teste e cobertura de instruções

Esta técnica testa as instruções executáveis do código. A cobertura é medida como o número de
instruções executadas pelos testes dividido pelo número total de instruções executáveis existentes, normalmente expresso como uma porcentagem.

### Teste e cobertura de decisão

Esta técnica testa as decisões existentes no código e o código executado com base nos resultados decisão. Para fazer isso, os casos de teste seguem os fluxos de controle que ocorrem de um ponto de decisão (p. ex., para uma instrução IF, um para o resultado verdadeiro e outro para o resultado falso; para uma instrução CASE, os casos de teste seriam necessários para todos os possíveis resultados, incluindo o resultado padrão).

A cobertura é medida como o número de resultados de decisão executados pelos testes dividido
pelo número total de resultados de decisão no objeto de teste, normalmente expresso como uma
porcentagem.

### O valor da instrução e teste de decisão

Quando a cobertura de 100% das instruções é alcançada, garante-se que todas as instruções executáveis no código tenham sido testadas pelo menos uma vez, mas não garante que toda a lógica de decisão tenha sido testada. Das duas técnicas caixa-branca discutidas neste syllabus, o teste de instrução pode fornecer menos cobertura do que o teste de decisão. Quando uma cobertura de decisão de 100% é alcançada, representa-se que todos os resultados de decisão foram testados, o que inclui testar os resultados verdadeiro e falso, mesmo quando não há
uma instrução falsa explícita (p. ex., no caso de uma instrução IF sem outra no código). A cobertura de instrução ajuda a encontrar defeitos no código que não foi exercido por outros testes. A cobertura de decisão ajuda a encontrar defeitos no código, em que outros testes não obtiveram resultados verdadeiros ou falsos.

Atingir 100% de cobertura de decisão garante 100% de cobertura de instrução (mas não vice-versa).
