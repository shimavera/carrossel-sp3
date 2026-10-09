# Carrossel SP3

Fluxo para configurar uma marca e produzir conteúdo de Instagram com pesquisa editorial, copy, direção visual, revisão e aprovação.

**Autor:** Juan Lourenco  
**Versão:** 1.0.0

## O que vem no pacote

- `skills/carrossel-sp3/`: onboarding da marca até aprovação e entrega.
- `skills/copy-social/`: headlines, estrutura de carrossel, legendas e revisão de copy.
- `skills/direcao-visual/`: referências, composição, prompts e direitos de imagem.
- `skills/pautas-editoriais/`: ideação, pesquisa e priorização de assuntos.
- `templates/Marca-template/`: pastas e arquivos iniciais para cada marca.
- `examples/saudecrm/`: cinco artes finais feitas para SaúdeCRM, incluídas como exemplos visuais.

O pacote não publica nem agenda conteúdo por conta própria. A publicação é manual, após aprovação. Pesquisa atual depende de acesso a navegador/web no ambiente em que as skills forem usadas. Um editor visual disponível no cliente pode ser usado para montar e exportar as peças.

## Como instalar no Codex

1. Baixe ou clone este repositório.
2. Copie as pastas dentro de `skills/` para `~/.codex/skills/` (ou a pasta de skills definida no seu ambiente).
3. Reinicie ou atualize o Codex para que ele carregue as skills.
4. Comece com: **“Use Carrossel SP3 para configurar minha marca.”**

As quatro skills podem ser instaladas separadamente; para o fluxo completo, instale todas.

## Como instalar no Claude Code

Copie as pastas dentro de `skills/` para `.claude/skills/` no projeto ou para `~/.claude/skills/` no perfil do usuário. As instruções de cada skill ficam em `SKILL.md`.

## Primeira configuração da marca

1. Duplique `templates/Marca-template/` uma vez para cada marca.
2. Preencha `00 - Perfil e briefing/Perfil da marca.md` com mercado, nicho, público, região, objetivo, tom, palavras permitidas/proibidas e tipos de comunicação.
3. Coloque o logo original em `01 - Identidade da marca/Logo - enviar aqui/`. Prefira PNG transparente ou SVG. Adicione manual, paleta, fontes e referências visuais nas pastas correspondentes.
4. Em `02 - Fontes editoriais/Fontes editoriais.md`, liste somente portais e URLs que a marca escolheu, temas, idioma e janela de recência.
5. Ajuste emojis, hashtags, CTA, créditos e presença de fontes públicas em `04 - Copies e legendas/Preferências de legenda.md`.
6. Peça ao Carrossel SP3 uma pauta, post ou carrossel. Revise copy e prévia e aprove antes de publicar.

Não misture perfis, logos, fontes ou históricos entre marcas. O assistente deve perguntar sobre dados essenciais ausentes; não deve inventar identidade nem fontes autorizadas.

## Exemplos visuais

As artes em `examples/saudecrm/` são peças finalizadas para a marca SaúdeCRM e demonstram uma aplicação possível do fluxo. [Veja a galeria](examples/saudecrm/README.md). Não reutilize a logo ou a identidade SaúdeCRM em outra marca. Os créditos e os limites de uso das fotos estão em [`examples/saudecrm/CRÉDITOS.md`](examples/saudecrm/CR%C3%89DITOS.md). As fotos originais não são fornecidas separadamente.

## Uso responsável

Confira matéria original, datas e fatos antes de publicar. Registre links e créditos na ficha interna. Use imagens próprias, autorizadas ou com licença compatível; não reutilize foto de notícia sem permissão e não trate imagem ilustrativa como registro do evento. A pessoa responsável pela marca aprova texto e arte finais.

## Licença e contribuições

Consulte [LICENSE.md](LICENSE.md). O uso do pacote é permitido para a própria marca, inclusive comercialmente; revenda e redistribuição do pacote não são permitidas. Este repositório contém instruções e skills originais de Juan Lourenco e não inclui o editor derivado do Carrossel Pro. Não reivindica direitos sobre plataformas ou ativos de terceiros.
