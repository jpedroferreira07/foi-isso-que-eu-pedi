# As 5 sprints

Resumo do que o Notion registrou em cada sprint: objetivo, histórias, weeklies, revisão e retrospectiva. O feedback do cliente é o do professor.

| Sprint | Período | Fase |
| --- | --- | --- |
| 1 | 29/09 a 06/10/2026 | Descoberta |
| 2 | 06/10 a 20/10/2026 (2 semanas, por causa dos feriados de 12 e 15/10) | Design do jogo |
| 3 | 20/10 a 27/10/2026 | Prototipagem e conteúdo |
| 4 | 27/10 a 03/11/2026 | Integração e validação |
| 5 | 03/11 a 10/11/2026 | Entrega final |
| 6 | 10/11 a 17/11/2026 | Ajustes e apresentação em 17/11 |

---

## Sprint 1: Descoberta

**Objetivo:** ter os papéis da equipe definidos, a visão do produto e o roadmap feitos, e um quadro Kanban com as colunas Backlog, A Fazer, Fazendo, Feedback e Pronto, mais limite de WIP.

**Histórias do Sprint Backlog**

| História | Responsável | Critérios de aceite (DoD) |
| --- | --- | --- |
| 3.1.1 Papéis da equipe | Equipe | Os 3 papéis (PO, SM e Devs) têm nome atribuído a cada membro da equipe. |
| 3.1.2 Visão do produto e roadmap | Giovanni | Visão em 1 parágrafo (para quem, qual problema, qual solução); roadmap com temas, épicos, histórias e tarefas, cobrindo as 5 semanas; roadmap aprovado pela equipe. |
| 3.1.3 Quadro Kanban | Giovanni | Quadro com as 5 colunas e limites de WIP. |

**Weekly**
- Giovanni: fez a visão do produto e o Notion; estava fazendo o roadmap; impedimento: não sabia como fazer o roadmap.
- Equipe: definiu os papéis.

**Revisão:** entregues 3.1.1 e 3.1.3. A 3.1.2 ficou pendente.
**Feedback do cliente:** começar definindo as histórias de usuário no proto-backlog, usando os pedidos do cliente como fonte; listar as tarefas de cada história; e checar se cada uma cabe em 1 semana. Se precisar de 2 a 4 semanas é um épico; se ocupar o projeto inteiro é um tema.

**Retrospectiva:** melhorar a organização, usar o Notion de forma correta e recuperar o que ficou pendente, evitando novas pendências nas próximas sprints.

---

## Sprint 2: Design do jogo

**Objetivo:** ter o jogo ensinando a estrutura de um prompt (contexto, persona, tarefa, formato e instrução objetiva), com mecânicas fundamentadas em Björk et al. (2003); objetivo, regras, pontuação e feedback imediato definidos; backlog organizado e priorizado; um protótipo de baixa fidelidade submetido a um playtest interno inicial; e concluir as pendências da Sprint 1.

**Histórias do Sprint Backlog**

| História | Responsável | Critérios de aceite (DoD) |
| --- | --- | --- |
| 1.1.1 Estrutura do prompt | João Pedro Ferreira Afonso | Os 5 elementos do prompt estão descritos, cada um com pelo menos 1 exemplo; conteúdo aprovado pelo cliente. |
| 1.2.1 Mecânicas de Björk | João Pedro Ferreira Afonso | Mecânicas listadas e ligadas aos padrões de Björk et al. (2003); referência completa registrada; coerência com o objetivo de aprendizagem validada pela equipe. |
| 1.2.2 Objetivo, regras e pontuação | Alexia | Objetivo, regras e pontuação claros e curtos; feedback imediato descrito; regras compreendidas por alguém de fora da equipe. |
| 1.3.1 Protótipo de baixa fidelidade | Bernardo V. | Cartões de papel e rascunho do tabuleiro prontos e utilizáveis; protótipo reflete as regras e a pontuação. |
| 1.3.2 Playtest interno | (ver Revisão) | Playtest com a equipe, falhas registradas. |
| 3.1.2 e 3.1.4 | Giovanni | Roadmap aprovado; backlog priorizado. |

