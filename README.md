# Proyecto_Practica
Esta practica sirve para conocer los comandos basicos del maquetado bajo el estandar de  MARKDOWN (.md), que nos servira para crear la documentacion de nuestros proyectos durante la fprmacion profesional.
## 1.Titulos (HEADERS)
Si para la documentacion deseamos secciones de algun tema o contenido podemos utilizar estos elementos para poder resaltarlos como encabezados. Es son similares a las etiquetas \<h1>...\<h6>

**Ejemplo**
# Titulo principal (Nivel 1)
## Subtitulo de Nivel 2
### Subtitulo de Nivel 3
#### Subtitulo de Nivel 4
##### Subtitulo de Nivel 5
###### Subtitulo de Nivel 6
####### El estandar solo te permite hasta 6 posibles titulos, a partir del septimo omitira la intruccion del maquetado.
## 2.Separadores (SEPARATORS)
Esta intruccion coloca una line vertical entre las secciones del documento permitiendo organizar y distribuir mejor el contenido, y puede ser maquetado utilizando 3 guines medios (-) continuos despues del parrafo deseado.

**Ejemplo**

Título de la Sección

---

Parrafo 1 Parrafo 1 Parrafo 1 Parrafo 1 Parrafo 1 Parrafo 1 Parrafo 1 Parrafo 1 Parrafo 1 Parrafo 1 Parrafo 1 


## 3.Parrafos (PARAGRAPHS)
Son utilizados para presentar texto descriptivo de la documentacion de los proyectos, en el cual podremos utilizar la propiedad de aling de HTML para poder controlar la alineacion de texto.

**Ejemplo**

<p align="left">
Parrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda.
Parrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda.
Parrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda.
Parrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda.
Parrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda.
Parrafo 1 en caso de no definir la alineacion estara por defecto a la izquierda.
</p>

<p align="right">
Parrafo 2 al utilizar la etiqueta p y la propiedad de alineacion con el valor right, este estara alineado a la derecha.
Parrafo 2 al utilizar la etiqueta p y la propiedad de alineacion con el valor right, este estara alineado a la derecha.
Parrafo 2 al utilizar la etiqueta p y la propiedad de alineacion con el valor right, este estara alineado a la derecha.
Parrafo 2 al utilizar la etiqueta p y la propiedad de alineacion con el valor right, este estara alineado a la derecha.
Parrafo 2 al utilizar la etiqueta p y la propiedad de alineacion con el valor right, este estara alineado a la derecha.
Parrafo 2 al utilizar la etiqueta p y la propiedad de alineacion con el valor right, este estara alineado a la derecha.
</p>

<p align="center">
Parrafo 3 este texto estara centrado.
Parrafo 3 este texto estara centrado.
Parrafo 3 este texto estara centrado.
Parrafo 3 este texto estara centrado.
Parrafo 3 este texto estara centrado.
Parrafo 3 este texto estara centrado.
</p>

<p align="justify">
Algunas veces desearemos justificar el texto para presentar el texto de una manera mas organizada.
Algunas veces desearemos justificar el texto para presentar el texto de una manera mas organizada.
Algunas veces desearemos justificar el texto para presentar el texto de una manera mas organizada.
Algunas veces desearemos justificar el texto para presentar el texto de una manera mas organizada.
Algunas veces desearemos justificar el texto para presentar el texto de una manera mas organizada.
Algunas veces desearemos justificar el texto para presentar el texto de una manera mas organizada.
</p>

## 4.Texto Enfatizado (BOLD, ITALIC, ITALIC/BOLD y UNDERLINE)
Tambien es posible resaltar algunas palabras importantes utilizando la estilizacion de **Letras Negritas**, para la que colocaremos dos * antes y depues que la palabra a resaltar, *Letras Cursivas* solo ponemos un * antes y depues de las palabras, ***Letras Cursivas y Negritas*** colocando 3 y por ultimo <ins>  texto subrayado <ins> encerrando la frase o palabras entre la etiqueta <ins> y la etiqueta de cierre <ins>.
## 5.Cuadores de Codigo o Reseña (BLOCKQUOTES)
Estos elementos son utilizados para resaltar intrucciones especificas para la intalacion, configuuracion y/o inicializacion del proyecto, para mostrar secciones de codigo fuente y se maqueta utilizando el simbolo de mayor que (>) antes del texto.

**Ejemplo**

Para listar las carpetas y archivos desde una terminal de comandos en el SO de Windows debemos usar el comando
>C:/dir
Despues oprimimos la tecla *Enter*
Tambien podemos poner texto multilinea

**Ejemplo**

Pasos para instalar MySQL
> - Descargar el archivo instalador desde la pagina oficial www.mysql.com
> - Intalar el servidor de Base de Datos
> - Definir el puerto y contraseña para el usuario **root**
> - Inicializar el servidor de Base de Datos
> - Conectarnos a la Base de Datos para verificar que se intalo correctamente
## 6.Listas Ordenadas y NO Ordenadas
Si en nuestra documentacion necesitamos incluir informacion en modo de lista, es decir un elemento tars otro podremos hacerlo utilizando las listas ya sea usando viñetas o numeracion definida.
Para el uso de las viñetas soloes necesario agregar un (-) antes del texto.

**Ejemplo**

Mi tipo favorito de musica es:
 - Balada
 - Rock
 - Electro Hause
 - Pop

Para enlistar elemntos en orden numerico solo basta con ateponer un numero antes de texto con un (.)

**Ejemplo**

Para crear un nuevo repositorio en **GitHub** debo:
1. Crear una cuenta de GitHub
2. Logearme con mi cuenta de GitHub
3. Ir al menu principal de mi perfil (Home)
4. En el menu lateral bucar el boton que dice **Nuevo Repositorio**
5. Asignar un nombre
6. Definir si el proyecto es:
      - **Publico:** Cualquier persona podra ver y consultar el contenido de mi proyecto
      - **Privado:** Solo aquella persona que yo autorize podra visualizar y modificar el contenido de mi proyecto
7. Agregar un primer archivo documental *README.md*
8. Aprobar la creacion de repositorio
## 7.Ligas e Hipervinculos (LINKS)
Estas son utilizadas para redirigir a archivos o secciones dentro o fuera de nuestro repositorio. Se maquetan utilizando corchetes [], inmediatamente de parentesis con la URL de destino ().

**Ejemplo**

Mi buscador favorito es: [GOOGLE](https://www.google.com)

Esta documentacion fue creada por **Samuel Galindo Vaquier**

<samygalind017@gmail.com>

## 8.Tablas (TABLES)
Si la documentacion lo requiere podemos presentar informacion en formatos de tablas con filas y columnas, para maquetados podemos utilizar el caracter | para delimitar las filas.

**Ejemplo**
| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4 | Encabezado 5 |
| -------------|--------------|--------------|--------------|------------- |
| Fila 1 Celda | Fila 2 Celda | Fila 3 Celda | Fila 4 Celda | Fila 5 Celda |
| Fila 1 Celda | Fila 2 Celda | Fila 3 Celda | Fila 4 Celda | Fila 5 Celda |
| Fila 1 Celda | Fila 2 Celda | Fila 3 Celda | Fila 4 Celda | Fila 5 Celda |

## 9.Imagenes
Para la vizualizacion de imagenes debemos cargar los archivos en nuestro repositorio y vincularlo.
![Shinobu](https://github.com/Samuel-Galindo-Vaquier/Practicagit/blob/main/Imagenes/Imagen%20de%20WhatsApp%202024-05-29%20a%20las%2021.49.58_7759eef3.jpg?raw=true)
   


   

