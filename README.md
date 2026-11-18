# evaluacion-vibe-coding.md
Evaluación comparativa de herramientas de vibe coding (Cursor, Windsurf y GitHub Copilot Workspace), incluyendo contexto de desarrollo, matriz de puntuación y elección final para proyectos de 4Geeks Academy.

# Evaluación de Herramientas de Vibe Coding

## 1. Necesidades y Contexto

* **Perfil / Contexto del Desarrollador:** Estudiante/desarrollador Full-Stack enfocado en prototipado rápido, construcción de MVPs (Productos Mínimos Viables) y desarrollo iterativo de funcionalidades donde la velocidad de ejecución es crítica.
* **Objetivos Principales:**
  * Construir y prototipar aplicaciones web rápidamente utilizando instrucciones en lenguaje natural (*prompts*).
  * Mantener una estructura de código limpia y legible sin perder tiempo en configuraciones repetitivas (*boilerplate*).
  * Depurar errores, refactorizar código y añadir nuevas funcionalidades de forma iterativa mediante asistencia de agentes de IA.
* **Criterios Clave de Evaluación:**
  * **Seguimiento de Instrucciones y Manejo de Contexto:** Capacidad de la herramienta para entender indicaciones complejas y mantener el contexto del proyecto a través de múltiples archivos.
  * **Calidad y Mantenibilidad del Código:** Limpieza del código generado y adherencia a las buenas prácticas modernas de desarrollo.
  * **Integración y Usabilidad:** Facilidad de configuración, integración con el entorno de desarrollo (IDE), velocidad de respuesta y experiencia de usuario (DX).

---

## 2. Tabla Comparativa (Scorecard)

| Característica / Criterio | **Cursor (IDE impulsado por IA)** | **Windsurf (Codeium)** | **GitHub Copilot Workspace** |
| :--- | :--- | :--- | :--- |
| **Ventana de Contexto y Comprensión** | Excelente (Indexación profunda del código base, referencia directa con `@` a archivos/carpetas) | Muy Buena (Flujos *Cascade* que navegan automáticamente entre archivos) | Buena (Muy vinculada al contexto de *issues* y *Pull Requests* de GitHub) |
| **Autonomía del Agente y Edición Multi-archivo** | Alta (El modo *Composer* gestiona la generación en múltiples archivos sin fricciones) | Muy Alta (El agente *Cascade* ejecuta comandos en terminal y refactoriza varios archivos) | Moderada-Alta (Enfocada principalmente en flujos de trabajo de *issue* a PR) |
| **Velocidad y Capacidad de Respuesta** | Rápida (Enrutamiento optimizado de modelos como Claude y GPT) | Rápida (Flujos personalizados y autocompletado en línea muy ágil) | Moderada (Depende de la orquestación en la nube de GitHub) |
| **Experiencia de Desarrollo (DX) / Configuración** | Familiar (Basado en VS Code, migración instantánea) | Fluida (Bifurcación de VS Code con agentes inteligentes en barra lateral) | Enfocada en la web / Integrada directamente en la interfaz de GitHub |
| **Puntuación Final (Sobre 10)** | **9.5 / 10** | **9.0 / 10** | **8.0 / 10** |

---

## 3. Elección Final

* **Herramientas Seleccionada:** **Cursor**
* **Justificación:** 
  Para el flujo de trabajo de *vibe coding* en **4Geeks**, **Cursor** destaca por la potencia de su modo *Composer* y su capacidad para indexar todo el repositorio local de manera instantánea. Permite pasar de una idea general a componentes funcionales en cuestión de segundos, manteniendo un control preciso sobre los cambios en múltiples archivos simultáneamente sin perder la coherencia del proyecto.
