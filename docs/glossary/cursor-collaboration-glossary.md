# Cursor Collaboration Glossary

Este glossário reúne termos e frases que você pode usar comigo para trabalhar melhor no repositório.

## Git e versionamento

- **Branch**: linha separada de trabalho. Use quando quiser isolar uma ideia, correção ou experimento.
- **Main**: branch principal do projeto. Normalmente é a base para novas branches.
- **Commit**: registro de um pacote de mudanças no histórico do Git.
- **Mensagem de commit**: texto curto que explica o que mudou.
- **Stage**: seleção dos arquivos que entram no próximo commit.
- **Diff**: comparação que mostra exatamente o que mudou.
- **Status**: estado atual do Git, incluindo branch, arquivos alterados e arquivos novos.
- **Push**: envio dos commits locais para o GitHub.
- **Pull**: atualização da máquina local com mudanças vindas do GitHub.
- **Remote**: repositório remoto, geralmente no GitHub.
- **Origin**: nome padrão do remote principal.
- **Pull Request** ou **PR**: pedido para revisar e juntar uma branch em outra.
- **Draft PR**: PR em rascunho, útil quando a mudança ainda está em validação.
- **Merge**: ação de juntar uma branch em outra.
- **Rebase**: reaplicação de commits sobre outra base. É útil, mas mais avançado.
- **Stash**: armazenamento temporário de mudanças ainda não commitadas.
- **Checkout**: troca para outra branch ou criação de uma nova branch.
- **Revert**: criação de um novo commit que desfaz uma mudança anterior.

## Cursor e IA

- **Agent**: modo em que a IA pode ler arquivos, editar, rodar comandos, testar e validar.
- **Plan Mode**: modo para planejar antes de implementar.
- **Debug Mode**: modo para investigar bugs com hipóteses, logs e evidência de execução.
- **Cloud Agent**: agente que roda em uma máquina na nuvem para trabalhar em uma tarefa.
- **Automation**: gatilho automático que inicia agentes a partir de eventos, horários ou integrações.
- **Rule**: instrução persistente que influencia o comportamento do Cursor.
- **AGENTS.md**: arquivo de instruções gerais para agentes dentro do repositório.
- **Skill**: fluxo reutilizável com instruções específicas para uma tarefa recorrente.
- **MCP**: conexão entre o Cursor e ferramentas externas, como bancos, APIs e sistemas internos.
- **Bugbot**: agente de revisão focado em encontrar bugs, regressões e riscos em PRs.

## Termos de trabalho

- **Contexto**: informações que ajudam a IA a tomar boas decisões.
- **Escopo**: limite do que deve ou não ser feito.
- **Critério de sucesso**: condição que mostra que a tarefa ficou correta.
- **Validação**: conferência de que a solução atende ao objetivo.
- **Teste automatizado**: teste executado por comando ou ferramenta.
- **Teste manual**: teste feito interagindo com a aplicação ou verificando o resultado diretamente.
- **Artifact**: evidência gerada pelo agente, como screenshot, vídeo, log ou arquivo de saída.
- **Rollback**: plano ou ação para desfazer uma mudança.
- **Migração**: alteração estruturada em banco de dados ou dados persistidos.
- **Refactor**: melhoria interna no código sem mudar o comportamento esperado.
- **Feature**: nova funcionalidade.
- **Bugfix**: correção de comportamento incorreto.

## Frases úteis para pedir trabalho

- "Explique o status atual do Git."
- "Mostre o diff antes de salvar."
- "Crie uma branch para essa mudança."
- "Faça um commit com uma mensagem clara."
- "Rode os testes relevantes antes do commit."
- "Faça push da branch."
- "Abra um PR em draft."
- "Atualize o PR com o que mudou."
- "Não faça push ainda."
- "Não edite arquivos não relacionados."
- "Valide antes de implementar."
- "Use Plan Mode e não edite nada ainda."
- "Use Debug Mode para reproduzir antes de corrigir."
- "Explique o que você entendeu antes de executar."
- "Crie um template para eu preencher."
- "Transforme essa ideia em uma especificação."
- "Liste riscos, dependências e critérios de sucesso."
- "Implemente, teste e me mostre evidências."
- "Reverta apenas a sua última mudança."

## Como pedir melhor

Use esta estrutura quando a tarefa for importante:

1. **Objetivo**: o que você quer alcançar.
2. **Contexto**: por que isso importa.
3. **Escopo**: o que entra e o que fica fora.
4. **Restrições**: limites técnicos, produto, prazo, design ou segurança.
5. **Critério de sucesso**: como saberemos que ficou bom.
6. **Teste esperado**: como validar o resultado.

Exemplo:

> Quero criar uma página de onboarding para novos usuários. O objetivo é reduzir dúvidas no primeiro acesso. Não quero mexer no backend agora. Antes de implementar, me ajude a definir escopo, critério de sucesso e testes.
