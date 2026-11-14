# verbissimo-content

Публичная раздача Verbissimo: пакеты — в Releases, `config.json` и `catalog.json` — на Pages.

- **Releases** `content-v1 … content-vN` — пакеты контента (`a1-data.json`, `a2-data.json`, …); опубликованный релиз
  не меняется.
- **Pages** (`docs/` → `verbissimo.akuma.in`) — `config.json`, `catalog.json` (полные ссылки на пакеты + sha256),
  страницы конфиденциальности и поддержки.

Пока пусто: содержимое публикует Studio из `verbissimo-apps`. Схема и правила — `verbissimo-apps/docs/ROADMAP.md`
§1.2–§1.3. Локально клонируется в `~/_dev/Verbi/content` рядом с `apps/` и `content-src/`.
