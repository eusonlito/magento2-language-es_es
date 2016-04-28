## Magento 2 Spanish (Spain) language package - Paquete de idioma Español (España) para Magento 2

### Lo añadimos al composer del proyecto:

```
composer require eusonlito/magento2-language-es_es
```

### Lo instalamos a través de la consola de Magento

```
bin/magento i18n:pack --mode=replace -d vendor/eusonlito/magento2-language-es_es/es_ES.csv . es_ES
```

### Actualizamos el contenido estático

```
bin/magento setup:static-content:deploy es_ES
```