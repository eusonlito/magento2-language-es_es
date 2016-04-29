## Magento 2 Spanish (Spain) language package - Paquete de idioma Español (España) para Magento 2

## Traducciones

Se han recopilado las traducciones existentes en https://crowdin.com/project/magento-2/es-ES#

## Ficheros

* **es_ES.csv** - Contiene todos los strings, tanto traducidos como no traducidos
* **es_ES-translated.csv** - Contiene sólo los strings traducidos
* **es_ES-not-translated.csv** - Contiene sólo los strings no traducidos
* **es_ES-translated-and-google.csv** - Contiene los strings traducidos y una traducción desde Google del resto

## Instalación

### Lo añadimos al composer del proyecto:

```
composer require eusonlito/magento2-language-es_es
```

### Lo instalamos a través de la consola de Magento

```
php bin/magento i18n:pack --mode=replace -d vendor/eusonlito/magento2-language-es_es/es_ES.csv . es_ES
```

### Actualizamos el contenido estático

```
php bin/magento setup:static-content:deploy es_ES
```

### Recuerda limpiar la caché después de instalar el paquete de idioma
