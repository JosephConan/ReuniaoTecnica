# Como saber quando um chamado deve ser encaminhado ao N2?

## Objetivo

Desenvolver a capacidade dos técnicos de realizar uma análise inicial do chamado e identificar quando o problema pode ser resolvido pelo próprio suporte e quando realmente precisa ser encaminhado ao N2.

## Por que o tema é importante?

O N2 deve atuar principalmente em problemas que exigem uma investigação mais profunda. Quando chamados simples chegam ao N2, isso consome tempo da equipe e reduz a eficiência do suporte.

Por outro lado, o técnico também não deve ficar tentando resolver indefinidamente um problema que está além da sua capacidade de diagnóstico.

O objetivo é encontrar o equilíbrio:

> **Ter autonomia para resolver o que é possível e saber quando e como pedir ajuda.**

## 1. Apresentação dos casos

Durante o acompanhamento do N2 na matriz, foram observados alguns chamados com níveis de complexidade diferentes.

### Caso 1 — Cópia de LOG e MDF

Um técnico entrou em contato com o N2 para saber como realizar a cópia de arquivos LOG e MDF.

Apesar de ter recorrido ao N2, era um procedimento relativamente simples que deveria fazer parte do conhecimento básico do suporte.

**Perguntas para a equipe:**

* Vocês encaminhariam esse chamado para o N2?
* Esse procedimento deveria fazer parte do conhecimento de todos os técnicos?
* Como evitar que dúvidas simples cheguem ao N2?

### Caso 2 — Comunicação do TEF Scope

Um técnico estava tratando um problema de comunicação com o TEF Scope.

Inicialmente, foram verificadas as DLLs e a versão do PDV.

Durante a análise junto com Alencar, foi identificado que o cliente havia sido configurado originalmente para outro tipo de TEF.

O cadastro foi ajustado e foi solicitado um novo teste ao cliente. Depois disso, não houve mais comunicação com o técnico, indicando que o problema provavelmente havia sido resolvido.

**Perguntas para a equipe:**

* O problema era realmente uma falha no sistema?
* O que levou à descoberta da causa?
* O que poderia ter acontecido se o técnico tivesse concluído imediatamente que era um bug?

### Caso 3 — Venda que não processava no caixa

Em outro chamado, o técnico identificou um problema mais complexo.

A venda era realizada pelo F1, mas, depois de inserir os produtos, a finalização não apresentava o processamento esperado.

A venda também não aparecia no F9/NFC-e.

Durante a análise, foi identificado que o pedido permanecia em cache e não era enviado corretamente.

Nesse caso, havia necessidade de uma investigação mais profunda, justificando o envolvimento do N2.

**Perguntas para a equipe:**

* Quais informações o técnico deveria levantar antes de encaminhar esse chamado?
* O que diferencia esse caso de uma dúvida simples?
* Quais testes poderiam ser realizados antes do encaminhamento?

## 2. O que podemos observar nos casos?

Os chamados que chegam ao N2 podem ter causas completamente diferentes.

Um problema pode estar relacionado a:

* Configuração;
* Cadastro;
* Versão do sistema;
* DLL;
* Equipamento;
* Integração;
* Rede;
* Ambiente do cliente;
* Procedimento realizado pelo usuário;
* Comportamento interno do sistema;
* Bug.

Por isso, **não devemos concluir que algo é um bug antes de investigar.**

O técnico precisa desenvolver uma **sequência lógica de diagnóstico**.

## 3. Sequência básica de diagnóstico

Antes de encaminhar um chamado para o N2, o técnico deve procurar responder às seguintes perguntas:

### 1. Qual é exatamente o problema?

Não basta dizer:

> "O sistema está com erro."

É necessário entender o que está acontecendo.

### 2. Quando o problema acontece?

* Acontece sempre?
* Acontece somente em determinada operação?
* Começou recentemente?
* Já funcionou anteriormente?

### 3. O problema acontece em todos os computadores?

* É somente em um PDV?
* Acontece em todas as máquinas?
* Acontece somente com determinado usuário?

Essa informação pode ajudar a separar um problema do sistema de um problema do ambiente.

