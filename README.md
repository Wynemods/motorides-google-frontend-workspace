# Moto Rides — Google / public web (account deletion)

Workspace root for the public-facing deletion request page (Vite + React).

## Clone (fresh)

```bash
git clone --recurse-submodules https://github.com/Wynemods/MOTO-RIDES-GOOGLE-FRONTEND-WORKSPACE.git
cd MOTO-RIDES-GOOGLE-FRONTEND-WORKSPACE
cd Frontend
npm install
cp .env.example .env
npm run dev
```

If you already cloned without submodules:

```bash
git submodule update --init --recursive
```

## Submodule

| Path | Remote |
|------|--------|
| `Frontend/` | https://github.com/Wynemods/Moto-rides-deletion-page.git |

Application commits are made inside `Frontend/` and push to `Moto-rides-deletion-page`. Bump the parent repo to record which submodule commit the workspace uses.

## Environment

See `Frontend/.env.example` for `VITE_API_URL` and related settings.
