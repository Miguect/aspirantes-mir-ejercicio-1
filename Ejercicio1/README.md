 Se valida la ubicación de la ruta actual y las carpetas creadas usando el comando <dir>
 
 C:\Users\Migue y Chris>dir
 El volumen de la unidad C no tiene etiqueta.
 El número de serie del volumen es: 461E-B0EE

 Directorio de C:\Users\Migue y Chris

02/03/2023  08:04 a. m.    <DIR>          .
02/03/2023  08:04 a. m.    <DIR>          ..
15/02/2022  03:51 p. m.             6.891 -1.14-windows.xml
21/05/2022  08:53 a. m.    <DIR>          .cache
01/03/2023  08:02 p. m.               177 .gitconfig
21/05/2022  09:43 a. m.    <DIR>          .m2
21/05/2022  09:20 a. m.    <DIR>          .nbi
20/02/2022  03:58 p. m.    <DIR>          .vscode
02/03/2023  07:33 a. m.    <DIR>          3D Objects
02/03/2023  07:35 a. m.    <DIR>          Contacts
02/03/2023  08:04 a. m.    <DIR>          Desktop
12/10/2022  08:42 p. m.    <DIR>          Documents
02/03/2023  07:35 a. m.    <DIR>          Downloads
02/03/2023  08:04 a. m.    <DIR>          Ejercicios
02/03/2023  07:35 a. m.    <DIR>          Favorites
02/03/2023  07:35 a. m.    <DIR>          Links
12/10/2022  08:42 p. m.    <DIR>          Music
14/02/2022  09:13 p. m.    <DIR>          OneDrive
12/10/2022  08:42 p. m.    <DIR>          Pictures
02/03/2023  07:35 a. m.    <DIR>          Saved Games
02/03/2023  07:35 a. m.    <DIR>          Searches
12/10/2022  08:42 p. m.    <DIR>          Videos
               2 archivos          7.068 bytes
              20 dirs  145.687.740.416 bytes libres


Se procede a cambiar la ruta de trabajo al escritorio usando <cd desktop>.
C:\Users\Migue y Chris>cd desktop

Se crea la carpeta "Ejercicios" con el comando <mkdir Ejercicios>
C:\Users\Migue y Chris\Desktop>mkdir Ejercicios

Se cambia nuevamente la ruta de trabajo ahora a la careta creada "Ejercicios".
C:\Users\Migue y Chris\Desktop>cd Ejercicios

Se configura el nombre y el email globalmente en git.
C:\Users\Migue y Chris\Desktop\Ejercicios>git config --global user.name Miguel Camargo

C:\Users\Migue y Chris\Desktop\Ejercicios>git config --global user.email miguelandrescamargo@gmail.com

Se inicia el repositorio en la carpeta Ejercicios.
C:\Users\Migue y Chris\Desktop\Ejercicios>git init
Initialized empty Git repository in C:/Users/Migue y Chris/Desktop/Ejercicios/.git/

Se indica al sistema la creación del primer commit con el mensaje "version inicial"
C:\Users\Migue y Chris\Desktop\Ejercicios>git add .

C:\Users\Migue y Chris\Desktop\Ejercicios>git commit -m "Version Inicial"
[master (root-commit) 0815111] Version Inicial
 1 file changed, 1 insertion(+)
 create mode 100644 Ejercicio1/README.md

 Se valida el estado actual del repositorio:
 C:\Users\Migue y Chris\Desktop\Ejercicios>git status
On branch master
nothing to commit, working tree clean

