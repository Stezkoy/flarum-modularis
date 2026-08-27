# Modularis

![Flarum](https://img.shields.io/badge/Flarum-%5E2.0-26A5E4)
![PHP](https://img.shields.io/badge/PHP-%5E8.3-777BB4)
![License](https://img.shields.io/badge/license-MIT-green)

[Русская версия](README_RU.md)

Manage custom CSS styles for the forum and the admin panel: split styles into named blocks, enable/disable them individually and group them by area.

## Features

- Separate sections for Forum and Admin Panel styles
- Named styles with individual activation toggle
- Create, edit and delete styles
- CSS validation against dangerous constructs (`@import`, `javascript:`, HTML tags, data URIs)
- Active styles are cached for performance

## Installation

```bash
composer require stezkoy/flarum-modularis
php flarum migrate
php flarum assets:publish
```

## Requirements

- PHP ^8.3
- Flarum ^2.0

## License

MIT · [Stezkoy](https://github.com/Stezkoy)
