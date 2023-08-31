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