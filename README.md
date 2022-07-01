# Exploratory Data Analysis

Para usar este repo como plantilla debemos hacer lo siguiente:

1. Reemplaza `dummy_transformations` por el nombre del nuevo módulo en:
    - `Makefile`
    - `pyproject.toml`
    - `tests\test_transformation.py`
1. Renombra el archivo `dummy_transformations\transformation.py` al nombre del primer archivo del
   nuevo módulo
1. Cambia la descripción del archivo `dummy_transformations\__init__.py`
1. Renombra el directorio `dummy_transformations` al nombre del nuevo módulo
1. Cambia el `codecov_token` del archivo `Makefile`

Los archivos del nuevo módulo los agregarás en la carpeta que antes se llamaba
`dummy_transformations` y las pruebas en la carpeta `tests`.
