# 📁 ESTRUCTURA DEL PROYECTO CEDETEC

## Visión General

```
cedetec-auditoria/
├── 📄 Archivos principales (Root)
├── 📁 docs/           - Documentación
├── 📁 assets/         - Recursos (imágenes, etc.)
├── 📁 servicios/      - Páginas de servicios
└── 📁 .github/        - Configuración de GitHub
```

---

## 📄 ARCHIVOS EN RAÍZ (Root)

**Estos archivos DEBEN estar en el root para GitHub Pages**

```
index.html              ✅ Home / Página principal
sobre-nosotros.html     ✅ About / Historia de CEDETEC
servicios.html          ✅ Services / Listado de servicios
auditoria.html          ✅ Formulario de auditoría digital
qr-codigo.png           ✅ Código QR para auditoría
README.md               ✅ Documentación principal del proyecto
.gitignore              ✅ Archivos ignorados por Git
```

### URLs en vivo:
```
🌐 Home:        https://cedetec-ti.github.io/cedetec-auditoria/
🌐 About:       https://cedetec-ti.github.io/cedetec-auditoria/sobre-nosotros.html
🌐 Services:    https://cedetec-ti.github.io/cedetec-auditoria/servicios.html
🌐 Audit Form:  https://cedetec-ti.github.io/cedetec-auditoria/auditoria.html
```

---

## 📁 docs/ - DOCUMENTACIÓN

**Toda la documentación del proyecto**

```
docs/
├── README.md                      - Guía de esta carpeta
├── PROGRESO.md                    - Registro de progreso diario
├── RESUMEN-COMPLETADO.md          - Resumen de todo lo hecho
├── CHANGELOG.md                   - Historial de cambios
├── SISTEMA-DE-TRABAJO.md          - Metodología y procesos
├── INSTRUCCIONES-PROSPECTACION.md - Guía de prospección
└── APPS-SCRIPT-CORRECTO.txt       - Código Google Sheets
```

### Para consultar:
- **Últimas actualizaciones:** PROGRESO.md
- **Descripción completa:** RESUMEN-COMPLETADO.md
- **Cambios históricos:** CHANGELOG.md
- **Cómo prospectar:** INSTRUCCIONES-PROSPECTACION.md

---

## 🖼️ assets/ - RECURSOS

**Imágenes, iconos y archivos multimedia**

```
assets/
├── README.md          - Guía de esta carpeta
└── qr-codigo.png      - QR del formulario de auditoría
```

### Próximos recursos a agregar:
- Logo CEDETEC (vectorial)
- Favicon
- Imágenes de servicios
- Iconos personalizados
- Screenshots/testimonios

---

## 🔧 servicios/ - PÁGINAS DE SERVICIOS

**6 servicios individuales con estructura consistente**

```
servicios/
├── README.md              - Guía de esta carpeta
├── automatizacion.html    - Automatización de procesos
├── inventario.html        - Control de inventario
├── clientes.html          - Gestión de clientes
├── turnos.html            - Sistema de turnos
├── analisis.html          - Análisis de datos
└── integracion.html       - Integración de sistemas
```

### Estructura de cada página:
1. Hero section (título + descripción)
2. ¿Qué es? (explicación)
3. 6 Beneficios (ventajas)
4. 6 Casos de uso (industrias)
5. CTA (llamada a acción WhatsApp)

### URLs:
```
https://cedetec-ti.github.io/cedetec-auditoria/servicios/automatizacion.html
https://cedetec-ti.github.io/cedetec-auditoria/servicios/inventario.html
... etc
```

---

## 🔗 FLUJO DE NAVEGACIÓN

```
HOME (index.html)
├── Sobre nosotros → sobre-nosotros.html
├── Servicios → servicios.html
│   ├── Automatización → servicios/automatizacion.html
│   ├── Inventario → servicios/inventario.html
│   ├── Clientes → servicios/clientes.html
│   ├── Turnos → servicios/turnos.html
│   ├── Análisis → servicios/analisis.html
│   └── Integración → servicios/integracion.html
├── Contacto → footer (WhatsApp, teléfono, email)
└── Auditoría → auditoria.html
    └── WhatsApp pre-llenado
```

---

## 📊 ESTADÍSTICAS

| Métrica | Valor |
|---------|-------|
| Páginas HTML | 10 |
| Documentos | 6 |
| Imágenes | 1 (QR) |
| Total de archivos | ~20 |
| Links internos | 40+ |
| Líneas CSS | 2,000+ |
| Commits | 10+ |

---

## 🎯 CÓMO USAR ESTA ESTRUCTURA

### Para agregar contenido:
1. **Documentación:** Agregar a `docs/`
2. **Imágenes:** Agregar a `assets/`
3. **Nuevo servicio:** Crear HTML en `servicios/` siguiendo patrón

### Para actualizar:
1. Editar archivos HTML en root o `servicios/`
2. Editar documentación en `docs/`
3. Hacer commit: `git add . && git commit -m "mensaje"`
4. Push: `git push origin main`

### Para ver cambios en vivo:
- GitHub Pages actualiza automáticamente
- Ver en: https://cedetec-ti.github.io/cedetec-auditoria/

---

## 🚀 PRÓXIMOS PASOS

- [ ] Agregar más servicios
- [ ] Agregar imágenes a servicios
- [ ] Crear página de precios
- [ ] Agregar blog/testimonios
- [ ] Integrar Google Analytics
- [ ] Mejorar SEO

---

**Última actualización:** 14 Agosto 2026
**Desarrollador:** Claude (IA)
**Cliente:** Guillermo Bassi - CEDETEC Digital
