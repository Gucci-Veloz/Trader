## 🧠 Introducción

> Bienvenido a tu centro táctico de análisis institucional para criptomonedas.  
Este sistema fue diseñado para operar con precisión quirúrgica en mercados de futuros volátiles, usando estrategias basadas en liquidez, manipulación institucional y psicología del mercado.

Aquí no hay adivinanza. Hay estructura, volumen y reacción.  
Prepárate para operar como las manos fuertes.

---

## 📦 Contenido del Sistema

Todos los archivos clave están contenidos en la carpeta `/GPT-Files`.  
Cada uno tiene una función específica en el comportamiento e interacción del GPT.

```
📁 DOCS/
├── README.md                         → Instructivo general del sistema.
├── schema/
│   └── schema.actions.json          → Esquema de ChatGPT Actions (basado en OpenAPI) que conecta el GPT con Make.
├── scripts/
│   └── webhook-handler.js           → Referencia de manejo lógico del webhook en entorno Node.js.
├── GPT-Files/
│   ├── PROMPT.md                    → Definición de personalidad, principios y restricciones del GPT.
│   ├── CONTEXTO.md                  → Entorno operativo del GPT (caso de uso, tipo de análisis, dinámica).
│   ├── ASM-TOOL.md                  → Estrategia técnica institucional completa: HVB, OB, FVG, Liquidez.
│   ├── ASK_USER.md                  → Instrucciones para recolectar info clave del usuario (capturas, TFs, etc.).
│   └── FORMATO_DE_RESPUESTA.md      → Plantilla estándar de respuesta para entradas swing/scalp.
```

---

## 🚀 Cómo usar este sistema

1. **Carga el contenido de `PROMPT.md`** como prompt del modelo.
2. Usa el contenido de `CONTEXTO.md` para establecer la dinámica de trabajo.
3. Instruyete a que siempre sigas el formato de `FORMATO_DE_RESPUESTA.md`.
4. Usa `ASK_USER.md` como guía para pedrile al usuario las imagenes.
5. Aplica la estrategia del archivo `ASM-TOOL.md` para evaluar, validar y ejecutar entradas institucionales.

---

## 💡 Recomendaciones Pro

- No ajustes los principios del PROMPT a menos que estés seguro de lo que haces.
- Puedes ampliar el archivo `ASM-TOOL.md` con tus propias estrategias, pero sigue el estilo modular.
- El GPT puede crecer: crea nuevas versiones de estrategias en archivos como `PATTERNS.md`, `VOLUME_TRAPS.md`, etc.

---

## 🛠 ¿Cómo escalar este sistema?

- **Para uso individual:** carga los `.md` en tu GPT personalizado (OpenAI, Chatbase, LangChain, etc.).
- **Para uso en equipo:** comparte el `.zip` completo y actualiza solo los módulos necesarios.
- **Para entrenamiento extendido:** combina estos `.md` con tu histórico de screenshots + análisis y alimenta un vector retriever.
