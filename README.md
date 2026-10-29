# tilda-skills

Скиллы Claude для вёрстки сайтов на Tilda, собранные на реальных проектах. Сейчас здесь один плагин:

- **tilda** — скилл `tilda-layout` «Верстка на Tilda»: правила переноса макетов из Figma в Zero Block, адаптив, типографика, изображения.

## Установка в Claude Code

```
/plugin marketplace add PashaMozhet1/tilda-skills
/plugin install tilda@tilda-skills
```

Обновить до свежей версии:

```
/plugin marketplace update tilda-skills
```

Скилл подхватывается автоматически, когда вы просите Claude сверстать или поправить страницу на Tilda.

## Использование в claude.ai

Скачайте папку `plugins/tilda/skills/tilda-layout`, упакуйте её в zip и загрузите в Settings → Capabilities → Skills.

## Как дополнять

Правила лежат в `plugins/tilda/skills/tilda-layout/SKILL.md`, сгруппированы по темам. Добавьте правило в подходящую группу, поднимите `version` в `plugins/tilda/.claude-plugin/plugin.json` и откройте PR (или закоммитьте, если вы владелец).
