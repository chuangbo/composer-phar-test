# composer-phar-test

This demostrate the `composer` issue of loading phar file which is fixed in [this commit](https://github.com/chuangbo/composer/commit/b14b64622afe4d3d684d3a0c274ae09544257636).

## How to reproduce issue

See [composer.json](composer.json) and [vendor/composer/autoload_static.php](vendor/composer/autoload_static.php)

## After fix?

See [after-fix/vendor/composer/autoload_static.php](https://github.com/chuangbo/composer-phar-test/blob/after-fix/vendor/composer/autoload_static.php)

## Pull Request Status

https://github.com/composer/composer/pull/6378