### 4. O que já foi testado?

O chamado deve informar quais procedimentos foram realizados.

**Exemplo:**

* Reiniciado o sistema;
* Verificada a configuração;
* Conferida a versão;
* Conferido o cadastro;
* Testado em outro computador;
* Verificado o LOG;
* Reproduzido o problema.

### 5. Qual foi o resultado dos testes?

Não basta informar que algo foi testado.

É importante registrar o resultado.

**Exemplo:**

> "Foi testado em outro computador e o erro também ocorreu."

Essa informação é muito mais útil para o N2 do que simplesmente:

> "Testado e continua dando erro."

## 4. Quando devemos encaminhar para o N2?

O chamado deve ser encaminhado quando:

* Os procedimentos básicos já foram realizados;
* As configurações relacionadas foram verificadas;
* As versões foram conferidas, quando aplicável;
* O problema foi reproduzido;
* Os LOGs foram analisados, quando necessário;
* Existe evidência de comportamento anormal do sistema;
* O problema exige uma análise mais profunda;
* O técnico não possui ferramentas ou conhecimento para continuar a investigação.

O objetivo não é impedir o técnico de chamar o N2.

O objetivo é fazer com que o chamado chegue ao N2 **com qualidade e com o máximo de informações possíveis**.

## 5. Debate com a equipe

**Perguntas para a discussão:**

1. Quais procedimentos básicos todo técnico deveria dominar?
2. Quais tipos de chamados não deveriam chegar ao N2?
3. Quando devemos insistir na investigação antes de pedir ajuda?
4. Qual o risco de encaminhar tudo para o N2?
5. Qual o risco de tentar resolver tudo sozinho?
6. O que um chamado precisa ter para facilitar o trabalho do N2?
7. Como o N2 pode ajudar a desenvolver o conhecimento dos técnicos?
8. Quando o N2 resolve um problema, esse conhecimento deveria voltar para o suporte?

## 6. Lições aprendidas

### Autonomia do suporte

Quanto mais preparado estiver o suporte de primeiro nível, menos problemas simples serão encaminhados ao N2.

### Nem todo problema é um bug

Antes de concluir que existe uma falha no sistema, devemos investigar:

* Configuração;
* Cadastro;
* Versão;
* Ambiente;
* Equipamento;
* Integrações;
* Procedimentos.

### O chamado precisa ter qualidade

Um chamado bem documentado permite que o N2 comece a investigação de um ponto muito mais avançado.

### N2 não deve substituir o conhecimento do suporte

Se um problema simples é resolvido pelo N2, o ideal é que o procedimento seja aprendido pelo suporte para evitar que a mesma dúvida volte a acontecer.

### Saber pedir ajuda também é uma habilidade

Um bom técnico não precisa saber resolver todos os problemas.

Ele precisa saber:

**Investigar → Testar → Identificar seus limites → Pedir ajuda → Fornecer informações suficientes**

## 7. Aplicação prática

Durante a reunião, apresentar para a equipe um problema fictício ou real sem revelar inicialmente a solução.

### Exemplo

> "O cliente informa que uma venda foi realizada, mas a NFC-e não aparece no F9."

**Perguntar:**

* O que vocês verificariam primeiro?
* Que perguntas fariam ao cliente?
* Quais testes realizariam?
* Que informações registrariam?
* Em que momento encaminhariam para o N2?

Depois da discussão, apresentar a solução real ou o caminho correto de investigação.

## 8. Desafio para a semana

Cada técnico deverá observar, durante a semana, um chamado em que ficou em dúvida se deveria resolver sozinho ou encaminhar para o N2.

Na próxima reunião, deverá apresentar:

* Qual era o problema;
* O que foi investigado;
* O que foi testado;
* Se resolveu ou encaminhou;
* Por que tomou essa decisão;
* O que faria diferente hoje.

### Resultado esperado

Ao final da aula, o técnico deve entender que:

> **Ser um bom técnico não significa nunca precisar do N2. Significa saber investigar, reconhecer seus limites e encaminhar o problema com qualidade quando realmente precisar de ajuda.**
