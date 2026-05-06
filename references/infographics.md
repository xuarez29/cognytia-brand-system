# CognytIA — Infografías y Gráficas

## Filosofía visual para este formato

Las infografías de CognytIA no son decoración — son argumentos visuales.
Cada pieza debe poder leerse en 5 segundos y entenderse en 15.
Si necesita más tiempo, hay demasiada información.

La estética es una extensión del resto de la marca: fondo blanco, espacio generoso,
jerarquía clara, colores con propósito. Serena. Profesional. Sin ruido.

---

## Tamaños por plataforma

| Plataforma | Formato | Tamaño recomendado |
|---|---|---|
| LinkedIn | Imagen única | 1200 × 627 px (landscape) o 1080 × 1080 px (cuadrado) |
| LinkedIn | Carrusel | 1080 × 1080 px por slide |
| X (Twitter) | Imagen única | 1200 × 675 px |
| Substack | Imagen en artículo | 1200 × 630 px |
| WhatsApp | Imagen única | 1080 × 1080 px |

**Default universal:** `1080 × 1080 px` — funciona en todas las plataformas sin recortes.
Usar landscape (1200 × 627) solo cuando el contenido lo requiere por su orientación horizontal.

---

## Paleta aplicada a infografías

La misma paleta de marca, con roles específicos para este formato:

| Color | Hex | Rol en infografías |
|---|---|---|
| Blanco | `#FFFFFF` | Fondo siempre. Sin excepciones. |
| Grafito | `#2D3142` | Texto principal, títulos, ejes de gráficas |
| Teal CognytIA | `#4DBDB5` | Elemento principal destacado, barra o dato clave, título de sección |
| Teal claro | `#A8DDD9` | Elementos secundarios, barras de comparación, fondos de cajas |
| Grafito suave | `#4A5568` | Texto de apoyo, etiquetas, descripciones |
| Neutro cálido | `#F7F8F9` | Fondos de cajas, separadores suaves, zonas de descanso |
| Ámbar suave | `#E8A838` | Un solo elemento por pieza — el dato más importante, el contraste crítico |

> Regla de los 3 colores: en una infografía típica usar máximo 3 colores activos
> (sin contar blanco y neutro). Más colores = más ruido.

---

## Tipografía en infografías

| Elemento | Fuente | Peso | Tamaño relativo |
|---|---|---|---|
| Título de la pieza | DM Sans | Medium 500 | El más grande. 1 solo nivel. |
| Subtítulos / etiquetas de sección | DM Sans | Regular 400 | Segundo nivel |
| Texto descriptivo / cuerpo | Inter | Regular 400 | Tercer nivel — siempre el más pequeño |
| Números, métricas, porcentajes | JetBrains Mono | Regular | Destacados. El número grande, la unidad pequeña. |
| Fuente de datos (si aplica) | Inter | Regular 400 | Mínimo. Parte inferior de la pieza. |

**Jerarquía:** Máximo 3 niveles tipográficos por pieza. Si hay un cuarto nivel, algo sobra.

**Números grandes:** Los datos numéricos son el protagonista en estadísticas.
El número va grande (en Mono), la descripción va pequeña debajo (en Inter).

---

## Tipos de pieza y cómo construirlos

---

### Tipo A — Estadística / métrica destacada

Para comunicar un dato con impacto.

**Estructura:**
```
[Título breve — el contexto del dato]
[Número grande en JetBrains Mono — teal o grafito]
[1 línea de descripción en Inter — lo que significa ese número]
[Fuente si aplica — pequeña, abajo]
[Logo — esquina inferior]
```

**Criterios:**
- El número es el centro visual. Todo lo demás es soporte.
- Máximo 2 estadísticas por pieza. Si son más, hacer carrusel.
- El ámbar puede usarse en el número si es el dato más crítico de la pieza.

---

### Tipo B — Concepto explicado visualmente

Para simplificar una idea técnica o un proceso.

**Estructura:**
```
[Título — afirmación o pregunta, no tema genérico]
[2-4 bloques o pasos con ícono + etiqueta + 1 línea de descripción]
[Conexión visual entre bloques: flecha, línea, numeración]
[Logo — esquina inferior]
```

**Criterios:**
- Los íconos son outline (trazo, no sólido). Estilo consistente entre todos.
- Máximo 4 bloques por pieza. Si son más, dividir en dos imágenes.
- Las flechas y conectores en Teal claro o Grafito suave — nunca en negro puro.
- El título es una afirmación, no un tema: "Automatizar no es costoso. No automatizar, sí." en vez de "Automatización de procesos".

---

### Tipo C — Comparación

Para mostrar contraste: antes/después, con/sin, opción A vs B.

**Estructura:**
```
[Título — el punto de contraste]
[Dos columnas o dos zonas]
  Izquierda: estado actual / problema / sin IA
  Derecha: estado mejorado / solución / con CognytIA
[Color diferenciador: Grafito suave para el problema, Teal para la solución]
[Logo — esquina inferior]
```

