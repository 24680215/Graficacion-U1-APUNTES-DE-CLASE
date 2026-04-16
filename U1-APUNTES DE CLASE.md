# 🎨 Graficación - Unidad I

---

## 📑 Índice

* [🧠 Historia y evolución](#1-historia-y-evolucion-de-la-graficacion-por-computadora)
* [🌐 Áreas de aplicación](#2-areas-de-aplicacion)
* [📐 Aspectos matemáticos](#3-aspectos-matematicos-de-la-graficacion)
* [🎨 Modelos de color](#4-modelos-de-color-rgb-cmy-hsv-y-hsl)
* [📏 Líneas y polígonos](#5-representacion-y-trazo-de-lineas-y-poligonos)
* [🖼️ Formatos de imagen](#51-formatos-de-imagen)
* [🖥️ Mapas de bits](#6-procesamiento-de-mapas-de-bits)
* [📚 Bibliografía](#7-bibliografia)
---

# 🧠 1. Historia y evolución de la graficación por computadora

La **graficación por computadora** es el conjunto de técnicas que permiten generar imágenes digitales mediante algoritmos, matemáticas y hardware especializado.

## 🔹 Evolución histórica

| Década     | Avances                                                |
| ---------- | ------------------------------------------------------ |
| 1950s      | Primeros gráficos vectoriales en osciloscopios         |
| 1960s      | Desarrollo de *Sketchpad* (primer sistema interactivo) |
| 1970s      | Introducción de gráficos raster (basados en píxeles)   |
| 1980s      | Interfaces gráficas (GUI)                              |
| 1990s      | Gráficos 3D y aceleración por GPU                      |
| 2000s      | Renderizado en tiempo real                             |
| Actualidad | Ray tracing, IA, VR y AR                               |

## 🔹 Tecnologías modernas

* Renderizado en tiempo real
* **Ray Tracing**
* Inteligencia Artificial aplicada a gráficos
* Realidad Virtual (VR) y Aumentada (AR)

## 🔹 Importancia

✔ Permite visualizar información compleja

✔ Base de videojuegos, cine y simulación

✔ Mejora la interacción humano-computadora

---

# 🌐 2. Áreas de aplicación

La graficación por computadora es fundamental en múltiples industrias:

## 🎮 Videojuegos

* Gráficos 2D y 3D
* Simulación física
* Motores gráficos (Unity, Unreal Engine)

## 🎬 Cine y animación

* Efectos visuales (VFX)
* Animación digital
* Renderizado realista

## 🏗️ CAD (Diseño asistido por computadora)

* Arquitectura
* Ingeniería mecánica
* Modelado de estructuras

## 🏥 Medicina

* Tomografías (CT)
* Resonancias magnéticas (MRI)
* Simulación quirúrgica

## 🧪 Ciencia y educación

* Visualización de datos
* Simulación de fenómenos físicos

## 🥽 Realidad Virtual y Aumentada

* Simuladores
* Videojuegos inmersivos
* Entrenamiento industrial

---

# 📐 3. Aspectos matemáticos de la graficación

Las matemáticas son la base de toda representación gráfica.

## 🔹 Geometría analítica

Permite describir figuras mediante ecuaciones.

Ejemplo:

```
Circunferencia:
x² + y² = r²
```

## 🔹 Álgebra lineal

Elementos clave:

* Vectores
* Matrices
* Espacios vectoriales

## 🔹 Transformaciones geométricas

| Transformación | Descripción     |
| -------------- | --------------- |
| Traslación     | Mover objetos   |
| Rotación       | Girar objetos   |
| Escalado       | Cambiar tamaño  |
| Reflexión      | Invertir figura |

Ejemplo de matriz de traslación:

```
[1 0 tx]
[0 1 ty]
[0 0 1 ]
```

## 🔹 Sistemas de coordenadas

* Cartesianas (x, y, z)
* Polares (r, θ)
* Coordenadas homogéneas

## 🔹 Interpolación

Se utiliza para:

* Animaciones
* Sombreado
* Generación de curvas

Tipos:

* Lineal
* Polinómica
* Bézier

---

# 🎨 4. Modelos de color: RGB, CMY, HSV y HSL

Los modelos de color permiten representar colores de forma numérica.

## 🔹 RGB (Modelo aditivo)

Utilizado en pantallas.

```
(255, 0, 0) → Rojo
(0, 255, 0) → Verde
(0, 0, 255) → Azul
```

## 🔹 CMY (Modelo sustractivo)

Utilizado en impresión.

* Cyan
* Magenta
* Yellow

## 🔹 HSV

| Componente | Descripción |
| ---------- | ----------- |
| Hue        | Tono        |
| Saturation | Intensidad  |
| Value      | Brillo      |

## 🔹 HSL

| Componente | Descripción |
| ---------- | ----------- |
| Hue        | Tono        |
| Saturation | Saturación  |
| Lightness  | Luminosidad |

## 🔹 Comparación

| Modelo  | Uso              |
| ------- | ---------------- |
| RGB     | Pantallas        |
| CMY     | Impresión        |
| HSV/HSL | Edición de color |

Ejemplo:
<img width="1115" height="632" alt="image" src="https://github.com/user-attachments/assets/59b94679-fd30-41b8-8412-2720f7433414" />

---

# 📏 5. Representación y trazo de líneas y polígonos

Los gráficos se construyen a partir de primitivas básicas.

## 🔹 Algoritmos de líneas

### DDA (Digital Differential Analyzer)

* Fácil implementación
* Uso de números reales
* Menos eficiente

### Bresenham

* Usa números enteros
* Mayor eficiencia
* Más usado en gráficos

## 🔹 Polígonos

Tipos:

* Convexos
* Cóncavos

## 🔹 Procesos fundamentales

* Rasterización
* Relleno de polígonos
* Recorte (clipping)

---

# 🖼️ 5.1 Formatos de imagen

| Formato | Características            | Uso          |
| ------- | -------------------------- | ------------ |
| BMP     | Sin compresión             | Alta calidad |
| JPEG    | Compresión con pérdida     | Fotografía   |
| PNG     | Sin pérdida, transparencia | Web          |
| GIF     | Animaciones                | Web          |
| TIFF    | Alta calidad               | Profesional  |

Ejemplos:
<img width="1123" height="668" alt="image" src="https://github.com/user-attachments/assets/644546e5-02bb-436a-87c3-005446ea5b69" />
<img width="903" height="504" alt="image" src="https://github.com/user-attachments/assets/7480cda0-b69e-4c9a-a779-726a90d6cedd" />

---

# 🖥️ 6. Procesamiento de mapas de bits

Un **mapa de bits** es una representación de imagen basada en píxeles.

## 🔹 Características

* Resolución
* Profundidad de color
* Tamaño de archivo

## 🔹 Operaciones

### Filtrado

* Suavizado
* Detección de bordes

### Transformaciones

* Rotación
* Escalado

### Ajustes

* Brillo
* Contraste
* Saturación

### Compresión

* Con pérdida (JPEG)
* Sin pérdida (PNG)

## 🔹 Importancia

✔ Base del procesamiento digital de imágenes

✔ Fundamental en visión por computadora

✔ Usado en edición y análisis de imágenes

---

# 📚 7. Bibliografía

* Foley, J. D., van Dam, A., Feiner, S. K., & Hughes, J. F. (1996). *Computer Graphics: Principles and Practice*. Addison-Wesley.
* Hearn, D., & Baker, M. P. (2014). *Computer Graphics with OpenGL*. Pearson.
* Rogers, D. F. (2001). *Procedural Elements for Computer Graphics*. McGraw-Hill.
* Angel, E., & Shreiner, D. (2015). *Interactive Computer Graphics*. Addison-Wesley.
* Gonzalez, R. C., & Woods, R. E. (2018). *Digital Image Processing*. Pearson.

Va, te lo armo igual de limpio y listo para copiar a tu README 👇

---

# 🎨 Graficación - Unidad II

---

## 📑 Índice

* [📐 Transformaciones bidimensionales](#1-transformacion-bidimensional)
* [🔄 Representación matricial](#2-representacion-matricial-de-las-transformaciones)
* [📈 Curvas](#3-trazo-de-lineas-curvas)
* [🌿 Fractales](#4-fractales)
* [🔤 Fuentes de texto](#5-uso-y-creacion-de-fuentes-de-texto)
* [📚 Bibliografía](#6-bibliografia)

---

# 📐 1. Transformación bidimensional

Las **transformaciones bidimensionales (2D)** permiten modificar la posición, tamaño y forma de objetos en un plano.

Se aplican sobre puntos representados como coordenadas (x, y).

---

## 🔹 1.1 Traslación

Consiste en mover un objeto de una posición a otra sin cambiar su forma ni tamaño.

📌 Fórmula:

```
x' = x + tx
y' = y + ty
```

Donde:

* (tx, ty) es el desplazamiento

---

## 🔹 1.2 Escalamiento

Permite cambiar el tamaño de un objeto.

📌 Fórmula:

```
x' = x * sx
y' = y * sy
```

Donde:

* sx = escala en X
* sy = escala en Y

✔ Puede agrandar o reducir objetos

---

## 🔹 1.3 Rotación

Gira un objeto respecto al origen o a un punto.

📌 Fórmula:

```
x' = x cosθ - y sinθ
y' = x sinθ + y cosθ
```

Donde:

* θ es el ángulo de rotación

---

## 🔹 1.4 Sesgado (Shear)

Deforma un objeto inclinándolo.

📌 Fórmulas:

**Sesgado en X:**

```
x' = x + shx * y
y' = y
```

**Sesgado en Y:**

```
x' = x
y' = y + shy * x
```

---

# 🔄 2. Representación matricial de las transformaciones

Las transformaciones se representan mediante **matrices**, lo que permite combinarlas fácilmente.

---

## 🔹 Coordenadas homogéneas

Se usa una tercera coordenada:

```
(x, y) → (x, y, 1)
```

---

## 🔹 Matriz de traslación

```
[1 0 tx]
[0 1 ty]
[0 0 1 ]
```

---

## 🔹 Matriz de escalamiento

```
[sx 0  0]
[0  sy 0]
[0  0  1]
```

---

## 🔹 Matriz de rotación

```
[cosθ -sinθ 0]
[sinθ  cosθ 0]
[0      0   1]
```

---

## 🔹 Matriz de sesgado

```
[1 shx 0]
[shy 1 0]
[0  0  1]
```

---

## 🔹 Ventaja

✔ Permite combinar transformaciones con multiplicación de matrices

✔ Optimiza cálculos en gráficos por computadora

---

# 📈 3. Trazo de líneas curvas

Las curvas permiten representar formas suaves y complejas.

---

## 🔹 3.1 Curvas de Bézier

Son curvas definidas por puntos de control.

📌 Características:

* Muy usadas en diseño gráfico
* Suaves y fáciles de manipular
* Se usan en Illustrator, Photoshop, etc.

📌 Fórmula general (grado n):

```
B(t) = Σ Pi * Bi,n(t)
```

Donde:

* Pi = puntos de control
* t ∈ [0,1]

---

## 🔹 3.2 B-Spline

Son una generalización de las curvas de Bézier.

📌 Características:

* Mayor control local
* Más flexibles
* No dependen de todos los puntos a la vez

✔ Usadas en modelado 3D y CAD

---

# 🌿 4. Fractales

Los **fractales** son figuras geométricas que se repiten a diferentes escalas.

---

## 🔹 Características

* Autosimilitud
* Detalle infinito
* Generados mediante algoritmos iterativos

---

## 🔹 Ejemplos

* Conjunto de Mandelbrot
* Triángulo de Sierpinski
* Curva de Koch

---

## 🔹 Aplicaciones

* Gráficos por computadora
* Simulación de naturaleza
* Arte digital

---

# 🔤 5. Uso y creación de fuentes de texto

Las fuentes son esenciales para mostrar texto en sistemas gráficos.

---

## 🔹 Tipos de fuentes

* **Bitmap** → basadas en píxeles
* **Vectoriales** → basadas en curvas (TrueType, OpenType)

---

## 🔹 Características

* Tamaño
* Estilo (negrita, cursiva)
* Espaciado

---

## 🔹 Creación de fuentes

Se realiza mediante:

* Curvas de Bézier
* Herramientas como:

  * FontForge
  * Glyphs
  * Adobe Illustrator

---

## 🔹 Importancia

✔ Mejora la legibilidad
✔ Influye en el diseño visual
✔ Fundamental en interfaces gráficas

---

# 📚 6. Bibliografía

* Foley, J. D., van Dam, A., Feiner, S. K., & Hughes, J. F. (1996). *Computer Graphics: Principles and Practice*. Addison-Wesley.
* Hearn, D., & Baker, M. P. (2014). *Computer Graphics with OpenGL*. Pearson.
* Rogers, D. F. (2001). *Procedural Elements for Computer Graphics*. McGraw-Hill.
* Angel, E., & Shreiner, D. (2015). *Interactive Computer Graphics*. Addison-Wesley.
* Gonzalez, R. C., & Woods, R. E. (2018). *Digital Image Processing*. Pearson.



