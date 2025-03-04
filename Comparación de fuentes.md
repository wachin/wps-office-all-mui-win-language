
patrón:

```
abcdefghijklmnopqrstuvwxyz ABCDEFGHIJKLMNOPQRSTUVWXYZ 0123456789 áéíóú üñ |@#~½{[]}¡!"'$%&\ /()=¿? ffi ffl fi fl
```

Este patrón para comparar fuentes cubre:

✅ **Letras minúsculas y mayúsculas** (para evaluar la legibilidad y diseño).
✅ **Números** (importante para documentos técnicos y financieros).
✅ **Símbolos comunes** (para ver cómo maneja puntuación y caracteres especiales).

Si quieres hacer una comparación aún más detallada, podrías agregar:
- **Caracteres con acentos**: `áéíóú üñ` (importante para español).
- **Caracteres extendidos**: `|@#~½{[]}¡!"'$%&\ /()=¿?` (para multiples usos).
- **Ligaduras tipográficas** (si aplican, en fuentes como Iosevka o Fira Code): `ffi ffl fi fl`



Aquí tienes ejemplos de código que contienen las ligaduras **fi, fl, ffi, ffl** para que puedas ver cómo se comportan en fuentes con ligaduras tipográficas activadas, como **Fira Code, JetBrains Mono o Iosevka**.

---

### **📌 Ejemplo en Python**
```python
# Definiendo una función ficticia con palabras que contienen fi, fl, ffi, ffl
def find_flight_info(office, affiliate):
    office_flight = "Flight information available"
    affiliate_flights = "Affiliate flights confirmed"

    print(office_flight)
    print(affiliate_flights)

find_flight_info("Main Office", "Global Affiliates")
```
**Palabras con ligaduras activadas:**
- `find` → `ﬁnd`
- `flight` → `ﬂight`
- `office` → `oﬃce`
- `affiliate` → `aﬃliate`

---

### **📌 Ejemplo en JavaScript**
```javascript
// Archivo que almacena información de vuelos
const flightInfo = {
    office: "Main Office",
    affiliate: "Global Affiliate",
    flights: ["Flight 101", "Flight 202"]
};

console.log(flightInfo.office);
console.log(flightInfo.affiliate);
console.log(flightInfo.flights);
```
**Palabras con ligaduras activadas:**
- `flight` → `ﬂight`
- `office` → `oﬃce`
- `affiliate` → `aﬃliate`
- `flights` → `ﬂights`

---

### **📌 Ejemplo en C++**
```cpp
#include <iostream>
using namespace std;

void affiliateFlightInfo(string office) {
    string flightDetails = "Flight confirmed for affiliate";
    cout << flightDetails << endl;
}

int main() {
    affiliateFlightInfo("Main Office");
    return 0;
}
```
**Palabras con ligaduras activadas:**
- `affiliate` → `aﬃliate`
- `flight` → `ﬂight`
- `office` → `oﬃce`

---

Si usas una fuente con ligaduras tipográficas activadas en tu editor (VS Code, JetBrains, Neovim con Nerd Fonts, etc.), notarás que estas combinaciones de letras se verán fusionadas.


### **📌 ¿Para qué sirven las ligaduras tipográficas en español?**  

En español, las ligaduras tipográficas **no son esenciales**, pero pueden mejorar la estética y la legibilidad en ciertos textos

✅ **1. Para mejorar la legibilidad en textos impresos**  
   - En libros, periódicos y documentos formales, el uso de ligaduras puede hacer que la lectura fluya mejor, especialmente en fuentes serif como **Libre Baskerville** o **EB Garamond**.  
   - Ejemplo:  
     ```
     La oficina está afiliada a la federación de filósofos.
     ```
     → Se activarán las ligaduras en **oficina, afiliada, filósofos** (`fi`, `ffi`, `fl`).  

✅ **2. Para un diseño más elegante en tipografía clásica**  
   - Las ligaduras son comunes en textos que buscan un **aspecto refinado**, como invitaciones, diplomas o cartas formales.  
   - En fuentes como **TeX Gyre Pagella** o **Goudy Bookletter 1911**, los caracteres se unen de forma más estilizada.  

### **📌 Todas las fuentes con ligaduras tipográficas en español**  

Lista de fuentes **libres y gratuitas** que incluyen ligaduras:  

#### **Fuentes serif (clásicas y elegantes)**  
📌 *Ideales para libros, documentos formales y diseño elegante*  
- **Libre Baskerville**  
- **EB Garamond** (contiene muchas ligaduras clásicas)  
- **TeX Gyre Pagella**  
- **TeX Gyre Termes**  
- **Goudy Bookletter 1911**  
- **Crimson Text**  
- **Cormorant Garamond**  
- **Charis SIL**  

#### **Fuentes monoespaciadas (para código y terminales)**  
📌 *Usadas en programación con ligaduras avanzadas para operadores*  
- **Fira Code**  
- **JetBrains Mono**  
- **Iosevka**  
- **Cascadia Code**  
- **Hasklig** (especialmente para Haskell y lenguajes funcionales)  

#### **Fuentes sans-serif con ligaduras**  
📌 *No es tan común en sans-serif, pero algunas lo soportan*  
- **IBM Plex Serif**  
- **Source Serif Pro**  
- **Noto Serif**  

---

### **📌 Resumen**
✅ **Las ligaduras en español ayudan a mejorar la estética y legibilidad en textos formales y diseño gráfico.**  
✅ **Se pueden usar en LibreOffice, LaTeX, y procesadores de texto avanzados.**  
✅ **Las fuentes más recomendadas para textos en español con ligaduras son EB Garamond, Libre Baskerville y TeX Gyre Pagella.**  
