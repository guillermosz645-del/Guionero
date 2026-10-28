# Guionero

Editor de guiones minimalista. Guarda en tu navegador y en la carpeta **Guiones** de tu Google Drive. Exporta a PDF y a `.guion` (su formato editable).

## 1. Publicar la página (GitHub Pages, gratis)

1. Entra a github.com → **New repository** → nombre `guionero` → **Public** → **Create repository**.
2. **Add file → Upload files** → arrastra TODOS los archivos de esta carpeta → **Commit changes**.
3. **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `(root)` → **Save**.
4. En 1–2 minutos tu app queda en `https://TU-USUARIO.github.io/guionero/`.

## 2. Conectar Google Drive (gratis, una sola vez)

1. Entra a console.cloud.google.com con tu **Gmail personal** (no la de la escuela) → crea un proyecto "Guionero".
2. **APIs & Services → Library** → busca **Google Drive API** → **Enable**.
3. **Google Auth Platform** (antes "OAuth consent screen") → **Get started**: nombre de la app, tu correo, tipo **External**.
   En **Audience → Test users** → **Add users** → tu Gmail.
4. **Clients → Create client** → tipo **Web application**.
   En **Authorized JavaScript origins** pon: `https://TU-USUARIO.github.io` (sin `/guionero`, sin `/` al final).
5. Copia el **Client ID**.
6. Abre tu app → ícono de cuenta (arriba a la derecha) → pega el Client ID → **Conectar con Google**.
7. Google avisará "app no verificada": es tuya → **Continue**.

## 3. En el celular / tablet

Abre la URL en Chrome → menú ⋮ → **Agregar a pantalla principal** (o **Instalar app**). Abre como app y funciona sin internet.

## Atajos

| Atajo | Qué hace |
|---|---|
| `Ctrl + Enter` | Nueva escena debajo |
| `Alt + ↑ / ↓` | Mover escena |
| `Ctrl + S` | Subir a Drive ya |
| `Ctrl + \` | Abrir/cerrar guiones e ideas |
| `Esc` | Mostrar las barras |
