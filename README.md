# Carta de presentación — Juan David Zambrano Becerra

Página de presentación personal sencilla, construida con HTML y Tailwind CSS. Muestra un breve resumen de formación y las tecnologías con las que se trabaja, con enlaces a redes sociales.

## Tecnologías

- HTML5
- Tailwind CSS v4 (vía `@tailwindcss/cli`)
- `@midudev/tailwind-animations` (animaciones de entrada)

## Cómo abrir o ejecutar la página

No requiere servidor ni pasos de compilación para verse:

1. Abre el archivo `index.html` directamente en tu navegador (doble clic o `File > Abrir archivo`).
2. Los estilos ya están generados en `assets/outpout.css`.

Para regenerar los estilos CSS tras editar `input.css`:

```bash
npm install
npm run build:styles
```

Esto ejecuta `npx @tailwindcss/cli -i ./input.css -o ./assets/outpout.css --watch`.

## Enlaces de redes sociales

Solo se confirma una red social, proporcionada por el usuario:

- LinkedIn: `https://www.linkedin.com/in/juan-david-zambrano-becerra-687953423/` (URL real, ya incluida en la página)

El usuario indicó que no tiene más redes sociales (Instagram, YouTube, X), por lo que esos botones se omitieron intencionalmente en `index.html` para no publicar enlaces genéricos ni inventados. Si en el futuro agrega alguna, añádela aquí y en la sección de redes del HTML.

## Idioma

La página está en español (`<html lang="es">`).
