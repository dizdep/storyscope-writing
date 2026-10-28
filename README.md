# storyscope-writing

Скилл для Claude, который учит агента писать прозу как человек — через структурные решения (сюжет, время, тема, персонажи), а не через замену слов. Основан на исследовании [StoryScope](https://arxiv.org/abs/2604.03136) (University of Maryland + Google DeepMind, 2026).

## Установка в Claude Code

В терминале:

```bash
claude plugin marketplace add dizdep/storyscope-writing
claude plugin install storyscope-writing@storyscope
```

Или внутри сессии Claude Code:

```
/plugin marketplace add dizdep/storyscope-writing
/plugin install storyscope-writing@storyscope
```

Скилл срабатывает автоматически, когда вы просите написать или переписать рассказ, сцену, диалог или «сделать текст живее». Вызвать вручную: `/storyscope-writing:storyscope-writing`.

Обновление: `claude plugin marketplace update storyscope`.

## Установка в Claude.ai

Скачайте `storyscope-writing.skill` из раздела Releases и загрузите его в Settings → Capabilities → Skills.

## Что внутри

- `SKILL.md` — рабочий процесс: карта структурных решений → письмо → аудит → структурная правка.
- `references/checklist.md` — чек-лист из 14 «ИИ-сигналов» с цифрами из исследования.

## Лицензия

MIT
