# ◈ xL1F3 Site Cloner v1.0

**by xL1F3 software**

Clonador profesional de sitios web con reescritura offline correcta, auto-carpeta y generación automática de ZIP.

---

## ⚠ Aviso Legal

Este software es **propietario y de código cerrado**.

- ❌ No se distribuye el código fuente
- ❌ No se permite modificación, descompilación o ingeniería inversa
- ❌ No se permite redistribución sin autorización expresa
- ✅ Uso autorizado únicamente por el titular de la licencia

**Copyright © 2024-2026 xL1F3 Software. Todos los derechos reservados.**

---

## ✨ Características

| Función | Descripción |
|---------|-------------|
| **Clonado Completo** | Descarga HTML, CSS, JS, imágenes, fuentes, medios |
| **Reescritura Offline** | Enlaces reescritos DESPUÉS de descargar todo (flujo correcto de dos pasadas) |
| **Auto-Carpeta** | Crea carpeta con nombre derivado del dominio + ruta URL |
| **ZIP Automático** | Genera archivo ZIP comprimido al finalizar |
| **Estructura Espejo** | Preserva jerarquía de URLs en carpetas locales |
| **Detección Encoding** | BOM + meta charset + fallback UTF-8 |
| **CSS Imports Recursivos** | @import y url() dentro de CSS se descargan automáticamente |
| **Validación Post-Rewrite** | Verifica que todos los enlaces relativos apunten a archivos existentes |
| **Manifiesto JSON** | Metadatos completos del clonado para auditoría |
| **GUI Profesional** | Dark theme, progress bar, log coloreado, selector de directorio nativo |
| **Multi-Thread** | Descarga paralela de assets configurable |
| **Robots.txt** | Respeto opcional a directivas de rastreo |
| **Dominio www** | Comparación inteligente ignora prefijo www |

---

## 🖥️ Requisitos

- Windows 10/11 (64-bit)
- No requiere instalación
- No requiere Python ni dependencias externas
- Ejecutable autónomo (`xL1F3_SiteCloner.exe`)

---

## 🚀 Uso

1. Ejecutar `xL1F3_SiteCloner.exe`
2. Ingresar URL del sitio a clonar
3. Seleccionar directorio base con el botón 📁
4. Configurar opciones según necesidad
5. Presionar **▶ INICIAR CLONADO**
6. Esperar finalización → carpeta + ZIP generados automáticamente

### Formatos de URL Soportados

- URL completa: `https://example.com/path/page`
- Dominio simple: `example.com`
- Con protocolo: `http://` o `https://`

### Opciones Disponibles

| Opción | Descripción | Default |
|--------|-------------|---------|
| Profundidad máx | Niveles de enlaces a seguir | 2 |
| Páginas máx | Límite de páginas a descargar | 100 |
| Workers | Hilos paralelos para assets | 8 |
| Delay (s) | Pausa entre requests | 0.5 |
| Respetar robots.txt | Obedecer directivas de rastreo | Desactivado |
| Reescribir enlaces | Convertir URLs absolutas a relativas | Activado |
| Descargar assets | CSS, JS, imágenes, fuentes, medios | Activado |
| Solo mismo dominio | Ignorar enlaces externos (ignora www) | Activado |
| Auto-carpeta | Crear carpeta con nombre del sitio | Activado |
| Preservar estructura | Mantener jerarquía de URLs | Activado |
| Crear ZIP | Comprimir resultado al finalizar | Activado |

---

## 📁 Salida Generada
