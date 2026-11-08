# UI/UX Skills

Coleção de skills de interface (UI/UX) para Claude Code, Codex e Cursor.

## Skills

| Skill | Para que serve |
|---|---|
| `ui-skills-root` | Roteador: escolhe a menor skill de UI útil para a tarefa |
| `baseline-ui` | Limpeza rápida: espaçamento, hierarquia, tipografia, layout |
| `improve-ui` | Auditoria de interface + planos de implementação (somente leitura) |
| `fixing-accessibility` | ARIA, teclado, foco, contraste, formulários (WCAG) |
| `fixing-motion-performance` | Animações travando, layout thrashing, scroll |
| `fixing-metadata` | Title, meta tags, Open Graph, SEO técnico da página |
| `create-design-md` | Gera um DESIGN.md com tokens e linguagem visual de um produto/site |
| `component-canvas` | Canvas interativo para explorar componentes e variantes |
| `create-canvas` | Canvas livre para explorar, comparar e iterar |

## Instalação

```bash
git clone https://github.com/eustudiox/ui-ux-skills.git ~/ui-ux-skills
cp -R ~/ui-ux-skills/skills/* ~/.claude/skills/
```

## Créditos

Skills originais do projeto [ui-skills](https://github.com/ibelick/ui-skills) por ibelick (MIT).
