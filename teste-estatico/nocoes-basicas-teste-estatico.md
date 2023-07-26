# Teste estático 

## Noções básicas sobre testes estáticos

Em contraste com o teste dinâmico, que requer a execução do software a ser testado, o teste estático
depende do exame manual dos produtos de trabalho (isto é, revisões) ou da avaliação orientada por
ferramentas do código ou outros produtos de trabalho (isto é, análise estática). Os dois tipos de
testes estáticos avaliam o código ou outro produto de trabalho que está sendo testado sem
realmente executar o código ou o produto de trabalho que está sendo testado.

A análise estática é importante para sistemas críticos de segurança (p. ex., software de aviação,
médico ou nuclear), mas a análise estática também se tornou importante e comum em outros
ambientes. Por exemplo, a análise estática é uma parte importante dos testes de segurança. A
análise estática também é frequentemente incorporada aos sistemas automatizados de criação e
distribuição, por exemplo, no desenvolvimento ágil, na entrega contínua e na implantação contínua.

### Produtos de trabalho que podem ser examinados por testes estáticos

Quase qualquer produto de trabalho pode ser examinado usando testes estáticos (revisões ou
análise estática), por exemplo:

> • Especificações, incluindo requisitos de negócios, requisitos funcionais e requisitos de
segurança;
>
> • Épicos, histórias de usuários e critérios de aceite;
> 
> • Especificações de arquitetura e design;
> 
> • Código;
> 
> • Testware, incluindo planos de teste, casos de teste, procedimentos de teste e scripts de teste automatizados;
>
> • Guias de usuários;
> 
> • Páginas web;
> 
> • Contratos, planos de projeto, cronogramas e orçamentos;
> 
> • Modelos, como os diagramas de atividades, que podem ser usados para testes baseados em
modelo

As avaliações podem ser aplicadas a qualquer produto de trabalho que os participantes saibam ler
e entender. A análise estática pode ser aplicada eficientemente a qualquer produto de trabalho com
uma estrutura formal (normalmente código ou modelos) para a qual existe uma ferramenta de
análise estática apropriada. A análise estática pode até ser aplicada com ferramentas que avaliam
produtos de trabalho escritos em linguagem natural, como requisitos. 

### Benefícios do teste estático

As técnicas de testes estáticos fornecem uma variedade de benefícios. Quando aplicado no início do
ciclo de vida de desenvolvimento de software, permite a detecção antecipada dos defeitos antes da realização dos testes dinâmicos. Os defeitos detectados precocemente costumam ser muito mais baratos de serem removidos do que os defeitos encontrados posteriormente no ciclo de vida, especialmente em comparação aos defeitos encontrados após o software ser implantado e em uso ativo. Usar técnicas de testes estáticos para localizar e corrigir os defeitos rapidamente é quase sempre muito mais barato para a organização do que usar testes dinâmicos para encontrar defeitos no objeto de teste e corrigi-los, especialmente considerando os custos adicionais associados à atualização de outros produtos de trabalho e à realização de testes de confirmação e regressão.

Benefícios adicionais do teste estático podem incluir:

> • Detectar e corrigir defeitos com mais eficiência e antes da execução dinâmica dos testes;
> 
> • Identificar os defeitos que não são facilmente encontrados por testes dinâmicos;
> 
> • Prevenir defeitos no desenho ou na codificação, revelando inconsistências, ambiguidades,
contradições, omissões, imprecisões e redundâncias nos requisitos;
>
> • Aumentar a produtividade no desenvolvimento (p. ex., devido ao desenho aprimorado,
código mais sustentável);
> 
> • Reduzir o custo e o tempo de desenvolvimento;
> 
> • Reduzir o custo e o tempo de teste;
> 
> • Reduzir o custo total de qualidade durante a vida útil do software, devido a menos falhas nas
etapas finais do ciclo de vida ou após a entrega em operação;
>
> • Melhorar a comunicação entre os membros da equipe durante a participação nas revisões.

### Diferenças entre teste estático e dinâmico

Os testes estático e dinâmico podem ter os mesmos objetivos, como fornecer uma avaliação da qualidade dos produtos de trabalho e identificar os defeitos o mais cedo possível. Os testes estático e dinâmico se complementam, encontrando diferentes tipos de defeitos.

Uma das principais distinções é que o teste estático encontra os defeitos diretamente em produtos
de trabalho, em vez de identificar as falhas causadas por defeitos quando o software é executado.
Um defeito pode residir em um produto de trabalho por muito tempo sem causar uma falha. Se caminho onde o defeito está é difícil de alcançar ou de ser testado, então não será fácil construir e executar um teste dinâmico que o encontre. O Teste estático pode encontrar o defeito com muito menos esforço.

Outra distinção é que o teste estático pode ser usado para melhorar a consistência e a qualidade
interna dos produtos de trabalho, enquanto o teste dinâmico geralmente se concentra em comportamentos externamente visíveis.

Em comparação com o teste dinâmico, os defeitos mais comuns que são mais fáceis e baratos de
encontrar e corrigir por meio de teste estático inclui:

> * Defeitos em requisitos (p. ex., inconsistências, ambiguidades, contradições, omissões,
imprecisões e redundâncias);
> 
> * Defeitos de desenho (p. ex., algoritmos ineficientes ou estruturas de banco de dados, alto
acoplamento, baixa coesão);
>
> * Defeitos de codificação (p. ex., variáveis com valores indefinidos, variáveis declaradas e nunca
utilizadas, código inacessível, código duplicado);
>
> * Desvios dos padrões (p. ex., falta de aderência aos padrões de codificação);
> 
> * Especificações incorretas de interface (p. ex., unidades de medida diferentes usadas pelo
sistema de chamada do que pelo sistema chamado);
> 
> * Vulnerabilidades de segurança (p. ex., suscetibilidade a estouro de buffer);
> 
> * Lacunas ou imprecisões na rastreabilidade ou cobertura da base de teste (p. ex., falta de
testes para um critério de aceite). 


Além disso, a maioria dos tipos de defeitos de manutenção só pode ser encontrada por testes estáticos (p. ex., modularização inadequada, reusabilidade ruim de componentes, código que é difícil de analisar e modificar sem introduzir novos defeitos).








