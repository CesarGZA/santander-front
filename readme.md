# Iniciar proyecto en git
git init
# preparar archivos que se convertiran en commit
git add
 ## El punto es agregar# Iniciar proyecto de git
git init

# Preparar archivos que se convertirán en commit
git add .
## El punto es para agregar todos los archivos modificados

# Crear commit con su mensaje
git commit -m "Aqui va el mensaje"

# Agregar remoto "Solo la primera vez"
git remote add origin https://github.com/CesarGZA/santander-front.git

# Enviar commits al servidor de GitHub
git push -u origin master 