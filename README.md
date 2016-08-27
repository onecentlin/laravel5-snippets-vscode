# Laravel 5 Snippets

Laravel 5 snippets for Visual Studio Code.

## Screenshot

![Screenshot](https://github.com/onecentlin/laravel5-snippets-vscode/raw/master/images/screenshot.gif)

## What's New in 1.3

* Support new snippets for Laravel 5.3 API Authentication ([Passport](https://laravel.com/docs/5.3/passport))
* Add missing support in Authentication: `Auth::guard`, `Auth::attempt`, `Auth::login`, `Auth::loginUsingId`, `Auth::viaRemember`, `Auth::routes`

## Installation

* Launch VS Code Quick Open (Ctrl+P), paste the following command `ext install laravel5-snippets`, and press enter.
* Open Extension Panel: search `Laravel 5 Snippets` and install

## Usage

Snippet prefix follows Laravel Facades. For example: `Request::`, `Route::`

## Support Snippet Prefix

* Auth
* Cache
* Config
* Console
* Cookie
* Crypt
* DB
* Event
* Hash
* Helper
* Log
* Mail - Contains `Mail::` and `Mailable::` prefix for mail related settings
* Passport (Laravel v5.3 - [API Authentication](https://laravel.com/docs/5.3/passport))
* Redirect
* Relation
* Request
* Response
* Route
* Schema - Contains `Schema::` and `Column::` prefix for database related settings
* Session
* Storage
* View

> Blade - Please install `Laravel Blade Snippets` [extension](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel-blade) for blade syntax highlighting and better support with blade and emmet.

## Contact

Please file any [issues](https://github.com/onecentlin/laravel5-snippets-vscode/issues) or have a suggestion please tweet me [@onecentlin](https://twitter.com/onecentlin).

## Credits

* Snippets based on [Laravel 5 Snippets for Sublime Text](https://github.com/Lykegenes/laravel-5-snippets)

## License

Please read [License](https://github.com/onecentlin/laravel5-snippets-vscode/blob/master/LICENSE.md) for more information.