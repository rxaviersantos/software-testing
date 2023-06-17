# Teste dinâmico 

O teste dinâmico é a execução de um componente ou sistema, que é executado para analisar o comportamento do código, que inclui o teste do software para os valores de entrada e de saída que são analisados. 


## Principais níveis de teste dinâmico

> Teste de Componente: 

O teste de componente é focado na verificação individual de cada componente do sistema. 
```` 
Exemplo  
- Teste de unidade 
````
> Teste de Integração: 

Teste de dois ou mais componentes do sistema (integração pequena) e integração de sistemas (integração grande).
````
Exemplo
- Teste de API 
````
> Teste de Sistema 

Verifica o sistema como um todo atendendo os requisitos especificados.
````
Exemplo 

- Teste de sistema camada de usuário, mobile, desktop etc...
````
> Teste de Aceitação 

Verifica se o sistema está pronto para ser entregue ao cliente ou usuário final.
````
Exemplo 

- Teste usuário ou cliente que homologa o software.
````
# Teste Estático 

O teste estático é um tipo de Teste de software método que é executado para verificar os defeitos no software sem realmente executar o código do aplicativo de software.

O teste estático é realizado no estágio inicial do desenvolvimento para evitar erros, pois é mais fácil encontrar fontes de falhas e pode ser corrigido facilmente.

Os erros que não podem ser encontrados usando o Teste Dinâmico podem ser facilmente encontrados pelo Teste Estático.

## Técnicas de teste estático:

Existem principalmente duas técnicas de tipo usadas no teste estático:

### Revisão 

Na revisão de testes estáticos, há um processo ou técnica que é executada para encontrar os possíveis defeitos no design do software. 

É um processo para detectar e remover erros e defeitos nos diferentes documentos de suporte, como especificações de requisitos de software. As pessoas examinam os documentos e resolvem erros, redundâncias e ambiguidades.

A revisão é de quatro tipos:

> - Informal: Na revisão informal, o criador dos documentos coloca o conteúdo na frente do público e todos dão sua opinião e, portanto, os defeitos são identificados no estágio inicial.

> - Passo a passo: É basicamente realizado por uma pessoa ou especialista experiente para verificar os defeitos, para que não haja mais problemas na fase de desenvolvimento ou teste.

> - Revisão por pares: Revisão por pares significa verificar documentos um do outro para detectar e corrigir os defeitos. É basicamente feito em uma equipe de colegas.

> - Inspeção: A inspeção é basicamente a verificação do documento, a autoridade superior, como a verificação das especificações de requisitos de software ( SRS ).



# Diferença entre testes estáticos e dinâmicos

> O teste estático é feito sem a execução do programa, enquanto o teste dinâmico é realizado executando o programa.

> O teste estático verifica o código, os documentos de exigência e os documentos de design para encontrar erros, enquanto o teste dinâmico verifica o comportamento funcional do sistema de software, o uso de memória / CPU e o desempenho geral do sistema.

> O teste estático é sobre a prevenção de defeitos, enquanto o teste dinâmico é sobre encontrar e corrigir os defeitos.

> O teste estático faz o processo de verificação enquanto o teste dinâmico faz o processo de validação.

> O teste estático é realizado antes da compilação, enquanto o teste dinâmico é realizado após a compilação.

> As técnicas de teste estático são cobertura estrutural e de declaração, enquanto as técnicas de teste dinâmico são Análise de Valor Limite e Particionamento de Equivalência.

<p align="center">
  <img alt="License" src="https://github.com/rxaviersantos/software-testing/assets/85380530/56791bec-3581-49e2-8358-47d932751fed">
</p>

### Abaixo segue a comparação detalhada

| Teste estático | Teste dinâmico | 
|    :----:      |    :----:   |        
| É realizado no estágio inicial do desenvolvimento do software.     | É realizado na fase posterior do desenvolvimento do software.     |
| No teste estático, o código inteiro não é executado.  | Nos testes dinâmicos, o código inteiro é executado.      | 
| O teste estático evita os defeitos.   | Testes dinâmicos encontram e corrigem os defeitos.       | 
| O teste estático é realizado antes da implantação do código. | O teste dinâmico é realizado após a implantação do código.     | 
| O teste estático é menos caro.  | O teste dinâmico é altamente caro.     | 
| O teste estático envolve uma lista de verificação para o processo de teste.  | Testes dinâmicos envolvem casos de teste para o processo de teste.      | 
| Inclui orientações, revisão de código, inspeção etc.   | Envolve testes funcionais e não funcionais.       | 
| Geralmente leva menos tempo.   | Geralmente leva mais tempo, pois envolve a execução de vários casos de teste.     | 
| Pode descobrir uma variedade de bugs.  | Expõe os bugs que são exploráveis através da execução, portanto, descobre apenas um tipo limitado de bugs.       | 
| O teste estático pode completar 100% da cobertura da instrução em comparativamente menos tempo.   |  Embora o teste dinâmico atinja apenas menos de 50% da cobertura da declaração.       | 
| Exemplo: Verificação  | Exemplo: Validação   | 