**Criterios:**
- No llamar a la columna izquierda "malo" ni a la derecha "bueno" — mostrar la diferencia, dejar que el lector concluya.
- El teal siempre del lado de la solución o del avance.
- Evitar checkmarks verdes y X rojas — es cliché. Usar contraste tipográfico y de color.

---

### Tipo D — Gráfica de datos (barra, línea, pastel)

Para mostrar tendencias, distribuciones o comparaciones numéricas.

**Criterios generales:**
- Fondo blanco. Siempre.
- Ejes en Grafito suave `#4A5568`, no en negro.
- Barra / línea / segmento principal: Teal `#4DBDB5`
- Barras secundarias o de comparación: Teal claro `#A8DDD9`
- Dato destacado (el más importante): Ámbar `#E8A838` — solo uno por gráfica
- Sin efectos 3D. Sin sombras. Sin gradientes en las barras.
- Etiquetas de datos siempre visibles — no obligar al ojo a leer el eje para entender el valor.
- Título de la gráfica: afirmación, no descripción. "El 70% del tiempo se va en tareas repetibles" en vez de "Distribución del tiempo operativo".

**Por tipo de gráfica:**

| Gráfica | Cuándo usarla |
|---|---|
| Barras verticales | Comparar categorías distintas |
| Barras horizontales | Cuando las etiquetas son largas o hay más de 5 categorías |
| Línea | Tendencia en el tiempo |
| Pastel / dona | Solo si hay máximo 4 segmentos y la proporción es el mensaje. Evitar por default. |

---

## Elementos gráficos permitidos

- **Íconos:** outline, trazo uniforme, sistema consistente (no mezclar estilos)
- **Líneas y flechas:** delgadas, en teal o grafito suave
- **Cajas / cards:** borde en teal claro o fondo neutro cálido, sin sombra pesada
- **Separadores:** línea horizontal fina en teal o neutro — no bloques de color sólido
- **El símbolo C:** puede usarse como elemento gráfico de fondo a 8-12% de opacidad

---

## Logo como firma de autoría

El logo aparece en cada pieza, pero de forma discreta.

- **Versión:** Wordmark horizontal ("CognytIA") sin tagline, o símbolo solo
- **Posición:** Esquina inferior derecha o inferior izquierda — consistente en todas las piezas
- **Tamaño:** No más del 10% del ancho total de la pieza
- **Color:** Grafito suave `#4A5568` o Teal `#4DBDB5` según el fondo de esa zona
- **Sin recuadro, sin fondo, sin borde** alrededor del logo

El objetivo es que quien vea la pieza sepa de quién es sin que el logo compita con el contenido.

---

## Prompts base para herramientas de IA

Usar como punto de partida al generar infografías con herramientas de IA visual.
Adaptar el contenido específico según la pieza.

### Para estadísticas:
```
Infographic design. Clean minimal style. White background (#FFFFFF).
Main stat: [NÚMERO] in large JetBrains Mono font, color #4DBDB5.
Supporting text in Inter Regular, color #2D3142.
Title in DM Sans Medium, color #2D3142.
Small logo "CognytIA" bottom right corner, subtle, color #4A5568.
No gradients. No shadows. No decorative elements. Generous white space.
1080x1080px.
```

### Para conceptos / procesos:
```
Infographic design. Minimal editorial style. White background (#FFFFFF).
[N] steps/blocks with outline icons, connected by thin arrows in #A8DDD9.
Section titles in DM Sans Medium #2D3142. Descriptions in Inter Regular #4A5568.
Accent color #4DBDB5 for highlights. One element in #E8A838 maximum.
Small logo "CognytIA" bottom right, subtle.
No shadows. No gradients. Clean geometry. 1080x1080px.
```

### Para gráficas de datos:
```
Data visualization. Minimal style. White background (#FFFFFF).
[TYPE] chart. Primary bars/lines in #4DBDB5. Secondary in #A8DDD9.
One highlighted element in #E8A838.
Axis labels in Inter Regular #4A5568. Chart title in DM Sans Medium #2D3142
as a statement, not a label.
No 3D effects. No shadows. Data labels visible on bars.
Small "CognytIA" wordmark bottom right corner.
1080x1080px.
```

---

## Lo que NO se hace en infografías CognytIA

- No usar fondos de color (ni teal, ni grafito) como base — solo blanco
- No más de 4 colores activos en una pieza
- No texto en cursiva — no va con el estilo tipográfico
- No íconos de robots, cerebros con circuitos ni engranajes — son clichés de IA
- No gráficas de pastel con más de 4 segmentos
- No efectos 3D ni sombras pesadas en ningún elemento
- No más de 40 palabras de texto en una imagen única — si necesita más, es carrusel
- No centrar todo — la composición puede tener alineación a la izquierda para dar ritmo
- No olvidar la fuente si el dato es externo — la credibilidad depende de eso
