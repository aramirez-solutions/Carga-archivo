TODOS ESTOS COMANDOS SE UTILIZAN PARA UN REPOSITORIO VACÍO Y CUANDO YA SE HA IDENTIFICADO AL AUTOR EN GIT BASH
#INICIALIZAR EL REPOSITORIO#
git init
#INSTAAR LFS PARA ARCHIVOS DE MÁS DE 100 MB#
git lfs install
#INDICAR LA EXTENSIÓN DE LOS ARCHIVOS A AGREGAR#
git lfs track "*.zip"
#AGREGAR TODOS LOS ARCHIVOS D CARPETA / AGREGAR UN ARCHIVO ESPECIFICO#
git add . / git add nombre_archiv.extension
#COMANDO PARA SABER ESTATUS DE GIT#
git status
#AGREGAR MENSAJE PARA IDENTIFICAR LA MODIFICACIÓN#
git commit -m "MENSAJE"
#CAMBIAR A BRANCH DONDE SE HARÁN LAS MODIFICACIONES
git branch -M main
#DIRIGIR LOS CAMBIOS AL REPOSITORIO DESEADO#
git remote add origin LINK_REPOSITORIO.git
#GUARDAR CAMBIOS A REPOSITORIO#
git push -u origin main
#EN CASO DE QUE EL REPOSITORIO YA EXISTA SE UTILIZA EL SIGUENTE COMANDO, 
TOMANDO EN CUENTA QUE REEMPLAZARÁ/ELIMINARÁ LOS ARCHIVOS EXISTENTES#
git push -f origin main
#PARA AGREGAR UN NUEVO ARCHIVO#
git add nombre_archivo.extension
#AGREGAR MENSAJE PARA IDENTIFICAR LA MODIFICACIÓN#
git commit -m "MENSAJE"
#AGREGAR ARCHIVO#
git push
#CUANDO LAS ACTUALIZACIONES HAN SIDO RECHAZADAS, UTIKIZAR EL SIGUIENTE COMANDO#
git pull
#POSTERIORMENTE, VOLVER A INTENTAR CON EL SIGUIENTE COMANDO#
git push
