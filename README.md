# 🐐 GOAT Mode - Optimized Prompts for GitHub Copilot

Una colección de **prompts de sistema optimizados** para maximizar el rendimiento de cada modelo de IA disponible en GitHub Copilot.

> 💡 Evolución de los conceptos presentados en <a href="https://burkeholland.github.io/posts/beast-mode-3-1/" target="_blank">Beast Mode 3.1</a>. Ahora con **APEX Mode 9.0** para Claude 4.5 family con estrategia adaptativa por modelo.

## 🎯 ¿Qué es GOAT Mode?

GOAT Mode (Greatest Of All Time) es un conjunto de instrucciones de sistema diseñadas específicamente para cada modelo de IA, aprovechando sus fortalezas únicas:

- **Maximizar la calidad del código** generado en el primer intento
- **Reducir iteraciones innecesarias** optimizando el uso de requests
- **Comportamiento autónomo** como un desarrollador senior real
- **Resultados listos para producción** desde la primera respuesta

## 📦 Prompts Disponibles

| Modelo                           | Archivo                          | Optimizado Para                                                              |
| -------------------------------- | -------------------------------- | ---------------------------------------------------------------------------- |
| Claude 4.5 Opus / Sonnet / Haiku | [apex.md](./apex.md)             | **APEX 9.0**: Estrategia adaptativa por modelo, first-time correctness       |
| Gemini 1.5 Pro / Ultra / 3.0     | [omni.md](./omni.md)             | **OMNI 9.0**: Omniscient context leverage, zero-shot, 1M+ tokens             |
| GPT-5.1 Codex                    | [mentor.md](./mentor.md)         | **MENTOR 1.0**: Extended reasoning, análisis → plan → aprobación → ejecución |
| GPT-5.2                          | [mentor-pro.md](./mentor-pro.md) | **MENTOR PRO 1.0**: MENTOR con respuestas en español nativo                  |
| Grok Fast                        | [blitz.md](./blitz.md)           | **BLITZ 1.0**: Velocidad + calidad, ejecución rápida sin compromiso          |

## 🚀 Cómo Usar

1. **Copia el contenido** del archivo correspondiente al modelo que estés usando
2. **Pégalo en las instrucciones de modo** de GitHub Copilot (VS Code Settings → Copilot → Mode Instructions)
3. **Disfruta** de un agente de código autónomo y eficiente

## 🎯 Cuándo Usar Cada Prompt

- **APEX 9.0** (Claude 4.5): Mejor opción general. Elige Opus para arquitectura compleja, Sonnet para desarrollo estándar, Haiku para tareas rápidas.
- **OMNI 9.0** (Gemini 1.5+): Contexto ilimitado (1M+ tokens). Ideal para análisis exhaustivo de proyectos grandes, zero-shot implementation.
- **MENTOR 1.0** (GPT-5.1): Razonamiento extendido. Flujo explícito: Análisis → Plan → Aprobación → Ejecución. Para cambios críticos.
- **MENTOR PRO 1.0** (GPT-5.2): MENTOR con respuestas 100% en español. Idéntico flujo, pero nativo en español latinoamericano.
- **BLITZ 1.0** (Grok): Velocidad máxima sin comprometer calidad. Ideal para sprints, prototipos y entregas rápidas.

## 💡 Filosofía

Todos los prompts (APEX, OMNI, MENTOR, BLITZ) comparten principios fundamentales:

```
Working Software > Correct Implementation > Clean Code > Best Practices
```

- **Implementar, no sugerir** - El agente actúa como desarrollador senior, no como asistente
- **Un request, una solución completa** - Maximizar valor por interacción
- **Razonamiento profundo primero** - Entender completamente antes de codificar
- **Código listo para producción** - Sin "debería funcionar", sino "funciona"
- **Estrategia adaptativa** - Optimización automática según modelo y contexto

## 👤 Autor

**Andrés Frei** - [andresfrei.dev](https://andresfrei.dev)

## 📄 Licencia

MIT - Usa, modifica y comparte libremente.

---

_Optimiza tu flujo de trabajo con GitHub Copilot usando el prompt correcto para cada modelo._
