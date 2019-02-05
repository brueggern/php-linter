# PHP Linter
PHP linter based on PSR-2 and PSR-12.

## Install

```
{
    "repositories": [
        {
            "type": "vcs",
            "url": "git@github.com:brueggern/php-linter.git"
        }
    ]
}
```

Install the composer package: `composer require brueggern/php-linter`

Add composer scripts to run the linting/fixing (replace app with the folder(s) you want to lint):

```
{
    "scripts": {
        "lint": "coding-style-guide-php app",
        "lint:fix": "coding-style-guide-php --fix app"
    }
}
```

## Usage

To lint the project and show all errors:
```
composer run lint
```

To automatically fix your errors:
```
composer run lint:fix
```
