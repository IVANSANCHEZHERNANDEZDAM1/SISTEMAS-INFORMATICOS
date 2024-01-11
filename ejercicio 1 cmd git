# git-bush
ejercicios clase
# Configurar el nombre del usuario
git config --global user.name "IVAN SANCHEZ"

# Configurar el correo electrónico
git config --global user.email "iivanssanchezzz42de@linkiafp.online"

# Activar el coloreado de la salida en rojo
git config --global color.ui true

# Mostrar la configuración final
git config --global --list

# Crear un nuevo repositorio llamado "libro"
git init libro

# Acceder al directorio del repositorio
cd libro

# Mostrar el contenido del repositorio
ls

# Comprobar el estado del repositorio
git status

# Crear el fichero indice.txt y añadir contenido
echo "Capítulo 1: Introducción a Git" > indice.txt
echo "Capítulo 2: Flujo de trabajo básico" >> indice.txt
echo "Capítulo 3: Repositorios remotos" >> indice.txt

# Comprobar el estado del repositorio
git status

# Añadir el fichero a la zona de intercambio temporal
git add indice.txt

# Comprobar el estado del repositorio después de agregar a la zona de intercambio temporal
git status

# Realizar un commit con el mensaje especificado
git commit -m "Añadido índice del libro."

# Ver el estado del repositorio
git status

# Modificar el fichero indice.txt
echo "Capítulo 1: Introducción a Git" > indice.txt
echo "Capítulo 2: Flujo de trabajo básico" >> indice.txt
echo "Capítulo 3: Gestión de ramas" >> indice.txt
echo "Capítulo 4: Repositorios remotos" >> indice.txt

# Mostrar los cambios en el fichero
git diff

# Hacer un commit de los cambios con el mensaje especificado
git commit -m "Añadido capítulo 3 sobre gestión de ramas"

# Mostrar los cambios de la última versión del repositorio con respecto a la anterior
git diff HEAD^ HEAD

# Cambiar el mensaje del último commit
git commit --amend -m "Añadido capítulo 3 sobre gestión de ramas al índice."

# Volver a mostrar los últimos cambios del repositorio
git log

