# Unicon for Statamic

[Unicon 🦄](https://unicon.rocks/) is a package for [Laravel](https://laravel.com/) that enables seamless, on-demand integration of over 200,000 icons from the Iconify API, with caching for optimized performance.

## What does this addon do?
It allows to install **Unicon** for Statamic and it adds a tag `unicon` that allows you to use Unicon inside of antlers files.

## How to Install

Just run the following command from your project root:

``` bash
composer require palmiak/unicon
```

You can optionally publish the configuration file by running:

```bash
php artisan vendor:publish --tag=unicon-config
```
Check the [cofiguration reference](https://unicon.rocks/config-reference) for more details.

## How to Use
### Antlers
Just use `{{ unicon icon='heroicons:clock' }}` inside of any antlers file. 

If you want to add some classes, you can do it by using `{{ unicon icon='heroicons:clock' class="some_class" }}`.

### Blade
Unicon provides blade support [out of the box](https://unicon.rocks/components/blade-component).