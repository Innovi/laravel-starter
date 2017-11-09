<h1 align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg">IMS</h1>

## About Laravel IMS

Project Description.

## Laravel Documentation

### Getting Started

1. [Installation](https://laravel.com/docs/5.4/installation)
2. [Configuration](https://laravel.com/docs/5.4/configuration)
3. [Directory Structure](https://laravel.com/docs/5.4/structure)


### The Basics

1. [Routing](https://laravel.com/docs/5.4/routing)
2. [Middleware](https://laravel.com/docs/5.4/middleware)
3. [CSRF Proteciton]()
4. [Controller](https://laravel.com/docs/5.4/controllers)
5. [Requests]()
6. [Responses]()
7. [Views](https://laravel.com/docs/5.4/views)
8. [Session]()
9. [Validation]()
10. [Errors &amp; Logging](https://laravel.com/docs/5.4/errors)

### Frontend

1. [Blade Templates](https://laravel.com/docs/5.4/blade)
2. [Localization](https://laravel.com/docs/5.4/localization)
3. [Frontend Scaffolding](https://laravel.com/docs/5.4/frontend)
4. [Compilling Assets](https://laravel.com/docs/5.4/mix)

### Security

1. [Authentication](https://laravel.com/docs/5.4/authentication)
2. [API Authentication]()
3. [Authorization](https://laravel.com/docs/5.4/authorization)
4. [Encryption]()
5. [Hashing]()
6. [Password Reset]()

### Database

1. [Getting Started](https://laravel.com/docs/5.4/database)
2. [Query Builder]()
3. [Pagination]()
4. [Migration](https://laravel.com/docs/5.4/migrations)
5. [Seeding](https://laravel.com/docs/5.4/seeding)
6. [Redis]()

### Eloquent ORM

1. [Getting Started](https://laravel.com/docs/5.4/eloquent)
2. [Relationships](https://laravel.com/docs/5.4/eloquent-relationships)
3. [Collections](https://laravel.com/docs/5.4/eloquent-collections)
4. [Mutators](https://laravel.com/docs/5.4/eloquent-mutators)
5. [Serialization](https://laravel.com/docs/5.4/eloquent-serialization)

### Testing

1. [Getting Started](https://laravel.com/docs/5.4/testing)
2. [HTTP Tests](https://laravel.com/docs/5.4/http-tests)
3. [Browser Tests (Laravel Dusk)](https://laravel.com/docs/5.4/dusk)
4. [Database Testing](https://laravel.com/docs/5.4/database-testing)
5. [Mocking](https://laravel.com/docs/5.4/mocking)

## Artisan Console

Artisan is the command-line interface included with Laravel. It provides a number of helpful commands that can assist you while you build your application.

1. [Introduction](https://laravel.com/docs/5.4/artisan#introduction)
2. [Writing Commands](https://laravel.com/docs/5.4/artisan#writing-commands)
   - [Generating Commands](https://laravel.com/docs/5.4/artisan#generating-commands)
   - [Command Structure](https://laravel.com/docs/5.4/artisan#command-structure)
   - [Closure Commands](https://laravel.com/docs/5.4/artisan#closure-commands)
3. [Defining Input Expectations](https://laravel.com/docs/5.4/artisan#defining-input-expectations)
	- [Arguments](https://laravel.com/docs/5.4/artisan#arguments)
	- [Options](https://laravel.com/docs/5.4/artisan#options)
	- [Input Arrays](https://laravel.com/docs/5.4/artisan#input-arrays)
	- [Input Descriptions](https://laravel.com/docs/5.4/artisan#input-descriptions)
4. [Command I/O](https://laravel.com/docs/5.4/artisan#command-io)
   - [Retrieving Input](https://laravel.com/docs/5.4/artisan#retrieving-input)
   - [Prompting For Input](https://laravel.com/docs/5.4/artisan#prompting-for-input)
   - [Writing Output](https://laravel.com/docs/5.4/artisan#writing-output)
5. [Registering Commands](https://laravel.com/docs/5.4/artisan#registering-commands)
6. [Programmatically Executing Commands](https://laravel.com/docs/5.4/artisan#programmatically-executing-commands)
   - [Calling Commands From Other Commands](https://laravel.com/docs/5.4/artisan#calling-commands-from-other-commands)

## Commit Message Format

Each commit message consists of a **header**, a **body** and a **footer**.  The header has a special
format that includes a **type**, a **scope** and a **subject**.
Extend git commit message from angular style.

All Commit Message Format **MUST** meet this Text Format:

```bash
[:<Emoji>: ][<Type>[(<Scope>)]: ]<Subject>
[<BLANK LINE>]
[<Message Body>]
[<BLANK LINE>]
[<Message Footer>]
```

### Types

| Type          | Description |
|:-------------|-------------|
| `new`         | for new feature implementing commit|
| `feature`     | for new feature implementing commit (equal `new`) |
| `bug`         | for bug fix commit |
| `security`    | for security issue fix commit |
| `performance` | for performance issue fix commit |
| `improvement` | for backwards-compatible enhancement commit |
| `breaking`    | for backwards-incompatible enhancement commit |
| `deprecated`  | for deprecated feature commit |
| `refactor`    | for refactoring commit |
| `docs`        | for documentation commit |
| `examples`    | for example code commit |
| `test`        | for testing commit |
| `dependency`  | for dependencies upgrading or downgrading commit |
| `config`      | for configuration commit |
| `build`       | for packaging or bundling commit |
| `release`     | for publishing commit |
| `update`      | for update commit |
| `wip`         | for work in progress commit |
| `chore`       | for other operations commit |

### Emojis

| Emoji                      | Raw Emoji Code               | Type               | Description |
|:--------------------------:|------------------------------|--------------------|-------------|
| :star:                     | `:star:`                     | `new` or `feature` | add **new feature** |
| :bug:                      | `:bug:`                      | `bug`              | fix **bug** issue |
| :lock:                     | `:lock:`                     | `security`         | fix **security** issue |
| :chart_with_upwards_trend: | `:chart_with_upwards_trend:` | `performance`      | fix **performance** issue |
| :zap:                      | `:zap:`                      | `improvement`      | update **backwards-compatible** feature |
| :boom:                     | `:boom`                      | `breaking`         | update **backwards-incompatible** feature |
| :warning:                  | `:warning:`                  | `deprecated`       | **deprecate** feature |
| :lipstick:                 | `:lipstick:`                 | `update`           | update **UI/Cosmetic** |
| :up:                       | `:up:`                       | `update`           | update **other** |
| :globe_with_meridians:     | `:globe_with_meridians:`     | `update`           | update or fix **internationalization** |
| :shirt:                    | `:shirt:`                    | `refactor`         | remove **linter**/strict/deprecation warnings or **refactoring** or code **layouting** |
| :white_check_mark:         | `:white_check_mark:`         | `test`             | add **tests** |
| :green_heart:              | `:green_heart:`              | `test`             | fix **tests** failur or **CI** building |
| :pencil:                   | `:pencil:`                   | `docs`             | update **documentation** |
| :copyright:                | `:license:`                  | `docs`             | decide or change **license** |
| :lollipop:                 | `:lollipop:`                 | `examples`         | for **example** codes |
| :arrow_up:                 | `:arrow_up:`                 | `dependency`       | upgrade **dependencies** |
| :arrow_down:               | `:arrow_down:`               | `dependency`       | downgrade **dependencies** |
| :pushpin:                  | `:pushpin:`                  | `dependency`       | pin **dependencies** |
| :wrench:                   | `:wrench:`                   | `config`           | update **configration** |
| :package:                  | `:package:`                  | `build`            | **packaging** or **bundling** or **building** |
| :hatching_chick:           | `:hatching_chick:`           | `release`          | **initial** commit |
| :confetti_ball:            | `:confetti_ball:`            | `release`          | release **major** version |
| :tada:                     | `:tada:`                     | `release`          | release **minor** version |
| :sparkles:                 | `:sparkles:`                 | `release`          | release **patch** version |
| :rocket:                   | `:rocket:`                   | `release`          | **deploy** to production enviroment |
| :back:                     | `:back:`                     | `revert`           | **revert** commiting |
| :construction:             | `:construction:`             | `wip`              | **WIP** commiting |
| :twisted_rightwards_arrows:| `:twisted_rightwards_arrows:`| -                  | merge **conflict resolution** |
| :heavy_plus_sign:          | `:heavy_plus_sign:`          | -                  | **add** files, dependencies, ... |
| :heavy_minus_sign:         | `:heavy_minus_sign:`         | -                  | **remove** files, dependencies, ... |
| :on:                       | `:on:`                       | -                  | **enable** feature and something ... |

Ask to Be [Creative](http://www.emoji-cheat-sheet.com/)!

### Examples

new:
```
:star: new(graphite): add 'graphiteWidth' option
```

bug fix:
```
:bug: fix(graphite): stop graphite breaking when width < 0.1

Closes #28
```

improve performance:
```
:chart_with_upwards_trend: performance(graphite): remove graphiteWidth option

The graphiteWidth option has been removed. The default graphite width of 10mm is always used for performance reason.
```

revert:
```
:back: revert: new: add 'graphiteWidth' option

This reverts commit 667ecc1654a317a13331b17617d973392f415f02.
```

[Git Commit Message Convention](https://github.com/kazupon/git-commit-message-convention)

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, yet powerful, providing tools needed for large, robust applications. A superb combination of simplicity, elegance, and innovation give you tools you need to build any application with which you are tasked.
