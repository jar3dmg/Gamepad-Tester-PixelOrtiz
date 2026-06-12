# Gamepad Tester - Pixel Ortiz Tech

Adaptacion de Gamepad Tester para **Pixel Ortiz Tech**, pensada para probar controles, joysticks y dispositivos de entrada de forma rapida desde Windows.

Este proyecto toma como base el trabajo original de **El Taller de Alex**:

https://github.com/alejandro7896/gamepad-tester

A partir de esa base se adapto la identidad visual, el empaquetado de escritorio y la presentacion para uso de Pixel Ortiz Tech.

## Caracteristicas

- Detecta controles compatibles con la API de Gamepad del navegador/Electron.
- Muestra botones, joysticks, triggers y valores de ejes en tiempo real.
- Visualiza valores de presion de botones y movimiento de palancas.
- Incluye pruebas de vibracion para controles compatibles.
- Interfaz adaptada con marca Pixel Ortiz Tech.
- Version portable para Windows empaquetada como archivo `.exe`.
- Sin anuncios y lista para uso local en taller o mostrador.

## Descargar para Windows

Puedes descargar la version portable desde la seccion **Releases** del repositorio:

https://github.com/jar3dmg/Gamepad-Tester-PixelOrtiz/releases

El archivo principal es:

```text
GT - Pixel Ortiz Tech 1.0.0.exe
```

No requiere instalacion. Solo descarga el ejecutable y abrelo en Windows.

## Uso local desde codigo

Si quieres ejecutar el proyecto desde el codigo fuente:

```bash
git clone https://github.com/jar3dmg/Gamepad-Tester-PixelOrtiz.git
cd Gamepad-Tester-PixelOrtiz
npm install
npm start
```

Tambien puedes abrir `index.html` directamente en un navegador, aunque la version recomendada para escritorio es Electron.

## Crear ejecutable

Para generar nuevamente el `.exe` portable:

```bash
npm install
npm run build
```

El ejecutable se genera en:

```text
dist/GT - Pixel Ortiz Tech 1.0.0.exe
```

## Creditos

Este proyecto fue adaptado por **Pixel Ortiz Tech** usando como base el Gamepad Tester de **El Taller de Alex**.

Proyecto base:

https://github.com/alejandro7896/gamepad-tester

Se mantiene el reconocimiento al autor original por la herramienta base y se publica esta version como una adaptacion personalizada para Pixel Ortiz Tech.
