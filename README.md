
### Script para listar 

### Requerimientos
```
composer 
(*)En windows es necesario tener instalado PHP.
```

### Instalación
Ejecutar el siguiente comando en la carpeta raíz del repositorio para descargar las librerías utilizadas.
```
composer install
```

### Utilización

Desde la carpeta raíz del repositorio ejecutar "./melitest test seller_id=VALOR DE ID". 
Si se quiere obtener el listado para más de un "seller_id" se pueden separar por ',' y sin espacios.

**Ejemplo:**

```
./melitest test seller_id='VALOR_DE_ID'

./melitest test seller_id='VALOR_DE_ID_1','VALOR_DE_ID_2'
```

### Guardar

Para guardar el archivo, ejecutar el comando "./mercadolibre items seller_id=VALOR DE ID > archivo.formato" el mismo quedara donde se especifique la ruta, de lo contrario, si no se especifica el archivo sera guardado en la carpeta del repositorio.

**Ejemplo:**

```
./melitest test seller_id='VALOR_DE_ID' > Listado.log
```


