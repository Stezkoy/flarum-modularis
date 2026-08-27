# Modularis

![Flarum](https://img.shields.io/badge/Flarum-%5E2.0-26A5E4)
![PHP](https://img.shields.io/badge/PHP-%5E8.3-777BB4)
![License](https://img.shields.io/badge/license-MIT-green)

[English version](README.md)

Менеджер пользовательских CSS-стилей для форума и админ-панели: разбивайте стили на именованные блоки, включайте/отключайте их по отдельности и группируйте по областям.

## Возможности

- Отдельные разделы для стилей Форума и Админ-панели
- Именованные стили с индивидуальным переключателем активации
- Создание, редактирование и удаление стилей
- Валидация CSS против опасных конструкций (`@import`, `javascript:`, HTML-тегов, data URI)
- Активные стили кэшируются для производительности

## Установка

```bash
composer require stezkoy/flarum-modularis
php flarum migrate
php flarum assets:publish
```

## Требования

- PHP ^8.3
- Flarum ^2.0

## Лицензия

MIT · [Stezkoy](https://github.com/Stezkoy)
