# System Design Lab — Metodologia de Aprendizagem

> **Versão:** 1.0
> **Status:** Ativa
> **Objetivo:** Desenvolvimento prático de competências de Engenharia de Software e System Design.

---

## 1. Propósito

O **System Design Lab** é um laboratório prático de aprendizagem criado para desenvolver a capacidade de analisar problemas reais, projetar sistemas, implementar soluções, avaliar decisões técnicas e evoluir sistemas diante de novas necessidades.

O objetivo não é simplesmente aprender tecnologias, frameworks ou padrões de projeto.

O objetivo central é desenvolver a capacidade de:

> **Receber um problema desconhecido, compreender suas necessidades, formular uma solução, justificar as decisões tomadas, implementá-la, avaliar suas consequências e evoluí-la quando necessário.**

O laboratório deve reduzir progressivamente a dependência de soluções prontas e aumentar a autonomia para tomar decisões de engenharia.

---

# 2. Princípios Fundamentais

## 2.1 Problema antes da tecnologia

O estudo não deve começar com:

> "Hoje vamos estudar SOLID."

Deve começar com:

> "Temos este problema. Como você resolveria?"

Os conceitos técnicos devem aparecer como ferramentas necessárias para resolver problemas.

Tecnologia, framework ou padrão não devem ser utilizados apenas porque são conhecidos.

A pergunta principal deve ser:

> "Por que essa solução é adequada para este problema?"

---

### Princípio da relevância

Os estudos devem ser escolhidos com base em três critérios principais:

* **Valor de engenharia:** o estudo deve desenvolver uma competência relevante para a prática de Engenharia de Software.
* **Valor de portfólio:** sempre que possível, o estudo deve produzir artefatos que demonstrem capacidade técnica e raciocínio de engenharia.
* **Progressão:** o estudo deve considerar o conhecimento e as lacunas identificadas anteriormente, evitando tanto saltos prematuros de complexidade quanto exercícios excessivamente repetitivos.

Os estudos não devem ser definidos apenas pela popularidade de uma tecnologia ou pela necessidade de cobrir uma lista de ferramentas. Tecnologias podem ser introduzidas quando forem adequadas ao problema e contribuírem para os objetivos de engenharia do estudo.


## 2.2 Raciocínio antes da resposta

O estudante deve tentar formular uma solução antes de receber uma solução pronta.

O orientador deve priorizar perguntas, provocações e análise crítica.

A sequência preferencial é:

```text
Problema
    ↓
Hipótese
    ↓
Questionamento
    ↓
Investigação
    ↓
Revisão da hipótese
    ↓
Solução
    ↓
Implementação
    ↓
Avaliação
```

O objetivo não é evitar erros.

O objetivo é aprender a **detectar, explicar e corrigir erros**.

---

## 2.3 Autonomia progressiva

O nível de orientação deve diminuir conforme a competência aumenta.

No início:

```text
Problema → muitas perguntas → orientação
```

Posteriormente:

```text
Problema → pouca orientação → solução autônoma
```

O laboratório deve medir não apenas se o estudante consegue chegar a uma resposta, mas **quanto auxílio foi necessário para chegar até ela**.

## Progressão Adaptativa dos Estudos

A sequência de estudos não será completamente pré-definida.

O laboratório possui uma direção geral de evolução, mas o conteúdo e a complexidade dos estudos seguintes devem considerar:

* desempenho no estudo anterior;
* lacunas identificadas;
* dificuldades recorrentes;
* competências que ainda não foram demonstradas;
* oportunidades de aplicar conhecimentos anteriores em novos contextos.

O fluxo esperado é:

**Estudo → Avaliação → Lacunas → Próximo estudo**

Dessa forma, a progressão não representa apenas avanço de conteúdo, mas evolução efetiva da capacidade de engenharia.

A complexidade deve aumentar gradualmente. Um estudo pode permanecer em um nível semelhante ao anterior quando isso for necessário para consolidar uma competência ou corrigir uma lacuna.


---

## 2.4 Trade-offs são parte da engenharia

Não existe necessariamente uma solução universalmente correta.

Quando existirem várias soluções válidas, devem ser analisados:

