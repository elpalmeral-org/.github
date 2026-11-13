# .github · elpalmeral-org

Configuración común de la organización del [agentic-platform-lab](https://github.com/elpalmeral-org/agentic-platform-lab).

| Fichero | Qué es |
|---|---|
| [`apm-policy.yml`](apm-policy.yml) | **Política de agentes de la org.** APM la descubre sola en cada `apm install` de cualquier repo de `elpalmeral-org` y decide qué se puede instalar: solo paquetes de la org, el harness corporativo [`platform-harness`](https://github.com/elpalmeral-org/platform-harness) obligatorio y fijado a una versión, solo el MCP de Port por HTTP y solo las herramientas Claude Code, Copilot, Codex y OpenCode. En modo `block`. |

Decisión: [ADR 0023](https://github.com/elpalmeral-org/agentic-platform-lab/blob/main/docs/adr/0023-apm-distribucion-harness-ok.md).
Se cambia por PR en este repo; el esquema de la política es experimental en APM, así que la plataforma
fija la versión de APM en CI.
