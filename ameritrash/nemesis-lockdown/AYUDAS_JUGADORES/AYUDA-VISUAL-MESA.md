# Nemesis: Lockdown — Especificación de ayuda visual de mesa

**Propósito:** definir una ayuda imprimible de consulta rápida

**Fuente:** [manual español](../doc/ES_Nemesis_LD_Rulebook_280x280mm_bleed3mm-32-pages.pdf) y [FAQ oficial](../doc/LOCKDOWN_FAQ.pdf) de 25-03-2022

**Última validación:** 24/07/2026

---

## Objetivo

La pieza debe permitir resolver sin abrir el manual:

1. el orden completo de la ronda;
2. las dos acciones del turno;
3. movimiento, Ruido y Encuentros;
4. Energía y Oscuridad;
5. Combate y Huida;
6. supervivencia y Chequeo final;
7. las erratas que alteran reglas frecuentes.

No debe intentar sustituir las cartas de personaje, Objetos, Compartimentos o Contingencias.

---

## Formato recomendado

### Opción principal

- Una hoja A4 horizontal a dos caras.
- Cara A: ronda, turno, movimiento y Encuentros.
- Cara B: Combate, peligros, vías de escape y FAQ.
- Márgenes mínimos de 10 mm.
- Cuerpo de texto de 9 pt o mayor.

### Opción panorámica

- Una cara en proporción 12:7.
- Secuencia de ronda como bloque central dominante.
- Tres columnas más una franja inferior.
- Adecuada para generar mediante [PROMPT-IMAGEN-MUNDREL.md](./PROMPT-IMAGEN-MUNDREL.md).

---

## Jerarquía común

1. **Nivel 1:** título y secuencia 1–10.
2. **Nivel 2:** Tu turno, Mover → Ruido → Encuentro, Energía/Oscuridad.
3. **Nivel 3:** Combate, escapar, valores críticos.
4. **Nivel 4:** recordatorios FAQ.

Cada regla debe combinar:

- icono;
- verbo;
- valor;
- consecuencia.

Ejemplo:

> FUEGO · fin de turno · 1 Herida leve

---

## Cara A — Ronda y exploración

### Cabecera

```text
NEMESIS: LOCKDOWN — AYUDA DE RONDA
GANA = Objetivo + Sobrevivir + Contingencia + Contaminación
```

### Bloque A — Secuencia de ronda

```text
FASE DE LOS JUGADORES
1 ROBAR → hasta 5
2 JUGADOR INICIAL → pasa a la izquierda
3 TURNOS → 2 acciones; repetir hasta que todos pasen

FASE DE EVENTO
4 SEC → lanzar si coincide con Tiempo
5 TIEMPO → avanzar; emergencia / autodestrucción / apagón
6 RUIDO → limpiar en Secciones con Energía
7 ATAQUES → Acechadores con personajes
8 FUEGO → 1 Herida a cada Acechador
9 EVENTO → movimiento + efecto
10 BOLSA → evolución
```

Notas pequeñas:

- No pases Jugador inicial en la primera ronda.
- No retires Ruido de Pasillos de servicio en el paso 6.
- Los Acechadores con personajes no se mueven por Evento.

### Bloque B — Tu turno

```text
2 ACCIONES
Paga descartando cartas de Acción
Contaminación NO paga
1 acción + pasar = fin del turno
Tras pasar: no vuelves esta fase
Al pasar: descarta las cartas que quieras
```

Lista compacta:

```text
Mover · Cauteloso · Recoger · Intercambiar
Preparar · Disparar · Cuerpo a cuerpo
Carta de Acción · Objeto · Compartimento · Computadora
```

### Bloque C — Mover → explorar → Ruido

```text
MOVER
↓
¿Compartimento sin explorar?
SÍ → revelar Compartimento + ficha
↓
¿Destino vacío?
SÍ → tirar Ruido
NO → sin tirada
```

Resultados:

```text
1–4 → coloca Ruido
Ruido repetido → ENCUENTRO
SILENCIO → nada
SILENCIO + MUCOSIDAD → PELIGRO
PELIGRO → atrae adyacentes libres
sin adyacentes → Ruido en todos los Pasillos
```

Aviso FAQ destacado:

```text
CAUTELOSO + PELIGRO
= resuelve Peligro
+ coloca el Ruido elegido
```

### Bloque D — Encuentro

```text
1 Limpia Ruido conectado
2 Saca ficha
3 Coloca miniatura
4 Mano < número → Ataque por sorpresa

ENERGÍA → número bajo
OSCURIDAD → número alto
```

---

## Cara B — Combate y supervivencia

### Bloque E — Energía / Oscuridad