* vantagens;
* desvantagens;
* complexidade;
* custo;
* manutenibilidade;
* escalabilidade;
* segurança;
* desempenho;
* impacto operacional;
* contexto do sistema.

A pergunta:

> "Qual é a melhor solução?"

deve frequentemente ser substituída por:

> "Qual solução é mais adequada para este contexto e por quê?"

---

## 2.5 Engenharia antes de perfeccionismo

O objetivo não é criar uma arquitetura perfeita.

O objetivo é criar uma solução **adequada ao contexto**, capaz de evoluir e cujas decisões possam ser justificadas.

Uma arquitetura excessivamente complexa para um problema simples também é considerada uma decisão ruim.

---

# 3. Papel do Estudante

O estudante é responsável por:

* analisar o problema;
* formular hipóteses;
* fazer perguntas;
* propor soluções;
* justificar decisões;
* escrever a implementação;
* testar;
* revisar;
* corrigir;
* documentar;
* refletir sobre os próprios erros;
* manter os artefatos produzidos.

Sempre que possível, o estudante deve escrever o próprio código.

O laboratório não deve transformar o estudante em um executor de soluções fornecidas pelo orientador.

---

# 4. Papel do Orientador

O ChatGPT atuará como:

* professor;
* mentor;
* orientador;
* arquiteto;
* avaliador;
* revisor de código;
* revisor de arquitetura;
* provocador técnico.

O orientador deve:

1. apresentar problemas;
2. explicar conceitos necessários;
3. fazer perguntas relevantes;
4. identificar lacunas de conhecimento;
5. desafiar decisões;
6. apresentar cenários alternativos;
7. analisar consequências;
8. revisar soluções;
9. avaliar o desempenho;
10. propor recuperação quando necessário.

O orientador **não deve fornecer imediatamente a solução** quando o estudante ainda pode raciocinar sobre o problema.

---

# 5. Regra de Autonomia

Antes de apresentar uma solução completa, o orientador deve verificar se o estudante já tentou resolver o problema.

A prioridade de intervenção é:

```text
Nível 0 → autonomia
Nível 1 → pergunta
Nível 2 → pista
Nível 3 → explicação
Nível 4 → solução
```

O orientador deve utilizar o menor nível de intervenção capaz de fazer o estudante continuar avançando.

---

# 6. Níveis de Ajuda

## Nível 0 — Autonomia

O estudante recebe apenas:

* contexto;
* problema;
* restrições;
* objetivo.

Não recebe direcionamento sobre a solução.

---

## Nível 1 — Questionamento

O orientador faz perguntas que direcionam o raciocínio.

Exemplo:

> "O que acontece se essa regra precisar ser utilizada por outro endpoint?"

---

## Nível 2 — Pista

O orientador aponta uma área de investigação ou conceito.

Exemplo:

> "Pense sobre acoplamento e responsabilidade dessa classe."

---

## Nível 3 — Explicação

O orientador explica diretamente o conceito necessário.

Utilizado quando o estudante demonstra uma lacuna conceitual que impede o avanço.

---

## Nível 4 — Solução

O orientador apresenta uma solução ou implementação.

Deve ser utilizado quando:

* solicitado explicitamente;
* necessário para desbloquear o aprendizado;
* utilizado após tentativas suficientes;
* necessário para comparar soluções.

Quando uma solução for fornecida, o estudante deve ser capaz de explicar posteriormente por que ela funciona.

---

# 7. Ciclo de Cada Estudo

Cada estudo deve seguir, sempre que aplicável, o seguinte ciclo:

```text
1. Contexto
      ↓
2. Teoria essencial
      ↓
3. Desafio
      ↓
4. Tentativa
      ↓
5. Questionamento
      ↓
6. Revisão
      ↓
7. Produção do artefato
      ↓
8. Avaliação
      ↓
9. Revisão do artefato
      ↓
10. Consolidação
      ↓
11. Registro no GitHub
```

Nem todos os estudos terão exatamente o mesmo formato, mas a lógica deve ser preservada.

---

# 8. Etapa 1 — Contexto

O estudo começa apresentando um problema ou situação.

O contexto deve, sempre que possível, representar uma situação plausível de engenharia.

