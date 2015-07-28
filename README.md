CKEditor 4 Unisharp Package
=====================

## Installation

### Set up package

in `composer.json` file

  ```"require": {
        "unisharp/laravel-ckeditor": "dev-master"
     },
     "repositories": [
         {
             "type": "git",
             "url": "https://github.com/UniSharp/laravel-ckeditor.git"
         }
  ```],

### View initiation

Default way (initiate by name or id) :
  
  ```<script src="/vendor/unisharp/laravel-ckeditor/ckeditor.js"></script>
     <script>
       CKEDITOR.replace( 'article-ckeditor' );
  ```</script>


Or if you want to initiate by jQuery selector :

  ```<script src="/vendor/unisharp/laravel-ckeditor/ckeditor.js"></script>
     <script src="/vendor/unisharp/laravel-ckeditor/adapters/jquery.js"></script>
     <script>
       $('textarea').ckeditor();
  ```</script>
