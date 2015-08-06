CKEditor Package
=====================

## Installation
### Set up package

```
composer require unisharp/laravel-ckeditor
php artisan vendor:publish --tag=ckeditor
```

## Usage

Default way (initiate by name or id) :

```javascript
    <script src="/vendor/unisharp/laravel-ckeditor/ckeditor.js"></script>
    <script>
        CKEDITOR.replace( 'article-ckeditor' );
    </script>
```

Or if you want to initiate by jQuery selector :

```javascript
    <script src="/vendor/unisharp/laravel-ckeditor/ckeditor.js"></script>
    <script src="/vendor/unisharp/laravel-ckeditor/adapters/jquery.js"></script>
    <script>
        $('textarea').ckeditor();
        // $('.textarea').ckeditor(); // if class is prefered.
    </script>
```
