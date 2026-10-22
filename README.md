<div align="center">

# ✳ bobrek

**Личная био-страница в стиле терминала и глитча.**
Статический сайт: один HTML, CSS и JS, без сборки и без фреймворков.

[![Live](https://img.shields.io/badge/live-open-7c3aed?style=for-the-badge)](https://screpka228.github.io/bobrek-bio/)
[![No Build](https://img.shields.io/badge/build-none-22c55e?style=for-the-badge)](#-запуск)
[![Vanilla JS](https://img.shields.io/badge/vanilla-JS%2FCSS-f7df1e?style=for-the-badge)](#-структура)

</div>

---

## ✨ Что внутри

- 🪪 **Карточка профиля**: аватар, имя, теглайн, локация.
- 🟢 **Статус Discord**: аватар, статус онлайн и активность через Discord User ID.
- 🔗 **Соцсети**: кнопки из списка в `config.js`.
- 🎵 **Плеер SoundCloud**: плейлист, перемотка, громкость, повтор, переключение треков.
- 👁️ **Счётчик посещений** в футере.
- 🌨️ **Атмосфера**: снег, курсор-точка, сканлайны и глитч-линия на фоне.

---

## ⚙️ Настройка

Всё настраивается в одном файле, `config.js`. Код `script.js` трогать не нужно.

| Что | Где | Комментарий |
| --- | --- | --- |
| Discord User ID | `config.js` | Без него блок статуса показывает «Discord presence not configured» |
| Соцсети | `config.js` | Список ссылок, которые появятся под карточкой |
| Плейлист | `index.html` | Ссылка `soundcloud.com/.../sets/...` в блоке плеера |

---

## 🚀 Запуск

Это статический сайт. Сборка не нужна.

```bash
# вариант 1: открыть index.html в браузере
# вариант 2: локальный сервер
npx serve .
```

---

## 🗂️ Структура

```
bobrek-bio/
├── index.html         # разметка: карточка, плеер, футер
├── style.css          # стили, эффекты, адаптив
├── script.js          # статус, плеер, снег, курсор
├── config.js          # личные настройки: Discord ID, соцсети
├── avatar-fallback.svg
└── LICENSE
```

---

## 📄 Лицензия

Подробности в [LICENSE](LICENSE).

---

<div align="center">

Сделано вайб-кодингом. ✳

</div>
