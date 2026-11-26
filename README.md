# Claude Code: subagentes y skills

Colección personal de **277 subagentes** (`agents/`) y **862 skills** (`skills/`) para [Claude Code](https://claude.com/claude-code).

## Cómo usarlos

```bash
# Subagentes (un archivo .md por agente)
cp agents/*.md ~/.claude/agents/

# Skills (una carpeta por skill, con su SKILL.md)
cp -R skills/* ~/.claude/skills/
```

Antes de copiar, revisa que no pises agentes o skills que ya tengas con el mismo nombre.

## Qué contiene

- **`agents/`**: subagentes de desarrollo, producto, marketing, datos, infraestructura y propios en español (`preservador`, `security-auditor`, `code-reviewer`, `terminos-legales`, `crew-*`, entre otros).
- **`skills/`**: skills de seguridad defensiva y ofensiva autorizada (forense, detección, respuesta a incidentes, pentesting), diseño de videojuegos, SEO, remotion y otras.

## Aviso importante

- **Autoría y licencias:** la mayor parte del contenido proviene de proyectos de terceros y conserva su licencia original (cada carpeta incluye su `LICENSE` cuando el autor la proporcionó). Este repositorio solo los reúne; respeta las licencias de origen antes de reutilizarlos. Si eres autor de algo y no quieres que aparezca aquí, abre un issue y se retira.
- **Skills de seguridad ofensiva:** están pensadas para pruebas **autorizadas**, entornos de laboratorio, CTF y defensa. No las uses contra sistemas sin permiso.
- **Revísalas antes de usarlas:** las skills pueden incluir scripts que se ejecutan con los permisos de tu agente. Lee su código antes de activarlas.
- **Sin secretos:** se escaneó el contenido en busca de claves, tokens y datos personales; los fragmentos que parecen claves son ejemplos de documentación.
