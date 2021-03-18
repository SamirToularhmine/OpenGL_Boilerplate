# Instructions

Afin de pouvoir configurer un environnement OpenGL, il faut installer quelques librairies.

Librairies utilisées : GLFW, glad.

## Installations des librairies
### MacOS
On commence par installer GLFW : 
```brew install glfw``` (pour macOS)
###

### Linux

```sudo apt-get install libglfw3``` puis
###

```sudo apt-get install libglfw3-dev``` (pour linux)

Ensuite il faut copier le contenu du dosier ```vendor/include``` dans dans le dossier ```/usr/local/include``` afin de pouvoir inclure les headers dans le projet.

Une fois cela fait, on peut construire le projet en procédant de la manière suivante : 

```
mkdir build
cd build
ccmake ../.
(c pour configuration 2 fois puis g pour generate puis q pour quit)
make
cd ../Cours1
```



