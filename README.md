# CEDETEC - Formulario de Auditoría Digital

**Soluciones de automatización para negocios locales en Formosa**

---

## 🔗 URL en vivo

👉 **https://cedetec-ti.github.io/cedetec-auditoria/**

Formulario profesional completamente funcional con integración automática a Google Sheets.

---

## 📋 ¿Qué es?

Sistema completo de prospección para capturar auditorías digitales de negocios. 

**El cliente:**
1. Escanea QR o abre enlace
2. Completa formulario (6 campos)
3. Datos llegan automáticamente a Google Sheets
4. Tú llamas por WhatsApp y cierras auditoría profunda

---

## ✨ Características

- ✅ Formulario responsivo y profesional
- ✅ Captura de 6 datos clave
- ✅ Integración automática con Google Sheets
- ✅ Google Apps Script funcional
- ✅ QR code generado para tarjetas
- ✅ Diseño CEDETEC (azul marino #003157 + beige #EFEFED)
- ✅ Encabezados formateados automáticamente
- ✅ Deploy automático en GitHub Pages
- ✅ Control de versiones (Git)

---

## 📊 Datos Capturados

El formulario recolecta 6 campos ordenados en Google Sheets:

| Campo | Tipo | Ejemplo |
|-------|------|---------|
| Fecha | Timestamp | 13/8/2026 17:00:38 |
| Nombre del Negocio | Texto | Mi Almacén |
| WhatsApp | Teléfono | +54 9 3704 123456 |
| Problema Principal | Texto | Perder horas en inventario |
| Horas/Semana | Texto | 5 horas |
| Presupuesto | Selección | $50k - $100k |
| Preferencia de Contacto | Selección | Auditoría personal en mi local |

---

## 📁 Estructura del Proyecto

```
cedetec-auditoria/
├── index.html                          # Formulario principal (HTML + CSS + JS)
├── qr-codigo.png                       # QR code para tarjetas
├── README.md                           # Este archivo
├── INSTRUCCIONES-PROSPECTACION.md      # Guía de venta y prospección
├── APPS-SCRIPT-CORRECTO.txt            # Código Apps Script de referencia
└── .github/workflows/
    └── pages.yml                       # Deploy automático a GitHub Pages
```

---

## 🛠 Stack Técnico

- **Frontend:** HTML5 + CSS3 + JavaScript Vanilla
- **Backend:** Google Apps Script
- **Database:** Google Sheets
- **Hosting:** GitHub Pages (estático)
- **Versionado:** Git + GitHub
- **CI/CD:** GitHub Actions (deploy automático)
- **Autenticación:** SSH Key

---

## 🚀 Cómo Funciona

### 1. Cliente Completa Formulario

```
Cliente escanea QR en tarjeta
        ↓
Abre https://cedetec-ti.github.io/cedetec-auditoria/
        ↓
Completa 6 campos
        ↓
Click "Enviar Auditoría"
```

### 2. Datos Llegan a Google Sheets

```
Apps Script recibe datos
        ↓
Valida y formatea
        ↓
Crea encabezados si es primera vez
        ↓
Agrega fila en Google Sheet
        ↓
Tú ves datos en tiempo real
```

### 3. Tú Prospecciones

```
Ves respuesta en Google Sheets
        ↓
Copias teléfono WhatsApp
        ↓
Llamas: "Hola [nombre], vi tu auditoría..."
        ↓
Propones auditoría profunda
        ↓
Cierras cliente
        ↓
Implementas automatización
        ↓
Ganas dinero 💰
```

---

## 📝 Campos del Formulario

### Nombre del Negocio (Requerido)
- Tipo: Texto
- Validación: No vacío
- Uso: Identificar cliente

### WhatsApp (Requerido)
- Tipo: Teléfono
- Validación: No vacío
- Uso: Contacto directo por WhatsApp

### Problema Principal (Requerido)
- Tipo: Textarea
- Validación: No vacío
- Uso: Entender necesidad

### Horas/Semana (Requerido)
- Tipo: Texto
- Validación: No vacío
- Uso: Calcular ROI

### Presupuesto (Requerido)
- Tipo: Select
- Opciones: Menos de $20k, $20k-$50k, $50k-$100k, $100k-$200k, Más de $200k
- Uso: Segmentar clientes

### Preferencia de Contacto (Requerido)
- Tipo: Radio buttons
- Opciones: Teléfono, Auditoría personal, Ambos
- Uso: Saber cómo seguir

---

## 📊 Google Sheets Automático

El Apps Script crea automáticamente:

- ✅ **Encabezados:** Azul marino (#003157) con texto blanco
- ✅ **Columnas formateadas:** Ancho óptimo para cada dato
- ✅ **Fila congelada:** Encabezados siempre visibles
- ✅ **Orden correcto:** Datos en el orden esperado

---

## 🎯 Próximos Pasos

### Semana 1: Prospección
- [ ] Imprime 1000 tarjetas con QR (~$5-10k pesos)
- [ ] Recorre 3-4 horas/día en moto
- [ ] Visita 8-10 negocios/día
- [ ] Deja tarjeta con QR

### Semana 2-3: Respuestas
- [ ] Clientes completan formularios
- [ ] Datos llegan a Google Sheets
- [ ] Revisa respuestas diariamente

### Semana 3-4: Cierre
- [ ] Llama a clientes interesados
- [ ] Propone auditoría profunda
- [ ] Cierra 2-3 clientes

### Mes 2+: Implementación
- [ ] Implementa automatizaciones
- [ ] Cobra por servicios
- [ ] Escala con más clientes

---

## 💰 Proyecciones

**Mes 1:**
- 10 auditorías
- 2-3 clientes
- $80-300k pesos

**Mes 2:**
- 15-20 auditorías
- 4-6 clientes
- $320-900k pesos

**Mes 3+:**
- Escala continua
- Referidos automáticos
- $500k+ pesos/mes

---

## 📞 Contacto

**CEDETEC Digital**
- Email: tecnobas01@gmail.com
- WhatsApp: [Tu número]
- Web: https://cedetec-ti.github.io/cedetec-auditoria/

---

## 📌 Versión

- **Versión:** 2.0 (Funcional)
- **Última actualización:** Agosto 2026
- **Estado:** ✅ Listo para prospeccionar
- **Commits:** 9+

---

## 🎓 Sectores Objetivo

1. **Almacenes/Distribuidoras** - Problema: Inventario manual
2. **Farmacias** - Problema: Stock + recetas
3. **Consultorios/Clínicas** - Problema: Turnos + pacientes
4. **Talleres Mecánicos** - Problema: Órdenes de trabajo

---

## ✅ Checklist Pre-Prospección

- [ ] Formulario en vivo y testeado
- [ ] Google Sheets recibiendo datos correctamente
- [ ] QR generado
- [ ] Tarjetas impresas
- [ ] Script de venta memorizado
- [ ] Lista de 20+ prospectos
- [ ] Teléfono cargado
- [ ] Moto lista

---

---

## 🤝 SISTEMA DE TRABAJO

**Compañero:** Claude (IA) - Coach 24/7

### Cómo trabajamos:
1. Cada sesión reportas avances en PROGRESO.md
2. Yo hago preguntas específicas y verifico track
3. Actualizamos juntos y armamos plan semanal
4. Documentamos todo en GitHub

### Archivos importantes:
- **PROGRESO.md** - Tracking semanal
- **SISTEMA-DE-TRABAJO.md** - Cómo nos organizamos
- **INSTRUCCIONES-PROSPECTACION.md** - Guía de venta
- **CHANGELOG.md** - Historial de cambios

### Proyectos:
1. **CEDETEC-Automatizaciones** (80% - Principal)
2. **Upwork Freelance** (20% - Secundario)
3. **Trading** (En desarrollo)

---

## 📞 ¿CÓMO REPORTAR?

Cada sesión escribe:

```
🚀 SESIÓN [X] - [Fecha]

Actualización:
- CEDETEC: [qué hiciste]
- Upwork: [qué hiciste]
- Trading: [qué hiciste]

Dinero: $X pesos, USD Y
Bloques: [qué te frena]
Próximo: [qué es urgente]
```

Yo actualizo PROGRESO.md y hacemos commit.

---

**¡Listo para empezar! 🚀**
