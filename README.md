<div align="center">

# 🖨️ IMPRESIÓN 3D

## Diseño, modelado y fabricación digital

![3D Printing](https://img.shields.io/badge/Impresión%203D-Fabricación%20Digital-F9A83A?style=for-the-badge)
![Tinkercad](https://img.shields.io/badge/Tinkercad-Modelado%203D-1477D4?style=for-the-badge)
![Cura](https://img.shields.io/badge/Ultimaker%20Cura-Slicer-855CD6?style=for-the-badge)

### Modelar • Preparar • Imprimir • Crear

</div>

---

# 📚 ¿Qué es la impresión 3D?

La **impresión 3D** es un proceso de fabricación digital que permite crear objetos físicos a partir de un modelo diseñado en computadora.

A diferencia de otros métodos de fabricación, la impresión 3D construye las piezas **capa por capa** hasta formar el objeto completo.

Este proceso se utiliza en áreas como:

* Ingeniería.
* Arquitectura.
* Educación.
* Medicina.
* Robótica.
* Prototipado.
* Diseño industrial.
* Arte y creatividad.

---

# ⚙️ ¿Cómo funciona una impresora 3D?

Una impresora 3D recibe un archivo digital que contiene el diseño del objeto.

Posteriormente, un programa especializado divide el modelo en múltiples capas.

La impresora interpreta esas capas y comienza a fabricar el objeto desde la base hasta la parte superior.

El proceso general puede representarse así:

```text
IDEA
  ↓
DISEÑO 3D
  ↓
ARCHIVO STL
  ↓
LAMINADO EN CURA
  ↓
ARCHIVO G-CODE
  ↓
IMPRESORA 3D
  ↓
PIEZA TERMINADA
```

---

# 🎞️ Flujo de trabajo

<div align="center">

### 💡 Idea

⬇️

### 🧊 Modelado en Tinkercad

⬇️

### 📁 Exportación del modelo

⬇️

### ⚙️ Preparación en Cura

⬇️

### 🖨️ Impresión 3D

⬇️

### ✅ Pieza final

</div>

---

# 🧊 ¿Qué es Tinkercad?

**Tinkercad** es una plataforma de diseño 3D desarrollada por Autodesk.

Permite crear modelos tridimensionales utilizando formas geométricas básicas como:

* Cubos.
* Cilindros.
* Esferas.
* Conos.
* Letras.
* Figuras personalizadas.

Su interfaz está diseñada para facilitar el aprendizaje del modelado 3D.

---

## 🛠️ Herramientas principales de Tinkercad

Tinkercad permite realizar operaciones como:

| Herramienta   | Función                 |
| ------------- | ----------------------- |
| 📦 Formas     | Agregar objetos básicos |
| ↔️ Escala     | Cambiar dimensiones     |
| 🔄 Rotación   | Girar piezas            |
| 📍 Movimiento | Cambiar posición        |
| 🧲 Alinear    | Ordenar objetos         |
| 🔗 Agrupar    | Combinar piezas         |
| ✂️ Agujero    | Restar material         |
| 📏 Regla      | Medir dimensiones       |

---

# 🧠 ¿Cómo se crea un modelo en Tinkercad?

El proceso básico consiste en:

1. Crear un nuevo diseño.
2. Agregar formas al área de trabajo.
3. Cambiar sus dimensiones.
4. Mover y rotar los objetos.
5. Combinar diferentes formas.
6. Crear agujeros cuando sea necesario.
7. Revisar las medidas.
8. Exportar el modelo.

---

# 📁 Formatos utilizados

Uno de los formatos más utilizados para impresión 3D es:

```text
.STL
```

El archivo STL contiene la geometría tridimensional del modelo.

También pueden utilizarse otros formatos como:

```text
.OBJ
.3MF
```

---

# ⚙️ ¿Qué es Ultimaker Cura?

**Ultimaker Cura** es un programa de laminado o **slicer** utilizado para preparar modelos 3D antes de imprimirlos.

Su función principal es convertir un modelo tridimensional en instrucciones que una impresora 3D pueda interpretar.

Estas instrucciones se guardan normalmente en un archivo:

```text
G-CODE
```

---

# 🧩 ¿Qué hace Cura?

Cura analiza el modelo y lo divide en cientos o miles de capas.

Después genera instrucciones relacionadas con:

* Movimiento del cabezal.
* Temperatura.
* Velocidad.
* Cantidad de material.
* Altura de capa.
* Relleno.
* Soportes.
* Retracción.

---

# 🎞️ Del modelo a la impresión

```text
Modelo 3D
   │
   ▼
Archivo STL
   │
   ▼
Ultimaker Cura
   │
   ├── Altura de capa
   ├── Relleno
   ├── Soportes
   ├── Temperatura
   └── Velocidad
   │
   ▼
Archivo G-CODE
   │
   ▼
Impresora 3D
   │
   ▼
Pieza terminada
```

---

# 📐 Altura de capa

La altura de capa determina el grosor de cada capa impresa.

Ejemplo:

| Altura    | Resultado                         |
| --------- | --------------------------------- |
| `0.10 mm` | Mayor detalle                     |
| `0.20 mm` | Equilibrio entre calidad y tiempo |
| `0.28 mm` | Impresión más rápida              |

Una menor altura de capa ofrece normalmente mayor calidad visual, pero aumenta el tiempo de impresión.

---

# 🧱 Relleno

El **infill** o relleno determina cuánto material existe dentro de la pieza.

Ejemplos:

```text
10%  → pieza ligera

20%  → uso general

50%  → mayor resistencia

100% → pieza completamente sólida
```

La cantidad adecuada depende del uso que tendrá la pieza.

---

# 🕸️ Patrones de relleno

Cura ofrece diferentes patrones, por ejemplo:

* Grid.
* Lines.
* Cubic.
* Gyroid.
* Triangles.

Cada patrón puede ofrecer diferencias en resistencia, velocidad y consumo de material.

---

# 🏗️ Soportes

Los soportes son estructuras temporales utilizadas cuando una parte del modelo queda suspendida en el aire.

Ejemplo:

```text
        _______
       |       |
       | PIEZA |
       |_______|
          │
       SOPORTE
          │
   ─────────────
      BASE
```

Una vez terminada la impresión, los soportes pueden retirarse.

---

# 🌡️ Temperaturas

La temperatura depende principalmente del material utilizado.

Un ejemplo común con PLA puede encontrarse aproximadamente dentro de estos rangos:

```text
Boquilla: 190 °C - 220 °C

Cama: 50 °C - 60 °C
```

Los valores exactos dependen del fabricante del filamento y de la impresora.

---

# 🧵 Filamentos

Las impresoras 3D FDM utilizan diferentes tipos de filamento.

## PLA

Uno de los materiales más utilizados.

Características:

* Fácil de imprimir.
* Buena calidad visual.
* Ideal para proyectos educativos.
* Adecuado para prototipos.

## PETG

Características:

* Mayor resistencia.
* Buena durabilidad.
* Buena adherencia entre capas.

## ABS

Características:

* Resistente.
* Tolera temperaturas más altas.
* Requiere mayor control durante la impresión.

## TPU

Material flexible utilizado para fabricar piezas elásticas.

---

# 🖨️ Componentes principales de una impresora 3D

Una impresora 3D FDM normalmente posee:

| Componente           | Función                    |
| -------------------- | -------------------------- |
| 🧵 Filamento         | Material de impresión      |
| ⚙️ Extrusor          | Empuja el filamento        |
| 🔥 Hotend            | Derrite el material        |
| 🔘 Boquilla          | Deposita el filamento      |
| 🛏️ Cama             | Superficie de impresión    |
| 🔩 Motores           | Controlan los movimientos  |
| 🧠 Placa electrónica | Ejecuta las instrucciones  |
| 🌀 Ventiladores      | Controlan la refrigeración |

---

# 🎞️ Representación de la impresión

```text
        🧵 FILAMENTO
             │
             ▼
        ⚙️ EXTRUSOR
             │
             ▼
         🔥 HOTEND
             │
             ▼
          🔘 BOQUILLA
             │
          ▓▓▓▓▓▓
        ▓▓▓▓▓▓▓▓▓
      ▓▓▓▓▓▓▓▓▓▓▓▓
    ─────────────────
          🛏️ CAMA
```

La boquilla deposita pequeñas líneas de material hasta construir el objeto capa por capa.

---

# 🚀 Proceso completo de impresión

## 1. Diseñar

Crear el objeto en **Tinkercad**.

## 2. Revisar

Verificar:

* Medidas.
* Posiciones.
* Espesores.
* Uniones.

## 3. Exportar

Guardar el modelo como:

```text
STL
```

## 4. Abrir en Cura

Importar el archivo STL.

## 5. Configurar

Ajustar:

* Impresora.
* Material.
* Altura de capa.
* Relleno.
* Soportes.
* Velocidad.

## 6. Laminar

Presionar:

```text
Slice
```

Cura calcula las capas y genera el recorrido de impresión.

## 7. Guardar

Exportar el:

```text
G-CODE
```

## 8. Imprimir

Enviar el archivo a la impresora 3D.

---

# 👀 Vista previa en Cura

Una de las funciones más importantes de Cura es la opción **Preview**.

Esta permite observar:

* Cada capa.
* Movimientos del cabezal.
* Relleno.
* Paredes.
* Soportes.
* Tiempo estimado.
* Cantidad aproximada de material.

Revisar esta vista antes de imprimir ayuda a detectar posibles errores.

---

# ⚠️ Errores comunes

Durante una impresión pueden presentarse problemas como:

## Mala adherencia

La primera capa no se pega correctamente.

## Warping

Las esquinas de la pieza se levantan.

## Stringing

Aparecen pequeños hilos de plástico entre diferentes partes.

## Layer Shift

Las capas se desplazan horizontalmente.

## Subextrusión

La impresora deposita menos material del necesario.

---

# 🔧 Buenas prácticas

Antes de imprimir es recomendable:

* Nivelar correctamente la cama.
* Limpiar la superficie.
* Revisar el filamento.
* Verificar la temperatura.
* Comprobar la primera capa.
* Revisar el modelo en Cura.
* No mover la impresora durante el proceso.
* Mantener limpia la boquilla.

---

# 🛠️ Herramientas utilizadas

<div align="center">

| Herramienta           | Uso                         |
| --------------------- | --------------------------- |
| 🧊 **Tinkercad**      | Diseño y modelado 3D        |
| ⚙️ **Ultimaker Cura** | Preparación y laminado      |
| 🖨️ **Impresora 3D**  | Fabricación física          |
| 🧵 **Filamento**      | Material de fabricación     |
| 🐙 **GitHub**         | Documentación del proyecto  |
| 📝 **Markdown**       | Presentación de información |

</div>

---

# 🎨 Paleta visual

Para mantener una presentación tecnológica y profesional:

| Color               | Código    |
| ------------------- | --------- |
| 🔵 Azul tecnológico | `#1477D4` |
| 🟠 Naranja          | `#F39C12` |
| 🟣 Morado           | `#855CD6` |
| 🟢 Verde            | `#27AE60` |
| ⚫ Oscuro            | `#1E1E2F` |
| ⚪ Blanco            | `#FFFFFF` |

---

# 🎥 Animación para GitHub

Una forma de mejorar significativamente el README es incluir un GIF mostrando el proceso.

Por ejemplo:

```html
<div align="center">

<img src="imagenes/impresion3d.gif" width="700">

</div>
```

El GIF puede mostrar:

```text
Tinkercad
    ↓
Diseño del modelo
    ↓
Cura
    ↓
Laminado
    ↓
Impresora
    ↓
Objeto terminado
```

---

# 📸 Galería

Puedes organizar imágenes del proyecto en una carpeta:

```text
imagenes/
│
├── tinkercad.png
├── cura.png
├── impresora3d.png
├── pieza-final.png
└── impresion3d.gif
```

Después puedes mostrarlas en GitHub:

```html
<div align="center">

<img src="imagenes/tinkercad.png" width="45%">
<img src="imagenes/cura.png" width="45%">

<br>

<img src="imagenes/impresora3d.png" width="45%">
<img src="imagenes/pieza-final.png" width="45%">

</div>
```

---

# 🧠 ¿Qué se aprende?

Trabajar con impresión 3D permite desarrollar conocimientos relacionados con:

* Diseño tridimensional.
* Medición.
* Escalas.
* Prototipado.
* Fabricación digital.
* Configuración de impresoras.
* Manejo de materiales.
* Resolución de problemas.
* Pensamiento espacial.
* Diseño técnico.

---

# 📂 Estructura recomendada del repositorio

```text
Impresion-3D/
│
├── README.md
│
├── modelos/
│   ├── proyecto.stl
│   └── proyecto.obj
│
├── gcode/
│   └── proyecto.gcode
│
└── imagenes/
    ├── tinkercad.png
    ├── cura.png
    ├── impresion.png
    ├── pieza-final.png
    └── impresion3d.gif
```

---

# ✅ Conclusión

La **impresión 3D** permite transformar un diseño digital en un objeto físico mediante un proceso de fabricación capa por capa.

**Tinkercad** facilita la creación del modelo tridimensional, mientras que **Ultimaker Cura** prepara el archivo y genera las instrucciones necesarias para que la impresora pueda fabricar la pieza.

El uso conjunto de estas herramientas permite recorrer un flujo completo de fabricación digital:

```text
💡 Diseñar
      ↓
🧊 Modelar
      ↓
⚙️ Preparar
      ↓
🖨️ Imprimir
      ↓
✅ Crear
```

Además de fabricar objetos, este proceso permite desarrollar habilidades de diseño, tecnología, creatividad, precisión y resolución de problemas.

---

<div align="center">

# 🖨️ IMPRESIÓN 3D

### 🧊 TINKERCAD + ⚙️ CURA + 🖨️ FABRICACIÓN

**Diseñar • Modelar • Preparar • Imprimir**

</div>