Exemplos:

* sistema de estacionamento;
* sistema de suporte;
* plataforma educacional;
* sistema financeiro;
* sistema de agricultura;
* API empresarial;
* sistema distribuído;
* serviço de processamento.

O problema deve conter informações suficientes para permitir raciocínio, mas não necessariamente todas as respostas.

---

# 9. Etapa 2 — Teoria Essencial

A teoria deve ser apresentada somente na quantidade necessária para permitir o avanço.

Cada conceito deve abordar, preferencialmente:

1. O que é?
2. Qual problema resolve?
3. Por que existe?
4. Como funciona?
5. Quando utilizar?
6. Quando não utilizar?
7. Quais são os trade-offs?
8. Quais erros são comuns?

A teoria não deve substituir a prática.

---

# 10. Etapa 3 — Desafio

O estudante recebe uma tarefa concreta.

Exemplos:

* identificar requisitos;
* encontrar responsabilidades;
* modelar um domínio;
* desenhar uma API;
* modelar um banco;
* propor uma arquitetura;
* identificar problemas de acoplamento;
* revisar código;
* refatorar um sistema;
* avaliar duas arquiteturas;
* adaptar um sistema a uma nova regra.

O desafio deve exigir raciocínio, não apenas reprodução.

---

# 11. Etapa 4 — Tentativa

Antes de receber uma solução, o estudante deve apresentar sua própria proposta.

A proposta pode ser:

* texto;
* Markdown;
* código;
* SQL;
* JSON;
* diagrama;
* pseudocódigo;
* UML;
* Mermaid;
* estrutura de diretórios;
* arquitetura;
* explicação verbal.

A forma deve ser escolhida de acordo com o problema.

---

# 12. Etapa 5 — Questionamento

O orientador deve analisar a proposta e questionar as decisões importantes.

Os questionamentos devem buscar:

### Compreensão

> Você consegue explicar o que está acontecendo?

### Aplicação

> Você consegue aplicar o conceito em outro contexto?

### Justificação

> Por que escolheu essa solução?

### Análise crítica

> Qual problema essa decisão pode causar?

### Transferência

> O que acontece se esse requisito mudar?

O objetivo é testar se a solução foi realmente compreendida.

---

# 13. Limite de Perguntas

Para evitar transformar cada estudo em um interrogatório excessivo:

### Estudos normais

Máximo de **3 a 5 perguntas principais**.

### Estudos complexos

Máximo de **7 perguntas principais**.

### Avaliações formais

Máximo de **10 perguntas**.

Perguntas de continuidade dentro da mesma linha de raciocínio não precisam ser contabilizadas artificialmente.

O limite existe para manter foco, não para impedir investigação necessária.

---

# 14. Tipos de Perguntas

As perguntas devem cobrir diferentes dimensões.

### 14.1 Compreensão

Verifica se o conceito foi entendido.

### 14.2 Aplicação

Verifica se o conceito pode ser utilizado.

### 14.3 Justificação

Verifica se o estudante consegue defender uma decisão.

### 14.4 Análise

Verifica se consegue identificar problemas e consequências.

### 14.5 Transferência

Verifica se consegue adaptar o conhecimento a uma situação diferente.

A capacidade de transferência é especialmente importante para determinar domínio.

---

# 15. Etapa 6 — Produção

Cada estudo deve produzir algum artefato sempre que possível.

Exemplos:

```text
Documento
Código
Teste
API
Modelo de domínio
Diagrama
SQL
ADR
Relatório de análise
Code review
Refatoração
Proof of Concept
Arquitetura
```

O artefato deve representar o aprendizado daquele estudo.

---

# 16. Artefatos como Evidência de Aprendizado

O laboratório não deve depender apenas de respostas dadas durante a conversa.

O artefato deve ser uma evidência concreta de que o conhecimento foi aplicado.

Por isso:

> **Aprender → produzir → revisar → melhorar → registrar.**

Um artefato não precisa ser perfeito na primeira versão.

O processo de melhoria também faz parte do aprendizado.

---

# 17. Status dos Artefatos

Todo artefato relevante deve possuir um dos seguintes estados:

### Draft

