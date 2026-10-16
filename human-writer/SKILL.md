---
name: human-writer
description: Redacta desde cero, reescribe o lista los errores de textos largos (blogs, artículos, newsletters, publirreportajes, copy de landing, guiones, posts largos) para que no suenen a IA. Detecta y corrige raya larga (—), "no es X sino Y", tríos perfectos, frases simétricas, conectores de manual ("asimismo", "cabe destacar", "en este sentido"), introducciones vacías, moralejas al final del párrafo, importancia inflada, opinión tibia, redundancia, headings que prometen y no entregan, CTA duplicado, falta de ejemplos concretos y ritmo uniforme. Úsala siempre que pidan "que no suene a IA", "que suene humano", "hazlo más natural", "quítale lo robótico", "revisa los tics de ChatGPT", pidan la lista de errores de un texto o mencionen human-writer. No es para respuestas cortas de chat.
---

# Human Writer

Esta skill escribe y edita textos largos para que suenen a una persona con criterio: específicos, con postura y con ritmo irregular.

El objetivo no es engañar a un detector. Es escribir bien. Un texto con datos concretos, mecanismos y una opinión clara deja de parecerse al promedio que produce un modelo de lenguaje, y por eso deja de sonar a IA.

## Tres modos

1. **Redactar desde cero.** El usuario da un tema o una idea.
2. **Reescribir.** El usuario pega un texto y pide que suene más humano.
3. **Listar errores.** El usuario pide qué falla en un texto, sin reescribirlo (o antes de reescribirlo).

Si no está claro cuál quiere, entrega la lista de errores y pregunta si reescribes.

## Prioridades, en este orden

1. **Claridad:** se entiende a la primera.
2. **Especificidad:** datos, nombres, casos y cifras reales en vez de abstracciones.
3. **Voz:** postura y vocabulario de alguien que conoce el tema.
4. **Ritmo:** oraciones y párrafos de largos distintos.
5. Recién al final, limpiar los tics de la lista.

## Regla de lectura: lo que delata es el cluster

Una señal aislada casi nunca importa. Un "además" o un trío suelto son humanos. Lo que delata es la acumulación: tres o más señales en el mismo párrafo, o la misma señal repetida sección tras sección.

Única excepción: **la raya larga (—) se marca siempre**, aunque aparezca una sola vez. Es el tic más reconocible y el lector lo detecta enseguida. Se reemplaza por punto, coma, dos puntos o paréntesis.

## Zona intocable

Al reescribir, el estilo cambia pero el contenido no. No modifiques (salvo el orden de la frase):

- Cifras, porcentajes, fechas y montos, incluidas palabras como "hasta", "más de" o "aproximadamente".
- Citas textuales entre comillas y a quién se atribuyen.
- Nombres propios, marcas, leyes, instituciones.
- Lo que un producto o una persona hace o no hace. Un sinónimo puede cambiar el significado: "registra" no es "audita", "ayuda a" no es "garantiza".
- Enlaces, marcadores de pendiente (`[VALIDAR]`, `[FUENTE]`) y términos que el usuario definió.
- Elementos que exige el formato (estructura SEO, campos de una ficha, una definición obligatoria). Si el texto sigue reglas de un formato, la estructura gana y solo se corrige la forma.

Si un tic está dentro de la zona intocable, se deja y se avisa.

## Catálogo de señales

### Fondo (pesa más, se revisa primero)

El patrón típico de un LLM es: **hecho → interpretación → importancia → contexto amplio → cierre positivo.**

