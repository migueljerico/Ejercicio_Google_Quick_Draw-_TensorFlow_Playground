# 🧠 Ejercicio Google Quick Draw & TensorFlow Playground

![Lenguaje](https://img.shields.io/badge/lenguaje-múltiple-blue?style=for-the-badge)
![Stack](https://img.shields.io/badge/stack-Deep%20Learning-orange?style=for-the-badge)
![Estado](https://img.shields.io/badge/estado-Publicado-green?style=for-the-badge)
![Licencia](https://img.shields.io/badge/licencia-MIT-yellow?style=for-the-badge)

*Ejercicio práctico de introducción al Deep Learning mediante Google Quick, Draw! y TensorFlow Playground sin necesidad de programar.*

🔗 **Acceso / Demo**
- Google Quick, Draw!: https://quickdraw.withgoogle.com
- TensorFlow Playground: https://playground.tensorflow.org

📋 **Descripción**
Este repositorio contiene la documentación del Ejercicio 3.5 del curso de Análisis de Datos e IA (INAEM) realizado por el alumno Miguel Jericó. El proyecto introduce los conceptos fundamentales de Deep Learning a través de dos experiencias web visuales e interactivas que no requieren escritura de código.

La primera parte utiliza Google Quick, Draw!, un modelo ya entrenado con más de 50 millones de dibujos que realiza inferencia en tiempo real para reconocer trazos a mano. La segunda parte emplea TensorFlow Playground para construir y entrenar redes neuronales desde cero, modificando arquitectura y funciones de activación mientras se observa el descenso del error.

El material está dirigido a principiantes en IA, permitiendo conectar el uso de un modelo entrenado (inferencia) con su construcción (entrenamiento), fomentando el pensamiento crítico sobre los fallos de la IA y la cultura de medir resultados.

✨ **Funcionalidades**

| Funcionalidad | Descripción |
|---------------|-------------|
| Inferencia con Quick, Draw! | Juego de 6 dibujos con 20s cada uno; la IA adivina en directo usando modelo preentrenado |
| Registro de aciertos | Tabla de reconocimiento por dibujo con tiempo aproximado y análisis de fallos |
| Entrenamiento en TensorFlow Playground | Creación de red neuronal visual con capas, neuronas y funciones de activación |
| Visualización de error | Observación en directo del descenso del error y frontera de decisión por épocas |
| Documentación formativa | Informe comprimido en `/docs` con contexto, pasos y conclusiones del ejercicio |

⚙️ **Instalación**
1. Clonar el repositorio:
```bash
gh repo clone migueljerico/Ejercicio_Google_Quick_Draw-_TensorFlow_Playground
```
2. Acceder a la carpeta del proyecto:
```bash
cd Ejercicio_Google_Quick_Draw-_TensorFlow_Playground
```
3. Abrir el documento principal de la práctica:
```bash
start docs/Ejercicio_3.5_Introducci-n-al-Deep-Learning-mediante-Google-Quick-Draw-y-TensorFlow-Playground_Miguel_Jerico-comprimido.md
```
4. Para las experiencias, abrir los sitios web indicados en Acceso/Demo (no requieren instalación local).

🚀 **Uso**
- Parte 1: Entrar en `quickdraw.withgoogle.com`, pulsar "▶ A dibujar", completar 6 dibujos y registrar en la tabla:

| Dibujo | ¿Lo reconoció? | ¿Cuánto tardó aproximadamente? |
|--------|----------------|-------------------------------|
| 1      | (pendiente)    | –                             |

- Parte 2: En `playground.tensorflow.org` modificar capas ocultas, neuronas y activación (ReLU, Tanh, Sigmoid) y observar el error por épocas.

📁 **Estructura del proyecto**
```
Ejercicio_Google_Quick_Draw-_TensorFlow_Playground/
├── README.md
└── docs/
    └── Ejercicio_3.5_Introducci-n-al-Deep-Learning-mediante-Google-Quick-Draw-y-TensorFlow-Playground_Miguel_Jerico-comprimido.md
```

🛠️ **Tecnologías**

| Herramienta | Versión/Detalle | Uso en el proyecto |
|-------------|-----------------|--------------------|
| Google Quick, Draw! | Web app | Inferencia de dibujos a mano en tiempo real |
| TensorFlow Playground | Web app | Entrenamiento visual de redes neuronales |
| Markdown | - | Documentación de la práctica y README |
| GitHub | - | Repositorio y publicación del ejercicio |

📚 **Contexto formativo o motivación del proyecto**
Ejercicio 3.5 del bloque de Deep Learning del curso Análisis de Datos e IA (INAEM) por Miguel Jericó. Su motivación es ofrecer una introducción visual y accesible al reconocimiento de patrones y redes neuronales sin requerir conocimientos de programación.

<p align="center">Desarrollado por @migueljerico · 2026</p>
