# Contenido Original - Eldritch Horror

## Archivo Centralizado de Contenido Crudo

**Fuente principal**: Manual original - Edición 2008 - Fantasy Flight Games  
**Distribuidor**: Fantasy Flight Games  
**Tipo**: Almacenamiento centralizado de contenido sin procesar (Base + Expansiones)  
**Última sincronización**: 20/03/2026

---

## Propósito

Este archivo contiene **todo el contenido crudo** de Eldritch Horror: juego base y todas las expansiones, sin modificaciones. Centraliza en un único lugar la fuente de verdad original para auditoría, validación y preservación.

**Uso autorizado:**
- Referencia para verificar cambios contra fuente original
- Resolución de ambigüedades en documentación procesada
- Base para expansiones cuando se agreguen nuevas
- Validación de precisión en Entendimiento y Redacción
- Preservación completa de contenido oficial

**NO se debe usar para:**
- Copia directa a documentos procesados sin análisis (Lectura → Entendimiento → Redacción)
- Referencias en guías de juego (usar documentos procesados específicos)
- Distribución sin atribución de fuente

---

## Estructura de Archivo

El contenido se organiza por:

### 📄 Base Game
- **[manual-base.txt](manual-base.txt)** (2143 líneas)
  - OCR completo del manual 2008 original
  - Todas las secciones: reglas, componentes, investigadores, primigenios
  - Referencia de autoridad para validaciones

### 📚 Expansiones (Futuro - Lugares para almacenar cuando lleguen)
- `manual-expansion-1.txt` - [Nombre expansión 1]
- `manual-expansion-2.txt` - [Nombre expansión 2]
- Etc.

**Pantalla de estado actual:**
- ✅ Base game: Completo (manual-base.txt)
- ⏳ Las Montañas de la Locura: Pendiente
- ⏳ Bajo las Pirámides: Pendiente
- ⏳ Tierras del Sueño: Pendiente
- ⏳ Otras expansiones: Pendiente

---

## Mapeo de Contenido: Original → Documentos Procesados

### Base Game

| Sección Original | Líneas | Documento de Destino | Notas |
|------------------|--------|----------------------|-------|
| Descripción del Juego | 1-150 | [Eldritch-Horror.md](Eldritch-Horror.md#Descripción-General) | ✅ Procesada y resumida |
| Componentes | 150-400 | [Eldritch-Horror.md](Eldritch-Horror.md#Componentes) | ✅ Completamente documentada |
| Objetivo del Juego | 400-500 | [Eldritch-Horror.md](Eldritch-Horror.md#Objetivo) | ✅ Procesada |
| Mecanismos | 500-1200 | [Eldritch-Horror.md](Eldritch-Horror.md#Mecanismos) | ✅ Estructurada en subsecciones |
| FAQs y Erratas Base | 2000-2143 | [FAQs-Eldritch-Horror.md](FAQs-Eldritch-Horror.md) | ✅ 7 erratas + 16 FAQs documentadas |

### Expansiones (Cuando se agreguen)

| Expansión | Sección | Documento de Destino | Estado |
|-----------|---------|----------------------|--------|
| Las Montañas de la Locura | TBD | `[NombreExpansión].md` | ⏳ Pendiente |
| Bajo las Pirámides | TBD | `[NombreExpansión].md` | ⏳ Pendiente |
| Tierras del Sueño | TBD | `[NombreExpansión].md` | ⏳ Pendiente |

---

## Protocolo de Gestión

### Cuando consultar contenido original:

1. **Validación de precisión**: Si hay duda sobre si documentación refleja fielmente el manual
2. **Resolución de ambigüedades**: Cuando Entendimiento detecta conflicto de interpretaciones
3. **Ampliación de documentación**: Si hay información adicional no capturada en Redacción
4. **Verificación post-correcciones**: Después de aplicar erratas
5. **Incorporación de expansiones**: Al procesar nuevo manual de expansión

### Flujo para incorporar contenido original a documentos procesados:

```
1. Localizar fragmento en contenido original (ej: manual-base.txt línea 612)
   ↓
2. Verificar mapeo en esta tabla (¿a qué documento va?)
   ↓
3. Ejecutar SKILL: Lectura (leer sin omisiones)
   ↓
4. Ejecutar SKILL: Entendimiento (extraer núcleo, resolver ambigüedades)
   ↓
5. Ejecutar SKILL: Gestión de Contenido Original (adaptar a formato)
   ↓
6. Ejecutar SKILL: Redacción (integrar al documento procesado destino)
   ↓
7. Actualizar mapeo en esta tabla si es nuevo contenido
```

### Al procesar expansión nueva:

```
1. Recibir archivo OCR/manual de expansión
   ↓
2. Guardar en CONTENIDO-ORIGINAL como: manual-expansion-[nombre].txt
   ↓
3. Leer y crear mapeo de secciones → documento destino
   ↓
4. Crear documento: [NombreExpansión].md aplicando plantilla
   ↓
5. Aplicar correcciones de FAQs (si existen)
   ↓
6. Crear [NombreExpansión]-FAQs.md
   ↓
7. Actualizar mapeo en esta tabla
   ↓
8. Actualizar [FAQs-Eldritch-Horror.md](FAQs-Eldritch-Horror.md) con referencias a expansión
```

---

## Integridad de Contenido

**Verificaciones realizadas en Base Game:**
- ✅ OCR completado y verificado (manual-base.txt)
- ✅ 7 erratas oficiales identificadas documentadas
- ✅ 16 FAQs extraídas
- ✅ 12 investigadores procesados
- ✅ 4 Primigenios base catalogados
- ✅ Sistema de iconos validado contra original
- ✅ Contenido crudo separado de procesado

**Por expansión (cuando se agreguen):**
- Verificación de que OCR es legible
- Mapeo explícito de secciones
- Identificación de FAQs/Erratas específicas
- Actualización de referencias cruzadas

**Última verificación generales**: 20/03/2026  
**Siguiente verificación**: Cuando se agregue primera expansión

---

## Organización Física

```
ameritrash/eldritch-horror/
├── manual-base.txt                 ← Contenido crudo BASE
├── CONTENIDO-ORIGINAL.md           ← ESTE ARCHIVO (índice centralizado)
├── Eldritch-Horror.md              ← Documento procesado: Base
├── FAQs-Eldritch-Horror.md         ← FAQs: Base + referencias Expansiones
├── ICON-REFERENCE.md               ← Referencias iconos compartidas
│
├── [NombreExpansión].md            ← Futuro: Documento expansión 1
├── [NombreExpansión]-FAQs.md       ← Futuro: FAQs expansión 1
├── manual-expansion-1.txt          ← Futuro: Contenido crudo expansión 1
│
└── [NombreExpansión].md            ← Futuro: Documento expansión 2
    [NombreExpansión]-FAQs.md       ← Futuro: FAQs expansión 2
    manual-expansion-2.txt          ← Futuro: Contenido crudo expansión 2
```

---

## Referencias Cruzadas

- **Documento principal base**: [Eldritch-Horror.md](Eldritch-Horror.md)
- **FAQs base + expansiones**: [FAQs-Eldritch-Horror.md](FAQs-Eldritch-Horror.md)
- **Referencias de iconos**: [ICON-REFERENCE.md](ICON-REFERENCE.md)
- **Premisas del proyecto**: [../../../PREMISAS.md](../../../PREMISAS.md)
- **Índice maestro**: [../../../README.md](../../../README.md)

---

*Gestionado por SKILL: Gestión de Contenido Original (Redacción especializada)*  
*Última actualización: 20/03/2026*
