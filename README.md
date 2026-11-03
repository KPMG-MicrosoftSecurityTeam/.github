# `.github` — Perfil público de la organización

Repositorio **público** que alimenta el Overview de
[KPMG-MicrosoftSecurityTeam](https://github.com/KPMG-MicrosoftSecurityTeam).

| Ruta | Uso |
| :--- | :--- |
| [`profile/README.md`](./profile/README.md) | Texto que se muestra en la pestaña **Overview** de la org |
| `profile/assets/` *(opcional)* | Imágenes públicas (banner, logo) referenciadas desde el perfil |

## Reglas de contenido

Este perfil es visible en Internet. **No** commits con:

- Información de clientes, proyectos o contratos
- Enlaces a SharePoint / Confluence / Teams internos
- Secretos, diagramas de arquitectura interna o inventarios
- Datos personales de empleados más allá de lo estrictamente público

## Cómo editar el perfil

1. Edita `profile/README.md` (busca los comentarios `<!-- [EDITAR] ... -->`).
2. Haz commit en `main`.
3. Revisa el resultado en `https://github.com/KPMG-MicrosoftSecurityTeam`.

## Perfil solo para miembros (opcional)

Si más adelante necesitáis un Overview distinto para miembros autenticados,
cread un repo **privado** llamado `.github-private` con `profile/README.md`.
Eso no sustituye este perfil público: GitHub muestra ambas vistas según el visitante.

Más info: [Customizing your organization's profile](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile).
