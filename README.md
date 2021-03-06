# Laravel Preset

The starting point for all **[Alara Creative](https://alaracreative.com)** Laravel projects.

Starts with:

- Laravel Mix Plugins
    - PostCSS Import
    - Precss
    - PurgeCSS
    - Tailwind
- Tailwind
- Vue

Also removes `SASS` directory in favor of a `CSS` directory for `PostCss` and adds a custom `.editorconfig`.

Inspired by Laracasts tutorial.

## Installation

Create a new Laravel project.

Require via composer: `composer require alaracreative/alara-laravel-preset`

Install Preset: `php artisan preset alara`

Install npm: `npm install`

Setup Tailwind: `node_modules/.bin/tailwind init tailwind.js`

Run npm: `npm dev` or `npm watch`

Yay!
