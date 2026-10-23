# SPEC: Portfolio Personal Trainee

## 1. Problema
No tengo un lugar público y profesional donde mostrar quién soy y qué prácticas vengo realizando como desarrollador trainee.

## 2. Usuario
Recrutadores técnicos y personas interesadas en ver mis primeros proyectos publicados.

## 3. Qué hace (alcance)
- Muestra una breve presentación personal sobre mí.
- Incluye una sección de proyectos con enlaces a mis repositorios de práctica (como `first-contributions`).
- Muestra enlaces de contacto directos (GitHub, email).
- Es responsive (se ve bien en celulares y computadoras).

## 4. Qué NO hace (fuera de alcance)
- No incluye formularios de contacto dinámicos por backend en esta versión.
- No tiene múltiples páginas (es de una sola pantalla / landing page).
- No incluye modo oscuro/claro por ahora.

## 5. Criterios de aceptación
- [ ] CA1: Dado que abro la página en un celular, cuando la visualizo, entonces los elementos se acomodan correctamente sin desbordar la pantalla.
- [ ] CA2: Dado que hago clic en el enlace de GitHub, cuando lo presiono, entonces me redirige a mi perfil o repositorio correspondiente.
- [ ] CA3: Dado que la página carga, cuando pasa menos de 2 segundos, entonces el contenido principal ya es visible.

## 6. Stack
- Front: HTML + CSS + Vite
- Deploy: Cloudflare Pages

## 7. Listo cuando
Está online en una URL pública de Cloudflare y los criterios de aceptación dan todos sí.