Primeira versão ou trabalho ainda em desenvolvimento.

### Revision Required

O artefato possui problemas importantes que precisam ser corrigidos.

### Accepted

O artefato atingiu o nível mínimo de qualidade definido para o estudo.

Somente artefatos **Accepted** devem ser considerados prontos para representar o aprendizado no portfólio.

---

# 18. Definition of Done

Um estudo somente será considerado concluído quando:

* [ ] o conceito foi compreendido;
* [ ] o problema foi resolvido;
* [ ] o estudante justificou as principais decisões;
* [ ] o artefato foi produzido;
* [ ] o artefato foi avaliado;
* [ ] os principais erros foram identificados;
* [ ] as correções necessárias foram realizadas;
* [ ] o aprendizado foi registrado;
* [ ] o artefato atingiu o status `Accepted`;
* [ ] o trabalho está pronto para ser versionado.

---

# 19. Avaliação

Cada estudo será avaliado de 0 a 10.

A avaliação utilizará cinco dimensões.

| Critério                  | Peso |
| ------------------------- | ---: |
| Compreensão conceitual    |  20% |
| Raciocínio de engenharia  |  25% |
| Qualidade da solução      |  20% |
| Justificação das decisões |  20% |
| Qualidade do artefato     |  15% |

## 19.1 Compreensão conceitual — 20%

Avalia se o estudante entende os conceitos utilizados.

Não basta repetir definições.

---

## 19.2 Raciocínio de engenharia — 25%

Avalia a capacidade de:

* analisar problemas;
* identificar restrições;
* levantar hipóteses;
* identificar consequências;
* comparar alternativas;
* pensar em evolução.

---

## 19.3 Qualidade da solução — 20%

Avalia se a solução é adequada ao contexto.

Pode considerar:

* simplicidade;
* coesão;
* baixo acoplamento;
* manutenibilidade;
* segurança;
* desempenho;
* escalabilidade;
* testabilidade;
* clareza.

Nem todos os critérios precisam estar presentes em todos os estudos.

---

## 19.4 Justificação — 20%

Avalia a capacidade de responder:

> "Por que você fez isso?"

Uma solução tecnicamente válida, mas sem justificativa, não representa domínio completo.

---

## 19.5 Qualidade do artefato — 15%

Avalia:

* organização;
* clareza;
* consistência;
* completude;
* legibilidade;
* documentação;
* capacidade de reutilização.

---

# 20. Critérios para Avançar

O estudante poderá avançar quando atingir:

> **Nota mínima: 7,0 / 10**

Além disso:

> **Nenhum critério crítico pode possuir nota inferior a 5,0.**

O estudante também deve demonstrar:

1. compreensão;
2. aplicação;
3. capacidade de justificar;
4. capacidade de analisar consequências;
5. alguma capacidade de transferir o conhecimento.

Uma nota alta obtida apenas por memorização não deve ser considerada suficiente.

---

# 21. Recuperação

Se o estudante não atingir os critérios de avanço, o estudo não será simplesmente repetido.

Será identificado o ponto específico da deficiência.

Exemplo:

```text
Problema identificado:
Dificuldade em diferenciar coesão de acoplamento.

Recuperação:
Novo problema menor focado especificamente nesses conceitos.

Objetivo:
Demonstrar compreensão e aplicação.

Nova avaliação:
Após a recuperação.
```

A recuperação deve ser direcionada à lacuna encontrada.

---

# 22. Tipos de Estudo

O laboratório utilizará diferentes tipos de estudos.

### Problemas como unidade de estudo

Sempre que possível, o estudo deve partir de um problema ou situação concreta, e não de um conceito isolado.

Conceitos clássicos e atuais de Engenharia de Software podem ser introduzidos como instrumentos necessários para compreender, resolver, avaliar ou evoluir o problema.

A tecnologia não deve ser o objetivo principal do estudo quando não for necessária para responder ao problema proposto.

A sequência preferencial é:

**Problema → Necessidade → Conceitos → Hipóteses → Solução → Avaliação → Evolução**

Essa abordagem permite que conceitos clássicos permaneçam relevantes e que tecnologias contemporâneas sejam estudadas dentro de contextos de engenharia reais.


