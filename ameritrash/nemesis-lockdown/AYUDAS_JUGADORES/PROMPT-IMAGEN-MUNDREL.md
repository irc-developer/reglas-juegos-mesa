# Nemesis: Lockdown — Prompt para ayuda visual de ronda

## Objetivo

Generar una ayuda visual horizontal en proporción 12:7 para **Nemesis: Lockdown**, pensada para explicar la ronda completa a jugadores novatos y resolver las consultas más frecuentes durante la partida.

La ayuda debe condensar la secuencia de ronda, el turno del jugador, movimiento y Ruido, Encuentros, Energía y Oscuridad, supervivencia y las erratas más relevantes sin convertirse en un reglamento en miniatura.

**Fuentes mecánicas revisadas:**

- `doc/ES_Nemesis_LD_Rulebook_280x280mm_bleed3mm-32-pages.pdf`
- `doc/LOCKDOWN_FAQ.pdf` — FAQ oficial de 25-03-2022

---

## Prompt listo para pegar

Crea una ayuda visual panorámica horizontal en proporción exacta **12:7** para el juego de mesa **Nemesis: Lockdown**. Debe ser una hoja de referencia de ronda para jugadores novatos, muy legible, densa pero ordenada y útil durante la partida. No quiero una portada, un póster cinematográfico ni una escena de terror decorativa: quiero una ayuda funcional que parezca un componente oficial o semioficial del juego.

Conserva el lenguaje visual real de Nemesis: Lockdown:

- fondo negro carbón y metal industrial oscuro;
- marcos tecnológicos de cobre, naranja quemado y rojo de alarma;
- azul cian para Energía activa y rojo para Oscuridad, peligro o Energía inactiva;
- paneles negros o verde oliva muy oscuro;
- líneas de circuito, esquinas técnicas y desgaste físico muy sutil;
- títulos blancos en mayúsculas, tipografía sans serif condensada y muy legible;
- iconos reales o extremadamente fieles al juego para Tiempo, Energía, Ruido, Fuego, Fallo, Puerta, Contaminación, Herida, SEC, Computadora y tipos de Acechador nocturno.

Usa las imágenes adjuntas como ancla visual principal. Respeta sus colores, iconografía, símbolos, componentes y jerarquía editorial. La ilustración ambiental debe ocupar como máximo un 10 % de la pieza y nunca debe competir con las reglas.

### Composición

Organiza la imagen mediante una retícula modular de tres columnas y una franja inferior:

1. **Cabecera compacta:** título «NEMESIS: LOCKDOWN — AYUDA DE RONDA» y una línea con las tres condiciones de victoria.
2. **Columna izquierda:** «TU TURNO» y «ACCIONES».
3. **Columna central dominante:** «SECUENCIA DE RONDA», numerada del 1 al 10, con una flecha continua de arriba abajo.
4. **Columna derecha:** «MOVER → RUIDO → ENCUENTRO» y «ENERGÍA / OSCURIDAD».
5. **Franja inferior:** «SOBREVIVIR Y ESCAPAR», «VALORES CRÍTICOS» y «FAQ / NO LO OLVIDES».

La secuencia de ronda debe ser el bloque más grande. Emplea iconos grandes, números inequívocos, flechas sin cruces, microtablas y frases de consulta rápida. No uses párrafos dentro de la imagen.

### Texto mecánico exacto que debe aparecer

#### CABECERA — PARA GANAR

**OBJETIVO cumplido + SOBREVIVIR + superar CONTINGENCIA y CONTAMINACIÓN**

Supervivencia: **Cuarentena / contenedor SEC / Búnker**

#### TU TURNO

- Roba hasta tener **5 cartas** al inicio de la fase.
- En tu turno: **2 acciones**.
- Luego actúa el siguiente jugador; repetid hasta que todos pasen.
- Si haces solo 1 acción, la segunda es **PASAR**.
- Tras pasar, no haces más acciones esta fase.
- Al pasar puedes descartar cualquier número de cartas, incluidas las de Contaminación.
- Terminar tu turno en Fuego: **1 Herida leve**; si pasas, solo una vez esa ronda.

#### ACCIONES

