# FitFolio Docs Agent Guide

Este repositório publica o Product Guide do FitFolio. O leitor é usuário, profissional ou pessoa avaliando o produto.

## Voz

- Português do Brasil, direto, acolhedor e claro.
- Explique ações reais do produto sem parecer documentação técnica interna.
- Preserve acentos em textos visíveis.
- Mantenha slugs, paths e nomes de arquivos em ASCII.

## Design visual

- A documentação deve seguir o visual real do FitFolio: preto, branco, cinza e superfície funcional.
- Não use verde como cor de marca, cor de CTA, cor de link ativo ou cor de scrollbar.
- Use Geist como fonte principal quando disponível, com fallback para Inter e fontes do sistema.
- Prefira superfícies pretas (`#000000`) e elevadas quase pretas (`#080808`), bordas brancas em baixa opacidade e texto branco/cinza.
- Todo foco interativo deve ter `focus-visible` claro e testável.

## Limites públicos

- Não exponha arquitetura interna, coleções, regras de acesso, secrets, payloads, Cloud Functions ou ferramentas administrativas.
- Não descreva o app como substituto de médico, nutricionista ou treinador.
- Não trate recursos planejados como se já estivessem disponíveis.
- Não copie conteúdo de lojas, artigos ou posts externos; resuma e cite quando necessário.

## Estrutura

- `product-guide/`: usuário final.
- `professionals/`: profissionais e acompanhamento.
- `help/`: suporte, privacidade, segurança e conta.

Antes de editar navegação, valide se todas as páginas adicionadas existem no `docs.json`.
