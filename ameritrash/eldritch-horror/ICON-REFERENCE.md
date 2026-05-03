# Referencia de Iconos - Eldritch Horror

## Leyenda de Símbolos y Códigos

> **Estado actual**: Usando códigos cortos `[SAB]`, `[INF]`, etc.  
> **Futuro**: Reemplazar con `![ICON-name](img/icon-name.png)` cuando haya imágenes

---

## Iconos de Habilidades

| Código | Símbolo | Nombre | Descripción |
|--------|---------|--------|-------------|
| `[SAB]` | [ | Saber | Habilidad mental: conocimiento, investigación |
| `[INF]` | ] | Influencia | Habilidad social: negociación, persuasión |
| `[OBS]` | \| | Observación | Habilidad perceptiva: detalles, búsqueda |
| `[FUE]` | } | Fuerza | Habilidad física: combate, resistencia |
| `[VOL]` | { | Voluntad | Habilidad psicológica: resistencia mental |

---

## Iconos de Mecánicas

| Código | Símbolo | Nombre | Descripción |
|--------|---------|--------|-------------|
| `[RET]` | @ | Retribución | Efecto que se resuelve al final de fase de Mitos |
| `[JUG#]` | ~ | Número de Jugadores | Cantidad de jugadores en partida |
| `[PIS]` | (ficha redonda) | Pista | Recurso de investigación |
| `[ARC]` | (ficha triangular) | Arcano | Ficha de progreso de Misterio |
| `[RUM]` | (ficha cuadrada) | Rumor | Efecto de Mito RUMOR |
| `[EXP]` | (icono de expedición) | Expedición | Encuentro de Expedición |

---

## Iconos de Recursos

| Código | Nombre | Descripción |
|--------|--------|-------------|
| `[SAL]` | Salud | Recurso físico |
| `[COR]` | Cordura | Recurso mental |
| `[BIL-T]` | Billete de Tren | Movimiento por ruta de tren |
| `[BIL-B]` | Billete de Barco | Movimiento por ruta de barco |

---

## Tipos de Cartas (por dorso)

| Código | Color | Tipo |
|--------|-------|------|
| `[MIL-A]` | Amarilla | Cartas de Mitos Etapa I |
| `[MIL-V]` | Verde | Cartas de Mitos Etapa II |
| `[MIL-Z]` | Azul | Cartas de Mitos Etapa III |
| `[ENC-AM]` | Amarilla | Encuentro América |
| `[ENC-EU]` | Verde | Encuentro Europa |
| `[ENC-OT]` | Azul | Encuentro Otros Mundos |

---

## Ejemplo de Uso

**Antes (con iconos gráficos - Ilegible en Markdown):**
```
Prueba de {. Si superas, obtén 1 Pista.
Si fallas el ~, pierdes 2 puntos de Cordura.
```

**Actual (con códigos):**
```
Prueba de [VOL]. Si superas, obtén 1 [PIS].
Si fallas el [JUG#], pierdes 2 puntos de [COR].
```

**Futuro (con imágenes):**
```
Prueba de ![ICON-vol](img/icon-vol.png). Si superas, obtén 1 ![ICON-pista](img/icon-pista.png).
Si fallas el ![ICON-jugadores](img/icon-jugadores.png), pierdes 2 puntos de ![ICON-cordura](img/icon-cordura.png).
```

---

## Búsqueda-Reemplazo (Para cuando tengas imágenes)

Si tienes archivos PNG/SVG, usar estas búsquedas para automatizar:

```
[SAB] → ![ICON-saber](img/icon-saber.png)
[INF] → ![ICON-influencia](img/icon-influencia.png)
[OBS] → ![ICON-observacion](img/icon-observacion.png)
[FUE] → ![ICON-fuerza](img/icon-fuerza.png)
[VOL] → ![ICON-voluntad](img/icon-voluntad.png)
[RET] → ![ICON-retribucion](img/icon-retribucion.png)
[JUG#] → ![ICON-jugadores](img/icon-jugadores.png)
[PIS] → ![ICON-pista](img/icon-pista.png)
[ARC] → ![ICON-arcano](img/icon-arcano.png)
[SAL] → ![ICON-salud](img/icon-salud.png)
[COR] → ![ICON-cordura](img/icon-cordura.png)
```

---

## Notas

- **Consistencia**: Estos códigos se usan en [Eldritch-Horror.md](Eldritch-Horror.md) y [FAQs-Eldritch-Horror.md](FAQs-Eldritch-Horror.md)
- **Expansibilidad**: Si añades expansiones con nuevos iconos, agrégalos aquí
- **Estandarización**: Si otros juegos comparten iconos, reutilizar este archivo
