
# Alternativa a fuentes tipográficas privativas de microsoft
La siguiente es una tabla donde están indicandos los usos típicos en documentos de fuentes tipográficas alternativas a las privativas de microsoft:

---

|   **Fuente de Windows**    |                         **Alternativa de Software Libre**                          |                    **Uso Común en Documentos**                     |                                      **Notas**                                       |
| -------------------------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| **Arial**                  | **Liberation Sans** / **IBM plex Sans** /  **Dejavu Sans**                         | Cuerpo de texto, títulos, subtítulos                               | Fuente sans-serif estándar y versátil.                                               |
| **Times New Roman**        | **Liberation Serif** / **Nimbus Roman** / **IBM plex serif**                       | Cuerpo de texto, informes formales, libros                         | Fuente serif clásica para documentos profesionales.                                  |
| **Courier New**            | **FreeMono** / **Mono Uralic** / **Inconsolata**                                   | Código, documentos técnicos, textos monoespaciados                 | Fuente monoespaciada usada en programación y tabulación.                             |
| **Calibri**                | **Carlito**                                                                        | Cuerpo de texto, presentaciones                                    | Fuente moderna y legible.                                                            |
| **Cambria**                | **Caladea**                                                                        | Cuerpo de texto, informes formales                                 | Similar a Times New Roman, con mejor legibilidad en pantalla.                        |
| **Comic Sans MS**          | **Comic Neue** /                                                                   | Usada en textos informales, educativos y presentaciones infantiles | Comic Neue es más refinada.                                                          |
| **Verdana**                | **Cantarell**                                                                      | Cuerpo de texto, páginas web, interfaces gráficas                  | Excelente legibilidad en pantallas.                                                  |
| **Georgia**                | **Source Serif 4** / **TeXGyreTermes**  / **BPG Gorda GPL&GNU**                    | Cuerpo de texto, títulos de documentos                             | Fuente serif con buena legibilidad en pantalla.                                      |
| **Trebuchet MS**           | **BPG Ingiri GPL&GNU**                                                             | Títulos, subtítulos, presentaciones                                | Alternativa con un diseño limpio y moderno.                                          |
| **Impact**                 | **Anton** / **Oswald**                                                             | Títulos llamativos                                                 | Anton es una alternativa con un impacto visual fuerte.                               |
| **Tahoma**                 | **TeXGyreHeros**                                                                   | Cuerpo de texto en interfaces gráficas y documentos empresariales  | Similar en espaciado y claridad.                                                     |
| **Palatino Linotype**      | **TeXGyrePagella** / **Pallatio Uralic**                                           | Libros, ensayos, textos académicos                                 | Basado en el diseño de Palatino.                                                     |
| **Book Antiqua**           | **EB Garamond 12**, **EB Garamond 08**, **EB Garamond ALL SC**                     | Cuerpo de texto en documentos elegantes o clásicos                 | Alternativas clásicas con estilo refinado.                                           |
| **Franklin Gothic Medium** | **Libre Franklin Medium**                                                          | Títulos, carteles, encabezados                                     | Fuente sans-serif gruesa con estilo fuerte.                                          |
| **Century Gothic**         | **URW Gothic**                                                                     | Títulos modernos, diseño gráfico                                   | Diseño limpio y futurista.                                                           |
| **Rockwell**               | **Slabo 27px** / **Arvo**                                                          | Títulos con impacto visual                                         | Alternativas de estilo slab-serif.                                                   |
| **Baskerville**            | **Goudy Bookletter 1911**                                                          | Cuerpo de texto en documentos clásicos y elegantes                 | Fuente con excelente legibilidad impresa.                                            |
| **Consolas**               | **JetBrains Mono** / **DejaVu Sans Mono** / **Fira Code** / **Hack** / **Iosevka** | Código de programación, terminales, documentos técnicos            | Consolas es monoespaciada, sus alternativas tienen soporte para ligaduras de código. |

---

### **Consejos de uso:**

Uso de fuentes tipográficas no privativas en Documentos:

- **Títulos:** Oswald, Anton, Libre Franklin, URW Gothic, Slabo 27px  
- **Cuerpo de texto:** Carlito, Caladea, Liberation Serif, EB Garamond, Source Serif Pro  
- **Código de programación:** Fira Code, JetBrains Mono, Source Code Pro, Liberation Mono  
- **Documentos formales:** Libre Baskerville, TeX Gyre Pagella, EB Garamond, Noto Serif  
- **Diseño gráfico y presentaciones:** Cantarell, DejaVu Sans, Noto Sans, TeX Gyre Adventor  

Estas fuentes cubren casi todos los usos y garantizan compatibilidad sin depender de las de Windows.

Y aquí tienes la lista solo con las **fuentes de Windows** más usadas en documentos de Microsoft Office:  

- **Títulos:** Franklin Gothic, Trebuchet MS, Impact, Century Gothic  
- **Cuerpo de texto:** Calibri, Cambria, Arial, Times New Roman, Verdana  
- **Código de programación:** Consolas, Courier New  
- **Documentos formales:** Times New Roman, Cambria, Georgia, Palatino Linotype, Book Antiqua  
- **Diseño gráfico y presentaciones:** Century Gothic, Tahoma, Comic Sans MS  