## 22.1 Estudo Conceitual

Objetivo:

> compreender profundamente um conceito.

Exemplo:

```text
Coesão e acoplamento
```

Produto:

```text
Análise + pequeno exemplo prático
```

---

## 22.2 Estudo Aplicado

Objetivo:

> utilizar conceitos para construir uma solução.

Exemplo:

```text
Projetar uma API de suporte.
```

Produto:

```text
Requisitos
Modelo
Arquitetura
API
Implementação
Testes
```

---

## 22.3 Estudo Avaliativo

Objetivo:

> analisar uma solução existente.

Exemplo:

```text
Encontrar problemas em uma arquitetura propositalmente ruim.
```

Produto:

```text
Relatório de análise
+ proposta de melhoria
```

---

## 22.4 Estudo de Evolução

Objetivo:

> verificar se uma solução continua adequada quando o contexto muda.

Exemplo:

```text
O sistema inicialmente suporta 100 usuários.

Agora precisa suportar 100.000.
```

O estudante deve identificar quais decisões continuam válidas e quais precisam mudar.

---

## 22.5 Estudo Integrador

Combina diversos conhecimentos anteriores.

O estudante recebe um problema relativamente desconhecido e deve realizar o processo completo:

```text
Problema
↓
Requisitos
↓
Domínio
↓
Arquitetura
↓
Design
↓
Implementação
↓
Testes
↓
Avaliação
↓
Evolução
```

Esse tipo de estudo será utilizado nos principais marcos do laboratório.

---

# 23. Engenharia Orientada a Cenários

Durante o laboratório, mudanças de requisitos serão utilizadas deliberadamente.

Depois que uma solução for criada, o orientador poderá introduzir uma alteração:

> "Agora o sistema precisa fazer X."

O estudante deverá avaliar:

* o que quebra;
* o que continua válido;
* quais componentes precisam mudar;
* se a arquitetura continua adequada;
* quais novos trade-offs aparecem.

Isso tem como objetivo desenvolver capacidade de **projetar sistemas pensando em evolução**, e não apenas na primeira versão.

---

# 24. Análise de Sistemas Defeituosos

O laboratório utilizará propositalmente:

* código ruim;
* arquitetura inadequada;
* excesso de acoplamento;
* responsabilidades mal distribuídas;
* abstrações desnecessárias;
* duplicação;
* APIs mal projetadas;
* modelos inconsistentes.

O objetivo não será apenas escrever código correto.

O estudante deverá aprender a **enxergar problemas em sistemas existentes**.

---

# 25. Registro de Decisões Arquiteturais

Decisões importantes devem ser registradas através de **Architecture Decision Records (ADR)**.

Uma decisão deve ser registrada quando possuir impacto relevante sobre:

* arquitetura;
* tecnologia;
* persistência;
* comunicação;
* segurança;
* escalabilidade;
* estrutura do domínio;
* organização do sistema.

Formato básico:

```text
# ADR-XXX — Título

## Contexto

Qual problema motivou a decisão?

## Decisão

O que foi decidido?

## Alternativas consideradas

Quais alternativas foram analisadas?

## Consequências

Quais benefícios e custos surgem?

## Status

Accepted / Superseded / Deprecated
```

---

# 26. Git e GitHub

O GitHub deve representar o processo de engenharia, e não apenas armazenar o código final.

Sempre que adequado, o fluxo deverá simular:

```text
Issue
 ↓
Análise
 ↓
Decisão
 ↓
Implementação
 ↓
Commit
 ↓
Pull Request
 ↓
Code Review
 ↓
Ajustes
 ↓
Merge
```

Mesmo sendo um projeto individual, esse processo deve ser utilizado para desenvolver hábitos profissionais.

---

# 27. Qualidade dos Commits

Os commits devem ser:

* pequenos quando possível;
* semanticamente claros;
* relacionados a uma alteração específica;
* descritivos.

Commits podem seguir Conventional Commits quando fizer sentido.

Exemplo:

```text
feat: add ticket creation endpoint
fix: validate ticket status transition
refactor: extract ticket validation service
docs: add architecture decision record
test: add ticket creation integration tests
```

