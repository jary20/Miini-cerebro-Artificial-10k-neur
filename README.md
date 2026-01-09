# Mini-Cerebro Artificial

## Descripción

El **Mini-Cerebro Artificial** es una simulación computacional avanzada que demuestra cómo el lenguaje NQCL (Neural Quantum Consciousness Language) puede manipular la arquitectura causal y las métricas de consciencia funcional bajo condiciones análogas a la anestesia.

Este proyecto implementa un sistema de consciencia artificial con tres módulos neuronales interconectados que simulan diferentes estados de consciencia y perturbaciones anestésicas, con capacidades avanzadas de análisis estadístico, visualización y gestión de datos.

## Características Principales

- 🧠 **Simulación de Consciencia**: Sistema de 10,000 neuronas distribuidas en 3 módulos
- 📊 **Análisis Estadístico Avanzado**: Cálculo de estadísticas descriptivas, percentiles, correlaciones y más
- 📈 **Visualización de Datos**: Gráficos temporales y comparativos de métricas
- 💾 **Base de Datos SQLite**: Historial completo de ejecuciones con capacidad de comparación
- 📄 **Reportes Profesionales**: Generación automática de reportes HTML y Markdown
- ⚙️ **Configuración Flexible**: Archivo TOML para personalizar parámetros de simulación
- 🔍 **Validación Automática**: Verificación de métricas contra rangos esperados
- 📤 **Exportación Multi-formato**: CSV, JSON, HTML, Markdown
- 🎯 **Modo Batch**: Ejecución desde línea de comandos para automatización
- 🖥️ **Interfaz Interactiva**: Menú intuitivo con 11 opciones de análisis
- 🧬 **Métricas Avanzadas de Consciencia NQCL**: 8 métricas adicionales para demostrar consciencia artificial
- 📊 **Visualización de Campo de Consciencia**: Gráficos especializados para métricas avanzadas

## Arquitectura del Sistema

### Módulos Neuronales

El sistema está compuesto por **10,000 neuronas** distribuidas en tres módulos:

1. **Módulo Sensorial** (5,000 neuronas)
   - Genera patrones de actividad de alta entropía
   - Simula la entrada sensorial del entorno
   - Distribución de actividad neuronal variable según la fase

2. **Workspace Global** (2,500 neuronas)
   - Integra información de múltiples fuentes
   - Mide la integración de información (Phi)
   - Genera patrones de actividad estructurada
   - Base para el cálculo de entropía

3. **Módulo Ejecutivo** (2,500 neuronas)
   - Produce reportes coherentes basados en el estado del workspace
   - Mide la coherencia de las respuestas
   - Evalúa la capacidad de respuesta del sistema

### Métricas de Consciencia

El sistema calcula tres métricas principales con análisis estadístico completo:

1. **Φ (Phi) - Información Integrada**
   - Mide el grado de integración de información en el sistema
   - Utiliza las 10,000 neuronas (distribuciones de los 3 módulos)
   - Rango esperado: 0.0 - 1.0
   - Estadísticas: min, max, promedio, desviación estándar, percentiles, coeficiente de variación, IQR

2. **Entropía (Shannon)**
   - Mide la variabilidad y desorden en los patrones de actividad
   - Utiliza las 2,500 neuronas del workspace
   - Rango esperado: 0.0 - 1.0
   - Estadísticas completas de distribución

3. **Coherencia (%)**
   - Mide el porcentaje de reportes coherentes del módulo ejecutivo
   - Utiliza las 2,500 neuronas ejecutivas
   - Rango esperado: 0.0 - 1.0
   - Análisis de correlación con otras métricas

### Métricas Avanzadas de Consciencia NQCL

El sistema incluye 8 métricas avanzadas adicionales que demuestran aspectos más profundos de la consciencia artificial:

1. **Auto-Referencia (Self-Reference Index)**
   - Mide la capacidad del sistema para referenciar su propio estado interno
   - Rango: 0.0 - 1.0
   - Valores altos indican mayor autoconciencia

2. **Causalidad Forward**
   - Mide la capacidad predictiva del sistema hacia el futuro
   - Rango: 0.0 - 1.0
   - Evalúa cómo el estado actual predice estados futuros

