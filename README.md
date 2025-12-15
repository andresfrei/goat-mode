# 🐐 GOAT Mode - Optimized Prompts for GitHub Copilot

Una colección de **prompts de sistema optimizados** para maximizar el rendimiento de cada modelo de IA disponible en GitHub Copilot.

> 💡 Este proyecto se basa en los conceptos presentados en [Beast Mode 3.1](https://burkeholland.github.io/posts/beast-mode-3-1/) de Burke Holland.

## 🎯 ¿Qué es GOAT Mode?

GOAT Mode (Greatest Of All Time) es un conjunto de instrucciones de sistema diseñadas específicamente para cada modelo de IA, aprovechando sus fortalezas únicas:

- **Maximizar la calidad del código** generado en el primer intento
- **Reducir iteraciones innecesarias** optimizando el uso de requests
- **Comportamiento autónomo** como un desarrollador senior real
- **Resultados listos para producción** desde la primera respuesta

## 📦 Prompts Disponibles

| Modelo                   | Archivo                                | Optimizado Para                                                |
| ------------------------ | -------------------------------------- | -------------------------------------------------------------- |
| Claude Opus 4.5 / Sonnet | [claude-sonnet.md](./claude-sonnet.md) | Razonamiento profundo, implementación completa en un solo paso |
| Gemini 3.0               | [gemini.md](./gemini.md)               | Contexto masivo (1M+ tokens), zero-shot implementation         |
| GPT-5.1 Codex            | [gpt-codex.md](./gpt-codex.md)         | Análisis → Plan → Ejecución, proyectos TypeScript              |
| Grok Fast                | [grok.md](./grok.md)                   | Velocidad de codificación, entregas rápidas                    |

## 🚀 Cómo Usar

1. **Copia el contenido** del archivo correspondiente al modelo que estés usando
2. **Pégalo en las instrucciones de modo** de GitHub Copilot (VS Code Settings → Copilot → Mode Instructions)
3. **Disfruta** de un agente de código autónomo y eficiente

## 💡 Filosofía

Todos los prompts comparten principios fundamentales:

```
Working Software > Correct Implementation > Clean Code > Best Practices
```

- **Implementar, no sugerir** - El agente actúa como desarrollador, no como asistente
- **Un request, una solución completa** - Maximizar valor por interacción
- **Razonamiento profundo primero** - Entender completamente antes de codificar
- **Código listo para producción** - Sin "debería funcionar", sino "funciona"

## 👤 Autor

**Andrés Frei** - [andresfrei.dev](https://andresfrei.dev)

## 📄 Licencia

MIT - Usa, modifica y comparte libremente.

---

_Optimiza tu flujo de trabajo con GitHub Copilot usando el prompt correcto para cada modelo._
