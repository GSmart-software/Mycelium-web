# Mycelium web

La versión web de Mycelium: Next.js (`frontend/`) + backend .NET (`backend/`) sobre
Cloudflare D1 y R2. `legacy/` y `DEPLOYMENT-PLAN.md` son registro histórico.

> [!important] La documentación y las instrucciones del proyecto NO están acá
> Viven en el repo **`mycelium-docs`**, que es el vault de Mycelium y la memoria del
> proyecto. En disco, este repo está dentro de ese vault (`<vault>/web/`), y Claude Code
> corre desde la raíz del vault, con su `CLAUDE.md` completo: el rol de orquestador, el
> contrato de los subagentes, las convenciones de commits y la receta para reflejar
> cambios desde desktop.
>
> Si estás leyendo esto con la sesión abierta **acá adentro**, abrí el `CLAUDE.md` del vault
> (`../CLAUDE.md`) antes de hacer nada.

En `frontend/` rige además [frontend/AGENTS.md](frontend/AGENTS.md).

Para reflejar cambios desde desktop, este repo tiene al de desktop como remoto local
`desktop` (`git remote add desktop ../desktop`, una sola vez por clon).

Hasta el 2026-10-21 este código era la rama `web-cloud` del repo `Myceliumv2`, hoy
archivado. El historial está completo acá.
