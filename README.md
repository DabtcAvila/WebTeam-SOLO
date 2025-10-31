# Sistema de Seguros - Contribuciones Analytics

**Desarrollado por:** David Fernando Ávila Díaz (CU: 197851)  
**Proyecto:** COM-11117 - Introducción al Desarrollo Web - ITAM 2025

## 🌐 Página Pública del Proyecto

**🔗 https://dabtcavila.github.io/WebTeam-SOLO/**

## 📋 Descripción

Este repositorio contiene las contribuciones técnicas especializadas en analytics y visualización de datos para el proyecto de Sistema de Seguros del Equipo 4. Incluye un módulo completo de análisis avanzado con métricas de riesgo, detección de fraudes y visualizaciones interactivas.

## ⚡ Inicio Rápido

### Instalación
```bash
# Clonar repositorio
git clone https://github.com/DabtcAvila/WebTeam-SOLO.git
cd WebTeam-SOLO

# Instalar dependencias
pip install -r server/requirements.txt

# Iniciar servidor
uvicorn server.main:app --reload
```

### Acceso Local
- **Dashboard Principal:** http://127.0.0.1:8000/client/index.html
- **Analytics Complementario:** http://127.0.0.1:8000/client/analytics.html
- **API Documentación:** http://127.0.0.1:8000/docs

## 🎯 Contribuciones Técnicas Principales

### Módulo Analytics Completo
- **dashboard-core.js** - Sistema core con Chart.js 4.4.6
- **api-client.js** - Cliente API robusto con cache inteligente
- **analytics.js** - Motor de análisis avanzado y métricas
- **analytics.html** - Interfaz de análisis complementario

### Características Técnicas
- **Índice de Riesgo Dinámico** - Cálculo basado en ratios claims/policies
- **Detección de Fraudes** - Algoritmos de reconocimiento de patrones
- **Visualizaciones Interactivas** - Chart.js con configuraciones avanzadas
- **Cache Inteligente** - Sistema de 5 minutos con invalidación automática
- **Diseño Responsive** - Mobile-first con Bootstrap 5.3.8

## 🛠️ Stack Tecnológico

### Frontend
- HTML5 Semántico
- Bootstrap 5.3.8 
- JavaScript ES6+
- Chart.js 4.4.6

### Backend
- FastAPI
- SQLModel
- Base de datos SQLite

### Características Avanzadas
- Sistema de cache inteligente
- Manejo robusto de errores con fallbacks
- Diseño responsive mobile-first
- Compatibilidad cross-browser

## 📊 Arquitectura del Sistema

```
WebTeam-SOLO/
├── client/                    # Frontend
│   ├── index.html            # Dashboard principal
│   ├── analytics.html        # Analytics complementario
│   ├── policies.html         # Gestión de pólizas
│   ├── claims.html          # Gestión de reclamos
│   └── js/
│       ├── dashboard-core.js  # Core del sistema
│       ├── api-client.js     # Cliente API robusto
│       └── analytics.js      # Motor de analytics
├── server/                   # Backend FastAPI
│   ├── main.py              # Aplicación principal
│   ├── models.py            # Modelos de datos
│   ├── db.py                # Configuración DB
│   └── requirements.txt     # Dependencias
├── assets/                  # Recursos GitHub Pages
│   ├── css/styles.css       # Estilos personalizados
│   └── js/main.js          # JavaScript interactivo
├── index.html              # Página pública principal
├── _config.yml             # Configuración Jekyll
└── README.md               # Este archivo
```

## 🎓 Cumplimiento Académico

✅ **Bootstrap 5.3.8** - Framework CSS responsive  
✅ **Chart.js** - Visualizaciones avanzadas  
✅ **LocalStorage** - Persistencia de datos  
✅ **API Consumption** - Cliente robusto  
✅ **Responsive Design** - Mobile-first  
✅ **Git Workflow** - Commits profesionales  

## 📞 Contacto

**David Fernando Ávila Díaz**  
- **CU:** 197851
- **Email:** df.avila.diaz@gmail.com
- **GitHub:** @DabtcAvila

---

**© 2025 David Fernando Ávila Díaz - ITAM COM-11117**  
*Proyecto académico desarrollado bajo estándares universitarios profesionales*