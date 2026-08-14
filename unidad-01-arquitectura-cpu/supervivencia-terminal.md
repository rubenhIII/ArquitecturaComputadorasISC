# 🐧 GUÍA DE SUPERVIVENCIA EN LINUX (TERMINAL)

> **Regla de oro:** *"Si no sabes qué hace un comando, no lo ejecutes. Primero escribe `man comando` o `comando --help`"*.

---

## 🌍 NAVEGACIÓN (¿Dónde estoy y a dónde voy?)

| Comando | Qué hace | Ejemplo |
|---------|----------|---------|
| `pwd` | **Muestra la ruta actual** (dónde estás parado) | `pwd` → `/home/alumno` |
| `ls` | **Lista archivos y carpetas** (qué hay aquí) | `ls -la` (versión con detalles y ocultos) |
| `cd` | **Cambiar de directorio** (moverse) | `cd Documentos` / `cd ..` (subir) / `cd ~` (ir a casa) |

---

## 📁 GESTIÓN DE ARCHIVOS Y CARPETAS

| Comando | Qué hace | Ejemplo |
|---------|----------|---------|
| `touch` | **Crear archivo vacío** | `touch notas.txt` |
| `mkdir` | **Crear carpeta** | `mkdir proyecto` |
| `cp` | **Copiar** archivo o carpeta | `cp origen.txt destino/` |
| `mv` | **Mover o renombrar** | `mv viejo.txt nuevo.txt` |
| `rm` | **Eliminar archivo** (¡cuidado!) | `rm temporal.log` |
| `rm -r` | **Eliminar carpeta** (recursivo) | `rm -r basura/` |
| `cat` | **Ver contenido de un archivo** | `cat config.ini` |
| `nano` | **Editor básico** (guardar con Ctrl+O) | `nano miarchivo.md` |

> ⚠️ **Peligro:** `rm -rf /` borra todo el sistema. **NUNCA lo ejecutes**.

---

## 🔍 BUSCAR Y FILTRAR

| Comando | Qué hace | Ejemplo |
|---------|----------|---------|
| `find` | **Buscar archivos** por nombre | `find . -name "*.pdf"` |
| `grep` | **Buscar texto dentro de archivos** | `grep "error" registro.log` |
| `wc` | **Contar líneas, palabras o caracteres** | `wc -l archivo.txt` |

---

## 🛠️ PERMISOS Y SUPERUSUARIO

| Comando | Qué hace | Ejemplo |
|---------|----------|---------|
| `sudo` | **Ejecutar como superusuario** | `sudo apt update` |
| `chmod` | **Cambiar permisos** | `chmod +x script.sh` (hacer ejecutable) |
| `chown` | **Cambiar propietario** | `chown alumno:alumno archivo` |

---

## 📦 INSTALAR Y ACTUALIZAR SOFTWARE

| Comando (Debian/Ubuntu) | Qué hace |
|-------------------------|----------|
| `sudo apt update` | Actualiza la lista de paquetes |
| `sudo apt upgrade` | Actualiza los paquetes instalados |
| `sudo apt install [paquete]` | Instala un programa |
| `sudo apt remove [paquete]` | Desinstala un programa |

---

## 🧠 COMANDOS ÚTILES PARA "NO PERDERSE"

| Comando | Para qué sirve |
|---------|----------------|
| `clear` o `Ctrl+L` | Limpiar la pantalla |
| `history` | Ver historial de comandos |
| `man [comando]` | Manual completo del comando |
| `[comando] --help` | Ayuda rápida |
| `Tab` | Autocompletar (¡úsalo siempre!) |
| `Ctrl+C` | Cancelar lo que se está ejecutando |
| `Ctrl+D` | Cerrar la terminal |

---

## 🧭 MAPA DE RUTAS IMPORTANTES

| Ruta | Significado |
|------|-------------|
| `/` | Raíz del sistema |
| `/home/usuario/` | Carpeta personal (~) |
| `/etc/` | Archivos de configuración del sistema |
| `/var/log/` | Archivos de registro (logs) |
| `/tmp/` | Archivos temporales (se borran al reiniciar) |

---

## ✨ TRUCO PRO: ENCADENAR COMANDOS

```bash
# Ejecutar uno después del otro (sin importar si falla)
comando1 ; comando2

# Ejecutar solo si el anterior funcionó
comando1 && comando2

# Guardar la salida de un comando en un archivo
ls -la > listado.txt

# Añadir salida al final de un archivo
echo "Nueva línea" >> archivo.txt
