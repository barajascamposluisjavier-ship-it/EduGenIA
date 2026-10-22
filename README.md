This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/pages/api-reference/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/pages/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn-pages-router) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/pages/building-your-application/deploying) for more details.

## Reglas de ramas y Pull Requests

**Ramas**
- `main`: versión estable. **Nadie hace push directo.**
- Cada integrante trabaja solo en su rama:
  - José: `feat/jose-ui`
  - Luis: `feat/luis-backend`
  - Eder: `feat/eder-auth-data`

**Flujo de trabajo**
1. Antes de empezar: `git pull origin main`.
2. Programar solo en los archivos de tu módulo.
3. Guardar y subir: `git add .` → `git commit -m "feat: descripción"` → `git push`.
4. Abrir un Pull Request hacia `main`.
5. Otro compañero lo revisa y aprueba (mínimo 1 aprobación).
6. Se hace el merge y todos corren `git pull origin main`.

**Reglas**
- PRs pequeños y frecuentes, no uno gigante al final.
- No modificar archivos de otro módulo sin avisar.
- Avisar antes de instalar dependencias o cambiar `package.json`.
- Nunca subir `.env.local` ni claves (usar `.env.example`).
- Resolver los comentarios de la revisión antes del merge.
- Mensajes de commit con prefijo: `feat:` (nuevo), `fix:` (corrección), `docs:` (documentación), `chore:` (configuración).