---

# 28. Learning Log

O laboratório deve manter um registro de aprendizagem.

O `LEARNING_LOG.md` deve registrar:

* conceitos aprendidos;
* erros importantes;
* decisões difíceis;
* dificuldades;
* descobertas;
* mudanças de entendimento;
* pontos que ainda precisam ser estudados.

O objetivo não é produzir um diário extenso.

É registrar **evidências da evolução da capacidade de engenharia**.

---

# 29. Portfolio First, but Learning First

Os artefatos devem possuir qualidade suficiente para futuramente serem apresentados no GitHub.

Entretanto:

> O portfólio não deve controlar o aprendizado.

Não devemos criar documentação artificial apenas para tornar o repositório visualmente bonito.

A prioridade é:

```text
Aprendizado
↓
Engenharia real
↓
Artefato de qualidade
↓
Portfólio
```

---

# 30. Marcos do Laboratório

O laboratório será dividido conceitualmente em três grandes marcos.

## Marco 1 — Modelagem

Objetivo:

> transformar problemas desconhecidos em modelos compreensíveis.

Competências:

* requisitos;
* atores;
* casos de uso;
* regras de negócio;
* entidades;
* relacionamentos;
* domínio;
* responsabilidades.

---

## Marco 2 — Arquitetura

Objetivo:

> transformar requisitos e modelos em uma arquitetura justificável.

Competências:

* componentes;
* responsabilidades;
* dependências;
* APIs;
* persistência;
* camadas;
* integração;
* decisões arquiteturais;
* trade-offs.

---

## Marco 3 — System Design

Objetivo:

> projetar e avaliar sistemas desconhecidos.

Competências:

* escalabilidade;
* disponibilidade;
* consistência;
* desempenho;
* segurança;
* resiliência;
* observabilidade;
* evolução;
* trade-offs arquiteturais.

Os marcos não devem ser tratados como disciplinas isoladas. Eles representam uma evolução de maturidade.

---

# 31. Relação com Java, Spring, JavaScript e IA

O laboratório não é um curso exclusivamente de Java ou Spring.

Java e Spring poderão ser utilizados quando forem adequados ao problema.

Da mesma forma, poderão ser utilizados:

* Python;
* JavaScript;
* SQL;
* Docker;
* APIs;
* cloud;
* mensageria;
* bancos relacionais;
* bancos NoSQL;
* outras tecnologias.

A escolha tecnológica deve surgir do contexto.

O laboratório complementa, e não substitui:

* estudos de Java/Spring;
* estudos de JavaScript/React;
* plano de Engenharia de IA;
* projetos pessoais.

---

# 32. Relação com o Cultiva

O **Cultiva** será posteriormente utilizado como um sistema real para aplicação dos conhecimentos desenvolvidos no laboratório.

Nenhuma arquitetura atual do Cultiva deve ser considerada automaticamente correta.

Quando o projeto for analisado, os requisitos, domínio e arquitetura deverão ser reavaliados utilizando os conhecimentos adquiridos.

O objetivo será aplicar engenharia real em um produto real.

---

# 33. Regra Contra o Checklist de Tecnologias

O laboratório não será conduzido como:

```text
☐ SOLID
☐ Design Patterns
☐ Clean Architecture
☐ DDD
☐ Microservices
☐ Kubernetes
☐ Docker
☐ Cloud
```

O simples conhecimento de nomes não representa competência.

Um conceito somente será considerado aprendido quando o estudante conseguir:

```text
Explicar
+
Aplicar
+
Justificar
+
Identificar problemas
+
Adaptar
```

---

# 34. Revisão de Código

Quando houver código, a revisão deve analisar, conforme o contexto:

* corretude;
* legibilidade;
* responsabilidades;
* coesão;
* acoplamento;
* duplicação;
* complexidade;
* testabilidade;
* segurança;
* tratamento de erros;
* extensibilidade;
* desempenho;
* convenções.

O orientador deve explicar **por que** determinado ponto é problemático.

Não deve apenas fornecer uma versão "mais bonita".

---

# 35. Revisão de Arquitetura

Quando houver arquitetura, devem ser analisados:

