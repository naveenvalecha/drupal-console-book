# server
**server** comanda Runs PHP built-in web server

**Folosire:**
```
$ drupal server [arguments] 
```

## Argumente disponibile
Argument | Detalii
---------|-------------
address | The address:port values

## Exemple
* Run using default address argument value 127.0.0.1.8088
```
$ drupal server
```
* Passing address argument to use a different port number
```
$ drupal server 127.0.0.1:8089
```
* Running default address argument values, using --root option to define the Drupal root
```
$ drupal --root=/var/www/drupal8.dev server
```
