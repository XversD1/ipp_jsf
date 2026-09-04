# ⛪ Iglesia Príncipe de Paz | Ministerio JSF

![Logo JSF](https://github.com/XversD1/ipp_jsf/blob/main/img/JSF%20LOGO%20VECTOR6.png?raw=true)

> **Jóvenes Sin Fronteras (JSF)**: Plataforma web exclusiva para la gestión y registro de miembros del ministerio de jóvenes.

link:
https://registrarsejsf.netlify.app/
---

## 📖 Descripción

Este proyecto es una aplicación web ligera y eficiente diseñada para facilitar el registro de los jóvenes de la iglesia. La aplicación permite:

1.  **Registro Público:** Un formulario sencillo para que los nuevos miembros ingresen sus datos (Nombre, Apellido, Fecha de Nacimiento).
2.  **Administración Privada:** Una sección protegida por contraseña donde los líderes pueden visualizar la base de datos completa de los registrados.

## 🛠️ Tecnologías Utilizadas

*   **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS).
*   **Backend / Base de Datos:** [Supabase](https://supabase.com/) (PostgreSQL en la nube).
*   **Hosting:** [Netlify](https://www.netlify.com/) (Despliegue continuo y CDN global).

## 🚀 Características

*   ✅ **Sin Servidores Locales:** Todo está alojado en la nube (Serverless).
*   ✅ **Seguridad Básica:** Acceso restringido a la tabla de datos mediante contraseña.
*   ✅ **Diseño Responsivo:** Adaptable a móviles y escritorio.
*   ✅ **Actualizaciones en Tiempo Real:** Los datos se reflejan instantáneamente al recargar.

## 📂 Estructura del Proyecto

```text
ipp_jsf/
├── index.html      # Página de registro (pública)
├── admin.html      # Panel de administración (protegido con contraseña)
├── img/            # Recursos visuales (logos, íconos)
└── README.md       # Documentación del proyecto
