# Epsol

### 1. Arduino Nano generico 
- Usa chip **CH340** para la comunicación USB.
- ⚠️ **En Windows:** es necesario instalar el driver CH340.
- ✅ **En macOS y Linux:** generalmente no se necesita instalar nada extra.

### 2. Arduino IDE
- Usamos la versión **1.8.x** (clásica, no la versión moderna 2.x).
- Puedes descargarla aquí:  
  👉 [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)

### 3. Librerías necesarias

Debes instalar la siguiente librería:

- **RF24 by TMRh20**

Para instalarla:
1. Abre el IDE de Arduino.
2. Ve a **Programa > Incluir Librería > Gestionar Bibliotecas...**
3. Busca **`RF24`** e instala la que diga “by TMRh20”.

La librería `SPI.h` ya viene incluida con el IDE.