Estas fuentes vienen preinstaladas en Windows y se usan ampliamente en documentos de Word, Excel y PowerPoint.

---

### **📌 Instalación de las fuentes libres en Linux (Debian/MX Linux/Ubuntu)**
Instala las fuentes libres directamente desde los repositorios con este comando:  

```bash
sudo apt install fonts-liberation fonts-freefont-ttf fonts-crosextra-carlito \
    fonts-crosextra-caladea fonts-dejavu fonts-cantarell fonts-firacode \
    fonts-jetbrains-mono fonts-texgyre fonts-texgyre-math fonts-ebgaramond \
    fonts-ibm-plex fonts-hack fonts-inconsolata fonts-uralic \
    fonts-urw-base35 fonts-bpg-georgian fonts-comic-neue \
    fonts-goudybookletter fonts-ebgaramond-extra
```

Entre las que se intalan, hay algunos paquetes que instalan varias fuentes con diferentes tipos y diferentes nombres:

**fonts-liberation =** Liberation Sans, Liberation Serif
**fonts-freefont-ttf =** FreeMono
**fonts-crosextra-carlito** = carlito
**fonts-crosextra-caladea** = caladea
**fonts-dejavu =** DejaVu Sans, DejaVu Sans Mono
**fonts-cantarell =** Canatarell
**fonts-texgyre =** TeXGyrePagella, TeXGyreHeros, TeXGyreTermes 
fonts-texgyre-math
**fonts-ebgaramond =** EB Garamond 12, 
**fonts-ebgaramond-extra =** EB Garamond 12,  EB Garamond 08, EB Garamond ALL SC
**fonts-ibm-plex =** IBM Plex Sans, IBM plex Serif 
**fonts-hack =** Hack
**fonts-inconsolata =** Inconsolata
**fonts-uralic =** Pallatio Uralic
**fonts-urw-base35 =** Nimbus Roman, URW Gothic
**fonts-bpg-georgian =** BPG Gorda GPL&GNU, BPG Ingiri GPL&GNU
**fonts-comic-neue =** Comic Neue
**fonts-goudybookletter =** Goudy Bookletter 1911


---

### **📌 Instalación manual desde Google Fonts**
Algunas fuentes como no están en los repositorios, pero puedes descargarlas desde [Google Fonts](https://fonts.google.com/):  
1. Busca la fuente y descárgala (`.zip` con archivos `.ttf` o `.otf`).  

**Slavo 27px → Alternativa a Rockwell**
[https://fonts.google.com/specimen/Slabo+27px](https://fonts.google.com/specimen/Slabo+27px)

**Libre Franklin → Alternativa a  Franklin Gothic**
[https://fonts.google.com/specimen/Libre+Franklin](https://fonts.google.com/specimen/Libre+Franklin)

**Oswald → Alternativa a Impact**  
[https://fonts.google.com/specimen/Oswald](https://fonts.google.com/specimen/Oswald)

**Anton → Alternativa a Impact**
[https://fonts.google.com/specimen/Anton](https://fonts.google.com/specimen/Anton)

**Arvo → Alternativa a Rockwell**
[https://fonts.google.com/specimen/Arvo](https://fonts.google.com/specimen/Arvo)

**Source Serif 4 → Alternativa a Georgia**
[https://fonts.google.com/specimen/Source+Serif+4](https://fonts.google.com/specimen/Source+Serif+4)

**Iosevka → Alternativa a Consolas**
https://github.com/be5invis/Iosevka/releases
Ejemplo:
https://github.com/be5invis/Iosevka/releases/download/v32.5.0/PkgTTF-Iosevka-32.5.0.zip

2. Extrae los archivos en `~/.fonts/` (para usuario actual) o en `/usr/share/fonts/` (para todos los usuarios).  
3. Refresca la caché de fuentes con:  
```bash
fc-cache -fv
```
---

3. **Fuentes TrueType de Windows** (Si tienes una copia de Windows)
   - Copia los archivos de fuentes (`.ttf`) desde `C:\Windows\Fonts` a `~/.local/share/fonts/` o `/usr/share/fonts/` en Linux.
   - Luego actualiza la caché de fuentes con:
    ```bash
    fc-cache -fv
    ```
---

### **📌 Verificar que las fuentes están instaladas**
Después de instalar, puedes comprobar si una fuente está disponible con:  
```bash
fc-list | grep "NombreFuente"
```
Por ejemplo, para verificar **Carlito**:  
```bash
fc-list | grep "Carlito"
```
---

### **📌 Opcional: Instalar una GUI para gestionar fuentes**
Si quieres ver, activar o desactivar fuentes fácilmente, instala **Font Manager**:  
```bash
sudo apt install fontmatrix
```
Luego ábrelo desde el menú y revisa tus fuentes instaladas.

---

### Consejos adicionales:
- **Evita usar fuentes exóticas** Si compartes documentos con usuarios de Windows sólo usa fuentes de Windows.
