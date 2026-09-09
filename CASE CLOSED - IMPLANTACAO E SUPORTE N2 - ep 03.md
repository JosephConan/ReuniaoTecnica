# Como começar um diagnóstico pelo simples antes de investigar o complexo

**Objetivo**

Desenvolver nos técnicos a capacidade de analisar um problema de forma lógica e sequencial, começando pelas configurações, cadastros e parâmetros básicos antes de partir para investigações mais complexas na estrutura do sistema.

Além disso, desenvolver a capacidade de analisar a operação e a infraestrutura do cliente antes de definir uma solução de implantação.

**Por que este tema é importante**

Durante um atendimento, um problema pode parecer muito mais complexo do que realmente é.

Quando o técnico parte diretamente para a estrutura interna do sistema, pode gastar muito tempo investigando uma possível falha quando a causa está em uma configuração simples.

Da mesma forma, durante uma implantação, uma solução não deve considerar apenas o funcionamento do sistema. É necessário entender como o cliente trabalha, sua infraestrutura e sua rotina para definir a melhor solução.


## 1. Apresentação dos casos

Durante a tarde, foram observadas duas situações diferentes, mas que possuem um ponto em comum: **antes de definir uma solução, é necessário entender o problema e analisar a situação como um todo.**

### Caso 1 — Dois CNPJs e a necessidade de um terminal auxiliar

Durante a implantação do sistema no restaurante Grão Forneria, foi realizada a configuração das máquinas restantes para o segundo CNPJ.

O técnico responsável pela implantação, Caio, também realizou uma reunião com o profissional de TI responsável pela infraestrutura do cliente.

Durante a conversa, foram analisadas as opções disponíveis para a operação do restaurante.

Como o cliente precisava realizar a mudança de CNPJ para as vendas ao longo do dia, foi identificada a necessidade de adicionar um **terminal auxiliar** para facilitar essa operação.

### Perguntas para a equipe

- Vocês teriam identificado essa necessidade durante a implantação?
- Por que é importante conversar com o responsável pela infraestrutura do cliente?
- O técnico deve considerar somente o funcionamento do sistema?
- Que problemas poderiam surgir se a infraestrutura não fosse analisada?
- Em quais situações devemos envolver o TI do cliente?
- Uma solução tecnicamente possível é necessariamente a melhor solução para o cliente?

## 2. Caso 2 — Estoque não sendo atualizado durante a produção

Logo no início do atendimento na matriz, surgiu um problema relacionado ao estoque.

O técnico relatou que o sistema não estava realizando a contagem de estoque durante o procedimento de produção.

Ao acessar o ambiente, foi possível perceber que o técnico já estava analisando diretamente a estrutura interna do sistema para tentar descobrir a causa.

Antes de continuar por esse caminho, a investigação foi reiniciada pelo básico.

Foi verificado o cadastro da mercadoria relacionada ao problema.

Durante essa verificação, foi identificado que a mercadoria estava configurada para **não realizar a movimentação de estoque**.

Após remover essa configuração e organizar o estoque, a movimentação voltou ao funcionamento normal.

## 3. O que aconteceu nesse diagnóstico?

O problema inicialmente poderia parecer um erro no processo de produção ou até mesmo um possível bug no sistema.

Porém, a causa estava em uma configuração simples do cadastro da mercadoria.

Isso demonstra que uma investigação deve seguir uma sequência lógica.

### Uma possível sequência de diagnóstico:

1. Entender exatamente o problema;
2. Reproduzir o problema;
3. Verificar o cadastro relacionado;
4. Verificar configurações;
5. Verificar parâmetros;
6. Conferir versões e componentes quando aplicável;
7. Realizar testes;
8. Analisar LOGs quando necessário;
9. Somente então partir para uma investigação mais profunda da estrutura do sistema;
10. Encaminhar ao N2 quando o problema exigir uma análise além da capacidade do técnico.

## 4. Pergunta principal para a equipe

Imagine que um cliente informe:

> "O estoque não está baixando quando faço uma produção."

### O que você verificaria primeiro?

Cada técnico deverá explicar a sequência que seguiria para investigar o problema.

Depois, comparar as respostas com o que realmente aconteceu no caso apresentado.

### Perguntas adicionais

- Você começaria pelo cadastro da mercadoria?
- Verificaria as configurações de estoque?
- Tentaria reproduzir o problema?
- Procuraria um bug imediatamente?
- Em que momento começaria a investigar a estrutura interna?
- Quando acionaria o N2?

## 5. Erro comum: começar pelo complexo

Um dos riscos no suporte é começar a investigação por aquilo que parece mais técnico.

Por exemplo:

