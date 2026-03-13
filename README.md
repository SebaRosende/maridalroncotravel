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

## 📸 Capturas de Pantalla

| Vista Mobile (Hebreo RTL) |
| --- | 
| <img width="358" height="755" alt="image" src="https://github.com/user-attachments/assets/e7580d8b-5dca-41d0-9f3f-bec6ad728f82" />
 | <img width="358" height="756" alt="image" src="https://github.com/user-attachments/assets/3b2efe73-3612-46e8-bbbb-26c24079ccde" />
 

---

## 👤 Autor

**Sebastian Rosende**

* 🎓 Estudiante de Desarrollo de Aplicaciones en **UNICEN**.
* 🛠️ Especializado en Fullstack Development e IT Infrastructure.

---