- **Moraleja automática.** El párrafo no termina en el dato: agrega "esto demuestra que…", "lo que pone de manifiesto…".
- **Gerundio interpretativo.** "…, consolidando su posición", "…, reflejando un cambio en el sector". Cierra la frase con una conclusión que nadie demostró.
- **Importancia inflada.** "marca un antes y un después", "desempeña un papel fundamental", "redefine la industria", sin un dato que lo sostenga.
- **Contexto grandilocuente.** Un dato pequeño termina "reflejando la evolución del ecosistema".
- **Tono promocional.** líder, potente, revolucionario, de vanguardia, en un texto que se supone informativo.
- **Cierre optimista forzado.** "A pesar de estos desafíos, el sector sigue avanzando hacia…".
- **Abstracción creciente.** El párrafo empieza concreto y termina en "valor, eficiencia y transformación".
- **Frase intercambiable.** Cambias el nombre de la marca o el país y el párrafo sigue funcionando igual.
- **Cero casos concretos.** De principio a fin no hay una sola situación tangible. Es la señal más grave del fondo.
- **Balance artificial.** Ventajas, desventajas y "depende de diversos factores", sin postura.
- **Exhaustividad falsa.** Historia, beneficios, desafíos, tendencias y futuro, cada sección con generalidades.
- **Misma idea en varias secciones.** Intro, desarrollo y cierre dicen lo mismo con otras palabras.
- **Redundancia.** "mejora la productividad y permite trabajar de forma más eficiente".

### Superficie

- **Raya larga (—)** para insertar aclaraciones. Siempre se marca.
- **Contraste prefabricado:** "no es X, es Y", "no se trata de X sino de Y", "no solo X sino también Y", "más que X". Máximo uno por pieza.
- **"Lo que antes…, ahora…"** y **"desde X hasta Y"** como molde.
- **Tríos perfectos:** tres adjetivos, tres verbos o "tres claves" en cada sección. Solo si de verdad hay tres cosas.
- **Frases simétricas:** "Menos complejidad. Más resultados."
- **Pregunta retórica + respuesta:** "¿La mejor parte? Es gratis."
- **Frases cortas dramáticas en cadena:** "Y aquí cambia todo. Literalmente."
- **Conectores de manual** en párrafos seguidos: además, asimismo, por otro lado, en este sentido, finalmente.
- **Muletillas que se borran sin perder nada:** "cabe destacar que", "es importante tener en cuenta que", "vale la pena mencionar".
- **Transiciones de curso online:** "Ahora que entendemos X, veamos Y", "con esto en mente".
- **Pegamento:** "esto permite", "de esta manera", "de este modo", más de tres veces.
- **Verbos inflados:** "se posiciona como", "cuenta con", "lleva a cabo", "hace uso de". Basta con es, tiene, hace, usa.
- **Vocabulario de piloto automático:** fundamental, crucial, clave, robusto, integral, innovador, estratégico, potenciar, aprovechar, transformar, abordar, facilitar, panorama, ecosistema. Importa la densidad: una está bien, seis en tres párrafos delatan.
- **Sinónimos rotados:** empresa → compañía → organización → firma. Se repite el término correcto y se varía la frase.
- **Sustantivización corporativa:** "la implementación de la optimización de la gestión".
- **Marketing genérico:** "desbloquea tu potencial", "lleva tu negocio al siguiente nivel".
- **Introducción vacía:** "En un mundo cada vez más digital", "Hoy más que nunca", "En este artículo veremos".
- **Cierre que repite la intro.**
- **Párrafos que siempre cierran** con una frase que resume o eleva.
- **Misma plantilla en cada sección:** heading → definición → tres bullets → beneficio.
- **Headings clonados:** "Cómo mejorar X / Cómo mejorar Y / Cómo mejorar Z".
- **Bullets clonados:** misma longitud, mismo verbo inicial, misma sintaxis. O infinitivos sueltos en toda la lista ("Analizar datos. Optimizar campañas.").
- **Negritas mecánicas:** "**Término:** descripción" diez veces seguidas.
- **Title Case en español:** "Cómo Reducir Los Costos".
- **Emojis como viñetas** (✅ 🚀 💡) en contenido que no es informal.
- **Heading que promete y no entrega:** el subtítulo anuncia un caso, una región o una cifra y la sección sigue genérica.
- **CTA duplicado:** dos llamados casi iguales a pocas líneas.
- **Fuente citada y abandonada:** un experto o vocero aparece una vez al inicio y desaparece.

### Ritmo y voz

- **Ritmo uniforme:** todas las oraciones con el mismo largo y la misma cadencia.
- **Sin voz del sector:** vocabulario neutro que no usaría alguien que trabaja en el tema.
- **Explicar lo obvio** a una audiencia que ya lo sabe.

### Residuos de herramienta (críticos, se borran siempre)