- **Básicas:** Mover, Movimiento cauteloso, Recoger objeto voluminoso, Intercambiar, Preparar, Disparar, Cuerpo a cuerpo.
- **También:** carta de Acción, carta de Objeto, acción de Compartimento y acción de Computadora.
- Paga el coste descartando cartas de Acción de la mano.
- **Contaminación no paga costes.**
- Carta de Acción jugada: descártala y paga además su coste.
- En Combate: Mover se convierte en **Huir**.
- Revisa los símbolos **Solo en Combate / Nunca en Combate**.

#### SECUENCIA COMPLETA DE RONDA

Usa dos colores de fase, pero conserva la numeración continua:

**FASE DE LOS JUGADORES**

1. **ROBAR:** todos roban hasta 5 cartas.
2. **JUGADOR INICIAL:** pasa la ficha a la izquierda; no se pasa en la primera ronda.
3. **TURNOS:** 2 acciones por jugador, en sentido horario, hasta que todos pasen.

**FASE DE EVENTO**

4. **SEC:** revela y lanza los contenedores cuya ficha coincida con la posición actual del Tiempo.
5. **TIEMPO:** avanza 1; resuelve Autodestrucción, Procedimiento de emergencia y Apagón.
6. **RUIDO:** en Secciones con Energía, retira el Ruido de pasillos no conectados a personajes. Nunca retires aquí el Ruido de Pasillos de servicio.
7. **ATAQUES:** cada Acechador nocturno que comparta compartimento con un personaje ataca.
8. **FUEGO:** cada Acechador nocturno en un compartimento con Fuego sufre 1 Herida.
9. **EVENTO:** mueve los tipos indicados que no estén con personajes; después resuelve el efecto.
10. **BOLSA:** saca 1 ficha y resuelve su evolución.

Al final: **NUEVA RONDA → vuelve al paso 1**.

#### EVOLUCIÓN DE LA BOLSA

Muestra una microtabla con silueta e icono de cada tipo:

- **Larva:** retírala de la bolsa → añade 1 Adulto.
- **Reptador:** retíralo → añade 1 Reproductor.
- **Adulto / Reproductor:** devuelve la ficha → todos los personajes que no estén en Combate hacen una tirada de Ruido.
- **Reina — corrección FAQ:** si hay un personaje en el Nido, coloca allí la Reina y resuelve un Encuentro; **no devuelvas su ficha a la bolsa**. Si no hay personajes o el Nido no está descubierto, añade 1 Huevo y devuelve la ficha de Reina.
- **En blanco:** devuelve la ficha → añade 1 Adulto.

#### MOVER → EXPLORAR → RUIDO

Representa este flujo con flechas:

**MOVER → entrar → explorar si está bocabajo → resolver ficha → ¿compartimento vacío?**

- Si estaba sin explorar: revela compartimento y ficha; fija Objetos y resuelve el símbolo.
- Si el destino está vacío: haz tirada de Ruido.
- Si hay personaje o Acechador nocturno: no hay tirada de Ruido.
- Resultado 1–4: coloca Ruido en el pasillo correspondiente.
- Si ese pasillo ya tenía Ruido: **ENCUENTRO**.
- Silencio + Mucosidad = **Peligro**.
- Peligro: atrae Acechadores adyacentes libres; si no hay, llena de Ruido todos los pasillos conectados.
- **FAQ:** si Peligro se revela durante Movimiento cauteloso, resuelve Peligro y además coloca el Ruido del Movimiento cauteloso.

#### ENCUENTRO Y COMBATE

- Encuentro: limpia el Ruido de todos los pasillos conectados → saca ficha → coloca miniatura.
- Ataque por sorpresa si **cartas en mano < número de la ficha**.
- Con Energía usa el número bajo; en Oscuridad usa el alto.
- Entran en tu compartimento por movimiento: hay Combate, no Encuentro.
- **Huir:** cada Acechador presente te ataca antes de moverte.
- **Disparar con Energía:** usa dado de Ventaja.
- Cuerpo a cuerpo: recibes 1 Contaminación; un fallo puede causar 1 Herida grave.

#### ENERGÍA / OSCURIDAD

Divide el bloque en dos mitades claramente contrastadas:

**ENERGÍA — azul cian**

- Dado de Ventaja al Disparar.
- Acciones de Computadora disponibles.
- No hay Oscuridad.
- Parte del Ruido se retira en Evento.

