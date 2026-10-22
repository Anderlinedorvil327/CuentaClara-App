# CuentaClara

Aplicación web sencilla para registrar gastos, revisar un presupuesto mensual y comparar precios de referencia en pesos chilenos (CLP).

## Probar la aplicación

Abre [`index.html`](./index.html) en un navegador moderno. No requiere instalación, dependencias ni servidor.

Los gastos y el presupuesto se guardan en el almacenamiento local del navegador (`localStorage`); no se envían a un servidor. Para borrar esos datos, limpia el almacenamiento del sitio desde la configuración del navegador.

## Funciones

- Resumen de gastos por día, semana, mes o año.
- Presupuesto mensual y visualización de gastos por categoría.
- Registro, edición indirecta y eliminación de gastos.
- Comparación con precios de ejemplo para estimar posibles ahorros.
- Diseño adaptable y compatible con tema claro/oscuro.

## Datos y limitaciones

- Los precios de supermercados son ficticios y se usan solo como demostración. No representan precios actuales ni ofertas reales.
- El lector de boletas necesita una integración de reconocimiento de imágenes proporcionada por el entorno de ejecución. Esa integración no viene incluida en este proyecto y no está disponible al publicar el sitio estático en GitHub Pages; en ese caso, los gastos se pueden ingresar manualmente.
- No se requiere ni se debe publicar ninguna clave de API para usar las funciones disponibles en esta versión.

## Publicar en GitHub Pages

1. Sube los archivos del proyecto a un repositorio de GitHub.
2. En el repositorio, abre **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**.
4. Selecciona la rama que contiene el proyecto y la carpeta raíz (`/`), y guarda.
5. Abre la URL que GitHub Pages muestre en esa sección.

Al estar `index.html` en la raíz, GitHub Pages lo usará como página inicial.