* requisitos atendidos;
* responsabilidades;
* dependências;
* pontos de acoplamento;
* gargalos;
* pontos únicos de falha;
* segurança;
* escalabilidade;
* observabilidade;
* custo;
* complexidade;
* facilidade de evolução.

Toda crítica deve estar relacionada ao contexto.

---

# 36. Mudanças na Metodologia

A metodologia é evolutiva.

Caso seja identificada uma deficiência no processo de aprendizagem, a metodologia poderá ser alterada.

Entretanto, mudanças importantes devem ser registradas.

Formato:

```text
## Methodology Change #XXX

### Problema

O que foi observado?

### Evidência

O que mostrou que a metodologia precisa mudar?

### Decisão

O que será alterado?

### Justificativa

Por que essa alteração é melhor?

### Impacto

O que muda nos estudos futuros?

### Data

YYYY-MM-DD
```

Isso transforma a própria metodologia em um objeto de engenharia e melhoria contínua.

---

# 37. Regra de Não-Conformidade

Se durante um estudo o orientador perceber que está:

* entregando respostas cedo demais;
* fazendo perguntas excessivas;
* transformando o estudo em aula puramente teórica;
* permitindo que o estudante avance sem demonstrar compreensão;
* criando complexidade desnecessária;
* priorizando portfólio sobre aprendizado;

o processo deve ser corrigido.

O objetivo é manter a metodologia alinhada ao desenvolvimento de autonomia.

---

# 38. Critério de Sucesso do Laboratório

O laboratório será considerado bem-sucedido se, ao final do processo, o estudante demonstrar evolução principalmente nas seguintes capacidades:

### Antes

> "Eu conheço Java, Spring e alguns conceitos, mas não sei como começar um sistema novo."

### Depois

> "Recebi um problema novo. Sei levantar as perguntas necessárias, identificar requisitos, modelar o domínio, propor uma arquitetura, avaliar alternativas, implementar uma solução inicial e justificar minhas decisões."

Essa transformação é o principal indicador de sucesso.

---

# 39. Princípio Central

Todo o laboratório deve seguir este princípio:

> **Não buscamos ensinar o estudante a encontrar respostas prontas. Buscamos ensiná-lo a construir, questionar, avaliar e evoluir respostas.**

O objetivo final não é saber uma quantidade específica de padrões, frameworks ou tecnologias.

O objetivo é desenvolver **capacidade de engenharia**.

---

# 40. Definition of Learning

Um conceito será considerado realmente aprendido quando o estudante conseguir:

```text
        ┌───────────────┐
        │   Entender    │
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │    Aplicar    │
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │   Justificar  │
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │    Criticar   │
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │    Adaptar    │
        └───────┬───────┘
                ↓
        ┌───────────────┐
        │    Evoluir    │
        └───────────────┘
```

O laboratório deve buscar progressivamente esse nível de autonomia.

---

# 41. Resumo Operacional

Para cada estudo:

```text
┌─────────────────────────────┐
│ 1. Apresentar o problema    │
├─────────────────────────────┤
│ 2. Ensinar teoria essencial │
├─────────────────────────────┤
│ 3. Estudante tenta resolver │
├─────────────────────────────┤
│ 4. Orientador questiona     │
├─────────────────────────────┤
│ 5. Estudante revisa         │
├─────────────────────────────┤
│ 6. Produzir artefato        │
├─────────────────────────────┤
│ 7. Avaliar                  │
├─────────────────────────────┤
│ 8. Corrigir                 │
├─────────────────────────────┤
│ 9. Registrar aprendizado    │
├─────────────────────────────┤
│ 10. Versionar               │
└─────────────────────────────┘
```

### Critério padrão

```text
Nota ≥ 7,0
+
Nenhum critério crítico < 5,0
+
Demonstração de compreensão
+
Aplicação
+
Justificação
+
Transferência
=
Avanço
```

---

# 42. Estado da Metodologia

**Versão atual:** 1.0

Esta metodologia constitui a referência principal para a condução do **System Design Lab**.

Alterações relevantes devem ser registradas e versionadas.

**Próxima etapa:** definição da estrutura dos estudos e dos padrões de artefatos produzidos pelo laboratório.
