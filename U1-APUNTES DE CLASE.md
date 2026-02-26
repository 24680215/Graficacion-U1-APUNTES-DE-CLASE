# 🎨 Graficación por Computadora - Unidad I

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Subject-Computer%20Graphics-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Level-Engineering-orange?style=for-the-badge">
</p>

---

## 📑 Índice

* [🧠 Historia y evolución](#-1-historia-y-evolución-de-la-graficación-por-computadora)
* [🌐 Áreas de aplicación](#-2-áreas-de-aplicación)
* [📐 Aspectos matemáticos](#-3-aspectos-matemáticos-de-la-graficación)
* [🎨 Modelos de color](#-4-modelos-de-color-rgb-cmy-hsv-y-hsl)
* [📏 Líneas y polígonos](#-5-representación-y-trazo-de-líneas-y-polígonos)
* [🖼️ Formatos de imagen](#-51-formatos-de-imagen)
* [🖥️ Mapas de bits](#-6-procesamiento-de-mapas-de-bits)
* [📚 Bibliografía](#-7-bibliografía)

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

# 📚 7. Bibliografía (APA)

* Foley, J. D., van Dam, A., Feiner, S. K., & Hughes, J. F. (1996). *Computer Graphics: Principles and Practice*. Addison-Wesley.
* Hearn, D., & Baker, M. P. (2014). *Computer Graphics with OpenGL*. Pearson.
* Rogers, D. F. (2001). *Procedural Elements for Computer Graphics*. McGraw-Hill.
* Angel, E., & Shreiner, D. (2015). *Interactive Computer Graphics*. Addison-Wesley.
* Gonzalez, R. C., & Woods, R. E. (2018). *Digital Image Processing*. Pearson.

---

# 🚀 Notas finales

> 📌 Este documento resume los fundamentos de la **Graficación por Computadora**, abordando tanto aspectos teóricos como aplicaciones prácticas.

> 💡 Ideal para estudiantes de ingeniería, desarrollo de videojuegos, diseño gráfico y simulación.

---

Si quieres, te lo puedo dejar todavía más pro 🔥
con imágenes, diagramas, GIFs o hasta estructura de repo (carpetas, código, ejemplos en Python o OpenGL).