> "O estoque não está funcionando, então deve existir algum problema na estrutura do sistema."

Essa conclusão pode fazer o técnico ignorar verificações básicas.

Antes de investigar profundamente, devemos perguntar:

**Existe alguma configuração simples que explique o comportamento?**

No caso apresentado, a resposta era sim.

A mercadoria estava configurada para não contar estoque.

## 6. Diagnóstico não é apenas procurar um erro

Um bom diagnóstico significa construir uma sequência lógica para chegar à causa do problema.

O técnico deve evitar conclusões precipitadas como:

- "É bug."
- "É problema no banco."
- "É problema no sistema."
- "É problema de rede."

Essas possibilidades podem existir, mas precisam ser investigadas.

O objetivo é sair de uma situação de:

**"O sistema não está funcionando."**

para:

**"O problema acontece nesta situação específica, foi reproduzido, estas configurações foram verificadas, estes testes foram realizados e este foi o resultado."**

## 7. A importância de analisar a operação do cliente

O caso da Grão Forneria mostra outro ponto importante.

A solução encontrada não surgiu apenas da análise do sistema.

Foi necessário entender:

- Como o cliente trabalha;
- Como os dois CNPJs são utilizados;
- Como as vendas acontecem durante o dia;
- Como os equipamentos estão estruturados;
- Como o responsável pela infraestrutura pode contribuir;
- Qual solução facilita a operação do cliente.

A decisão de adicionar um terminal auxiliar foi resultado dessa análise conjunta.

## 8. Debate com a equipe

### Sobre diagnóstico

1. Por que devemos começar pelo simples?

2. Quais são as primeiras coisas que você verifica quando um cliente relata um problema?

3. Quais configurações básicas costumam ser esquecidas?

4. Em que momento uma investigação deve passar para uma análise mais profunda?

5. Como evitar concluir rapidamente que um problema é um bug?

### Sobre implantação

6. O técnico deve analisar somente o sistema?

7. Quando devemos envolver o responsável pela infraestrutura do cliente?

8. Como a infraestrutura pode impactar o funcionamento do sistema?

9. Como descobrir se uma solução realmente atende à rotina do cliente?

10. O que pode acontecer quando implantamos o sistema sem entender a operação do cliente?

## 9. Lições aprendidas

### Começar pelo simples

Antes de investigar estruturas complexas, verificar:

- Cadastro;
- Configuração;
- Parâmetros;
- Versões;
- Procedimentos;
- Ambiente.

### Não concluir que é bug sem investigar

Um comportamento inesperado não significa necessariamente que existe uma falha no sistema.

É necessário investigar e eliminar primeiro as causas mais simples.

### Seguir uma sequência lógica

O diagnóstico deve avançar gradualmente:

**Problema → reprodução → cadastro → configuração → testes → análise aprofundada → N2**

### Conhecer a operação do cliente

Durante uma implantação, é necessário entender como o cliente realmente trabalha.

A melhor solução não é necessariamente a mais simples de configurar, mas aquela que atende corretamente à operação.

### Trabalhar em conjunto

A reunião entre o técnico e o responsável pela infraestrutura do cliente mostrou que algumas decisões podem ser melhores quando diferentes pessoas contribuem com suas experiências.

## 10. Aplicação prática

Durante a reunião, apresentar à equipe um problema sem informar inicialmente a solução.

### Situação

> "O cliente informa que o estoque de determinada mercadoria não está sendo atualizado após realizar uma produção."

Cada técnico deverá responder:

1. Qual seria sua primeira verificação?
2. O que você perguntaria ao cliente?
3. O que verificaria no cadastro?
4. Quais configurações analisaria?
5. Que testes faria?
6. Em que momento consideraria a possibilidade de bug?
7. Em que momento acionaria o N2?

Depois da discussão, apresentar o caso real e comparar a sequência utilizada.

## 11. Desafio para a semana

Durante a semana, cada técnico deverá escolher um chamado em que inicialmente parecia existir um problema complexo.

O técnico deverá identificar:

- Qual era o problema informado;
- Qual foi a primeira coisa verificada;
- Quais configurações foram analisadas;
- Quais testes foram realizados;
- Qual era a verdadeira causa;
- Se a causa era simples ou complexa;
- Se houve necessidade de acionar o N2;
- O que poderia ter sido feito de maneira diferente.

## Resultado esperado

Ao final da aula, o técnico deve compreender que:

> **Um bom diagnóstico não começa pela solução mais complexa. Começa pela pergunta certa e pela verificação mais simples.**

E, durante uma implantação:

> **Uma boa solução não considera apenas o sistema. Ela considera a operação, a infraestrutura e a realidade do cliente.**
