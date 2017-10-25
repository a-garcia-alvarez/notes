# Terminal

## Redirecciones

* &gt; : redirección de salia. Crea fichero nuevo
* &gt;&gt; : Doble redirección de S. Anexa a un fichero
* &lt; : Redirigir entrada.
* &lt;&lt; : Here Document.
* &lt;&lt;&lt; : Here String


* `2>` :Redirigir stderr
* `|`: pipe, tubería (usa un fichero anónimo)
* `&>2` : redirige 1 a 2
* `&2>` : redirige 2 a 1


## Variables

* `#` : Cantidad de parametros
* `$` : PID de la shell
* `?` : valor retornado por el ultimo comando
* `@` : parameters como uno
* `*` : parameters por separado
* `1` : primer parámetro
* `0` : nombre de comando



## Sistema de ficheros

* `~` : $HOME
* `.` : actual directory
* `..` : parent directory
* `-` : stdin
* ` `(space) : partir parametros
* `*` : Cualquier secuencia de caracteres
* `?` : Cualquier caractere
* `[]` : conjunto de caracteres
  * `[aeiou]` : expande a cualquier vocal
* `{}` : convinacniones
  * `{aa,ee,uu,arg}` : expande a `aa` `ee` `uu` o `arg`


## Opciones / Metacaracteres
* `\` : Secuencia de escape
* `--` : A veces el fichero que representa a la terminal
* `"` : escapan la mayoría de Metacaracteres
* `'` : escapan todos los meta
* `` ` `` : ejecuta comando y se sustituye por la salida
* `$()` : lo mismo
* `#` : comment
* `$` : varialbe


## Otros

* `#!` Shebang: Interprete con el que hay que ejecutar el archivo
* `!!` Last command
* `!*` Las parameters

### Operadores lógicos
- `&&` AND
- `||` OR
- `!` NOT




## #C\# #
