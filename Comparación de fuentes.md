
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

¿Quieres que te explique cómo activar las ligaduras en tu editor? 🚀
