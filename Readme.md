# PRIMERA PARTE
## Creacion Repositorio
### Primero hacemos un git init, a continuacion usamos el git add Readme.me para crear el archivo readme y hameos un commit y para distinguirlo poner un comentario como "primer comentario"
![1 screenshot](https://github.com/Ramago1715/Examen_git/blob/main/Cap_Examen.png)
##### Aqui me he confundido asi que añado otra captura con el date bien hecho
![1.2](https://github.com/Ramago1715/Examen_git/blob/main/Cap_Examen2.png)
### Usamos ahora el git branch -M main y el git remote add origin y la url del repositorio de github y por ultimo git push -u origin main para finalmente subirlo del todo, y ya estaria creado
![2](https://github.com/Ramago1715/Examen_git/blob/main/Cap_Examen3.png)
## Clonacion
### Ahora clonaremos el repositorio para tenerlo en local con el comando git clone y la url del repositorio a clonar
![3](https://github.com/Ramago1715/Examen_git/blob/main/Cap_Examen4.png)
# SEGUNDA PARTE
## Revisamos cuantos commits tenemos hechos
### Lo revisamos con el comando git log --oneline --all y se puede observar todos los commits junto a sus hashes
![4](https://github.com/Ramago1715/Examen_git/blob/main/Part2_1.png)
## Visualizacion de contenido
### Como podemos ver con el comando cat y el archivo que querramos ver,se obeserva el contenido del readme
![5](https://github.com/Ramago1715/Examen_git/blob/main/Part2_2.png)
## Translado entre commits
### Usando los hashs de los commits nos moveremos entre ellos con el comando git checkout y el respectivo hash y asi nos movemos al primer commit
![6](https://github.com/Ramago1715/Examen_git/blob/main/Part2_Moverse.png)
## En que posicion estamos ahora?
### Se puede comprobar que el head esta en el primer commit usando el comando git  log  --oneline --all
![part2_movernos2](https://github.com/Ramago1715/Examen_git/blob/main/Part2_Moverse2.png)
## Nos movemos al segundo commit
### Usamos el comando usado antes pero con el hash del segundo commit ademas  con el comando tambien usado multiples veces mostramos que nos encontramos en el segundo commit
![part2_movernossegundo](https://github.com/Ramago1715/Examen_git/blob/main/Part2_moversesegundo.png)
## Nos movemos a la rama main
### con el mismo comando de antes pero sustituyendo en hash por la palabra main podemos vovler al ultimo commit (es decir al acutal)
![part2_movernosmain](https://github.com/Ramago1715/Examen_git/blob/main/Part2_moversemain.png)
# TERCERA PARTE
## 1.Directorio de trabajo
### Es la copia de una version  del proyecto en local para poder editarlo o usarlo
## 2.Área de preparación
### Es la zona a la que lo subes para alamcenar archvios antes de hacer el siguiente paso es decir, es la zona donde por ejemplo añades imagenes y archivos y despues haces el commit y push de todo, se sube algo a esta zona con el comando git add
## 3. Repositorio local
### El repositorio local es la copia exacta del proyecto que esta subido a git pero en local 