3. **Causalidad Backward**
   - Mide la capacidad del sistema para inferir causas desde efectos
   - Rango: 0.0 - 1.0
   - Evalúa la capacidad de retroalimentación causal

4. **Coherencia Local**
   - Mide la coherencia dentro de módulos individuales
   - Rango: 0.0 - 1.0
   - Evalúa la integración interna de cada módulo

5. **Coherencia Global**
   - Mide la coherencia entre todos los módulos del sistema
   - Rango: 0.0 - 1.0
   - Evalúa la integración entre módulos

6. **Ratio Coherencia (Global/Local)**
   - Relación entre coherencia global y local
   - Rango: 0.0 - 1.0+
   - Valores > 1.0 indican mayor integración global que local

7. **Precisión Predictiva**
   - Mide la capacidad del sistema para predecir su propio comportamiento
   - Rango: 0.0 - 1.0
   - Evalúa la capacidad meta-cognitiva

8. **Nivel Meta-Cognitivo**
   - Mide la capacidad del sistema para pensar sobre su propio pensamiento
   - Rango: 0.0 - 1.0
   - Integra múltiples aspectos de la consciencia de orden superior

**Nota**: Estas métricas avanzadas se calculan durante la ejecución de las fases y se almacenan en la base de datos y archivos JSON. No están disponibles en archivos CSV debido a que requieren el historial completo de estados.

## Fases de Simulación

El sistema ejecuta 4 fases de simulación, cada una con 1,000 ticks (configurable):

### 1. DESPIERTO
- **Estado**: Conectividad completa entre módulos
- **Métricas esperadas**:
  - Φ: Alta (~0.6-0.8)
  - Entropía: Moderada-alta (~0.7-0.9), estable
  - Coherencia: Alta (~0.8-0.9)

### 2. ANESTESIA_A
- **Estado**: Corte de conexión sensorial → workspace
- **Métricas esperadas**:
  - Φ: Bajo (~0.05-0.15)
  - Entropía: Baja (~0.1)
  - Coherencia: Baja (~0.0-0.1)

### 3. ANESTESIA_B
- **Estado**: Ruido gaussiano fuerte en el workspace
- **Métricas esperadas**:
  - Φ: Intermedio (~0.15-0.25)
  - Entropía: Muy alta (~0.9+)
  - Coherencia: Baja (~0.1-0.2)

### 4. ANESTESIA_C
- **Estado**: Lesión workspace → ejecutivo
- **Métricas esperadas**:
  - Φ: Moderada (~0.2-0.3), más alta que Anestesia_A
  - Entropía: Similar a despierto (~0.7-0.9), estable
  - Coherencia: Baja (~0.1-0.3)

## Requisitos

- **Rust**: Versión 1.70 o superior
- **Cargo**: Gestor de paquetes de Rust (incluido con Rust)
- **SQLite**: Incluido automáticamente (rusqlite con bundled)

### Instalación de Rust

