# Laravel - Disqus Platform Integration


A simple package integrating Disqus platform with Laravel.

## Install

- Via Composer
``` bash
$ composer require sumantablog/laravel-disqus
```

## Providers and Config
> If you are using Laravel 5.5+ then the steps below are optional.

- Register service provider
```php
Sumantablog\Disqus\DisqusServiceProvider::class
```

- Publish config
```bash
$ php artisan vendor:publish --tag=disqus
```

## Config
Append the following config on your `.env` file.

``` php
DISQUS_ENABLED=true
DISQUS_USERNAME=your_website_shortname
```

## Usage
To display Disqus platform on your page, just add:
```html
<div id="disqus_thread"></div>
```
