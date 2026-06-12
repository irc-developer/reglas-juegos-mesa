# Documentación de Juegos de Mesa 🎲

Biblioteca centralizada de reglas, mecanismos y guías para juegos de mesa. Cada juego está documentado con su información base, expansiones (si las hay), y materiales de apoyo generados por un experto jugador.

---

## 📚 Documentación fundamental

- [**PREMISAS**](PREMISAS.md) - Principios, roles, skills y criterios de calidad que rigen este proyecto
- [**PLANTILLA**](PLANTILLA.md) - Template estándar para crear nuevos documentos de juegos

---

## 🗂️ Índice por Género

### 🎯 Estrategia
Eurogames, juegos tácticos y de gestión de recursos

| Juego | Jugadores | Duración | Estado |
|-------|-----------|----------|--------|
| [High Moon](./eurogames/high%20moon/High-Moon.md) | 2-4 | No esp. en manual | ✓ Base + guía novatos |
| [Terraforming Mars](./eurogames/terraforming%20mars/Terraforming-Mars.md) | 2-5 | No esp. en manual | ✓ Base + ayudas |
| [Catan](./estrategia/Catan/Catan.md) | 2-4 | 60-90 min | ✓ Base + 3 expansiones |
| *(Próximamente)* | - | - | - |

### 🎊 Party Games
Juegos sociales, cooperativos y para grupo

| Juego | Jugadores | Duración | Estado |
|-------|-----------|----------|--------|
| *(Próximamente)* | - | - | - |

### 🃏 Juegos de Cartas
Juegos enfocados en mecánicas de cartas

| Juego | Jugadores | Duración | Estado |
|-------|-----------|----------|--------|
| *(Próximamente)* | - | - | - |

### 🛡️ Temáticos
Juegos con narrativa y temática fuerte

| Juego | Jugadores | Duración | Estado |
|-------|-----------|----------|--------|
| [The Witcher: El Viejo Mundo](./ameritrash/witcher-old-world/The-Witcher-El-Viejo-Mundo.md) | 1-5 | No esp. en manual | ✓ [Base](./ameritrash/witcher-old-world/The-Witcher-El-Viejo-Mundo.md) + [guía](./ameritrash/witcher-old-world/AYUDAS_JUGADORES/RESUMEN-Y-GUIA-NOVATO.md) + [resumen](./ameritrash/witcher-old-world/AYUDAS_JUGADORES/RESUMEN-TURNO.md) + [ayuda visual](./ameritrash/witcher-old-world/AYUDAS_JUGADORES/AYUDA-VISUAL-MESA.md) + [prompt](./ameritrash/witcher-old-world/AYUDAS_JUGADORES/PROMPT-IMAGEN-MUNDREL.md) |
| *(Próximamente)* | - | - | - |

### 🎲 Abstractos
Juegos sin temática, enfocados en mecánica pura

| Juego | Jugadores | Duración | Estado |
|-------|-----------|----------|--------|
| *(Próximamente)* | - | - | - |

### 👥 Cooperativos
Juegos donde los jugadores ganan o pierden juntos

| Juego | Jugadores | Duración | Estado |
|-------|-----------|----------|--------|
| *(Próximamente)* | - | - | - |

### 🏃 Deducción y Rol
Juegos de misterio, detectives, rol e improvisación

| Juego | Jugadores | Duración | Estado |
|-------|-----------|----------|--------|
| *(Próximamente)* | - | - | - |

---

## 🔍 Buscar por Criterios

### Por Número de Jugadores
- **2 jugadores**: *(Próximamente)*
- **3-4 jugadores**: *(Próximamente)*
- **5+ jugadores**: *(Próximamente)*
- **Sin límite (escalable)**: *(Próximamente)*

### Por Duración
- **Rápidos (< 30 min)**: *(Próximamente)*
- **Medios (30-90 min)**: [Catan](./estrategia/Catan/Catan.md)
- **Largos (90+ min)**: [Terraforming Mars](./eurogames/terraforming%20mars/Terraforming-Mars.md)

