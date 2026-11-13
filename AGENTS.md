# AGENTS.md: regras para agentes neste repositório

Imagens públicas dos posts do Instagram da Pareto Plus. Cada pasta guarda as imagens de uma peça.

## Quem é quem
- **Victor Santana (`victorsantana1995`)**: dono e CEO da Pareto Plus. É o único que pede trabalho ao agente e quem aprova e mescla os PRs. Não é programador: escreva para ele em linguagem de negócio.
- **`victorsantana-ui-superagente`**: o agente automático. Abre PR e comenta; nunca mescla.

## Como trabalhar
- A ramificação principal só muda por PR com 1 aprovação. Não tente gravar direto nela.
- Ramificação `agent/<assunto>`, um assunto por PR, a menor mudança que resolve tudo.
- Português do Brasil simples em tudo o que uma pessoa lê (título e descrição do PR, comentários, commits). O título diz o que muda para o Victor; a descrição diz o que foi feito, como foi testado e como desfazer.
- Toda mensagem do agente termina com a linha: "Esta mensagem é de um agente automático, não de uma pessoa."
- Segredo (chave, token, senha, webhook) nunca vai para arquivo, commit, log, issue ou PR.
- Dúvida de regra de negócio: pergunte na issue antes de escrever código.

## Deste repositório
- Este repositório é **público**: só entram imagens e vídeos já aprovados para publicação. Nunca coloque nele dado de cliente, segredo, rascunho ou texto interno.
- Uma pasta por peça, com o nome já usado nas pastas existentes (`ig-AAAAMMDD`, `carrossel-...`, `reel-...`). Não renomeie nem apague pasta: o endereço dela pode estar em uma publicação no ar.
- Não é o lugar de código nem de documentação.
