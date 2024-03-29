# SatAgro - Documentación

La documentación acutalizada se puede acceder desde:
https://dymaxionlabs.github.io/satagro-docs/


## Instalación

Para poder regenerar y visualizar la documentación localmente, se necesita
instalar MkDocs.  Primero es recomendable crear un entorno virtual y activarlo:

```
virtualenv -p python3 .venv/
source .venv/bin/activate
```

Luego, ejecutar lo siguiente para instalar MkDocs y el theme:

```
pip install -r requirements.txt
```


## Uso

Para levantar un servidor de desarrollo y visualizar la documentación desde el
navegador, ejecutar:

```
mkdocs serve
```

Para publicar la última versión a GitHub Pages:

```
mkdocs gh-deploy
```


## Licencia

Ver [LICENSE.txt](LICENSE.txt) para más información.
