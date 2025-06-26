# España: Análisis Económico 2008-2024

## 📊 Descripción

Análisis macroeconómico basado en datos oficiales del INE, Banco de España, Eurostat y Federal Reserve. Documentación del estancamiento del PIB per cápita real y el crecimiento exponencial de la deuda pública.

## 🔍 Contenido

### 1. [Página Principal](./index.html)

Resumen ejecutivo con indicadores clave y acceso a los análisis detallados.

### 2. [Análisis España](./espana.html)

- PIB per cápita real: +3.2% en 16 años
- Deuda per cápita real: +211%
- Impacto en poder adquisitivo
- Proyecciones de sostenibilidad fiscal

### 3. [Comparación Internacional](./divergencia.html)

- España: +3.2% vs USA: +25.3% (PIB per cápita real)
- Análisis de modelos económicos
- Divergencia con UE-27: 15.3 puntos porcentuales
- Implicaciones estructurales

## 📈 Datos Clave

- **PIB per cápita real**: Prácticamente estancado desde 2008 (+3.2%)
- **Deuda per cápita**: Aumentó un 211% en términos reales
- **Divergencia con Europa**: España crece 15.3 puntos menos que la UE-27
- **Coste de oportunidad**: 712€ por español al año en intereses (euros constantes 2015)

## 🛠️ Estructura Técnica

```
├── index.html          # Landing con métricas principales
├── espana.html         # Análisis detallado España
├── divergencia.html    # Comparación internacional
└── README.md          # Este archivo
```

## 📱 Visualización

- Gráficos interactivos con Chart.js
- Diseño responsive
- Datos en tiempo real actualizables

## 📚 Fuentes de Datos

- **INE**: Contabilidad Nacional Trimestral (base 2015)
- **Banco de España**: Boletín Estadístico y notificación EDP
- **Eurostat**: nama_10_pc, tec00114
- **FRED**: Federal Reserve Economic Data
- **Idealista**: Datos de alquiler
- **EPA**: Salarios medios

## 🚀 Despliegue

### Opción 1: Local

```bash
git clone [repositorio]
# Abrir index.html en navegador
```

### Opción 2: GitHub Pages

1. Settings → Pages
1. Source: Deploy from a branch
1. Branch: main, folder: / (root)
1. URL: `https://[usuario].github.io/[repositorio]`

## 📊 Metodología

- Euros constantes 2015 (volúmenes encadenados)
- Deflactor PIB 2024/2015: 1,18
- Criterios SEC-2010/EDP para deuda pública
- Población: Padrón continuo INE

## ⚖️ Licencia

Análisis basado en datos públicos. Libre distribución con atribución.

## 🤝 Contribuciones

- Issues: Errores en datos o metodología
- Pull Requests: Mejoras en visualización o análisis
- Contacto: A través del repositorio

-----

*Datos oficiales. Análisis independiente. Sin retórica, solo números.*
