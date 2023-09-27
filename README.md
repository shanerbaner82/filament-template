# A Slightly Opinionated Filament Template
Because I build so many of these I though it would be best to create a template to save myself some time.

## What's in the box?
This is a fresh Laravel 10 application plus the following:
1. [Filament](https://filamentphp.com)
2. [filament-spatie-roles-permissions](https://github.com/althinect/filament-spatie-roles-permissions)
3. [filament-breezy](https://github.com/jeffgreco13/filament-breezy)

## How do I use this?
1. Above the file list, click Use this template.
2. Select Create a new repository.
3. Use the Owner dropdown menu to select the account you want to own the repository.
4. Type a name for your repository, and an optional description.
5. Choose a repository visibility.

[Click here](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) for help if necessary.

## What next?
After you have cloned the project and opened it up in your editor make sure to:
```bash
composer install
```

```bash
cp .env.example .env
```

```bash
php artisan key:generate
```

```bash
php artisan migrate
```
