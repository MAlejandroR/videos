# App de vídeos

Desarrollo para visualizar vídeos para seguimiento de las clases

Para instalar este sitio web realizado con hugo, se ha utilizado la plantilla slate
# Instalación del tema slate

Una vez clonado el proyecto, hay que descargar la plantilla *****salate*****
```shell
mkdir themes
cd themes
git clone https://github.com/gesquive/slate
```
# Descripción de la plantilla

Es muy sencillo el uso. Básicamente tenemos dos elementos:
1 *****tags**** o agrupaciones
2 *****links o lista de vídeos***** (puede ser cualquier cosa que queramos linkar )
## tags
*Aparecerán en un menú de navegación en la parte izquierda de la pantalla
*Tienen 3 atributos:
1. *****name*****: Nombre que se visualizará al poner el cursor sobre el icono
2. *****tag*****: EL nombre del tag, usado posteriormente en los links que serán asociados a uno o varios tags
3. *****icon*****: El icono para mostrar. Será un nombre de ***font-awesome*** 
*Es una agrupación temática. Se especifica en el fichero *****config.toml****
```yaml
[[ params.nav ]]
name = "Ficheros en php"
tag = "ficheros"
icon = "file"
```

 
