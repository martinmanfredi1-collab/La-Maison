# La Maison Buffet - Sistema de caja

Sitio estático (HTML/JS). Los datos se guardan en Supabase.

## Puesta en marcha
1. En `config.js` pegar la **Project URL** y la **anon public key** de Supabase.
2. Subir todos los archivos a este repositorio de GitHub.
3. En Netlify: **Add new site → Import from Git** y elegir este repositorio.
   - Build command: (vacío)
   - Publish directory: (vacío o `.`)
4. Cada cambio que subas a GitHub se publica solo en https://lamaisonbuffet.netlify.app/

## Archivos
- `index.html`: la aplicación completa.
- `config.js`: credenciales públicas de Supabase (la anon key es pública por diseño; la seguridad la da el login y las reglas RLS de la tabla).
