# Instruções para agentes (Cursor / Claude / Grok)

Markdown livre, sem campos obrigatórios. Este arquivo é a base para copiar nos projetos da House: PreHouse, PhotoHouse, LightHouse, HOUSE-ROOM e House Academy. O `AGENTS.md` mais próximo do arquivo editado é o que vale.

O jeito de trabalhar está no [CONTRIBUTING.md](https://github.com/HOUSE-DE-CRIATIVIDADE/.github/blob/main/CONTRIBUTING.md). Vulnerabilidade e segredo estão no [SECURITY.md](https://github.com/HOUSE-DE-CRIATIVIDADE/.github/blob/main/SECURITY.md).

## Visão geral do projeto

<o que este repositório é, em uma frase>

É pra <pra quem>. Os projetos da House são:

- PreHouse é o Premiere da House.
- PhotoHouse é o Photoshop da House.
- LightHouse é o Lightroom da House.
- HOUSE-ROOM é o site central da House.
- House Academy é a plataforma de cursos da House.

A missão da House é creative minds for the kingdom.

## Comandos

Rode lint, testes e build antes de commitar e corrija até ficar verde.

- Setup: `<comando>`
- Dev: `<comando>`
- Teste: `<comando>`
- Lint: `<comando>`
- Build: `<comando>`

## Estrutura do repositório

- `<pasta/>` — <o que mora aqui>
- `<pasta/>` — <o que mora aqui>

## Estilo de código

<convenção deste repositório: nomes, arquivos, formato>

Siga o padrão do código ao redor. Comentários e textos de interface ficam em português.

## Testes

Adicione ou atualize testes para o que mudar. Rode o comando de teste acima.

## Issues

O título da issue sempre leva a tag `[BUG]` ou `[IDEIA]`. O corpo tem Contexto, Escopo e Fora de escopo. Use os modelos de issue da organização.

## Labels

Use só as labels padrão da org: `bug`, `ideia`, `design`, `vídeo`, `copy`, `docs`, `urgente` e `ajuda`. Nunca crie labels `priority:*`. A prioridade fica no campo Priority do Project da org.

## Git

Trabalhe numa branch sua, com prefixo `feat/`, `fix/`, `design/`, `chore/` ou `docs/`. Nunca faça commit direto na `main`. O pull request aponta para a `main` e precisa de pelo menos 1 aprovação do líder. Nunca faça merge sem um OK explícito.

## Versão

Não edite `version` no `package.json`. A tag e a Release saem no merge, pelo workflow. O nível vem das labels `versao:major`, `versao:minor`, `versao:patch` ou `versao:nenhuma`, ou do título do PR.

## Commits

O autor é Guilherme Aranega <guilhermee.aranega@gmail.com>. Não use Cursor Agent como autor nem como co-autor. A mensagem é curta e leva um prefixo: `FEAT:`, `FIX:`, `DOCS:` ou `CHORE:`.

## Pull request

O título leva um prefixo: `FEAT:`, `FIX:`, `DOCS:` ou `CHORE:`. Use o modelo de PR da organização. Descreva como testar. Se a mudança for visual, inclua print ou vídeo. Uma mudança por PR.

## Segurança

Nunca faça commit de segredo: `.env`, chave, token ou senha. Não logue dados pessoais. Dependência nova só entra com justificativa. Se algo vazar, avise os admins na hora. O caminho está no [SECURITY.md](https://github.com/HOUSE-DE-CRIATIVIDADE/.github/blob/main/SECURITY.md).

## Limites do agente

Nunca faça merge, deploy, force-push, apagar branches ou mexer em configuração da org sem OK explícito do líder. Não edite arquivos gerados nem lockfiles na mão. Em dúvida, pergunte.

## Monorepo

Se uma parte do repositório pedir outra regra, coloque um `AGENTS.md` aninhado na subpasta. O mais próximo manda.