**SIN ENERGÍA — rojo**

- Estás en Oscuridad.
- Encuentro: número alto de la ficha.
- Resuelve efectos adicionales de Oscuridad.
- Las Computadoras no funcionan para acciones de Computadora.

Añade esta precisión FAQ en letra breve:

**Una carta que solo exija estar en un compartimento con Computadora no exige Energía, salvo que la propia carta lo indique.**

#### SOBREVIVIR Y ESCAPAR

Muestra tres rutas con iconos:

- **CUARENTENA:** disponible desde Tiempo 08 o por Procedimiento de emergencia; no protege si el complejo se destruye.
- **SEC:** entra cuando el Tiempo esté sobre su ficha; 1 personaje por contenedor; se resuelve en Evento. Un mismo SEC puede lanzarse varias veces si así lo indican sus fichas.
- **BÚNKER:** estar en Salida + Puerta principal abierta + sin Acechador + Rover o Traje de supervivencia.

Puerta principal: se abre con **primera muerte / Llave / Autodestrucción roja**.

#### VALORES CRÍTICOS

Preséntalos como chips o indicadores grandes:

- Mano al inicio: **5**
- Acciones por turno: **2**
- **3 Heridas leves = 1 Herida grave**
- Con 3 Heridas graves, cualquier Herida adicional = **MUERTE**
- Al colocar el **13.º Fuego**: el complejo explota
- Al colocar el **11.º Fallo**: el complejo se destruye
- Fallo: bloquea acción de Compartimento y Computadora; **Registrar sí funciona**

#### FAQ / NO LO OLVIDES

- Los Objetos no se usan sobre otro personaje salvo que el Objeto lo permita: primero hay que Intercambiarlo.
- Cualquier Objeto que inflija Heridas puede destruir Huevos: **1 Herida = 1 Huevo**.
- Archivo: mira una Contingencia no activa, gana 2 Conocimiento y activa tu ficha; solo una vez por personaje.
- Al Escanear «INFECTADO» teniendo ya una Larva: el personaje muere y aparece 1 Reptador.
- Si el Procedimiento de emergencia acaba la partida, resuélvelo como el final del Tiempo; una Autodestrucción activa destruye el complejo.

### Jerarquía y legibilidad

- Frases de entre 2 y 12 palabras.
- Nada de texto diminuto ni columnas de prosa.
- Cuerpo mínimo visual equivalente a 9 pt en una impresión A4 horizontal.
- Alto contraste y lectura correcta en escala de grises.
- No codifiques ninguna regla solo mediante color: acompaña cada color con icono y etiqueta.
- Máximo dos familias tipográficas.
- Todas las etiquetas y reglas deben estar en español.
- Los nombres propios deben coincidir con la edición española: Acechador nocturno, Reptador, Reproductor, Compartimento, Pasillo, Fuego, Fallo, Ruido, Energía, Oscuridad, Contaminación, Contingencia y Sistema de Envío de Carga.

---

## Prompt con imágenes adjuntas

Usa las imágenes adjuntas del manual y los componentes de **Nemesis: Lockdown** como referencia principal y prioritaria. Crea una ayuda de ronda horizontal 12:7 que parezca pertenecer al mismo producto físico.

Conserva:

- los marcos industriales negros con circuitos de cobre y naranja;
- la codificación azul cian de Energía y roja de Oscuridad o peligro;
- la iconografía exacta de Ruido, Fuego, Fallo, Puerta, Tiempo, Energía y Acechadores nocturnos;
- las siluetas y nombres españoles de Larva, Reptador, Adulto, Reproductor y Reina;
- el acabado de panel metálico oscuro y la jerarquía tipográfica del manual.

Reorganiza esas referencias como una infografía, no como una reproducción de una página del manual. La secuencia de ronda 1–10 debe ocupar el centro; el flujo Mover → Ruido → Encuentro debe leerse de un vistazo; Energía y Oscuridad deben distinguirse incluso sin depender solo del color.

No inventes iconos incompatibles, nombres nuevos, acciones nuevas ni cifras. Si una referencia visual contradice el texto del prompt, prioriza el texto mecánico, porque ya incorpora las correcciones de la FAQ oficial.

---

## Referencias ideales para adjuntar

