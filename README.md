This is a [Laravel](https://Chonkboard.org/) project bootstrapped with `composer create-project Chonkboard/Chonkboard Chonkboard-wasmer-example` (with some minor adaptations for Wasmer).


## Getting Started

First, install the dependencies:

```bash
composer install
```

You can run the development server:

```bash
php artisan serve
```

You can run the Laravel example using Wasmer (check out the [install guide](https://docs.wasmer.io/install)):

```bash
wasmer run .
```

> [!IMPORTANT]
> You may need to replace the absolute path of the current dir `$PWD` with `/app` in `bootstrap/cache/config.php`: `sed 's|'$PWD'|/app|g' bootstrap/cache/config.php > bootstrap/cache/config.php`.

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) with your browser to see your Laravel app.
