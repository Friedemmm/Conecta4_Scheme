## Paradigmas de Programación

# Laboratorio 1 "Conecta 4" en Scheme

Implementación del clásico juego **Conecta 4** en lenguaje **Scheme**, desarrollado como laboratorio en el ramo de Paradigmas de Programación.

---
 
## 🔧 Instalación y Uso
 
### Requisitos previos
 
- **Racket** (versión 8.0 o superior)
- Editor de texto o IDE compatible con Racket (DrRacket, VS Code + extensión Racket, etc.)

### 📚 Estructura del proyecto
 
```
Laboratorio-1-Paradigmas/
├── main_210821481_SofiaVergaraGodoy.rkt
├── TDAboard_210821481_SofiaVergaraGodoy.rkt
├── TDAgame_210821481_SofiaVergaraGodoy.rkt
├── TDApiece_210821481_SofiaVergaraGodoy.rkt
│── TDAplayer_210821481_SofiaVergaraGodoy.rkt
├── script1_210821481_SOFIA_VERGARAGODOY.rkt
├── script2_210821481_SOFIA_VERGARAGODOY.rkt
├── script_base_210821481_SOFIA_VERGARAGODOY.rkt
└── README.md
```

### Configuración inicial
 
 **Clonar o descargar el repositorio**:
```bash
cd Laboratorio-1-Paradigmas
git clone https://github.com/Friedemmm/Conecta4_Sceheme.git
```

### Inicializar una partida
 
Ejecuta uno de los tres scripts que están estructurados como una partida:

**Desde la terminal:**
```bash
racket script1_210821481_SOFIA_VERGARAGODOY.rkt
```

**Desde DrRacket:**
1. Abre el archivo `script1_210821481_SOFIA_VERGARAGODOY.rkt`
2. Presiona **Run** o `Ctrl + Shift + F5`
 
---
 
## ✨ Características principales
 
- 🎯 **Lógica de juego completa**: Inserción de piezas, validación de movimientos y detección de ganadores.
- 👥 **Soporte para 2 jugadores**: Turnos alternados entre jugadores.
- 🔴🟡 **Sistema de piezas por color**: Diferenciación visual mediante colores (rojo y amarillo).
- 📋 **Tablero dinámico**: Creación flexible de tableros con dimensiones personalizables.
- ✅ **Validación de dominios**: Todas las funciones respetan restricciones de dominio para funcionamiento correcto.
- 🏆 **Detección de victoria**: Identifica ganadores por línea horizontal, vertical o diagonal.
---
 
*© 2024 · Universidad de Santiago de Chile*
