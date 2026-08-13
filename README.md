# CEDETEC - Formulario de Auditoría Digital

**Soluciones de automatización para negocios locales en Formosa**

## 🔗 URL en vivo

👉 **https://cedetec-ti.github.io/cedetec-auditoria/**

---

## 📋 ¿Qué es?

Formulario profesional para capturar información de auditoría de negocios. Diseñado para prospectar clientes y entender sus necesidades de automatización.

### Características

- ✅ Formulario responsivo y profesional
- ✅ Conexión automática con Google Sheets
- ✅ 5 preguntas de diagnóstico clave
- ✅ Integración con Apps Script de Google
- ✅ QR para compartir en tarjetas
- ✅ Diseño CEDETEC (azul marino + beige)

---

## 📁 Estructura del Proyecto

```
cedetec-auditoria/
├── index.html              # Formulario principal
├── qr-codigo.png          # QR code para tarjetas
├── README.md              # Este archivo
└── .github/workflows/
    └── pages.yml          # Deploy automático a GitHub Pages
```

---

## 🎯 Cómo Usar

### Para Prospectar

1. **Genera una tarjeta** con el QR (`qr-codigo.png`)
2. **Imprime 1000 tarjetas** en imprenta local (~$5k pesos)
3. **Recorre negocios en moto** y ofrece "auditoría gratis 30 min"
4. **Deja tarjeta con QR** o muéstralo en tu teléfono
5. **Cliente escanea QR** → Abre formulario → Completa preguntas
6. **Los datos llegan automáticamente a Google Sheets**

### Para Editar el Formulario

1. **Edita `index.html`** en VS Code
2. **Haz cambios** en preguntas, diseño, etc.
3. **Git commit y push automático** (yo manejo esto)
4. **Cambios en vivo** en 1-2 minutos

---

## 📊 Datos Recolectados

El formulario captura:

- Nombre del negocio
- Problema principal de tiempo/dinero
- Horas/semana perdidas
- Presupuesto disponible
- Preferencia de contacto (teléfono, auditoría personal, ambos)

Todos los datos van a **Google Sheets** automáticamente.

---

## 🔧 Stack Técnico

- **Frontend:** HTML5 + CSS3 + JavaScript
- **Backend:** Google Apps Script
- **Database:** Google Sheets
- **Hosting:** GitHub Pages
- **Versionado:** Git + GitHub
- **Deploy:** Automático vía GitHub Actions

---

## 📝 Próximas Mejoras

- [ ] Agregar campos personalizados por sector
- [ ] Integración con WhatsApp automático
- [ ] Dashboard de resultados en tiempo real
- [ ] Envío de propuestas automáticas
- [ ] Analytics de formulario

---

## 🚀 Próximos Pasos

1. **Imprime tarjetas** con el QR
2. **Empieza prospección** en Formosa
3. **Recibe datos en Google Sheets**
4. **Califica leads** y llama para auditoría profunda
5. **Cierra clientes** y empieza implementación

---

## 📞 Contacto

**CEDETEC Digital**  
Formosa, Argentina  
Email: tecnobas01@gmail.com

---

*Actualizado: Agosto 2026*  
*Versión: 1.0*
