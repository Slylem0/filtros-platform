# Cómo trabajamos

- Todo cambio entra a `main` por Pull Request con una aprobación y CI en verde.
- Ramas `tipo/numero-descripcion`: `feat/`, `infra/`, `obs/`, `ci/`, `docs/`, `fix/`.
- Commits estilo Conventional Commits: `feat(trabajador): métricas de latencia`.
- Cada épica tiene sub-issues; se toma uno, se asigna y se mueve en el tablero.
- Una decisión que cambie la arquitectura se escribe como ADR en `docs/adr/`.
- Ninguna credencial en el repositorio. Nada se crea desde la consola de GCP:
  si no está en Terraform o en YAML, no existe.
- Toda infraestructura en la nube se apaga cuando no se usa.
