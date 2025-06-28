# AGUA-NEWENKO
COMPRA Y VENTA DE AGUA PURIFICADA Y AGUA SABORIZADA
# 💧 Aguas Newenko – Sistema de Gestión Interna

Plataforma digital integral para la gestión operativa, contable y logística de la empresa Aguas Newenko (agua purificada y saborizada).

## 🚀 Características clave

* Login con control de acceso por rol
* Finanzas: ingresos, egresos, balance, metas y proyecciones
* Pedidos y reparto con seguimiento
* Reportes exportables (PDF, Excel)
* Respaldos automáticos diarios/semanales/anuales a Google Drive
* Reporte ejecutivo automático por correo
* Panel de monitoreo de servicios y estado del sistema
* Centro de notificaciones, soporte interno y auditoría

## 🧰 Tecnologías utilizadas

* React (frontend)
* Tailwind CSS (UI)
* Node.js (backend/respaldo)
* Railway (deploy + cron)
* Google Drive API (respaldos)
* jsPDF + html2canvas (PDF)

## 📦 Instalación local

```bash
git clone https://github.com/aguas-newenko/app.git
cd app
npm install
npm run dev
```

## ⚙️ Variables de entorno (.env)

```env
VITE_API_FINANZAS=https://api.aguasnewenko.cl/finanzas
VITE_GOOGLE_DRIVE_TOKEN=...
VITE_CARPETA_DRIVE_ID=...
VITE_REPORT_EMAIL=gerencia@aguasnewenko.cl
```

## 🛠️ Comandos Railway

```bash
node respaldo_diario.js
node reporte_ejecutivo.js
```

## 📚 Manuales

* `docs/ManualAdministrador.md`
* `docs/ManualFinanzasReparto.md`

## ✅ Estado

Proyecto completo y listo para producción.
