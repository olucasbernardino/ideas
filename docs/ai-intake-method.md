# AI Intake Method

Este repositório usa um processo de intake para ajudar usuários a transformar ideias vagas em pedidos claros, testáveis e executáveis por IA.

O objetivo não é obrigar o usuário a escrever prompts perfeitos. O objetivo é fazer a IA extrair o contexto certo antes de agir.

## Princípio

A IA deve adaptar suas perguntas à intenção do usuário.

Uma tarefa simples deve continuar simples. Uma solicitação ampla, estratégica ou arriscada deve ser esclarecida antes da implementação.

## Fluxo

1. O usuário descreve uma intenção.
2. A IA classifica o tipo de pedido.
3. A IA verifica se há contexto suficiente.
4. Se houver contexto suficiente, a IA prossegue.
5. Se faltar contexto, a IA faz perguntas objetivas ou oferece um template curto.
6. O usuário preenche as lacunas relevantes.
7. A IA resume objetivo, restrições e critérios de sucesso.
8. A IA executa, testa e reporta evidências.

## Por que isso importa

Muitos usuários não falham por falta de ideias. Eles falham porque não sabem quais informações uma IA precisa para entregar um trabalho excelente.

O intake funciona como um coach de briefing, estratégia de produto e filtro de execução.

## Objetivos de design

- Reduzir pedidos vagos.
- Evitar implementações precipitadas.
- Melhorar o pensamento de produto.
- Tornar o trabalho com IA mais repetível.
- Manter tarefas simples rápidas.
- Tornar tarefas complexas mais rigorosas.

## Antiobjetivos

- Não forçar templates longos para todo pedido.
- Não bloquear mudanças óbvias e pequenas.
- Não substituir julgamento humano.
- Não transformar toda interação em burocracia.

## Exemplo

Usuário:

> Quero melhorar o onboarding.

IA:

> Esse pedido é amplo o suficiente para eu precisar de mais contexto antes de propor mudanças. Preencha o que souber:
>
> - Objetivo:
> - Usuário-alvo:
> - Problema atual do onboarding:
> - Resultado desejado:
> - Referências de produto:
> - Restrições:
> - Critérios de sucesso:

## Critério de qualidade

Um bom intake deve deixar claro:

- o que será feito;
- por que isso importa;
- o que está fora de escopo;
- como validar se deu certo;
- quais riscos precisam ser considerados.
