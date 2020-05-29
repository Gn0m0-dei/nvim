Mi configuración para NeoVim. Requiere instalar primero  [vim-plug](https://github.com/junegunn/vim-plug).  

Si los plugins de python dan error, ejecutar en terminal:

    python -m pip install --user --upgrade pynvim

# Windows
Poner el archivo en (sino existe la ruta crearla):

    C:\Users\"TU USUARIO"\AppData\Local\nvim
Ir a la ruta por cmd y ejecutar:

    nvim init.vim
Una vez dentro de nvim escribir:

    :PlugInstall
Y por último esperar a que se instalen todos los plugins
