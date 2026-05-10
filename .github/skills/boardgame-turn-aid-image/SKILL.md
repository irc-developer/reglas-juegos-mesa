---
name: boardgame-turn-aid-image
description: "Genera prompts muy precisos para ayudas visuales de turno de juegos de mesa. Usar cuando: el usuario quiera una imagen horizontal 12:7, apoyada en referencias visuales del juego real, con secuencia de turno, iconografía, simbología y recordatorios para novatos."
argument-hint: "Indica el juego, las reglas o resúmenes a usar y si quieres una ayuda panorámica de turno para novatos."
user-invocable: true
disable-model-invocation: false
---

# Boardgame Turn Aid Image

## Qué hace esta skill

Esta skill sirve para redactar prompts de imagen muy detallados para generadores como Mundrel cuando el objetivo es crear una ayuda visual de turno de un juego de mesa.

El caso base de esta skill es este:

- formato horizontal 12:7,
- ayuda de turno para jugadores novatos,
- alta densidad de información,
- apoyo en referencias visuales subidas por el usuario,
- máxima fidelidad posible al aspecto real del juego,
- inclusión explícita de iconografía y simbología.

## Cuándo usarla

Usa esta skill cuando el usuario pida cualquiera de estas cosas:

- un prompt para Mundrel u otra generadora de imágenes,
- una ayuda visual de turno,
- una chuleta panorámica,
- una hoja de referencia rápida del flujo del juego,
- una infografía de juego de mesa fiel al estilo original,
- una pieza 12:7 horizontal con mucho contenido mecánico,
- una ayuda apoyada en referencias visuales del juego real.

## Supuestos por defecto

Salvo que el usuario diga lo contrario, trabaja con estas decisiones:

1. El formato es horizontal 12:7.
2. La pieza es una ayuda de turno y no un póster decorativo.
3. El público principal es novato.
4. El usuario aportará referencias visuales del tablero, iconos, componentes o cartas.
5. Hay que acercarse todo lo posible al lenguaje visual real del juego: componentes, colores, distribución, iconografía, simbología, densidad y sensación de ayuda oficial o semioficial.
6. El texto debe ser mínimo, de consulta rápida, con microfrases, flechas, iconos, microtablas y mini diagramas.

## Procedimiento

### 1. Leer la mejor fuente mecánica disponible

Busca primero, en este orden:

1. resumen de turno o ayuda de jugador ya creada,
2. guía para novatos,
3. reglamento oficial,
4. FAQ o erratas,
5. ayudas fan solo como contraste terminológico.

Extrae solo lo que hace falta para una ayuda visual de turno:

- objetivo y derrota,
- secuencia completa de ronda,
- fases y subfases,
- acciones o decisiones del jugador,
- valores numéricos críticos,
- palabras clave de efectos,
- excepciones fáciles de olvidar,
- iconos o símbolos que merezca la pena representar.

### 2. Reducir la información a bloques visuales

Para una ayuda panorámica 12:7, usa una estructura de este tipo:

1. cabecera,
2. objetivo y derrota,
3. prioridad táctica o lectura correcta del turno,
4. secuencia de ronda como bloque dominante,
5. detalle de la fase más importante,
6. valores rápidos,
7. simbología y conceptos esenciales,
8. recordatorios de novato.

Si el juego no necesita todos esos bloques, elimina antes decoración que contenido mecánico.

### 3. Redactar el prompt con máxima precisión visual

El prompt debe pedir de forma explícita:

- que parezca una ayuda oficial o semioficial del juego,
- que no parezca un póster, una portada ni un fanart libre,
- que conserve el lenguaje visual real del tablero y componentes,
- que la jerarquía visual esté pensada para leer el turno,
- que la tipografía sea muy legible a tamaño reducido,
- que la composición sea densa pero ordenada,
- que incluya iconografía y simbología del juego cuando el usuario haya dado referencias.

Cuando el usuario diga que subirá referencias visuales, asume que puedes pedir una fidelidad muy alta a:

- colores reales,
- iconos reales,
- símbolos de recursos o terrenos,
- siluetas de unidades o piezas,
- estructura del tablero,
- tono material de cartas, tableros y ayudas.

### 4. Incluir siempre estas secciones de salida

El entregable debe seguir la estructura de la [plantilla base](./assets/prompt-template.md):

1. objetivo,
2. prompt listo para pegar,
3. prompt con imágenes adjuntas,
4. referencias ideales para adjuntar,
5. negative prompt,
6. variante más concreta,
7. ajustes recomendados,
8. nota de uso.

### 5. Reglas de redacción

- Escribe en español.
- Prioriza frases cortas y concretas.
- No generes párrafos largos dentro del prompt principal.
- No pidas interfaces genéricas futuristas.
- No conviertas la ayuda en un póster temático.
- Pide símbolos y iconos reales del juego si son útiles para la lectura.
- Si el juego tiene una fase crítica, dale el bloque visual central.
- Si el juego tiene mucha carga iconográfica, exige una leyenda o microbloque de simbología.

## Checklist de contenido mínimo

Antes de cerrar el prompt, comprueba que incluye:

- proporción 12:7,
- orientación horizontal,
- finalidad de ayuda de turno,
- público novato,
- secuencia de ronda completa,
- valores o números clave,
- prioridades tácticas o recordatorios,
- referencia a iconografía y simbología,
- uso de imágenes adjuntas como ancla principal,
- negative prompt para evitar pósteres o composiciones inútiles.

## Checklist visual mínimo

- bloques claros y modulares,
- jerarquía fuerte,
- alto contraste,
- apariencia de componente real de mesa,
- gran legibilidad,
- mucha información pero ordenada,
- fidelidad alta al juego real.

## Dónde guardarlo en este repo

Si el usuario quiere que lo escribas en el proyecto actual, usa esta ruta:

- [AYUDAS_JUGADORES/PROMPT-IMAGEN-MUNDREL.md](./assets/prompt-template.md)

Adapta solo el nombre del juego y el contenido mecánico.

## Resultado esperado

El resultado debe ser un prompt listo para pegar en una generadora de imágenes que produzca una ayuda panorámica 12:7, muy fiel al juego real, muy informativa y útil durante partida, con simbología incluida y pensada para novatos.