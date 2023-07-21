# Teste de manutenção

Depois de implantados em ambientes de produção, o software e os sistemas precisam ser mantidos.
Vários tipos de mudanças são quase inevitáveis em softwares e sistemas entregues, seja para corrigir
defeitos descobertos no uso operacional, para adicionar novas funcionalidades, ou para remover ou
alterar funcionalidades já entregues.  

A manutenção também é necessária para preservar ou melhorar as características de qualidade não-funcionais do componente ou do sistema ao longo de sua vida útil, especialmente a eficiência de performance, compatibilidade, confiabilidade, segurança e portabilidade.

Quando quaisquer alterações são feitas como parte da manutenção, testes de manutenção devem ser realizados, tanto para avaliar o sucesso com que as alterações foram feitas quanto para verificar possíveis efeitos colaterais (p. ex., regressões) em partes do sistema que permanecem inalteradas (o que geralmente é a maior parte do sistema).

O teste de manutenção se concentra em testar as alterações no sistema, bem como em testar as partes inalteradas que podem ter sido afetadas pelas alterações. A manutenção pode envolver lançamentos planejados e liberações não planejadas (hot fixes).

Uma versão de manutenção pode exigir testes de manutenção em vários níveis de teste, usando vários tipos de teste, com base em seu escopo. O escopo do teste de manutenção depende do:

> • Grau de risco da mudança, por exemplo, o grau em que a área alterada do software se comunica com outros componentes ou sistemas;
> 
> • Tamanho do sistema existente;
> 
> • Tamanho da mudança.

### Gatilhos para manutenção

Existem várias razões pelas quais a manutenção de software e, portanto, os testes de manutenção, ocorrem tanto para alterações planejadas como não planejadas.

Podemos classificar os gatilhos para manutenção da seguinte forma:

> • *Modificação*: como aprimoramentos planejados (p. ex., baseado na versão), alterações corretivas e emergenciais, alterações no ambiente operacional (como sistema operacional ou atualizações de banco de dados), atualizações de software de prateleira usados e correções para defeitos e vulnerabilidades;
>
> • *Migração*: como de uma plataforma para outra, que pode exigir testes operacionais do novo ambiente, bem como do software alterado, ou testes de conversão de dados quando os dados de outro aplicativo serão migrados para o sistema que está sendo mantido;
>
> • *Aposentadoria*: como quando um aplicativo atinge o fim de sua vida útil.

Quando um aplicativo ou sistema é retirado, isso pode exigir o teste de migração ou arquivamento dos dados, se forem necessários longos períodos de retenção para esses dados. Também pode ser necessário testar os procedimentos de recuperação após o arquivamento por longos períodos de retenção. Além disso, testes de regressão podem ser necessários para garantir que qualquer funcionalidade que permaneça em serviço ainda funcione.

Para os sistemas da Internet das Coisas (IoT), o teste de manutenção pode ser acionado pela introdução de itens completamente novos ou modificados, como dispositivos de hardware e serviços de software, no sistema geral. O teste de manutenção para tais sistemas coloca ênfase particular nos testes de integração em diferentes níveis (p.e, nível de rede, nível de aplicação) e nos aspectos de segurança, em particular aqueles relacionados a dados pessoais.

<p align="center">
  <img alt="nivel de teste" src="https://github.com/rxaviersantos/software-testing/assets/85380530/30f10a6c-c17c-428c-b494-c51d325b8cda" "height="400px" width="600px">
</p>







