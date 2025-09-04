# 📚 Portal de Programación

Material educativo para fundamentos de programación.

## 🔑 Licencia

- El **código** (HTML, CSS, YAML, etc.) se distribuye bajo licencia [MIT](LICENSE).
- El **contenido educativo** (textos, explicaciones, artículos) se distribuye bajo licencia 
  [Creative Commons BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Esto significa:
- Podés leer y compartir libremente el material, siempre dando atribución.
- No podés usarlo con fines comerciales.
- Si lo adaptás, debe mantenerse con la misma licencia.


Blog educativo con material de estudio y tutoriales de programación.

## Desarrollo Local

1. Instalar dependencias:
   \`\`\`bash
   npm install
   \`\`\`

2. Compilar CSS en modo desarrollo (con watch):
   \`\`\`bash
   npm run dev
   \`\`\`

3. Compilar CSS para producción:
   \`\`\`bash
   npm run build
   \`\`\`

## Despliegue

El sitio se despliega automáticamente en GitHub Pages cuando se hace push a la rama `main`. El workflow de GitHub Actions:

1. Instala las dependencias
2. Compila el CSS con Tailwind
3. Despliega el sitio estático

## Estructura

- `index.html` - Página principal
- `src/input.css` - CSS fuente con Tailwind
- `dist/styles.css` - CSS compilado (generado automáticamente)
- `tailwind.config.js` - Configuración de Tailwind
- `.github/workflows/deploy.yml` - Workflow de despliegue