# Kuanta - Gestión Financiera Inteligente 📊✨

Bienvenido a **Kuanta**, una solución integral de gestión y control de finanzas personales diseñada bajo el concepto de **Clean Minimalism**.

Esta plataforma cuenta con un enfoque dual innovador:
1. **Aplicación Android Nativa** (Jetpack Compose, Room Database, Kotlin Coroutines, MVVM).
2. **Aplicación Web Estática Multidispositivo** (HTML5, Tailwind CSS, Chart.js, LocalStorage).

Ambas implementaciones conviven de manera armoniosa en el mismo repositorio, permitiéndote compilar y generar tus APKs para celular mientras hospedas instantáneamente tu portal contable en la web mediante **GitHub Pages**.

---

## 🚀 Despliegue en GitHub Pages

Convertir este repositorio en una página web accesible desde cualquier celular o navegador de escritorio es sumamente sencillo. Sigue estos pasos rápidos:

1. **Sube el código a tu repositorio de GitHub**:
   - Pasa los archivos a tu carpeta local de Git y haz push a tu rama principal (ej. `main` o `master`).
2. **Activa GitHub Pages**:
   - Ve a la pestaña **Settings** (Configuración) de tu repositorio en GitHub.
   - En el menú lateral izquierdo, haz clic en **Pages**.
   - Bajo la sección **Build and deployment**:
     - Selecciona **Deploy from a branch** en el menú desplegable.
     - Bajo **Branch**, selecciona tu rama principal (ej. `main`) y la carpeta raíz (`/root`).
     - Haz clic en **Save** (Guardar).
3. **Disfruta de tu Web App**:
   - GitHub generará un enlace público en un par de minutos (generalmente `https://<tu-usuario>.github.io/<tu-repositorio>/`).
   - Abre la URL en cualquier dispositivo para usarla con sincronización local persistente en tu navegador.

---

## 📱 Características de la Web App (`index.html`)

Nuestra versión web replica al 100% de manera fiel las capacidades del software móvil nativo:

- **Estética Minimalista Slate**: Tonos suaves claros y negros que reducen el cansancio visual, con un selector de tema **Modo Oscuro** reactivo en la sección de Ajustes.
- **Gráficos en Tiempo Real (Chart.js)**: Tres pestañas interactivas de análisis:
  - *Gasto Diario*: Un gráfico lineal que ilustra las fluctuaciones de consumo en los últimos 7 días.
  - *Categorías*: Un diagrama tipo rosquilla pulido con colores pastel que desglosa porcentajes de consumo.
  - *Tasa de Ahorro*: Evolución de ahorro porcentual calculada mes a mes de manera inteligente.
- **Gestión Completa de Movimientos**: Búsqueda interactiva en tiempo real, filtros segmentados por ingresos/gastos y fichas horizontales de categorías para auditar movimientos rápidamente.
- **Calendario Financiero Dinámico**: Visualiza qué días exactos registraste actividad y pulsa sobre cualquier casilla numérica para desglosar sus transacciones en un menú contextual.
- **Alertas de Sobre-gasto**: Basadas en un motor inteligente que analiza tu promedio de gasto histórico y te previene mediante alertas si un cobro puntual se sale de tus límites comunes.
- **Metas de Ahorro Activas**: Panel de evolución de objetivos financieros con barras de progreso con gradientes dinámicos de carga.
- **Exportación Versátil**: Modulo para generar informes completos descargando un archivo formato `.csv` con todos tus registros al instante.
- **Seeding & Resets**: Botón rápido en Ajustes para restablecer valores simulados iniciales y realizar demostraciones al instante.

---

## 🛠️ Estructura del Proyecto

- `index.html` — Punto de entrada del cliente web optimizado para dispositivos móviles y escritorio.
- `app/` — Código fuente nativo de la aplicación para Android.
- `build.gradle.kts` — Scripts de construcción del motor compilador de Android Gradle.

---

*Desarrollado con pasión, diseñado para darte el control total de tu bienestar financiero.*
