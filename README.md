# 🛍️ PETGO-RD - DOBEHA Storefront

Tienda oficial generada y gestionada por **DOBEHA Commerce OS**.

## 🚀 Arquitectura Headless Multi-Tenant
- **Frontend:** Next.js 15 (App Router), React 19, Tailwind CSS.
- **Backend Core:** DOBEHA Vendure Core (Cluster Central).
- **Aislamiento Multi-Tenant:** `vendure-token: petgord`.
- **Despliegue Global:** Cloudflare Pages (Borde con latencia < 15ms).

## 🛠️ Comandos de Desarrollo Local

```bash
# 1. Instalar dependencias
npm install

# 2. Iniciar servidor de desarrollo
npm run dev
```

Abre [http://localhost:3000](http://localhost:3000) para ver tu tienda en local conectada en vivo a tus productos.
