# PHP / Laravel — engineering notes

Modernising legacy PHP into maintainable, tested, idiomatic Laravel, with an eye on application security. Focus on code that stays readable and safe over time: thin controllers, authorisation in policies, `declare(strict_types=1)`, PHPStan level 6, CI on every push.

## Selected work

- **[legacy-php-to-laravel](https://github.com/Yeonik/legacy-php-to-laravel)** — a 2010-era procedural CMS and its Laravel rewrite, side by side. Catalogued findings, a strangler-fig migration plan, and a transparent MD5 to bcrypt password upgrade on login. Built to be read in 90 seconds.
- **[laravel-legacy-password-upgrader](https://github.com/Yeonik/laravel-legacy-password-upgrader)** — a small Laravel package that transparently upgrades legacy MD5/SHA1 password hashes to bcrypt on login. Tested, PHPStan level 6, CI on Laravel 12.

## Focus

`PHP 8.3` · `Laravel` · `PHPStan / Larastan` · `Pint` · `PHPUnit` · `Docker` · `GitHub Actions` · `Application Security`
