# Introducción al Deep Learning con Google Quick, Draw! y TensorFlow Playground

## 📋 Resumen
Ejercicio práctico de introducción al Deep Learning del alumno Miguel Jericó en el curso de Análisis de Datos e IA (INAEM), dividido en dos partes. La primera explora el reconocimiento de patrones con un modelo ya entrenado (Google Quick, Draw!) y la segunda permite construir y entrenar redes neuronales desde cero en un entorno visual (TensorFlow Playground).

## 🔑 Puntos clave
- El ejercicio se divide en dos experiencias sin necesidad de programar: inferencia (Quick, Draw!) y entrenamiento (TensorFlow Playground).
- Google Quick, Draw! utiliza un modelo ya entrenado con más de 50 millones de dibujos para reconocer trazos a mano en tiempo real.
- En Quick, Draw! se juega una partida de 6 dibujos con 20 segundos cada uno; luego se analizan aciertos/errores y se registran en una tabla.
- TensorFlow Playground sirve para crear redes neuronales, modificar arquitectura (capas, neuronas), probar funciones de activación y ver el descenso del error en directo.
- La práctica fomenta el pensamiento crítico sobre los fallos de la IA (trazos ambiguos, perspectivas, falta de contexto) y la cultura de medir resultados.

## 📝 Detalle

### Contexto y autoría
- **Alumno**: Miguel Jericó
- **Formación**: INAEM – Análisis de Datos e IA
- **Entornos web**: Quick, Draw! y TensorFlow Playground
- **Bloque**: Deep Learning (redes neuronales y reconocimiento de patrones)
- **Ejercicio**: 3.5 – Introducción al Deep Learning mediante las dos herramientas citadas

### Parte 1: Google Quick, Draw!
Experimento de IA que reconoce en tiempo real dibujos trazados a mano. La red ya está entrenada y solo realiza inferencia (aplica lo aprendido, no aprende del usuario).

1. **Acceder a la web** (`quickdraw.withgoogle.com`): pantalla inicial con lema "¡Corre, dibuja!" y botón amarillo para iniciar. La IA está lista para inferir.
2. **Completar una partida de 6 dibujos**: se pulsa "▶ A dibujar"; el sistema propone 6 conceptos aleatorios (ej. arcoíris, corbata, arbusto) con 20 segundos por dibujo mientras la IA adivina en directo.
3. **Observar el resultado final**: resumen con los 6 dibujos y marca de acierto o etiqueta del concepto confundido. Se analiza por qué falla (trazos ambiguos, perspectivas inusuales, falta de contexto visual).
4. **Completar tabla de reconocimiento**: se registra para cada dibujo si fue reconocido y el tiempo aproximado, cuantificando el comportamiento del modelo frente a la percepción subjetiva.

| Dibujo | ¿Lo reconoció? | ¿Cuánto tardó aproximadamente? |
|--------|----------------|-------------------------------|
| 1      | (pendiente en PDF truncado) | – |

### Parte 2: TensorFlow Playground (según resumen del ejercicio)
Entorno visual de entrenamiento para construir redes neuronales desde cero:
- Modificar arquitectura: capas ocultas y número de neuronas.
- Probar funciones de activación: ReLU, Tanh, Sigmoid.
- Observar en directo el descenso del error y la adaptación de la frontera de decisión a medida que avanzan las épocas.

### Conceptos relevantes señalados en el análisis previo
- **Inferencia**: la IA ya entrenada aplica su conocimiento (Quick, Draw!).
- **Tiempo real**: la IA cambia de predicción según se traza.
- **Capas ocultas y neuronas**: profundidad del modelo.
- **Funciones de activación**: reglas que deciden si una neurona se activa.
- **Épocas y error**: más épocas tienden a reducir el error y ajustar la frontera de decisión.

## ✅ Conclusiones / siguientes pasos
- El ejercicio es muy visual y apto para principiantes sin experiencia técnica, conectando el uso de un modelo (inferencia) y su construcción (entrenamiento).
- Para documentar en el repositorio se sugiere añadir: conclusiones personales, glosario de términos y comparativa Quick, Draw! (inferencia) vs Playground (entrenamiento).
- El PDF adjunto está truncado en la tabla de la Parte 1; si se dispone del resto, conviene completar la documentación con el detalle íntegro de pasos y capturas.
- Publicación: utilizar la opción "📤 Documentar y publicar" disponible en la interfaz para volcar la documentación al repositorio mediante commit.