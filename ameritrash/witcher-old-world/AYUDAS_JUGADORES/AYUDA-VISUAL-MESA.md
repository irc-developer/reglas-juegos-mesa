# The Witcher: El Viejo Mundo — Especificación de ayuda visual de mesa

## Objetivo

Crear una referencia vertical, imprimible y de lectura inmediata que permita resolver el turno y el combate sin abrir la guía. No debe enseñar todo el juego desde cero ni incluir texto narrativo.

**Fuente mecánica**: manual local, pp. 9-29 y 35-36.

---

## Formato recomendado

La información completa resulta demasiado densa para una sola tarjeta pequeña. Se recomiendan dos salidas coordinadas:

1. **Versión de una página**: A4 o Carta vertical, una cara.
2. **Versión de dos tarjetas**:
   - **Tarjeta A — Turno del jugador**
   - **Tarjeta B — Combate**

Ambas deben usar las mismas etiquetas, colores funcionales y orden de lectura.

---

## Jerarquía visual común

1. Título breve.
2. Objetivo en una franja superior.
3. Flujo principal numerado con flechas verticales.
4. Cajas laterales para costes y límites.
5. Franja inferior de recordatorios críticos.

Usar frases de 2-8 palabras, números grandes, flechas claras y no más de dos niveles tipográficos por bloque.

---

## Versión 1 — Una página vertical

### Cabecera

**THE WITCHER: EL VIEJO MUNDO**  
**AYUDA DE TURNO Y COMBATE**

### Objetivo

**4 TROFEOS → VICTORIA**  
**El último debe venir de un combate**

### Bloque A — Turno

```text
I. MOVER Y ACTUAR
Mover → Acción local / Póquer / Misión → Repetir o seguir

II. ELEGIR 1
Combatir | Meditar | Explorar

III. CARTAS
Descartar opcional → Robar hasta 3 → Obtener 1 obligatoria
```

### Bloque B — Movimiento

```text
1 carta del Terreno
O 2 cartas cualesquiera
O 1 carta + 1 Oro
O 1 Comodín
→ Localización conectada
```

Aviso destacado: **Muévete antes de usar una Acción de Localización.**

### Bloque C — Decisión de Fase II

| Opción | Recordatorio corto |
|---|---|
| **Combatir** | Monstruo o brujo en tu Localización |
| **Meditar** | Atributo 5 + trofeo disponible |
| **Explorar** | Ciudad o Tierras Salvajes |

### Bloque D — Fase III

```text
Conserva máximo 3 → Roba hasta 3
→ Obtén 1 carta obligatoriamente
Coste = descartes de mano
Derecha -1 | Izquierda +1
```

### Bloque E — Combate

```text
1. Pociones / Especialidad / efectos
2. Combo por colores
3. Daño → Escudo → efectos
4. Roba: Ataque + modificadores
```

### Bloque F — Daño

```text
A BRUJO:
Escudo → Mazo → Mano → Noqueado

A MONSTRUO:
1 Daño = -1 carta de Reserva de Vida
```

### Bloque G — Monstruo

```text
Rastro: empiezas tú
Sin Rastro: empieza el monstruo
Turno: elegir Embestida/Mordisco → revelar → aplicar
```

### Franja de límites

```text
MANO 7 | POCIONES 4 | USOS MÁX. = ALQUIMIA
ESCUDO ≤ DEFENSA | ACCIÓN LOCAL 1×/TURNO
MOVER ANTES DE ACTUAR | MEDITAR NO CIERRA PARTIDA
```

---

## Versión 2 — Dos tarjetas coordinadas

### Tarjeta A — Turno del jugador

**Cara única vertical**

1. Objetivo.
2. Fases I, II y III.
3. Costes de movimiento.
4. Caja de decisión Combatir/Meditar/Explorar.
5. Flujo de compra y modificadores del mercado.
6. Recordatorios:
   - mover antes de Acción local;
   - Acción local 1 vez por turno;
   - obtener carta es obligatorio;
   - mano máxima 7;
   - Póquer bloquea combatir contra ese brujo.

### Tarjeta B — Combate

**Cara única vertical**

1. Preparación de Mazo de Vida.
2. Preparación del monstruo y efecto del Rastro.
3. Turno de Brujo en 4 pasos.
4. Orden de Daño.
5. Turno de monstruo.
6. Miniresultado:
   - derrotar;
   - ahuyentar;
   - derrota absoluta;
   - atacante/defensor.
7. Recordatorios:
   - Escudo ≤ Defensa;
   - 4 Pociones poseídas;
   - usos máximos por combate = Alquimia;
   - Fatiga tras trofeo;
   - reconstruir mazos y restaurar Escudo.

---

## Sistema visual

- **Fondo**: pergamino claro y mate, con textura muy suave.
- **Paneles**: cuero oscuro, piedra o metal envejecido solo en bordes.
- **Acentos**:
  - azul grisáceo para movimiento;
  - dorado apagado para recursos y entrenamiento;
  - rojo oscuro para Daño;
  - verde alquímico para Pociones;
  - marfil para texto principal.
- **Tipografía**: serif robusta para títulos y sans serif de alta legibilidad para reglas.
- **Iconos**: símbolos genéricos y originales, no copias de los iconos oficiales.
- **Decoración**: huellas, mapas, frascos y marcas de espada como detalles secundarios, nunca detrás del texto.

---

## Restricciones de densidad

- Una página: máximo aproximado de 90-120 palabras visibles más etiquetas.
- Cada tarjeta: máximo aproximado de 55-70 palabras visibles.
- Ningún párrafo.
- Máximo 10 recordatorios en la página y 5 por tarjeta.
- No incluir preparación completa, reglas de Póquer, texto de especialidades ni tablas extensas de resultados.

---

## Control previo a impresión

- Legible a distancia de brazo.
- Contraste suficiente en color y escala de grises.
- Flechas sin cruces.
- El flujo principal se entiende en menos de 10 segundos.
- No hay texto inferior a 8 pt en A4 ni inferior a 7 pt en tarjeta.
- Los textos coinciden con [RESUMEN-TURNO.md](./RESUMEN-TURNO.md).