**Weekly**
- João Pedro: descreveu os 5 elementos do prompt; estava fazendo as mecânicas ligadas aos padrões de Björk; sem impedimentos.
- Alexia: escreveu regras e pontuação de forma clara e curta; sem impedimentos.
- Bernardo V.: fez o protótipo de baixa fidelidade e registrou.

**Revisão:** entregues 1.1.1, 1.2.1, 1.2.2, 1.3.1, 3.1.2 e 3.1.4. A 1.3.2 (playtest) ficou pendente.
**Feedback do cliente:** estava tudo certo, seguir para a Sprint 3.

**Retrospectiva:** é preciso se comprometer mais em testar o jogo para desenvolver com eficiência; o playtest inicial deve ser feito com toda a equipe o quanto antes.

**Incremento:** mecânicas de Björk ([docs/Mecanicas_de_Bjork.pdf](Mecanicas_de_Bjork.pdf)), primeira versão do tabuleiro, das cartas de problema e de poder, dos versos, dos robôs e da ficha do avaliador, e a primeira versão do validador.

---

## Sprint 3: Prototipagem e conteúdo

**Objetivo:** ter o protótipo de média fidelidade (cartas impressas e regras refinadas), a primeira versão do Manual do Professor, um esboço do suporte digital offline e concluir o playtest interno pendente da Sprint 2.

**Histórias do Sprint Backlog**

| História | Responsável | Critérios de aceite (DoD) |
| --- | --- | --- |
| 1.1.2 Conceitos, dores, necessidades, localização e documentos | João Pedro Ferreira Afonso | Elementos incluídos no jogo, cada um com pelo menos 1 exemplo adaptado à realidade da escola; aprovado pelo cliente. |
| 1.1.3 Ética (vieses, dados sensíveis, boas práticas e LGPD) | Bernardo N. | Temas descritos e incluídos no jogo, cada um com pelo menos 1 situação prática; validado pelo cliente. |
| 1.1.4 Níveis de dificuldade | Alexia | Níveis do básico ao avançado, com critérios de progressão e pelo menos 1 desafio por nível. |
| 1.2.3 Jogo em grupo com papéis | Bernardo V. | Papéis definidos, regras de cooperação e pontuação coletiva claras; dinâmica testada com um grupo. |
| 1.3.3 Cartas impressas e regras refinadas | Bernardo V. | Utilizáveis sem internet; refletem os ajustes do playtest da Sprint 2; protótipo registrado em foto ou escaneamento. |
| 1.4.1 Manual do Professor | Vitor | Regras e passo a passo da aula, em linguagem clara para um professor sem treinamento prévio. |
| 2.1.1 Tela para escrever o prompt | Vitor | Tela simples, funcionando sem internet, testada por alguém de fora da equipe. |
| 2.2.1 Lógica de gabarito | Vitor | Critérios, pontuação e respostas esperadas por desafio; o validador simula a avaliação de uma IA sem internet. |
| 1.3.2 Playtest interno | Bernardo N. | Playtest com a equipe; falhas e dúvidas registradas; ajustes listados. |

**Weekly**
- João Pedro: colocou conceitos, dores, necessidades, localização e documentos como elementos do prompt do jogo; sem impedimentos.
- Bernardo N.: incluiu os temas de ética no jogo; iria realizar o playtest com a equipe.
- Alexia: definiu os níveis de dificuldade; estava descrevendo os desafios.
- Bernardo V.: definiu os papéis dos jogadores, imprimiu as cartas e ajustou as regras; precisava testar a dinâmica com outro grupo.

**Revisão:** entregues todas as 9 histórias (1.1.2, 1.1.3, 1.1.4, 1.2.3, 1.3.3, 1.4.1, 2.1.1, 2.2.1 e 1.3.2).
**Feedback do cliente:** a ordem para dar nota ao prompt é Contexto, Persona, Tarefa e Formato.

**Retrospectiva:** a equipe conseguiu concluir tudo corretamente, só precisando ajustar pequenas coisas a partir do feedback do cliente. Agora o foco é a produção e o refinamento do jogo e das mecânicas.

**Incremento:** Manual do Professor (primeira versão), vídeo do manual, tabuleiro A3 v2, cartas de problema e de superpoder v3, peças dos robôs e validador v2.

