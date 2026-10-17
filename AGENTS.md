# Instruções para agentes (Cursor / Claude / Grok)

Este arquivo é a base para copiar nos projetos da House: PreHouse, PhotoHouse, LightHouse, HOUSE-ROOM e House Academy. O jeito de trabalhar está no [CONTRIBUTING.md](https://github.com/HOUSE-DE-CRIATIVIDADE/.github/blob/main/CONTRIBUTING.md). Vulnerabilidade e segredo estão no [SECURITY.md](https://github.com/HOUSE-DE-CRIATIVIDADE/.github/blob/main/SECURITY.md).

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

## Segurança

Nunca faça commit de segredo: `.env`, chave, token ou senha. Se algo vazar, avise os admins na hora. O caminho está no [SECURITY.md](https://github.com/HOUSE-DE-CRIATIVIDADE/.github/blob/main/SECURITY.md).