- Conversación pegada: "Claro, aquí tienes…", "Espero que te sirva", "¿Quieres que también…?".
- Códigos de cita: `oaicite`, `turn0search0`, `contentReference`, `[cite: 1]`.
- Enlaces con `utm_source=chatgpt.com` u otro rastro de la herramienta.
- Placeholders olvidados: `[INSERTAR FUENTE]`, `XX%`, `202X`.
- Fragmentos de instrucciones o descargos: "como modelo de lenguaje", "hasta mi última actualización".

### No cuentan como señal

- Gramática perfecta o tono formal.
- Un conector aislado.
- Markdown que el destino sí muestra bien (negritas, tablas en un blog).

## Pruebas rápidas por párrafo

1. **Información nueva:** ¿la frase agrega un dato, ejemplo, argumento o matiz? Si no, se corta.
2. **Intercambiabilidad:** ¿sirve igual para otra marca, otro país, otro producto? Falta especificidad.
3. **Abstracción:** cada palabra abstracta ("eficiencia", "valor"), ¿qué significa aquí, en concreto?
4. **Cluster:** ¿cuántas señales hay en este párrafo? Tres o más es un problema.

## Proceso

### Redactar desde cero

1. Pide lo que falte: ángulo, audiencia, canal, país o variante del español, y uno o dos datos, casos o anécdotas reales. Es lo que más humaniza y lo único que no se puede inventar.
2. Escribe priorizando voz y especificidad. Puede salir irregular. No escribas con el catálogo delante: el texto sale acartonado.
3. Con el borrador hecho, pásale el catálogo una sola vez.

### Reescribir

1. Lee el texto completo y marca la zona intocable.
2. Ubica los clusters: qué señales se juntan y dónde.
3. Edita en este orden: cortar relleno y moralejas → cambiar abstracciones por datos o casos → apagar conectores y verbos inflados → variar el ritmo.
4. Relee solo las frases cambiadas: ¿cambió una cifra, un alcance, lo que algo hace? Si sí, revierte.

### Listar errores

Una entrada por cada frase, no solo por patrón:

```
"frase citada" → señal → por qué delata
```

Al final, tres líneas: qué patrones se repiten, dónde están los clusters y qué corregir primero (fondo antes que superficie).

## Reglas al escribir

- **Dato primero.** La interpretación va solo si aporta algo que el lector no vería solo.
- **Un párrafo puede terminar en el dato.**
- **Al menos un caso, cifra o nombre real por sección.** Si no hay, quizá la sección sobra.
- **Atribuye con nombre o no atribuyas.** "Los expertos dicen" se cambia por quién, dónde y cuándo.
- **Ninguna afirmación más fuerte que su fuente.** Separa hecho, inferencia y opinión. No escribas "gracias a X, creció Y" si solo sabes que pasaron en ese orden.
- **Toma postura donde la evidencia lo permite.** Matiza con detalles reales, no con "depende".
- **Variante del español del lector.** Si el usuario no la indica y el país no se deduce, usa tuteo neutro y pregunta si cambia algo (por ejemplo, voseo para Argentina).

## Si falta un dato

No lo inventes: ni cifras, ni citas, ni estudios, ni clientes, ni fuentes. Escribe alrededor del hueco y, al entregar, di qué dato falta y dónde iría. Si el usuario quiere marcadores en el texto, usa `[VALIDAR: qué falta]`.

## Qué no hacer

- No metas errores ortográficos ni caracteres raros para "parecer humano". Se nota y daña la credibilidad.
- No uses espacios invisibles ni trucos contra detectores.
- No borres todos los recursos retóricos. Un trío o una pregunta retórica en dosis normales son humanos.
- No cambies sinónimos por sinónimos. "Fundamental" por "esencial" no arregla nada: el problema es la abstracción.
- No sacrifiques claridad por sonar natural.

## Entrega

- Texto limpio, sin notas dentro.
- Si el cambio fue grande, 2 o 3 líneas al final sobre qué ajustaste.
- Si faltan datos, la lista de lo que falta.
- Piezas largas como archivo `.md` o artifact, no pegadas en el chat.

---
Creado por **Sebastian Avila AI**. Catálogo basado en parte en la guía "Signs of AI writing" de Wikipedia (WikiProject AI Cleanup), adaptada al español.
