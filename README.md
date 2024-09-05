# Comandos usados en clases de Sistemas Operativo Avanzado

## Debian 11/linux

### 1. Comando: `who`

**¿Qué hace?**  
Muestra una lista de los usuarios que están conectados al sistema.

**¿Cómo usarlo?**  
Escribe `who` en la consola y presiona `Enter`.

**Ejemplo de uso:**

```bash
who
```

---
### 2. Comando: `Alt + F2`

**¿Qué hace?**  
Cambia entre diferentes terminales virtuales. En un entorno sin interfaz gráfica, Debian generalmente inicia con múltiples terminales virtuales (tty), y puedes cambiar entre ellas con las teclas `Alt + F1` a `Alt + F6`.

**¿Cómo usarlo?**  
Presiona `Alt + F2` (o cualquier combinación de `Alt` con `F1` a `F6`) para cambiar entre terminales.

---
### 3. Comando: `ls`

**¿Qué hace?**  
Lista los archivos y directorios en el directorio actual.

**¿Cómo usarlo?**   
Escribe `ls` y presiona `Enter`. Si quieres listar los archivos con más detalles (como permisos, tamaños, etc.), puedes usar `ls -l`.

**Ejemplo de uso:**

```bash
ls      # Lista los archivos y carpetas.
ls -l   # Lista con detalles como permisos, propietario, tamaño, etc.
```

---
### 4. Comando: `cd`

**¿Qué hace?**  
Cambia el directorio en el que te encuentras. Te permite moverte entre carpetas.

**¿Cómo usarlo?**   
Escribe `cd` seguido de la ruta del directorio al que quieres moverte. Si escribes solo `cd`, te lleva al directorio principal (/home) del usuario.

**Ejemplo de uso:** 

```bash
cd /home/usuario  # Te lleva al directorio /home/usuario.
cd ..             # Te mueve un directorio hacia arriba.
cd                # Te lleva a tu directorio principal.
```

---
### 5. Comando: `pwd`

**¿Qué hace?**  
Muestra el directorio actual en el que te encuentras (la ruta completa).

**¿Cómo usarlo?**   
Escribe `pwd` y presiona `Enter` para mostrar la ruta completa del directorio actual.

**Ejemplo de uso:** 

```bash
pwd
```

---
### 6. Comando: `mkdir`

**¿Qué hace?**  
Crea un nuevo directorio (carpeta).

**¿Cómo usarlo?**   
Escribe `mkdir` seguido del nombre del directorio que quieres crear.

**Ejemplo de uso:**

```bash
mkdir nueva_carpeta
```

---
### 7. Comando: `rm`

**¿Qué hace?**  
Elimina archivos o directorios. ¡Ten cuidado! Si usas `rm` para eliminar un archivo, no hay papelera de reciclaje.

**¿Cómo usarlo?**   
Escribe `rm` seguido del archivo que deseas eliminar. Si quieres eliminar un directorio y su contenido, usa la opción `-r`.

**Ejemplo de uso:** 

```bash
rm archivo.txt          # Elimina archivo.txt.
rm -r nombre_directorio  # Elimina un directorio y su contenido.
```

---
### 8. Comando: `cp`

**¿Qué hace?**  
Copia archivos o directorios.

**¿Cómo usarlo?**   
Escribe `cp` seguido del archivo a copiar y luego la ubicación o nombre del nuevo archivo.

**Ejemplo de uso:** 

```bash
cp archivo.txt /ruta/destino      # Copia archivo.txt a otra ubicación.
cp -r directorio /ruta/destino    # Copia un directorio y su contenido.
```

---
### 9. Comando: `mv`

**¿Qué hace?**  
Mueve archivos o cambia el nombre de archivos o directorios.

**¿Cómo usarlo?**   
Escribe `mv` seguido del archivo o directorio a mover y la ubicación de destino, o el nuevo nombre si deseas renombrarlo.

**Ejemplo de uso:** 

```bash
mv archivo.txt /ruta/nueva         # Mueve archivo.txt a otra ubicación.
mv archivo_viejo.txt archivo_nuevo.txt  # Renombra archivo_viejo.txt a archivo_nuevo.txt.
```

---
### 10. Comando: `man`
**¿Qué hace?**  
Muestra el manual de cualquier comando. Es útil para aprender más sobre cómo usar un comando y todas sus opciones.

**¿Cómo usarlo?**   
Escribe `man` seguido del comando del cual deseas leer el manual.

**Ejemplo de uso:**

```bash
man ls    # Muestra el manual del comando ls.
```

---
### 11. Comando: `clear`

**¿Qué hace?**  
Limpia la pantalla del terminal.

**¿Cómo usarlo?**   
Escribe `clear`clear y presiona `Enter`.

**Ejemplo de uso:** 
```bash
clear
```

---
### 12. Comando: `touch`

**¿Qué hace?**  
Crea un archivo vacío o actualiza la fecha y hora de acceso/modificación de un archivo existente.

**¿Cómo usarlo?**   
Escribe `touch` seguido del nombre del archivo que deseas crear o actualizar.

**Ejemplo de uso:**    
```bash
touch archivo.txt  # Crea un archivo vacío llamado archivo.txt.
```