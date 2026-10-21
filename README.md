# Mi Control de Dinero para iPhone

Aplicación web progresiva para control manual, en un solo dispositivo.

Incluye:
- Panel mensual: ingresos recibidos y previstos, efectivo, banco, pagos y saldo disponible fuera del Libro Marrón.
- Registro de fuentes de ingresos, método de cobro, fecha y estado.
- Presupuestos editables: Hogar 300 €, Transporte 200 €, Sofía 30 €, Kayleighn 30 €, Gastos personales, Salidas y Otros.
- Registro de gastos principales por categoría.
- Libro Marrón con Navidad, Recibos y Retos. Apartar dinero registra un traspaso en el principal y una entrada en el Libro Marrón. Los gastos del Libro Marrón solo se registran allí, sin duplicar el gasto principal.
- Cierre mensual/anual, exportación JSON/CSV y restauración JSON.
- Datos guardados localmente en el navegador; sin cuentas ni conexión bancaria.

## Seguridad
La información se guarda solo en el almacenamiento local de Safari. Exporta una copia JSON con regularidad. No borres los datos del sitio sin copia. No subas copias JSON con información personal a un repositorio público.

## Publicar en GitHub Pages
Extrae este ZIP y sube/reemplaza en la raíz del repositorio los seis archivos de aplicación: index.html, app.js, manifest.webmanifest, sw.js, icon-192.png e icon-512.png. Mantén Pages publicando desde la rama principal y la carpeta raíz. Espera a que se publique y abre la URL del proyecto en Safari; usa Compartir > Añadir a pantalla de inicio.

## Nota
Esta versión no sincroniza entre dispositivos ni consulta automáticamente cuentas bancarias. Los ingresos previstos no son dinero cobrado; los presupuestos no son gastos realizados. Los traspasos al Libro Marrón son movimientos internos, no gastos de consumo.
