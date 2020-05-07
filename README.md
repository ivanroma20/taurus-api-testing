
[![N|Solid](https://www.culqi.com/wp-content/themes/wp-bootstrap-starter-child/images/logomenu.png)](https://nodesource.com/products/nsolid)
# Taurus Rest API Testing

Taurus es una herramienta open source que nos permite automatizar de forma sencilla nuestras pruebas.

## Instalar Taurus
https://gettaurus.org/docs/Installation/

En el proyecto se presentan los scripts para lanzar pruebas de rendimiento sobre APIs Rest.(Scripts creados con Jmeter, ejecutados con Taurus y utilizando reportería de blazemeter)

## Ejecutar las pruebas
### Ejemplo online
```sh
$ bzt perform-api-testing.yml
```

### Ejemplo platform
```sh
$ bzt stress-api-testing.yml
```

*Debes crearte una cuenta en blazemeter y crear tu token para reamplazarlo en el archivo de configuración .yml
