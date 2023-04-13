# loremipsum

> Crea un nuevo repositorio público de github "loremipsum"

> Clona el repositorio en tu local

```
git clone https://github.com/betogus/loremipsum.git
```
> Crea una nueva rama en tu repositorio local, llamada "generarlipsum"

```
git checkout -b generarlipsum
```

> Agrega  a tu repositorio el archivo lipsum.sh que se provee adjunto a esta tarea. 

> Genera los 5 archivos txt basándose en el sitio lipsum.com (ejecutando bash ./lipsum.sh). 

> Verifica que se crearon los cinco archivos y que tengan contenido

> Crea un commit con los archivos generados y el lipsum.sh, luego haz un push a tu repositorio en github.

```
bash ./lipsum.sh
git add .
git commit -m "se agregaron los archivos"
git push --set-upstream origin generarlipsum
```

> Codifica un nuevo archivo, "contar.sh", que lea cada uno de los txt generados y luego devuelva por cada archivo, la cantidad de líneas de ese archivo.
Al ejecutar el archivo, se deben mostrar la cantidad de líneas que tiene cada uno, por ejemplo:
    bash ./contar.sh
    loremipsum-1.txt tiene 4 líneas.
    loremipsum-2.txt tiene 7 líneas.
    loremipsum-3.txt tiene 15 líneas.
    loremipsum-4.txt tiene 7 líneas.
    loremipsum-5.txt tiene 16 líneas.

```
bash ./contar.sh
```

> Crea un nuevo commit en la rama "generarlipsum" sumando el nuevo archivo "contar.sh"

```
git add .
git commit -m "se incorporo el archivo contar.sh"
```

> Realiza un merge de tu rama "generarlipsum" a la rama principal de tu repositorio usando una Pull Request.

```
git push
// Para traer los cambios desde github una vez hecho el merge, me dirijo a la rama main:
git pull
```
