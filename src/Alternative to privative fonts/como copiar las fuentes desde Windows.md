
# 🖋️ Cómo copiar las Fuentes Tipográficas de Windows a Linux

Este tutorial explica cómo **copiar e instalar las fuentes tipográficas (TrueType, OpenType, etc.) desde Windows a un sistema Linux**, ya sea Debian, Ubuntu o cualquier distribución basada en GNU/Linux. Ideal si vienes de Windows y no quieres perder tus fuentes favoritas.

---

## 📚 Índice

1. [Requisitos previos](#-requisitos-previos)
2. [Paso 1: Localizar las fuentes en Windows](#paso-1-localizar-las-fuentes-en-windows)
3. [Paso 2: Copiar las fuentes a Linux](#paso-2-copiar-las-fuentes-a-linux)
4. [Paso 3: Crear un directorio para las fuentes](#paso-3-crear-un-directorio-para-las-fuentes)
5. [Paso 4: Copiar los archivos de fuente](#paso-4-copiar-los-archivos-de-fuente)
6. [Paso 5: Actualizar la caché de fuentes](#paso-5-actualizar-la-caché-de-fuentes)
7. [Formatos compatibles](#-formatos-compatibles)
8. [Fuentes que no funcionan o necesitan conversión](#fuentes-que-no-funcionan-o-necesitan-conversión)
9. [Consejos adicionales](#-consejos-adicionales)

---

## 🔧 Requisitos previos

- Acceso a particiones NTFS donde esté instalado Windows (si usas dual boot).
- Conocimientos básicos de terminal.
- Tener permisos de superusuario si deseas instalar las fuentes para todos los usuarios del sistema.

---

## 📍 Paso 1: Localizar las fuentes en Windows

En Windows, todas las fuentes instaladas se almacenan en la carpeta:

```
C:\Windows\Fonts
```

Esta carpeta contiene principalmente archivos `.ttf`, `.otf`, `.fon` y algunos `.ttc`.

> 💡 Puedes acceder a esta carpeta desde tu sesión de Windows o montando la partición desde Linux.

---

## 📥 Paso 2: Copiar las fuentes a Linux

### Opción A: Desde Windows

1. Abre `C:\Windows\Fonts`.
2. Selecciona todas las fuentes que quieras llevar a Linux (usa `Ctrl + A` para seleccionar todas).
3. Cópialas a un pendrive o unidad compartida accesible desde Linux.

### Opción B: Desde Linux (Dual Boot)

1. Monta la partición donde está instalado Windows.
2. Navega hasta `/media/tu_usuario/NombreDePartición/Windows/Fonts`.
3. Copia los archivos a una carpeta temporal en tu home.

---

## 🗂️ Paso 3: Crear un directorio para las fuentes

Puedes crear una carpeta para organizar tus fuentes copiadas:

### Puedes hacerlo con un administrador de archivos
Has visibles los archivos y directorios ocultos con `Ctrl + H`. Luego **Crea un directorio para las fuentes** con el nombre `.fonts` y luego dentro de ella `windows_fonts` (en tu home), así debe de quedar:

.fonts/windows_fonts

**Nota:** Si no existe la carpeta .fonts debes crearla y entrar en ella, y allí crear la carpeta: `windows_fonts`, esto para el usuario actual.

o

`/usr/share/fonts/windows_fonts`

para todos los usuarios, pero deberás hacer esto como superusuario (en este caso lo mejor será hacerlo desde la terminal).

### Para crear los directorios desde la terminal, para el usuario actual:
```bash
mkdir -p ~/.fonts/windows_fonts
```

### Para todos los usuarios del sistema (requiere permisos de superusuario):
```bash
sudo mkdir -p /usr/share/fonts/windows_fonts
```

---

## 📁 Paso 4: Copiar los archivos de fuente

Una vez tengas los archivos `.ttf`, `.otf` o `.ttc` en tu equipo Linux, cópialos al directorio creado.

Puedes usar tu administrador de archivos como **Nautilus**, **Dolphin**, **Thunar** o **Nemo** para arrastrar y soltar los archivos

o:

Ejemplo usando el terminal:
```bash
cp ~/Descargas/fuentes_windows/*.ttf ~/.fonts/windows_fonts/
cp ~/Descargas/fuentes_windows/*.otf ~/.fonts/windows_fonts/
```

> ❌ Ignora los archivos `.fon`: No son compatibles con Linux moderno.

---

## ♻️ Paso 5: Actualizar la caché de fuentes

Puedes cerrar el programa que estés usando como LibreOffice, GIMP, Inkscape, etc y volverlo a abrir para que reconozca la fuentes tipográficas instaladas

y además se puede hacer desde la terminal:

```bash
fc-cache -fv
```

Este comando forzará la reconstrucción de la caché de fuentes. Si no lo ejecutas, las fuentes aparecerán después de reiniciar las aplicaciones o el sistema.

---

## 📄 Formatos compatibles

Linux soporta varios formatos de fuentes. Aquí tienes una lista de los más comunes:

| Extensión | Nombre completo          | ¿Compatible? | Notas |
|----------|---------------------------|--------------|-------|
| `.ttf`   | TrueType Font             | ✅ Sí         | Totalmente compatible |
| `.otf`   | OpenType Font             | ✅ Sí         | Totalmente compatible |
| `.ttc`   | TrueType Collection       | ⚠️ Parcial    | Contiene varias fuentes; puede requerir extracción |
| `.fon`   | Fuente bitmap de Windows  | ❌ No         | Antiguo formato incompatible |

---

## ⚠️ Fuentes que no funcionan o necesitan conversión

### Archivos `.fon`

Son fuentes bitmap antiguas usadas en versiones viejas de Windows. Ejemplos:

- `coure.fon`
- `roman.fon`
- `script.fon`
- `vgafix.fon`

No son útiles en Linux moderno. Puedes eliminarlas sin problema.

### Archivos `.ttc`

Contienen múltiples fuentes dentro de un mismo archivo. Algunas aplicaciones pueden no reconocerlas correctamente. Puedes usar herramientas como **FontForge** para dividirlas.

Instalación de FontForge (en Debian/Ubuntu):
```bash
sudo apt install fontforge
```

---

## 💡 Consejos adicionales

- Si usas KDE Plasma, puedes gestionar las fuentes desde **Configuración del Sistema > Fuentes**.
- En GNOME, usa la extensión **GNOME Tweaks** para ver las fuentes disponibles.
- Las fuentes instaladas en `~/.fonts/` solo serán visibles para ti como usuario.
- Las fuentes en `/usr/share/fonts/` estarán disponibles para todos los usuarios del sistema.

---

## 🙌 Conclusión

Migrar tus fuentes de Windows a Linux es un proceso sencillo y útil, especialmente si trabajas con documentos, diseño gráfico o edición de texto. Con este procedimiento podrás disfrutar de tus fuentes favoritas en entornos Linux como Debian, Ubuntu, Fedora o Arch Linux.

