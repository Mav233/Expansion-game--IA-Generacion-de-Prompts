# Expansión Game: Meta Visión

## Introducción
**Expansión Game: Meta Visión** es un sistema de recomendación basado en inteligencia artificial diseñado para ayudar a los usuarios a seleccionar componentes de PC según sus necesidades y presupuesto.

### Problema a abordar
Los entusiastas de la tecnología enfrentan dificultades al elegir componentes de hardware compatibles y adecuados para su uso. La falta de conocimiento técnico y la rápida evolución del mercado pueden llevar a compras incorrectas o ineficientes.

### Propuesta de solución
Se desarrolló un sistema basado en IA que, mediante el uso de **Fast Prompting**, guía al usuario en la selección de componentes óptimos para su PC. El sistema permite:
- Recomendaciones personalizadas basadas en presupuesto y uso.
- Verificación de compatibilidad entre componentes.
- Comparación entre productos para evaluar cuál es mejor.
- Optimización de configuraciones para gaming a 1440p.
- Respuestas a consultas técnicas sobre hardware.

## Justificación de viabilidad
El proyecto es técnicamente viable gracias a modelos avanzados como **Google Gemini**, integrados en una aplicación interactiva. Además, el desarrollo se estructura en fases:
1. **MVP (Producto Mínimo Viable)**: Implementación de prompts básicos y recomendaciones iniciales.
2. **Expansión de funcionalidades**: Integración de más componentes, compatibilidad mejorada y ajustes basados en retroalimentación de los usuarios.

## Objetivos
- Crear un sistema interactivo que facilite la elección de componentes de PC.
- Mejorar la experiencia de compra con IA que oriente a los usuarios.
- Implementar herramientas de comparación y verificación de compatibilidad.
- Optimizar configuraciones para obtener el mejor rendimiento dentro del presupuesto.

## Metodología
El desarrollo del sistema sigue un enfoque iterativo:
1. **Análisis de requerimientos**: Definición de los prompts clave para recopilar información del usuario.
2. **Implementación del modelo IA**: Uso de **Google Gemini** para generar recomendaciones precisas.
3. **Pruebas y validación**: Evaluación de respuestas y ajuste de prompts.
4. **Optimización y mejoras**: Incorporación de más opciones de hardware y refinamiento del sistema de recomendaciones.

## Herramientas y Tecnologías
- **Modelo IA:** Google Gemini (Generative AI)
- **Lenguaje:** Python
- **Entorno:** Jupyter Notebook
- **Estrategias de Prompting:**
  - **Prompt inicial**: "¿Para qué usarás tu PC y cuál es tu presupuesto en pesos argentinos?"
  - **Prompt de compatibilidad**: "Estos son los componentes seleccionados. ¿Hay alguna incompatibilidad técnica que deba considerar?"
  - **Prompt de optimización**: "Con el presupuesto disponible, ¿cuál es la mejor configuración posible para gaming a 1440p?"
  - **Prompt de comparación**: "Compara estos productos: Producto A vs Producto B. ¿Cuál es mejor y por qué?"
  - **Prompt de consulta técnica**: "¿Cuál es la diferencia entre DDR4 y DDR5 y cuál me conviene más?"

## Implementación
El sistema se implementa en Python y permite la interacción con el usuario a través de una consola.

### Código principal
1. **El usuario visualiza una lista de productos disponibles.**
2. **Ingresa su presupuesto y uso de la PC para obtener recomendaciones personalizadas.**
3. **Puede verificar la compatibilidad de los componentes seleccionados.**
4. **Tiene la opción de comparar dos productos en formato 'versus'.**
5. **Puede optimizar su configuración para gaming a 1440p.**
6. **Puede realizar consultas técnicas sobre hardware.**

Este sistema proporciona una experiencia interactiva eficiente, asegurando que los usuarios tomen decisiones informadas al seleccionar componentes para su PC gamer.


