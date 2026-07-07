# Manual Técnico – Ejercicio Google Quick Draw & TensorFlow Playground

## 1. Arquitectura general

```
└── Capa de presentación (Web apps: Quick,Draw! y TF Playground)
       ↓ (interacción usuario / datos de dibujo)
    Capa de lógica (Modelo preentrenado / Red neuronal configurable)
       ↓ (inferencia o entrenamiento)
    Capa de datos/API (50M+ dibujos en Quick,Draw! / datasets sintéticos en Playground)
```

## 2. Módulos y componentes principales

- **README.md**
  - Responsabilidad: Presentación y guía de uso del repositorio.
  - Funciones exportadas: N/A (documento estático).

- **docs/Ejercicio_3.5_..._Miguel_Jerico-comprimido.md**
  - Responsabilidad: Documento técnico-formativo con resumen, puntos clave, detalle de partes 1 y 2, y conclusiones.
  - Contenido clave: Secciones de inferencia, entrenamiento, tabla de reconocimiento, conceptos de DL.

- **Entorno Quick, Draw! (externo)**
  - Responsabilidad: Inferencia en tiempo real de dibujos.
  - Parámetros manejados: 6 dibujos, 20s/dibujo, modelo de 50M+ trazos.

- **Entorno TensorFlow Playground (externo)**
  - Responsabilidad: Entrenamiento visual de RNA.
  - Configuración: capas ocultas, nº neuronas, activación (ReLU/Tanh/Sigmoid), épocas.

## 3. APIs y endpoints

No aplica (el ejercicio usa apps web sin endpoints propios del repo).

| Método | Ruta | Descripción | Parámetros |
|--------|------|-------------|------------|
| GET | quickdraw.withgoogle.com | UI de inferencia | - |
| GET | playground.tensorflow.org | UI de entrenamiento | - |

## 4. Variables de entorno

No existen variables de entorno en el repositorio (basado en documentación estática y webs externas).

| Variable | Valor de ejemplo | Obligatoria | Descripción |
|----------|------------------|-------------|-------------|
| N/A      | N/A              | No          | Sin variables locales |

## 5. Guía de despliegue

1. Crear repo en GitHub (ej. `migueljerico/Ejercicio_Google_Quick_Draw-_TensorFlow_Playground`).
2. Subir `README.md` y carpeta `docs/` con el informe comprimido.
3. Usar opción "📤 Documentar y publicar" de la interfaz del asistente para commit automático.
4. Verificar acceso vía URL de GitHub Pages o raw del repo.
5. Para uso: abrir URLs de las dos web apps desde navegador.

## 6. Limitaciones y mejoras

**Limitaciones:**
- PDF de la práctica truncado en tabla de Parte 1.
- Sin código propio ni modelo entrenable localmente.
- Dependencia de servicios externos de Google.

**Mejoras futuras:**
- Completar tabla de reconocimiento con datos reales.
- Añadir glosario y comparativa inferencia vs entrenamiento.
- Incluir capturas y conclusiones personales.
- Migrar a notebook con TensorFlow local para reproducibilidad.
