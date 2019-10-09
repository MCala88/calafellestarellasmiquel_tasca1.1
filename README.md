# calafellestarellasmiquel_tasca1.1

### Alumne: Miquel Calafell

## En este documento aprenderemos a usar los diferentes recursos que nos ofrece el lenguaje Markdown


# Titulos
# Este es el titulo mas grande 
``` Usando (# Titulo) tendriamos este formato de titulo ```

-----------------
## Los titulos van teniendo una fuente mas pequeña a medida que ponemos mas almohadillas
``` En este caso (## Titulo) ```

--------------
###### Este es el ultimo y mas pequeño titulo
``` El ultimo es (###### Titulo) dependiendo de los titulos que queremos podemos usar el mas adequado pudiendo poner tambien los de 3, 4 o 5 almohadillas ```


# Emphasis
Usando ciertos caracteres al principio y final de una o varias palabras puedes consegir los siguientes resultados
### *asteriscos* o _barra baja_ o ~tachado~
``` *palabra* o _barra baja_ y es el mismo metodo con todos los demas ```

--------------------
### **dos asteriscos** o __dos barras bajas__ o ~tachado~
``` **dos asteriscos** o __dos barras bajas__ usando el caracter dos veces se le añade la carecteristica que se pone en negrita ```

-------------------------
### **asteriscos and _barra baja_**
``` **asterisks and _underscores_** de esta manera combinamos diferentes enfasis ```

# Lists
A la hora de crear listas 
1. Lista principal
* lista secundaria
* ejemplo
2. Segunda lista principal
* lista secundaria de
* la segunda principal

```Para la lista principal es (1. Lista principal) y (* lista secundaria)```


# Links

[Google](https://www.google.com)

[Videos de gatitos](https://www.youtube.com/watch?v=tmvDgUBoBSQ)

```Si queremos poner un link escribiendo un mensaje sobre el debemos hacer el siguiente codigo ([Google](https://www.google.com))```
```Si solo queremos poner la url basta con dejar el link entre ()```


# Imagenes

```Se pueden hacer de dos maneras, en linea y en referencia```


## En linea:

![alt text](https://www.comprarbanderas.es/images/banderas/400/21636-espana-rcd-mallorca_400px.jpg "Imagen 1")


```![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")```
```Para poner la imagen que queremos copiamos la direccion de la imagen y la cambiamos, tambien podemos cambiar el texto de relacion con la imagen```

---------
## En referencia:

![alt text][logo]

[logo]: https://www.comprarbanderas.es/images/banderas/400/21636-espana-rcd-mallorca_400px.jpg "Logo Title Text 2"

```![alt text][logo]```
```[logo]: https://www.comprarbanderas.es/images/banderas/400/21636-espana-rcd-mallorca_400px.jpg "Logo Title Text 2"```
```Usando el modo de referencia si queremos poner la misma imagen varias veces va a ser mas rapido con este metodo```


# Code and Syntax Highlighting

## Con Markdown podemos usar lenguajes de programación para diversas cosas como estos dos ejemplos:

### Podemos resaltar palabras con el siguiente comando 

```Inline `code` has `back-ticks around` it.```

-----------------
### Tambien podemos usar diversos lenguajes de programación para hacer variables

``` javascript
var s = "JavaScript syntax highlighting";
alert(s);```
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```


# 