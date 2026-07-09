# Cthulhu: Dark Providence - Ayuda visual de mesa

**Proposito**: especificacion para una ayuda imprimible de una pagina  
**Fuente**: `resumendk.pdf`, reglamento ES p. 24, secciones completas relacionadas y aclaraciones BGG del disenador  
**Ultima validacion**: 09/07/2026

---

## Que debe contener

La hoja visual debe cubrir las reglas que mas interrumpen la partida:

1. Asesinar.
2. Cerrar o abrir Portal.
3. Prueba de Cordura.
4. Desencadenantes del final.
5. Puntuacion por Lealtad.
6. Determinar ganador.
7. Aclaraciones FAQ que cambian mesa: Reclamar sin gratuitas antes, Agentes como Influencia, Profundos, R'lyeh.

## Bloque 0 - Turno y Reclamar

1. Turno: 2 acciones + acciones gratuitas; despues roba hasta 5.
2. Si vas a Reclamar, no hagas acciones gratuitas antes.
3. Reclamar requiere: primera accion normal, mayoria, al menos 1 cubo propio y sin Bloqueo.
4. Anadir Influencia coloca cubos en 1 unico objetivo, salvo excepcion de carta.
5. Agentes propios y rivales cuentan siempre como Influencia en Ciudad y carta revelada.

---

## Bloque 1 - Asesinar

Iconos clave: <img src="../img/icons/asesinar.png" alt="[ASE]" width="18"> asesinar, <img src="../img/icons/poder.png" alt="[POD]" width="18"> Poder.

1. Agente propio en la misma Ciudad que un Agente rival.
2. Juega carta que permita asesinar con ese Agente o con cualquier Agente.
3. Iguala/supera valor de control de la Ciudad con Poder de Agentes presentes + cartas extra.
4. La carta que habilita la accion no aporta Poder.
5. Toma la ficha asesinada y ponla en Cripta. El rival aniquila la carta.

Recordatorio lateral:

- Resucitados no pueden ser asesinados salvo efecto.
- Agente principal: solo si el jugador no tiene otros Agentes y tiene 5 PV o mas.
- Profundos pueden ser asesinados; vuelven al suministro personal del propietario.
- Tener solo Profundos no protege al Agente principal.

---

## Bloque 2 - Cerrar o abrir Portal

Iconos clave: <img src="../img/icons/portal-cerrado.png" alt="[CER]" width="18"> cerrar, <img src="../img/icons/portal-abierto.png" alt="[ABR]" width="18"> abrir, <img src="../img/icons/poder.png" alt="[POD]" width="18"> Poder.

1. Agente propio en Ciudad sin Portal.
2. Juega carta que permita cerrar/abrir.
3. Iguala/supera valor de Portal con Poder de Agentes presentes + cartas extra.
4. La carta que habilita la accion no aporta Poder.
5. Coloca Portal por la cara correspondiente y tu Control encima.
6. Haz Prueba de Cordura.

Recordatorio lateral:

- Si lo hace un Agente reclutado y roba Locura, se aniquila.
- Esa Locura tambien cuenta para el limite de 3 Locuras del jugador.

---

## Bloque 3 - Cordura

Iconos clave: <img src="../img/icons/cordura.png" alt="[COR]" width="18"> Prueba de Cordura, <img src="../img/icons/locura.png" alt="[LOC]" width="18"> Locura.

Haz Prueba de Cordura al reclamar carta con icono de Cordura o al abrir/cerrar Portal:

1. Roba 1 ficha de la bolsa.
2. Ponla en tu tablero.
3. Con 3 Locuras:
   - Sectario: revela y sigue.
   - Investigador/Disidente: final de partida.

Recordatorio lateral:

- R'lyeh exige Prueba de Cordura cada vez que se usa.

---

## Bloque 4 - Final de partida

- Umbral de PV: 2j 33 / 3j 30 / 4j 26 / 5j 22.
- 3ª Locura revelando Investigador o Disidente.
- Agente principal asesinado.
- Ritual o Investigacion llega al final.
- Profundos: accion jugada con los 8 en juego.

Nota: Profundos asesinados vuelven al suministro personal; Profundos aniquilados se retiran de la partida.

---

## Bloque 5 - Puntuacion rapida

### General

- +3 PV si Lealtad no revelada.
- PV de cartas/Agentes aplicables.
- Mitos con FINAL DE LA PARTIDA.

### Investigadores

- Medidor Investigacion.
- Portales cerrados propios.
- Agentes con PV de Investigador.

### Sectarios

- Medidor Ritual.
- 1 PV por Agente en Cripta.
- Portales abiertos propios.
- Mitos con PV de Sectario.
- 1 PV por Resucitado.
- +8 PV por Profundos si reclamados y los 8 estan en juego.

### Disidentes

- -3 PV si se revelaron antes de puntuar.
- Medidor de su antigua Lealtad.
- Portales cerrados y abiertos propios.
- 1 PV por Agente en Cripta.
- No PV de faccion por cartas/Agentes.
- Nunca tienen companeros, aunque Impostor cambie su etiqueta.

---

## Bloque 6 - Ganador

1. Elimina la Lealtad del jugador con menos PV.
2. Entre los restantes, gana quien tenga mas PV.
3. Empate por arriba: mas Mitos, luego prioridad de Lealtad, luego compartida.

---

## Recomendacion de formato

- Una pagina horizontal.
- Dos columnas: acciones a la izquierda, puntuacion a la derecha.
- Colores discretos por Lealtad:
  - Investigador: rosa/magenta.
  - Sectario: verde.
  - Disidente: gris/ambar.
- Mantener texto corto; esta ayuda es para mesa, no para aprender desde cero.

---

## Accesibilidad y legibilidad

- Alto contraste: texto oscuro sobre fondo claro.
- La ayuda debe funcionar en escala de grises; no codificar informacion solo por color.
- Cada icono debe ir acompanado por texto o codigo corto.
- Evitar fondos con textura fuerte detras de reglas.
- Tamano minimo: 9 pt en A4/Carta; 8 pt solo para notas.
- Frases de 2-8 palabras en la pieza visual, sin parrafos largos.
- Mantener margenes amplios y separacion clara entre bloques.
- Flechas simples y sin cruces.
- Usar maximo 2 familias tipograficas.

---

## Fuente visual

El archivo [resumendk.pdf](../fuentes/resumendk.pdf) contiene una hoja-resumen en ingles y sin texto extraible. Esta version traduce y corrige su contenido contra el reglamento ES y las aclaraciones BGG.

Para generar una version grafica, usar [PROMPT-IMAGEN-MUNDREL.md](./PROMPT-IMAGEN-MUNDREL.md).