| Energía | Oscuridad |
|---|---|
| Dado de Ventaja al Disparar | Número alto en Encuentros |
| Acciones de Computadora | Efectos adicionales |
| Sin efectos de Oscuridad | Sin acciones de Computadora |
| Puede limpiarse Ruido | Ruido permanece |

Nota:

```text
Carta que solo pide Computadora
≠ acción de Computadora
No exige Energía salvo que lo indique
```

### Bloque F — Combate

```text
DISPARAR
Munición -1 → dado → Heridas → resistencia/Repliegue
Con Energía: dado de Ventaja

CUERPO A CUERPO
Contaminación +1 → dado
Fallo posible → 1 Herida grave

HUIR
Todos los Acechadores atacan → si sobrevives, mueve
```

Resistencia:

```text
Larva / Huevo → 1 Herida
Reptador / Adulto → 1 carta de sangre
Reproductor / Reina → suma 2 cartas
```

### Bloque G — Evolución de bolsa

| Ficha | Flecha visual |
|---|---|
| Larva | fuera → + Adulto |
| Reptador | fuera → + Reproductor |
| Adulto | vuelve → tiradas de Ruido |
| Reproductor | vuelve → tiradas de Ruido |
| Reina | personaje en Nido → aparece y Encuentro |
| Reina | Nido vacío/no descubierto → + Huevo y vuelve |
| Blanco | vuelve → + Adulto |

Aviso:

```text
REINA EN EL NIDO
NO devuelve su ficha a la bolsa
```

### Bloque H — Valores críticos

```text
MANO INICIAL          5
ACCIONES              2
3 LEVES               1 GRAVE
3 GRAVES + 1 Herida   MUERTE
13.º FUEGO            EXPLOSIÓN
11.º FALLO            DESTRUCCIÓN
```

### Bloque I — Escapar

```text
CUARENTENA
Tiempo 08 / emergencia
tirada de Ruido
no protege de destrucción

SEC
Tiempo sobre ficha
1 personaje
resolver en Evento

BÚNKER
Salida + Puerta abierta
sin Acechador
Rover o Traje
```

Puerta principal:

```text
primera muerte / Llave / Autodestrucción roja
```

### Bloque J — Chequeo final

```text
1 CONTINGENCIA
2 CONTAMINACIÓN
3 OBJETIVO
```

### Bloque K — FAQ de mesa

```text
OBJETOS → no sobre otros salvo permiso
HUEVOS → 1 Herida destruye 1
ARCHIVO → +2 Conocimiento y activar; una vez
INFECTADO + Larva → muerte + Reptador
REPOSITORIO → todos preparan con 1 Componente
```

---

## Sistema visual

### Colores

- Negro carbón: fondo.
- Blanco: texto principal.
- Cobre/naranja: estructura y números de ronda.
- Azul cian: Energía.
- Rojo: Oscuridad, Ataque, Fuego y alertas.
- Amarillo: Ruido y precaución.

El color nunca debe ser el único identificador.

### Iconos prioritarios

- Tiempo;
- Energía activa e inactiva;
- Ruido;
- Fuego;
- Fallo;
- Puerta;
- Contaminación;
- Herida leve y grave;
- Computadora;
- SEC;
- Larva, Reptador, Adulto, Reproductor y Reina.

### Tipografía

- Máximo dos familias.
- Sans serif condensada para títulos.
- Sans serif de alta legibilidad para cuerpo.
- Mayúsculas solo en títulos, fases y alertas.

---

## Restricciones de densidad

- Máximo 12 palabras por viñeta.
- Máximo 7 líneas por módulo, salvo la secuencia de ronda.
- Ningún texto sobre ilustración o textura fuerte.
- Flechas sencillas y sin cruces.
- Evitar repetir reglas presentes en las cartas de personaje.
- Si falta espacio, eliminar decoración antes que contenido mecánico.

---

## Control previo a impresión

- La secuencia 1–10 está completa y ordenada.
- SEC aparece antes de avanzar Tiempo.
- Ataques aparecen antes que daño por Fuego.
- Movimiento de Evento aparece antes que su efecto.
- La Reina incorpora la errata oficial.
- Peligro no queda anulado por Movimiento cauteloso.
- Contaminación no figura como pago.
- Energía y Oscuridad se distinguen en escala de grises.
- Se lee a distancia de brazo.
- Los nombres coinciden con la edición española.

---

[Resumen de turno](./RESUMEN-TURNO.md) · [Guía para novatos](./RESUMEN-Y-GUIA-NOVATO.md) · [FAQ oficial resumida](./FAQ-OFICIAL-RESUMIDA.md) · [Prompt de imagen](./PROMPT-IMAGEN-MUNDREL.md)
