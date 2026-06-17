# FitFolio Product Guide

Documentação pública do FitFolio em Mintlify.

Este repositório é separado do app principal porque o Product Guide é público. Ele deve explicar o produto para usuários, profissionais e pessoas avaliando o FitFolio, sem expor detalhes internos de Firebase, regras, chaves, coleções privadas, Cloud Functions ou rotinas administrativas.

## Estrutura

- `docs.json`: configuração principal do Mintlify.
- `index.mdx`: entrada do guia.
- `product-guide/`: uso do app por usuários finais.
- `professionals/`: uso e visão pública para profissionais.
- `help/`: FAQ, suporte, privacidade e exclusão de conta.
- `assets/`: logo, favicon e imagens públicas.

## Comandos locais

Instale a CLI do Mintlify se ainda não tiver:

```bash
npm i -g mint
```

Rode o preview local:

```bash
mint dev --no-open
```

Valide a documentação:

```bash
mint validate
```

## Regras editoriais

- Escreva em português do Brasil.
- Preserve acentos no texto visível.
- Use slugs, nomes de arquivos e identificadores técnicos em ASCII.
- Trate números públicos como snapshots datados.
- Não prometa prescrição médica, nutricional ou de treino.
- Deixe claro quando IA é apoio e quando o usuário deve revisar manualmente.
- Não publique detalhes internos de implementação, segurança, Firestore, Storage ou funções administrativas.
