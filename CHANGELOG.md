# Изменения

## 1.3.0

- Новый алфавит — английская транскрипция BGN/PCGN (`alphabets/english.json`, #4).

## 1.2.0

- Версия в Profile README сама: job `profile` workflow `release` (секрет `PROFILE_TOKEN`).

## 1.1.0

- Релиз из тега workflow `release`: архив `translit-<версия>.tgz` в GitHub Release.
- Новые алфавиты — чешская (`alphabets/czech.json`) и польская (`alphabets/polish.json`) транскрипции.
- Проверка `ci` на каждый PR и push в `main`, сайт — сам после слияния (`pages`), ревью агента (`review`), правки по `@claude` (`claude`), Dependabot.

## 1.0.0

- Свой алфавит по умолчанию — ISO 9; README с примером и разделом «откуда».
- Версия 1.0: формат алфавитов и настройки стабилен до 2.0.