### Por Mecanismo Principal
- **Worker Placement**: *(Próximamente)*
- **Push Your Luck**: *(Próximamente)*
- **Deck Building**: *(Próximamente)*
- **Área Control**: *(Próximamente)*
- **Press Your Luck**: *(Próximamente)*
- **Juego de Rol**: *(Próximamente)*
- **Cooperativo**: *(Próximamente)*

---

## 📖 Estructura de Cada Documento

Cada juego sigue una estructura normalizada:

1. **Metadatos** - Información base (género, jugadores, duración, etc.)
2. **Descripción General** - ¿Qué es el juego?
3. **Componentes** - Qué hay en la caja
4. **Objetivo del Juego** - Las condiciones de victoria
5. **Mecanismos Principales** - Cómo funciona
6. **Reglas Principales** - Orden de juego y acciones
7. **Notas y Aclaraciones** - FAQs, erratas, variantes
8. **Contenido Original** - Manual completo tal cual

Además, incluye materiales generados por experto:
- Guía rápida para novatos
- Resumen ejecutivo (1 página)
- FAQ de reglas
- Hojas de referencia rápida
- Estrategias para principiantes

---

## ✨ Características Especiales

### Expansiones
Cada juego base tiene links directos a sus expansiones documentadas por separado. Por ejemplo:
- Catan → [5-6 Jugadores](./estrategia/Catan/Catan_Expansion-5-6-Jugadores.md)
- Catan → [Ciudades y Caballeros](./estrategia/Catan/Catan_Expansion-Ciudades-y-Caballeros.md)

### Materiales de Apoyo
Para cada juego se generan (bajo demanda):
- 📝 Resúmenes ejecutivos
- 🎓 Guías para novatos
- ❓ FAQs de reglas
- 📋 Hojas de referencia
- 💡 Consejos de estrategia
- 🔄 Variantes de juego

### Formato Obsidian
Todos los documentos son compatibles con Obsidian, con:
- Tags jerárquicos para clasificación
- Links internos automáticos entre juegos
- Grafo de relaciones visualizable
- Propiedades YAML enriquecidas

---

## 🚀 Cómo Usar Este Proyecto

### Para Comenzar
1. Lee [PREMISAS.md](PREMISAS.md) para entender la estructura
2. Navega por género en el índice de arriba
3. Accede al juego que te interese
4. Consulta las secciones que necesites

### Para Agregar un Nuevo Juego
1. Copia la [PLANTILLA.md](PLANTILLA.md)
2. Rellena los metadatos y secciones
3. Coloca el archivo en la carpeta de su género
4. Actualiza este índice (README.md)

### Para Generar Materiales Específicos
- Solicita a tu experto jugador: *"Hazme una guía rápida para [Juego]"*
- O: *"Necesito un FAQ de reglas para [Juego]"*
- Se generarán en formato Markdown en la carpeta del juego

---

## 📊 Estadísticas

| Métrica | Cantidad |
|---------|----------|
| Juegos documentados | 2 |
| Expansiones incluidas | 0 |
| Géneros representados | 7 |
| Materiales de apoyo | 5 |

*(Se actualiza automáticamente al agregar juegos)*

---

## 🛠️ Mantenimiento

- **Última actualización**: 3 de mayo de 2026
- **Versión**: 1.0
- **Estado**: 🟢 Activo - Listo para recibir juegos

### Próximas mejoras
- [ ] Agregar primeros juegos
- [ ] Crear filtros interactivos
- [ ] Generar hojas de referencia rápida
- [ ] Integrar con Obsidian vault completo

---

**¿Necesitas ayuda?** Consulta [PREMISAS.md](PREMISAS.md#mi-rol-como-experto-jugador) sobre mi rol como experto jugador y qué puedo hacer por ti.