Adjunta, preferiblemente, recortes claros y sin perspectiva de:

- **manual, página 12:** carta de Ayuda y secuencia oficial de ronda;
- **manual, páginas 14–15:** iconos de acciones, costes y restricciones de Combate;
- **manual, página 17:** dado de Ruido y fichas de Exploración;
- **manual, página 19:** iconos de Ruido, Mucosidad, Fuego, Fallo y Puertas;
- **manual, página 20:** fichas y símbolos de los Acechadores nocturnos;
- **manual, página 24:** fichas de Energía activa/inactiva y ejemplo de Oscuridad;
- una foto cenital del tablero completo;
- una foto clara de una carta de Ayuda original;
- una captura de los contenedores SEC, el Búnker y la consola de Tiempo.

Prioridad recomendada: carta de Ayuda oficial → iconografía → tablero → páginas de estilo editorial → ilustraciones ambientales.

---

## Negative prompt

Evitar:

- formato vertical, cuadrado, tarot o A4 vertical;
- proporción distinta de 12:7;
- póster cinematográfico o portada;
- monstruo gigante o astronauta como foco principal;
- fanart libre;
- ilustración ambiental dominante;
- interfaz futurista genérica;
- estética cyberpunk de neón;
- hologramas de videojuego;
- exceso de rojo que reduzca la legibilidad;
- fondos con humo, sangre o textura bajo el texto;
- texto largo en párrafos;
- letras diminutas, deformadas o inventadas;
- traducción al inglés;
- iconos genéricos cuando exista un símbolo real en las referencias;
- cambiar Reptador por «Creeper» o Reproductor por «Breeder»;
- omitir pasos de la fase de Evento;
- mezclar el orden de los pasos 4–10;
- mostrar que la ficha de Reina vuelve a la bolsa cuando aparece en el Nido;
- indicar que Movimiento cauteloso anula Peligro;
- indicar que Contaminación sirve para pagar acciones;
- composición caótica;
- flechas cruzadas;
- bajo contraste;
- mockup de caja;
- manos humanas;
- logotipos añadidos;
- sellos promocionales;
- texto cortado por los bordes.

---

## Variante más concreta

Infografía horizontal 12:7 titulada «NEMESIS: LOCKDOWN — AYUDA DE RONDA», fiel al manual español: fondo negro metálico, circuitos naranja y cobre, alertas rojas y Energía azul cian. Retícula de tres columnas, secuencia central dominante numerada 1–10: robar a 5, pasar Jugador inicial, turnos de 2 acciones, lanzar SEC, avanzar Tiempo, retirar Ruido, ataques, daño por Fuego, Evento y evolución de bolsa. Columna izquierda con turno, costes y acciones; columna derecha con Mover → Ruido → Encuentro y Energía frente a Oscuridad; franja inferior con Cuarentena, SEC, Búnker, valores 5 / 2 / 3 leves / 13.º Fuego / 11.º Fallo y recordatorios FAQ. Iconografía real tomada de las referencias, español correcto, texto mínimo, contraste alto, apariencia de componente oficial premium, sin póster ni ilustración dominante.

---

## Ajustes recomendados

- **Proporción:** 12:7 horizontal.
- **Resolución mínima:** 3600 × 2100 px.
- **Detalle:** alto.
- **Fidelidad al prompt:** alta.
- **Peso de referencias:** alto para iconos y estilo; medio para ilustración.
- **Estilo:** `board game player aid`, `editorial reference sheet`, `premium tabletop infographic`.
- **Texto en imagen:** breve y funcional.
- **Variaciones:** generar primero una versión sin arte ambiental y añadirlo solo si queda espacio.
- **Impresión:** comprobar legibilidad en A4 horizontal y a distancia de brazo.

---

## Nota de uso

La FAQ oficial está en inglés, pero sus correcciones ya se han integrado en el texto español del prompt. La corrección más importante es la evolución de la ficha de Reina: cuando aparece en el Nido por haber allí un personaje, su ficha **no vuelve a la bolsa**.

Los generadores de imagen pueden deformar texto extenso. Si la primera generación no respeta todas las frases, úsala como base de composición y vuelve a generar cada módulo por separado, o reemplaza después la tipografía manteniendo exactamente el texto mecánico de este archivo.
