# 🚗 Trayectos App

> App PWA para control de rutas, kilometraje y tiempo laborado — diseñada para uso móvil desde el navegador.

🔗 **Demo en vivo:** [byeilerdev.github.io/trayectos-app](https://byeilerdev.github.io/trayectos-app/)

---

## 📱 Vista general

Aplicación web progresiva (PWA) para el registro y control de trayectos vehiculares. Permite llevar un historial detallado de rutas, kilómetros recorridos y tiempo laborado, con exportación a Excel y PDF.

---

## ✨ Funcionalidades

- 📝 **Registro de trayectos** — fecha, código, sitio de inicio/fin, horarios en AM/PM
- ⏱️ **Cálculo automático** de tiempo en ruta y jornada laboral
- 📍 **KM recorridos** calculados automáticamente
- 🔍 **Filtros** por fecha, mes, conductor y vehículo
- 📊 **Resúmenes** por conductor y por vehículo
- ✏️ **Editar y duplicar** registros existentes
- 🗑️ **Eliminar** con modal de confirmación
- 📤 **Exportar a Excel** (.xlsx) con totales
- 📄 **Exportar a PDF** con tabla formateada
- 🌙 **Modo oscuro** con persistencia de preferencia
- 🔤 **Autocompletar** conductor y móvil con datos previos
- 💾 **Persistencia local** con localStorage
- 📲 **Instalable como PWA** en Android e iOS

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura y semántica |
| CSS3 | Diseño responsive, variables, animaciones |
| JavaScript (Vanilla) | Lógica de negocio, sin frameworks |
| SheetJS (xlsx) | Exportación a Excel |
| jsPDF + AutoTable | Generación de PDF |
| localStorage | Persistencia de datos |
| PWA (Web App Manifest) | Instalación en dispositivo móvil |

---

## 🚀 Cómo usar

### En el navegador
1. Abre el [link de la app](https://byeilerdev.github.io/trayectos-app/)
2. Empieza a registrar trayectos desde la pestaña **Nuevo**

### Instalar en celular (Android)
1. Abre el link en Chrome
2. Toca los tres puntos → **"Agregar a pantalla de inicio"**
3. La app queda instalada como si fuera nativa

### Correr localmente
```bash
git clone https://github.com/ByEilerDev/trayectos-app.git
cd trayectos-app
# Abre index.html en tu navegador
```

---

## 📂 Estructura del proyecto

```
trayectos-app/
└── index.html      # App completa en un solo archivo
```

---

## 💡 Decisiones de diseño

- **Single file app** — toda la lógica, estilos y estructura en un solo `index.html` para máxima portabilidad y facilidad de despliegue
- **Sin frameworks** — JavaScript vanilla para demostrar dominio de los fundamentos del lenguaje
- **Mobile-first** — diseñada primero para pantallas de celular, con navegación inferior tipo app nativa
- **localStorage** — almacenamiento del lado del cliente, sin necesidad de backend para uso personal

---

## 🔮 Próximas mejoras

- [ ] Sincronización en la nube (Firebase / Supabase)
- [ ] Múltiples usuarios con autenticación
- [ ] Gráficas de KM por semana/mes
- [ ] Backup y restauración de datos

---

## 👨‍💻 Autor

**ByEilerDev**  
GitHub: [@ByEilerDev](https://github.com/ByEilerDev)

---

> Proyecto desarrollado como herramienta real de uso personal, con enfoque en UX móvil y funcionalidad práctica.
