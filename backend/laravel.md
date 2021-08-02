## :one: `php artisan optimize`
* `php artisan optimize` creates a compiled file of commonly used classes in order to reduce the amount of files that must be loaded on each request. 
* The file is saved to, or overwrites, `bootstrap/cache/compiled.php`, which needs to be writable by the web server (PHP process).
