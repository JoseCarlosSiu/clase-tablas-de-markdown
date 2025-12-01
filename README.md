# clase-tablas-de-markdown

cat > comandos-linux-basicos.md << 'EOF'
# Comandos Básicos en Linux para Empezar

## Comandos que hay que conocer

| Comando  | Descripción |
|----------|-------------|
| `man`    | Muestra el manual de usuarios de un comando específico. Si lo escribes primero y luego escribes otro comando, verás para qué sirve ese otro comando. |
| `clear`  | Limpia el terminal y deja la ventana en blanco eliminando todo lo que se había hecho y escrito antes. |
| `sudo`   | Abreviatura de "superuser do". Permite ejecutar una acción como superusuario (administrador), como instalar aplicaciones o modificar archivos. Se coloca antes del comando que quieres ejecutar con privilegios. |
| `history`| Muestra una lista con el historial de comandos utilizados en la terminal durante la sesión actual. |

## Comandos básicos de directorios

| Comando            | Descripción |
|--------------------|-------------|
| `pwd`              | Muestra el directorio actual en el que te encuentras. |
| `cd`               | Change Directory. Cambia de directorio. Si se usa solo, te lleva al directorio personal (Home). |
| `cd dirección/`    | Te permite ir a un directorio concreto. |
| `cd ..`            | Sube al directorio padre (nivel superior). |
| `cd -`             | Regresa al directorio anterior en el que estabas. |
| `ls`               | Lista los archivos y directorios dentro del directorio actual. |
| `mkdir`            | Crea un nuevo directorio en la ubicación actual. |

## Comandos básicos para archivos

| Comando | Descripción |
|---------|-------------|
| `find`  | Busca archivos y directorios en el sistema. |
| `cp`    | Copia archivos o directorios. Ejemplo: `cp archivo.txt destino/` |
| `mv`    | Mueve o renombra archivos y directorios. Ejemplo: `mv archivo carpeta/` |
| `rm`    | Elimina archivos y directorios. |
| `wget`  | Descarga archivos desde Internet. |
| `head`  | Muestra las primeras líneas de un archivo. |
| `tail`  | Muestra las últimas líneas de un archivo (por defecto 10). |
| `grep`  | Busca patrones de texto dentro de archivos. |
| `cat`   | Muestra, concatena o crea archivos. |
| `wc`    | Cuenta líneas, palabras y caracteres en un archivo. |
| `less`  | Muestra el contenido de un archivo página a página. |
| `touch` | Crea un archivo vacío o actualiza sus marcas de tiempo. |
| `chmod` | Cambia los permisos de un archivo (lectura, escritura, ejecución). Ejemplo: `chmod +x script.sh` |
| `unzip` | Descomprime archivos ZIP. |
| `./`    | Ejecuta un archivo ejecutable en el directorio actual. Ejemplo: `./programa` |
| `kill`  | Finaliza un proceso por su identificador (PID). |
| `shred` | Sobrescribe un archivo múltiples veces para hacer imposible su recuperación. |

## Otros comandos

| Comando     | Descripción |
|-------------|-------------|
| `alias`     | Define un alias temporal para comandos. Ejemplo: `alias ll="ls -la"` |
| `unalias`   | Elimina un alias previamente definido. |
| `htop`      | Muestra los procesos en ejecición y el uso de recursos del sistema (interfaz interactiva). |
| `ps`        | Muestra los procesos de la sesión actual del terminal. |
| `ping`      | Verifica la conectividad con una dirección IP o dominio. |
| `echo`      | Muestra un mensaje en la terminal. Ejemplo: `echo "Hola"` |
| `passwd`    | Cambia la contraseña del usuario actual. |
| `whoami`    | Muestra el nombre del usuario actual. |
| `uname`     | Muestra información del sistema. Usa `uname -a` para ver todos los detalles. |
| `neofetch`  | Muestra información del sistema con un logo ASCII de la distribución (requiere instalación). |
| `whatis`    | Muestra una breve descripción de un comando o programa. |
| `exit`      | Cierra la sesión de terminal. |
| `shutdown`  | Apaga el sistema. Ejemplo: `shutdown now` para apagar inmediatamente. |

**Nota:** Los comandos deben usarse con precaución, especialmente aquellos que modifican o eliminan archivos (`rm`, `shred`, `shutdown`, etc.).
EOF
