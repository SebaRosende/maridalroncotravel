# ✈️ Mari's Travel - Descubriendo Perú

Plataforma web de alto rendimiento desarrollada para una agencia de viajes internacional. El proyecto destaca por su arquitectura escalable, optimización de infraestructura y un sistema de internacionalización dinámico con soporte nativo para alfabetos no latinos.

## 🚀 Web

🌐 **Sitio en vivo:** [marys-travel.com](https://marys-travel.com)

---

## 🛠️ Stack Tecnológico

| Categoría | Tecnologías |
| --- | --- |
| **Frontend** | Next.js 16 (App Router), React 19, Tailwind CSS 4 |
| **Lenguaje** | TypeScript |
| **Infraestructura** | Vercel Edge Network, Cloudflare (DNS/WAF) |
| **Monitoreo** | Vercel Analytics (Core Web Vitals) |
| **UI/UX** | Lucide React, Google Fonts (Assistant) |

---

## 🌟 Características Principales

### 🌍 Internacionalización Pro (i18n)

* **Soporte Multilingüe:** Español, Inglés y Hebreo.
* **Arquitectura RTL:** Adaptación automática de la interfaz para lectura de derecha a izquierda (Hebreo).
* **Ruteo Dinámico:** Uso de `app/[lang]/` para una navegación SEO-friendly sin duplicidad de archivos.

### 🛡️ Infraestructura y Seguridad

* **Cloudflare Integration:** Gestión de DNS ultra-rápida, protección WAF contra ataques DDoS y certificados SSL/TLS automáticos.
* **Auditoría de Dependencias:** Limpieza profunda de vulnerabilidades transitivas (0 High Severity Vulnerabilities) garantizando un código seguro en producción.
* **Vercel Analytics:** Monitoreo en tiempo real de la experiencia de usuario y rendimiento (LCP, FID, CLS).

### ⚡ Rendimiento Optimizado

* **Fuentes Inteligentes:** Implementación de `@next/font` para eliminar el parpadeo de texto (layout shift).
* **Despliegue Global:** Servido a través de la red perimetral de Vercel para baja latencia en cualquier parte del mundo.

---

## 📂 Estructura del Proyecto

```text
├── app/
│   └── [lang]/         # Rutas dinámicas por idioma (ES, EN, HE)
│       ├── layout.tsx  # Configuración global, SEO y Analíticas
│       └── page.tsx    # Página principal
├── components/         # Componentes UI (Navbar, Footer, Hero)
├── lib/                # Lógica de i18n, diccionarios y helpers
├── public/             # Assets estáticos (Logo Mary, Imágenes)
└── middleware.ts       # Lógica de ruteo y redirección inteligente

```

---

## 🧠 Desafíos Técnicos y Soluciones

> **Caso: Resolución de Bucles de Redirección**
> * **El Problema:** Al implementar el ruteo dinámico, el middleware generaba rutas recursivas (ej: `/es/en`), causando errores 404 y bucles infinitos.
> * **La Solución:** Desarrollé una lógica de filtrado en el Middleware de Next.js que valida la existencia del prefijo de idioma antes de aplicar la redirección por defecto. Se eliminaron "fantasmas" de frameworks innecesarios (Nuxt) detectados en una auditoría de seguridad, resultando en una arquitectura 100% limpia.
> 
> 

---

## 📸 Capturas de Pantalla

| Vista Desktop | Vista Mobile (Hebreo RTL) |
| --- | --- |
| <img width="400" alt="Home ES" src="[https://github.com/user-attachments/assets/4018dafe-caeb-4bbc-9fc9-c0db1cd37bcc](https://github.com/user-attachments/assets/4018dafe-caeb-4bbc-9fc9-c0db1cd37bcc)" /> | <img width="200" alt="Mobile HE" src="[https://github.com/user-attachments/assets/c5a19c76-c9cd-41b7-bbbd-860bd1981b59](https://github.com/user-attachments/assets/c5a19c76-c9cd-41b7-bbbd-860bd1981b59)" /> |

---

## 👤 Autor

**Sebastian Rosende**

* 🎓 Estudiante de Desarrollo de Aplicaciones en **UNICEN**.
* 🛠️ Especializado en Fullstack Development e IT Infrastructure.

---
