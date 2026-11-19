# Equalizer APO — дзеркало з SourceForge

Equalizer APO — параметричний і графічний еквалайзер для Windows, що працює на рівні всієї системи. Він реалізований як Audio Processing Object (APO) для інфраструктури системних звукових ефектів Windows (з'явилася у Windows Vista).

Цей репозиторій — **дзеркало** офіційного Git-репозиторію проєкту на SourceForge. Автор оригіналу — Jonas Thedering (так у копірайтах коду; у комітах — Jonas Dahlinger, акаунт SourceForge `jthedering`). Тут немає власних змін коду, крім цього файлу `README.md`.

## Джерело

- Проєкт: https://sourceforge.net/projects/equalizerapo/
- Код: https://sourceforge.net/p/equalizerapo/code/ci/main/tree/
- Git URL: `https://git.code.sf.net/p/equalizerapo/code`
- Вікі (встановлення та налаштування): https://sourceforge.net/p/equalizerapo/wiki/

## Як створено дзеркало

Імпортовано 2026-11-19 через GitHub Importer, з повною історією:

- гілка `main` — 88 комітів;
- теги версій від `0.5` до `1.4.2`;
- останній коміт на момент імпорту — `bbfcc3e5024cbb9d61ba75fc88d78605cc4c9687` (2025-11-28, «Switched from Uncrustify to ClangFormat and reformatted all code.»).

Дзеркало **не оновлюється автоматично**.

## Як перевірити й підтягнути зміни з SourceForge

Додайте SourceForge як окремий remote:

```bash
git remote add upstream https://git.code.sf.net/p/equalizerapo/code
```

Завантажте зміни та подивіться нові коміти:

```bash
git fetch upstream --tags
```

```bash
git log --oneline main..upstream/main
```

Якщо список порожній — нових змін немає. Якщо є — злийте їх:

```bash
git merge upstream/main
```

## Ліцензія

GNU GPL версії 2 або новішої — див. [`License.txt`](License.txt).
