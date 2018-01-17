## Magento 2 Spanish (Spain) language package - Paquete de idioma Español (España) para Magento 2

## Traducciones

Se han recopilado las traducciones existentes en https://crowdin.com/project/magento-2/es-ES#

Si deseas participar, por favor regístrate en Crowdin y ayuda con las traducciones desde su panel.

## Ficheros

* **es_ES/crowdin.csv** - Contiene las traducciones realizadas en Crowdin
* **es_ES/all.csv** - Contiene todas las cadenas de texto existentes en Crowdin, traducidas o no
* **es_ES/translated-and-translator.csv** - Contiene las traducciones realizadas en Crowdin y una traducción mediante APIs de resto

## Instalación Automática

### Lo añadimos al composer del proyecto:

```
composer require eusonlito/magento2-language-es_es dev-master
```

### Lo instalamos a través de la consola de Magento

```
php bin/magento i18n:pack --mode=replace -d vendor/eusonlito/magento2-language-es_es/es_ES/crowdin.csv es_ES
```

### Actualizamos el contenido estático

```
php bin/magento setup:static-content:deploy es_ES
```

### Recuerda limpiar la caché después de instalar el paquete de idioma

## Instalación Manual

### Lo añadimos al composer del proyecto:

```
composer require eusonlito/magento2-language-es_es
```

### Creamos una carpeta donde colocaremos el fichero de traducciones

```
install -d app/vendor/eusonlito/magento2-language-es_es/i18n
```

### Copiamos el fichero de idioma en ese directorio

```
cp vendor/eusonlito/magento2-language-es_es/es_ES/crowdin.csv app/vendor/eusonlito/magento2-language-es_es/i18n/
```

### Recuerda limpiar la caché después de instalar el paquete de idioma
