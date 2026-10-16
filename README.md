# human-writer: que tus textos no suenen a IA

Una skill en español para Claude (adaptable a otros asistentes) que **redacta, reescribe o lista los errores** de textos largos para que suenen a una persona: blogs, newsletters, artículos, copy de landing, guiones, posts largos.

No usa trucos contra detectores. Hace lo que hace un buen editor: cortar relleno, cambiar abstracciones por datos concretos, tomar postura y variar el ritmo. Un texto así deja de sonar a IA porque deja de parecerse al promedio.

Creado por **Sebastian Avila AI**.

> ¿Publicas seguido y quieres un proceso de revisión completo (auditoría de tics, consistencia y verificación de fuentes)? Usa el kit: **[kit-skill-human-writer](https://github.com/alamoaq/kit-skill-human-writer)**. Instala uno u otro, no los dos: ambos traen una skill llamada `human-writer`.

## Qué detecta y corrige

- La raya larga (—), siempre.
- "No es X, es Y", "no solo X sino también Y".
- Tríos perfectos: "más rápido, más simple y más eficiente".
- Frases simétricas: "Menos complejidad. Más resultados."
- Conectores de manual en cadena: "además", "asimismo", "por otro lado", "cabe destacar".
- Introducciones vacías: "En un mundo cada vez más digital…".
- Párrafos que terminan con moraleja: "esto demuestra que…".
- Importancia inflada: "marca un antes y un después".
- Vocabulario de piloto automático: crucial, fundamental, potenciar, robusto, ecosistema.
- Opinión tibia: "depende de diversos factores".
- Textos sin un solo ejemplo concreto de principio a fin.
- Restos del chat pegados: "Claro, aquí tienes…", `utm_source=chatgpt.com`.

## Cómo instalar

### En Claude.ai (web o app de escritorio)

1. Descarga este repositorio: botón verde **Code → Download ZIP**, y descomprímelo.
2. Adentro está la carpeta `human-writer/` con el archivo `SKILL.md`.
3. Comprime **esa carpeta** en un `.zip` (en Windows o Mac: clic derecho → Comprimir).
4. En Claude.ai, ve a **Configuración → Capacidades** (sección Skills) y sube el `.zip`.

Necesitas tener activadas las Skills en tu cuenta. Si no ves la opción, revisa que tu plan las incluya.

### En Claude Code

```bash
git clone https://github.com/alamoaq/human-writer.git
cp -r human-writer/human-writer ~/.claude/skills/
```

En Windows la ruta es `C:\Users\TU_USUARIO\.claude\skills\`. Para usarla solo en un proyecto, cópiala a `.claude/skills/` dentro del proyecto.

### En ChatGPT, Gemini u otros

Pega el contenido de `human-writer/SKILL.md` como instrucciones de un GPT personalizado, de un Gem, o al inicio de la conversación.

## Cómo usarla

No hace falta nombrarla: se activa sola cuando pides algo relacionado.

- "Escríbeme un artículo sobre cómo elegir un CRM para una tienda online. Público: dueños de pymes en México."
- "Reescribe este texto para que no suene a ChatGPT: [pega el texto]"
- "Dame la lista de errores de este blog, frase por frase."

Lo que más mejora el resultado: darle **un dato, un caso o una anécdota real**. Es lo único que la IA no puede inventar bien, y la skill está hecha para no inventarlo.

## Lo que no hace

- No mete errores a propósito ni caracteres invisibles para "engañar" detectores.
- No inventa datos, clientes, estudios ni citas. Si falta algo, te dice qué falta.
- No garantiza pasar un detector de IA. Está hecha para que el texto sea mejor, no para esconder cómo se escribió.

## Créditos y licencia

Creado por **Sebastian Avila AI**.

Parte del catálogo de señales está basado en la guía ["Signs of AI writing"](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) del WikiProject AI Cleanup de Wikipedia, adaptada al español y ampliada.

Licencia [CC BY-SA 4.0](LICENSE): puedes usar, modificar y compartir esta skill, incluso con fines comerciales, siempre que des crédito a Sebastian Avila AI y compartas tus versiones con la misma licencia.
