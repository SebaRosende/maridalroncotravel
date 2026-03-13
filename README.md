# ✈️ Mari's Travel - Descubriendo Perú

Este proyecto es una plataforma web moderna desarrollada para una agencia de viajes, enfocada en la escalabilidad, el rendimiento y la accesibilidad internacional. El desarrollo implementa una arquitectura robusta utilizando el **App Router de Next.js** y un sistema de internacionalización dinámico.

## 🚀 Demo

Puedes ver la aplicación en producción aquí: https://marys-travel.com

---

## 🛠️ Tecnologías Aplicadas

* **Framework:** [Next.js 16](https://nextjs.org/) (App Router)
* **Biblioteca UI:** [React 19](https://react.dev/)
* **Estilos:** [Tailwind CSS 4](https://tailwindcss.com/)
* **Lenguaje:** [TypeScript](https://www.google.com/search?q=https://www.typescript.org/)
* **Analíticas:** [Vercel Analytics](https://vercel.com/analytics)
* **Iconografía:** [Lucide React](https://lucide.dev/)

---

## 🌟 Características Principales

### 1. Internacionalización (i18n) & Soporte RTL

La aplicación cuenta con soporte nativo para tres idiomas: **Español, Inglés y Hebreo**.

* **Ruteo Dinámico:** Implementación de rutas mediante `app/[lang]/` para una navegación limpia.
* **Soporte RTL (Right-to-Left):** Ajuste automático de la dirección del documento para el idioma hebreo, garantizando una experiencia de usuario nativa.
* **Middleware de Detección:** Un middleware personalizado gestiona las redirecciones basadas en el idioma preferido o la URL solicitada.

### 2. Infraestructura y Despliegue

* **Vercel Edge Network:** Despliegue optimizado para baja latencia global.
* **Seguridad:** Auditoría de dependencias rigurosa para garantizar un entorno libre de vulnerabilidades (0 high severity vulnerabilities).
* **SEO Optimizado:** Generación dinámica de metadatos según el idioma seleccionado.

### 3. Rendimiento y UX

* **Fuentes Optimizadas:** Uso de `next/font` para cargar la tipografía *Assistant* sin parpadeos (CLS bajo).
* **Diseño Responsive:** Interfaz adaptativa para móviles y escritorio con Tailwind CSS.

---

## 📂 Estructura del Proyecto

```text
├── app/
│   └── [lang]/         # Rutas dinámicas por idioma
│       ├── layout.tsx  # Configuración global, SEO y Analíticas
│       └── page.tsx    # Página principal
├── components/         # Componentes reutilizables (Navbar, Footer, etc.)
├── lib/                # Lógica de i18n y diccionarios
├── public/             # Activos estáticos (Imágenes, Logos)
└── middleware.ts       # Lógica de ruteo y redirección de idiomas

```

---

## 📸 Screenshots

| Home (Español) | Mobile View (Hebreo - RTL) |
<img width="368" height="750" alt="image" src="https://github.com/user-attachments/assets/4018dafe-caeb-4bbc-9fc9-c0db1cd37bcc" />
<img width="349" height="597" alt="image" src="https://github.com/user-attachments/assets/c5a19c76-c9cd-41b7-bbbd-860bd1981b59" />




---

## 👤 Autor

**Sebastian Rosende**

* Estudiante de Desarrollo de Aplicaciones en **UNICEN**.





