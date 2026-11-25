---
name: configurar-token
description: Activa el Pack Copys Meta Ads de Blanko Studio con el token del comprador. Úsala cuando el usuario reciba su token (empieza por bk_), diga "activa mi licencia", "configura mi token", o cuando una skill de Blanko diga que falta el conector o el token.
---

# Configurar token · Blanko Studio

1. Pide el token si el usuario no lo ha pegado. Debe empezar por `bk_` y tener 35 caracteres en total.
2. Si la herramienta `estado_licencia` del conector **Blanko Pack Copys** ya está disponible, llámala y dile al usuario si su licencia está activa. Si está activa, ya puede usar las skills del pack.
3. Si el conector todavía no está, dale estos pasos:
   - Su dirección personal de conexión es `https://blanko-pack-copys.blankostudio.workers.dev/mcp/` seguida de su token (sin espacios).
   - En Claude debe agregar un **conector personalizado** con esa dirección y el nombre "Blanko Pack Copys".
   - Luego debe abrir un chat nuevo y escribir "verifica mi licencia de Blanko".
4. Recuérdale que el token es personal y que, si su suscripción de Hotmart se pausa, el mismo token vuelve a funcionar apenas renueve; no tiene que reinstalar nada.