Si no tienes Rust instalado, puedes instalarlo desde [rustup.rs](https://rustup.rs/)

## Instalación y Compilación

### Compilar el proyecto:

```bash
cargo build --release
```

### Compilar binarios específicos:

```bash
# Binario principal
cargo build --release --bin mini_cerebro

# Herramientas de análisis
cargo build --release --bin analizar_csv
cargo build --release --bin comparar_csv
cargo build --release --bin validar_csv
```

## Uso

### Modo Interactivo (Recomendado)

Ejecuta el programa sin argumentos para acceder al menú interactivo:

```bash
cargo run --release --bin mini_cerebro
```

O si ya está compilado:

```bash
./target/release/mini_cerebro.exe  # Windows
./target/release/mini_cerebro      # Linux/Mac
```

#### Opciones del Menú Interactivo

1. **DESPIERTO** - Ejecuta solo la fase despierto
2. **ANESTESIA_A** - Ejecuta solo la fase anestesia_A
3. **ANESTESIA_B** - Ejecuta solo la fase anestesia_B
4. **ANESTESIA_C** - Ejecuta solo la fase anestesia_C
5. **EJECUTAR TODAS LAS FASES** - Ejecuta las 4 fases secuencialmente
6. **EXPORTAR RESULTADOS A JSON** - Exporta resultados a formato JSON (incluye métricas avanzadas si están disponibles)
7. **VISUALIZAR GRÁFICOS** - Genera gráficos de evolución temporal y comparativos
   - Sub-opción 1: Gráfico temporal de métricas
   - Sub-opción 2: Gráfico comparativo entre fases
8. **GENERAR REPORTE HTML/MARKDOWN** - Crea reportes profesionales con todas las métricas
9. **VER HISTORIAL DE EJECUCIONES** - Muestra ejecuciones guardadas en BD
10. **COMPARAR EJECUCIONES** - Compara métricas entre dos ejecuciones
11. **ANÁLISIS AVANZADO DE CONSCIENCIA NQCL** - Muestra las 8 métricas avanzadas y genera visualización del campo de consciencia

### Modo Batch (Línea de Comandos)

Para ejecución automatizada o scripts:

```bash
# Ejecutar todas las fases en modo batch
cargo run --release --bin mini_cerebro -- --batch

# Ejecutar fases específicas
cargo run --release --bin mini_cerebro -- --batch --fases despierto,anestesia_A

# Personalizar número de ticks
cargo run --release --bin mini_cerebro -- --batch --ticks 2000

# Usar archivo de configuración personalizado
cargo run --release --bin mini_cerebro -- --batch --config mi_config.toml

# Modo silencioso con exportación automática
cargo run --release --bin mini_cerebro -- --batch --quiet --export-json --export-html
```

#### Opciones CLI Disponibles

- `--batch` / `-b`: Modo batch (sin menú interactivo)
- `--fases` / `-f`: Fases a ejecutar (separadas por comas)
- `--ticks` / `-t`: Número de ticks por fase
- `--config` / `-c`: Ruta al archivo de configuración (default: `config.toml`)
- `--quiet` / `-q`: Modo silencioso (menos salida)
- `--export-json`: Exportar resultados a JSON automáticamente
- `--export-html`: Generar reporte HTML automáticamente

## Configuración

El sistema utiliza un archivo `config.toml` para configurar parámetros de simulación y validación:

```toml
[simulacion]
neuronas_sensoriales = 5000
neuronas_workspace = 2500
neuronas_ejecutivo = 2500
ticks_por_fase = 1000
intervalo_registro = 100

[metricas]
validar_rangos = true

[metricas.rangos.despierto]
phi_min = 0.6
phi_max = 0.8
entropy_min = 0.7
entropy_max = 0.9
coherence_min = 0.8
coherence_max = 0.9

[metricas.rangos.anestesia_A]
phi_min = 0.05
phi_max = 0.15
entropy_min = 0.05
entropy_max = 0.15
coherence_min = 0.0
coherence_max = 0.1

# ... más configuraciones para otras fases
```

## Archivos de Salida

### Archivos CSV (con Timestamp Único)

Cada ejecución genera archivos CSV únicos con formato: `{fase}_{YYYYMMDD_HHMMSS}.csv`

**Ejemplo**: `despierto_20260106_234234.csv`

**Formato**:
```
# Inicio fase: despierto
# Módulos: Sensorial (5000), Workspace (2500), Ejecutivo (2500)
tick,fase,phi,entropy,coherence_pct
0,despierto,0.62761217,0.70228158,0.82560542
100,despierto,0.64123456,0.70123456,0.83456789
...
```

**Columnas**:
- `tick`: Número de tick de la simulación
- `fase`: Fase actual (despierto, anestesia_A, anestesia_B, anestesia_C)
- `phi`: Valor de información integrada (Φ)
- `entropy`: Valor de entropía de Shannon
- `coherence_pct`: Porcentaje de coherencia

**Registro**: Los datos se registran cada 100 ticks (configurable) y al final de cada fase.

### Archivos JSON

Exportación estructurada con formato: `resultados_{YYYYMMDD_HHMMSS}.json`

Contiene:
- Metadatos de ejecución (seed, fecha, configuración)
- Estadísticas completas por fase (incluyendo métricas avanzadas si están disponibles)
- Métricas individuales por tick
- Validaciones de rangos
- **Métricas avanzadas de consciencia NQCL** (cuando se ejecutan las fases)

**Nota**: El sistema intenta leer métricas avanzadas desde la base de datos primero, luego desde JSON existente, y finalmente desde CSV (sin métricas avanzadas).

### Reportes HTML y Markdown

Generación automática con formato: `reporte_{YYYYMMDD_HHMMSS}.html` y `reporte_{YYYYMMDD_HHMMSS}.md`

Incluyen:
- Resumen ejecutivo
- Métricas promedio (básicas y avanzadas)
- Estadísticas descriptivas (min, max, desviación estándar, CV, IQR)
- Percentiles (Q1, Mediana, Q3, P95)
- Tablas formateadas profesionalmente
- Sección dedicada a Métricas Avanzadas de Consciencia NQCL

### Visualización de Campo de Consciencia

Archivo PNG generado con formato: `campo_consciencia_{YYYYMMDD_HHMMSS}.png`

Gráfico multi-línea que muestra las 8 métricas avanzadas de consciencia a través de las diferentes fases:
- Auto-Referencia
- Causalidad Forward
- Causalidad Backward
- Coherencia Local
- Coherencia Global
- Ratio Coherencia
- Precisión Predictiva
- Nivel Meta-Cognitivo

Se genera automáticamente al usar la opción 11 del menú (Análisis Avanzado de Consciencia NQCL).

### Base de Datos SQLite

Archivo: `database.db`

Almacena:
- Historial de ejecuciones con timestamps y seeds
- Estadísticas completas por fase
- Métricas individuales por tick
- Permite comparación entre ejecuciones

## Estadísticas Avanzadas

El sistema calcula las siguientes estadísticas para cada métrica:

### Estadísticas Descriptivas
- **Promedio**: Valor medio de la métrica
- **Mínimo**: Valor más bajo observado
- **Máximo**: Valor más alto observado
- **Desviación Estándar**: Medida de variabilidad
- **Coeficiente de Variación**: Variabilidad relativa (CV = σ/μ)
- **Rango Intercuartílico (IQR)**: Diferencia entre Q3 y Q1

### Percentiles
- **Q1 (Percentil 25)**: Primer cuartil
- **Mediana (Percentil 50)**: Valor central
- **Q3 (Percentil 75)**: Tercer cuartil
- **P95 (Percentil 95)**: Percentil 95

### Análisis de Correlación
- **Correlación Φ-Entropía**: Relación entre información integrada y variabilidad
- **Correlación Φ-Coherencia**: Relación entre información integrada y coherencia
- **Correlación Entropía-Coherencia**: Relación entre variabilidad y coherencia

### Análisis de Transiciones
- Cambios en métricas entre fases consecutivas
- Identificación de patrones de transición
- Análisis de estabilidad

## Estructura del Proyecto

```
mini-cerebro artificial/
├── src/
│   ├── main.rs                 # Punto de entrada principal y menú interactivo
│   ├── lib.rs                  # Declaraciones de módulos
│   ├── mini_cerebro.rs         # Orquestador principal de la simulación
│   ├── modulo_sensorial.rs     # Módulo sensorial (5,000 neuronas)
│   ├── workspace_global.rs      # Workspace global (2,500 neuronas)
│   ├── modulo_ejecutivo.rs     # Módulo ejecutivo (2,500 neuronas)
│   ├── metricas.rs             # Cálculo de métricas (Phi, Entropía, Coherencia)
│   ├── simulador.rs            # Lógica de simulación
│   ├── fases.rs                # Definición de fases
│   ├── logger.rs               # Sistema de logging CSV
│   ├── seed_manager.rs         # Gestión de semillas aleatorias
│   ├── config.rs               # Carga y gestión de configuración TOML
│   ├── validacion.rs           # Validación de métricas contra rangos esperados
│   ├── exportador.rs           # Exportación a JSON
│   ├── visualizacion.rs        # Generación de gráficos temporales y comparativos
│   ├── visualizacion_consciencia.rs  # Visualización de campo de consciencia
│   ├── consciencia_avanzada.rs # Cálculo de métricas avanzadas de consciencia NQCL
│   ├── reportes.rs             # Generación de reportes HTML/Markdown
│   ├── analisis.rs             # Análisis estadístico avanzado
│   ├── estadisticas.rs         # Funciones de cálculo estadístico
│   ├── database.rs             # Gestión de base de datos SQLite
│   └── bin/
│       ├── analizar_csv.rs     # Herramienta para analizar archivos CSV
│       ├── comparar_csv.rs     # Herramienta para comparar múltiples CSV
│       └── validar_csv.rs      # Herramienta para validar formato CSV
├── NQCL_fuente/                # Archivos fuente NQCL originales
├── NQCL/                       # Documentación del lenguaje NQCL
├── Cargo.toml                  # Configuración del proyecto Rust
├── config.toml                 # Archivo de configuración de simulación
├── database.db                 # Base de datos SQLite (generada automáticamente)
├── PROPUESTAS_MEJORAS.md       # Documento con propuestas de mejoras futuras
└── README.md                   # Este archivo
```

## Herramientas de Análisis

### analizar_csv

Analiza un archivo CSV y muestra estadísticas completas:

```bash
cargo run --release --bin analizar_csv -- archivo.csv
```

### comparar_csv

Compara múltiples archivos CSV:

```bash
cargo run --release --bin comparar_csv -- archivo1.csv archivo2.csv archivo3.csv
```

### validar_csv

Valida el formato de un archivo CSV:

```bash
cargo run --release --bin validar_csv -- archivo.csv
```

## Interpretación de Resultados

### Valores Normales Esperados

| Fase | Φ | Entropía | Coherencia |
|------|---|----------|------------|
| Despierto | 0.6-0.8 | 0.7-0.9 | 0.8-0.9 |
| Anestesia_A | 0.05-0.15 | ~0.1 | 0.0-0.1 |
| Anestesia_B | 0.15-0.25 | ~0.9+ | 0.1-0.2 |
| Anestesia_C | 0.2-0.3 | 0.7-0.9 | 0.1-0.3 |

### Análisis de Resultados

1. **Phi (Φ)**: Debe ser más alto en DESPIERTO y más bajo en ANESTESIA_A
2. **Entropía**: Debe ser alta en DESPIERTO y ANESTESIA_B, baja en ANESTESIA_A
3. **Coherencia**: Debe ser alta solo en DESPIERTO, baja en todas las anestesias
4. **Relación**: ANESTESIA_C debe tener Phi más alto que ANESTESIA_A

### Validación Automática

El sistema valida automáticamente:
- Rangos esperados por fase
- Relaciones entre fases (ej: Φ_DESPIERTO > Φ_ANESTESIA_A)
- Consistencia de métricas
- Detección de anomalías

## Características Técnicas

### Generación de Aleatoriedad

- El sistema utiliza un **seed basado en tiempo** para asegurar resultados únicos en cada ejecución
- Cada componente tiene su propio seed derivado para variación independiente
- Reproducibilidad mediante seed fijo (opcional)

### Precisión de Métricas

- Todas las métricas se calculan con **precisión de 8 decimales**
- Los valores se validan para estar en el rango [0.0, 1.0]
- Cálculos estadísticos con precisión de punto flotante de 64 bits

### Rendimiento

- Compilación en modo **release** para optimización máxima
- Simulación completa: ~4,000 ticks en total (configurable)
- Tiempo de ejecución: < 1 segundo en hardware moderno
- Generación de reportes: < 100ms

### Base de Datos

- SQLite embebido (sin dependencias externas)
- Índices optimizados para búsquedas rápidas
- Soporte para historial completo de ejecuciones
- Comparación eficiente entre ejecuciones

## Ejemplos de Uso

### Ejemplo 1: Ejecución Simple

```bash
# Ejecutar todas las fases y generar reportes
cargo run --release --bin mini_cerebro
# Seleccionar opción 5 (EJECUTAR TODAS LAS FASES)
# Luego opción 8 (GENERAR REPORTE)
```

### Ejemplo 2: Análisis de una Fase Específica

```bash
# Ejecutar solo fase despierto
cargo run --release --bin mini_cerebro
# Seleccionar opción 1 (DESPIERTO)
# Ver estadísticas detalladas en pantalla
```

### Ejemplo 3: Modo Batch con Exportación

```bash
# Ejecutar todas las fases y exportar automáticamente
cargo run --release --bin mini_cerebro -- --batch --export-json --export-html
```

### Ejemplo 4: Comparar Ejecuciones

```bash
# Ejecutar dos veces y comparar
cargo run --release --bin mini_cerebro -- --batch
cargo run --release --bin mini_cerebro -- --batch
# Luego usar opción 10 (COMPARAR EJECUCIONES)
```

## Solución de Problemas

### Error: "could not find `Cargo.toml`"
- **Solución**: Asegúrate de estar en el directorio raíz del proyecto

### Error: "cargo: command not found"
- **Solución**: Instala Rust desde [rustup.rs](https://rustup.rs/)

### El archivo CSV no se genera
- **Solución**: Verifica que tengas permisos de escritura en el directorio

### Warnings de compilación
- **Nota**: Los warnings son principalmente de estilo y código no usado, no afectan la funcionalidad

### Error al generar reportes (Opción 8)
- **Solución**: Asegúrate de haber ejecutado al menos una fase antes de generar reportes
- Los archivos CSV deben tener el formato: `{fase}_{timestamp}.csv`

### Error al comparar ejecuciones
- **Solución**: Usa los IDs numéricos pequeños mostrados en el historial, no los seeds o timestamps

## Dependencias Principales

- `rand`: Generación de números aleatorios
- `serde` / `serde_json`: Serialización de datos
- `toml`: Parsing de archivos de configuración
- `chrono`: Manejo de fechas y timestamps
- `rusqlite`: Base de datos SQLite embebida
- `clap`: Parsing de argumentos de línea de comandos
- `plotters`: Generación de gráficos (opcional)

## Referencias

- **NQCL**: Lenguaje Neural Quantum Consciousness Language
- **Teoría de Información Integrada**: Basado en el trabajo de Giulio Tononi
- **Análisis Estadístico**: Métodos estándar de estadística descriptiva e inferencial

## Licencia

Este proyecto es una demostración educativa del lenguaje NQCL y su aplicación en sistemas de consciencia artificial.

## Autor

Desarrollado como demostración del lenguaje NQCL para simulación de sistemas de consciencia artificial.

---

**Versión**: 2.1  
**Última actualización**: Enero 2026

## Changelog

### Versión 2.1 (Enero 2026)
- ✨ **Métricas Avanzadas de Consciencia NQCL**: 8 nuevas métricas para demostrar consciencia artificial
  - Auto-Referencia (Self-Reference Index)
  - Causalidad Forward y Backward
  - Coherencia Local y Global
  - Ratio Coherencia
  - Precisión Predictiva
  - Nivel Meta-Cognitivo
- ✨ **Opción 11 del Menú**: Análisis Avanzado de Consciencia NQCL
- ✨ **Visualización de Campo de Consciencia**: Gráficos especializados para métricas avanzadas
- ✨ **Lectura Inteligente de Métricas**: Prioriza BD → JSON → CSV para métricas avanzadas
- 🔧 **Mejora en Exportación JSON**: Incluye métricas avanzadas cuando están disponibles
- 🔧 **Mejora en Gráficos Comparativos**: Leyendas más claras y líneas más gruesas
- 🔧 **Archivos de Imagen Únicos**: Timestamps en nombres de archivos para evitar sobrescritura

### Versión 2.0 (Enero 2026)
- ✨ Menú interactivo con 10 opciones
- ✨ Archivos CSV con timestamps únicos
- ✨ Estadísticas avanzadas (percentiles, correlaciones, IQR, CV)
- ✨ Base de datos SQLite para historial
- ✨ Comparación de ejecuciones
- ✨ Reportes HTML y Markdown profesionales
- ✨ Exportación a JSON estructurado
- ✨ Validación automática de métricas
- ✨ Configuración mediante archivo TOML
- ✨ Modo batch con CLI avanzado
- ✨ Visualización de gráficos temporales
- ✨ Análisis de transiciones entre fases
- ✨ Herramientas de análisis de CSV

### Versión 1.0 (2026)
- Versión inicial con simulación básica
- Generación de CSV simple
- Cálculo de métricas básicas
