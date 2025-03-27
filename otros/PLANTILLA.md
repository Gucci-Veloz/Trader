# Acción solicitada
- Quiero que me generes un objeto `schema.actions` que represente paso a paso el flujo definido en mis archivos. Este objeto será usado por un GPT como agente que actúa en base a reglas y archivos previamente definidos.

- Cada acción debe corresponder a un paso del flujo, leer un archivo o ejecutar una lógica indicada en el contenido (ej. leer prompt, entender contexto, fijar estrategia, pedir inputs, formatear respuesta).
Quiero automatizar, mediante Make, el flujo de lectura e interpretación de archivos por parte de un GPT que me asiste en trading.

# Contexto incluido
- El GPT tiene un prompt personalizado (disponible en `.md` y `.json`).
- En su interfaz, uso una frase activadora: `"Modo DIOS: ON"`.
- Esta frase debe iniciar un flujo definido, basado en archivos que el GPT debería leer y procesar.
- Los archivos están organizados en una carpeta `DOCS`, con esta estructura:

Docs/ 
├── README.md
├── GPT-Files/
│   ├── prompt.md
│   ├── CONTEXTO.md
│   ├── ASM-Tool.md
│   ├── ASK_USER.md
│   └── FORMATO_DE_RESPUESTA.md
├── scripts/
│   └── webhook-handler.js
└── schema/
    └── schema.actions.json




# Contexto incluido
@Files: 
- Docs/README.md  
- Docs/GPT-Files/prompt.md  
- Docs/GPT-Files/CONTEXTO.md  
- Docs/GPT-Files/ASM-Tool.md  
- Docs/GPT-Files/ASK_USER.md  
- Docs/GPT-Files/FORMATO_DE_RESPUESTA.md  
- Docs/scripts/webhook-handler.js  
- Docs/schema/schema.actions.json 
@Code: [fragmentos de código si aplica]  
@Folders: [carpetas si aplica]  
@Git: [diff, commit o PR si es relevante]  
[Otro: puedes usar también @Definitions, @Docs, @Web si es útil]

# Restricciones
- [Limitar alcance: qué no debe tocar o modificar]
- [Condiciones técnicas: formato, estilo, compatibilidad, etc.]

# Resultado esperado
[Especificar el tipo de respuesta: código listo para aplicar, explicación paso a paso, sugerencia de mejora, etc.]

# Preferencias (opcional)
Modelo: [ej. GPT-4 / Claude 3.5 / cursor-small]  
Modo: [ej. Long Context activado/desactivado, sin contexto, etc.]
