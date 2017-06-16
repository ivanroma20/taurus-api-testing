

[![N|Solid](http://qajungle.com/wp-content/uploads/2016/01/logo2.png)](http://qajungle.com)

# Taurus Rest API Testing

Taurus es una herramienta open source que nos permite automatizar de forma sencilla nuestras pruebas.

https://gettaurus.org/

En el proyecto se presentan los scripts para lanzar pruebas de rendimiento sobre APIs Rest.

### Ejecutar las pruebas

En el caso de las pruebas de carga:

```sh
$ bzt load-api-testing.yml
```

En el caso de las pruebas de estrés:

```sh
$ bzt stress-get-api-testing.yml stress-post-api-testing.yml
```