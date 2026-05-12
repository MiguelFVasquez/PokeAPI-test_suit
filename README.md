# PokeAPI Testing Suite

Suite completa de pruebas automatizadas para la API de Pokémon. Utiliza **Postman**, **Newman** y **JavaScript** para realizar pruebas funcionales, de rendimiento y validación de datos.

## Descripción del Proyecto

Este proyecto contiene una colección de pruebas automatizadas para validar los endpoints y funcionalidades de la PokeAPI. Las pruebas incluyen:

- ✅ Validación de respuestas HTTP
- ✅ Verificación de estructura de datos
- ✅ Scripts de prueba en JavaScript
- ✅ Generación de reportes en HTML
- ✅ Pruebas con datos de ejemplo (berries)

## Tech Stack

- **Postman**: Colección de requests y ambiente
- **Newman**: CLI para ejecutar colecciones de Postman de manera automatizada
- **Newman HTML Reporter**: Generación de reportes visuales en HTML
- **JavaScript**: Scripts personalizados en los tests (pre-request y post-response)
- **Node.js**: Gestor de dependencias



## 📁 Estructura del Proyecto

```
pokeapi-testing-suite/
├── postman/
│   ├── PokeAPI_Collection          # Colección de Postman con todos los requests y tests
│   └── PokeAPI_environment         # Variables de entorno (URLs, tokens, etc.)
├── reports/                         # Reportes generados por Newman (gitignored)
├── berries_data.json               # Datos de ejemplo para pruebas
├── package.json                    # Dependencias y scripts
├── .gitignore                      # Archivos/carpetas a ignorar en git
└── README.md                       # Este archivo
```

## 🔧 Características Principales

### Scripts en Tests
Los tests incluyen scripts JavaScript personalizados para:

- **Pre-request Scripts**: Configurar variables dinámicas, autenticación
- **Post-response Scripts**: 
  - Validación de respuestas
  - Extracción de datos
  - Verificaciones condicionales
  - Generación de logs

### Datos de Prueba
El archivo `berries_data.json` contiene datos de ejemplo para simular pruebas con información real de Pokémon.


**Última actualización:** Mayo 2026
