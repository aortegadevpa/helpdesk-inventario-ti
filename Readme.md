# 💻 IT Desk.pro — Sistema HelpDesk & Inventario TI

Aplicación web interactiva diseñada para optimizar las operaciones de **Soporte Técnico TI** y el **control de mantenimiento preventivo de equipos** en pequeñas y medianas empresas. Permite registrar incidencias por prioridad, hacer seguimiento en tiempo real mediante métricas (KPIs), gestionar activos tecnológicos y exportar reportes en CSV sin dependencias de servidor.

🚀 **Demo en Vivo:** <https://aortegadevpa.github.io/helpdesk-inventario-ti/>  
🔗 **Portafolio Principal:** <https://aortegadevpa.github.io/Portafolio/>

---

## 🎯 Funcionalidades Principales

* **Panel de Métricas en Tiempo Real (KPIs):** Contadores dinámicos de tickets *Abiertos*, *En Revisión*, *Resueltos* y total de *Activos TI* inventariados.
* **Gestión Completa de Tickets de Soporte:** Registro de incidencias asociadas a solicitante, departamento, código de equipo, categoría (*Hardware, Software/OS, Red/Conectividad, Mantenimiento*) y nivel de prioridad (*Alta, Media, Baja*).
* **Control de Inventario y Mantenimiento Preventivo:** Registro de laptops, equipos de escritorio e infraestructura de red con trazabilidad de asignación y actualización rápida de fecha de mantenimiento preventivo (`Mant. Hoy`).
* **Búsqueda y Filtrado Instantáneo:** Filtrado en tiempo real por código de ticket, solicitante, activo, descripción o estado operativo.
* **Exportación de Reportes CSV:** Generación y descarga directa de reportes operativos en formato `.csv` listos para auditoría o análisis en Excel/Google Sheets.
* **Persistencia Local Automática:** Almacenamiento en el navegador mediante `localStorage` con opción de restauración de datos de demostración (`Cargar Demo`).

---

## 🛠️ Stack Tecnológico

* **Estructura:** HTML5 Semántico
* **Estilos & Diseño:** Tailwind CSS (Interfaz oscura responsiva *Mobile-First*)
* **Lógica & Estado:** JavaScript (ES6+) Vanilla
* **Persistencia & Datos:** Web Storage API (`localStorage`) + Generación dinámica de archivos CSV

---

## 📂 Estructura del Proyecto

```text
helpdesk-inventario-ti/
├── index.html      # Aplicación web completa (UI, lógica CRUD, filtros y exportador CSV)
└── README.md       # Documentación técnica del repositorio
```

---

## 🚀 Ejecución Local

No requiere instalación de dependencias ni servidor backend:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/aortegadevpa/helpdesk-inventario-ti.git
   ```
2. Abre el archivo `index.html` directamente en tu navegador web favorito.

---

👤 **Desarrollado por:** [Angel Ortega](https://aortegadevpa.github.io/Portafolio/) — Desarrollo de Software, Soporte Técnico TI & Automatización con IA (Panamá)