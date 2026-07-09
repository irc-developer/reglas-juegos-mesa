# Cthulhu: Dark Providence - Prompt para ayuda visual accesible

**Objetivo**: generar una ayuda visual imprimible, clara y util durante partida  
**Formato recomendado**: A4 horizontal o Carta horizontal, una cara  
**Fuente mecanica**: [AYUDA-VISUAL-MESA.md](./AYUDA-VISUAL-MESA.md), [RESUMEN-TURNO.md](./RESUMEN-TURNO.md) y [FAQs-Dark-Providence.md](../FAQs-Dark-Providence.md)

---

## Prompt principal

Crea una ayuda visual horizontal de una pagina para un juego de mesa de horror lovecraftiano, lealtades ocultas, control de ciudades y construccion de mazo titulado "Dark Providence - Ayuda de mesa".

Debe ser una referencia de partida, no una portada ni una ilustracion decorativa. Prioriza legibilidad, contraste y consulta rapida por encima de la ambientacion. Usa composicion editorial modular con secciones bien separadas, flechas simples y tablas compactas.

La ayuda debe incluir estos bloques:

1. Turno: 2 acciones + acciones gratuitas, robar hasta 5.
2. Regla critica: si vas a Reclamar, no hagas acciones gratuitas antes.
3. Reclamar: primera accion normal, mayoria, al menos 1 cubo propio, sin Bloqueo.
4. Influencia: anadir a un unico objetivo; Agentes cuentan siempre para Ciudad y carta revelada.
5. Asesinar: mismo espacio, Poder suficiente, carta habilitadora no aporta Poder.
6. Portal: Agente en Ciudad sin Portal, Poder suficiente, colocar Portal y hacer Prueba de Cordura.
7. Cordura: tercera Locura revela Lealtad; Investigador/Disidente disparan final, Sectario sigue revelado.
8. Final: umbrales por jugadores, Locura, asesinato de Agente principal, medidor al final, Profundos.
9. Puntuacion por Lealtad: Investigador, Sectario, Disidente.
10. Recordatorios FAQ: 6 cubos iniciales disponibles, jugador inicial coloca ultimo, Mitos no se reponen al reclamar, Profundos asesinados vuelven al suministro personal.

Estilo visual: horror de investigacion de los anos 20, mapas urbanos, papel envejecido muy claro, tinta negra, acentos verde profundo, magenta oscuro y ambar. No copies arte oficial, logotipos, cartas, iconos exactos ni marcos oficiales. Los iconos deben ser originales, simples y funcionales.

---

## Reglas de accesibilidad

- Alto contraste real: texto oscuro sobre fondo claro.
- Debe seguir siendo legible en escala de grises.
- No uses texto sobre ilustraciones, humo, manchas o textura fuerte.
- Tamano minimo recomendado: 9 pt en A4, 8 pt absoluto en notas.
- No uses codificacion solo por color; cada color debe ir acompanado de etiqueta textual.
- Maximo 2 familias tipograficas: titulo atmosferico y cuerpo sans serif muy legible.
- Evita parrafos: usa frases de 2 a 8 palabras y listas cortas.
- Manten margenes amplios y separacion clara entre bloques.
- Flechas simples, sin cruces.
- Cada icono debe tener texto al lado.

---

## Layout sugerido

```text
+----------------------------------------------------------+
| DARK PROVIDENCE - AYUDA DE MESA                          |
+---------------+------------------+-----------------------+
| TURNO         | RECLAMAR         | INFLUENCIA / FAQ       |
+---------------+------------------+-----------------------+
| ASESINAR      | PORTALES         | CORDURA                |
+---------------+------------------+-----------------------+
| FINAL Y DISPARADORES             | PUNTUACION POR LEALTAD |
+----------------------------------+-----------------------+
```

---

## Texto mecanico compacto para la imagen

```text
TURNO
2 acciones + gratuitas
Luego roba hasta 5
Reclamar primero: sin gratuitas antes

RECLAMAR
1a accion normal
Mayoria + 1 cubo propio
Sin Bloqueo
Tus cubos al Limbo

INFLUENCIA
Anadir: 1 unico objetivo
Recuperar: cualquier combinacion
Agentes siempre cuentan
Ciudad + carta revelada

ASESINAR
Agente en misma Ciudad
Carta habilita
Poder >= valor Ciudad
Carta habilitadora no suma

PORTAL
Ciudad sin Portal
Poder >= valor Portal
Coloca Control
Prueba de Cordura

CORDURA
3a Locura revela
Sectario sigue
Investigador/Disidente: final

FINAL
2j 33 / 3j 30 / 4j 26 / 5j 22
Locura, principal asesinado
Ritual/Investigacion al final
Profundos con los 8 en juego

GANADOR
Elimina Lealtad del peor
Restantes: mas PV
Empate: mas Mitos
```

---

## Control de calidad antes de usar

- Se lee a distancia de brazo.
- Los textos no dependen de color.
- La regla "sin gratuitas antes de Reclamar" aparece en el bloque de turno.
- Profundos y Mitos no contradicen la FAQ.
- La ayuda sirve en mesa sin sustituir la guia de novatos.
