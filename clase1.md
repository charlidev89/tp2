## configuracion git
- git config --global user.name  "carlos arteaga"
- git config --global user.email dakaricarlos@gmail.com
- git config  --global core.editor "code --wait"    // sirve para no abrir el BIM o la consola 
- git config  --global -l   //sirve para ver la configuracion
- git config  --global -e   // vaveriguar
## window  :
- git config  --global core.autocrlf true      // configuracion para que al hacer merge por un tema de salto de linea no lo detecte y solamente detecte cambios reales.

## push sin especificar rama
- git config  --global push.default current   // sirve para hacer push sin especificar que rama pusheamos  git push y listo
- git remote -v // muestra los repositorios remotos que tenemos
- git add .  // agrega al staging area los cambios para ser commitiados
- git commit -m "Primer commit: Inicialización del proyecto"   
- git remote add origin https://github.com/tu-usuario/mi_proyecto.git   // conecta el repo local con el remoto
- git push -u origin main   // pushea el repo local al remoto en la direccion previa puesta
## renombrar rama
- git branch -m "nombreViejo" "nombreNuevo"    //sin comillas
## eliminar rama 
- git branch -d  "ramaEliminar" 
## clonar un repo remoto
- git clone https://github.com/tu-usuario/otro_proyecto.git   // se debe crear una carpeta en otra parte y luego simplemente clonamos con este comandoe