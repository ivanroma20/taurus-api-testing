
# Taurus Rest API Testing

Taurus es una herramienta open source que nos permite automatizar de forma sencilla nuestras pruebas.

https://gettaurus.org/

En el proyecto se presentan los scripts para lanzar pruebas de rendimiento sobre APIs Rest.

### Ejecutar las pruebas

```sh
$ bzt load-api-testing.yml
```

### Ejecutar prueba con reporte externo de blazemeter
Debes crearte una cuenta en blazemeter y crear tu token para reamplazarlo en el archivo de configuración .yml

```sh
$ bzt load-api-testing.yml -report 
```
```