# AeroRush

Juego de Roblox de aviones acrobáticos (HUD sin combate). Código en Luau, sincronizado con Roblox Studio mediante Rojo.

## Estructura
- `src/server` -> ServerScriptService.Server
- `src/client` -> StarterPlayer.StarterPlayerScripts.Client
- `src/shared` -> ReplicatedStorage.Shared
- `default.project.json` define el mapeo de Rojo.

## Convenciones
- Luau, tabs para indentar.
- Scripts con `.server.luau` / `.client.luau`; ModuleScripts con `.luau`.
- Modelos, mapas y UI armada a mano viven en el `.rbxl`, no en este repo.

## Flujo
1. Editar en la nube y subir a la rama.
2. En el PC: `git pull`, `rojo serve`, "Connect" en el plugin de Rojo.
