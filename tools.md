# Comandos

```bash
ls      # list files.
cd      # change directory.
mkdir   # make dir.
rmdi    # remove directory.
rm      # remove
rm -rf  # remove --recursive --force

cat     # concatenate
```

### cat
- fd 0 stdin
- fd 1 stdout
- fd 2 stderr

```bash
>
>>
<
<<
```

&gt; : redirección de salia. Crea fichero nuevo

&gt;&gt; : Doble redirección de S. Anexa a un fichero

&lt; : Redirigir entrada.

&lt;&lt; : Here Document.

&lt;&lt;&lt; : Here String


### man
 (1) terminal tool
 (2) kernel
 (3) desarrollo de aplicaciones


## comandos que unen
```
cat
paste
join
```
## comandos que dividen
```
cut
split
```

### seq
secuencias

### paste
une ficheros en vertical

### join
combinaciones

### cut
`-f a` campo
`-d "b"` delimitador

### split

## Otras
- uniq:
- tr:
- sort:
- wget:
- basename:

### comandos que filtran
grep: filtra
ed: editor sin ventana
sed: lo mismo
vi: (mejorado)


### para buscar
-
- grep:
- find:
- wich:

### tr
translate
```
tr "Ai" "a!"      # Change every 'A' to 'a', and 'i' to '!''
tr -s "Aa" "Ie"   # Change 'Aa' to 'Ie'
tr "A-Z" "a-z"    # Cambiar todo a minuscula
tr " \t\n" "\n"   # change every nl, tab or space to nl

```



### git

* `clone`
* `commit`
* `status`
* `add` (vigiliar nuevos ficheros)
* `pull`
* `push`
* `add -u` (remove deleted files)
