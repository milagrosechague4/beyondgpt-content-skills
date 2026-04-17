# BeyondGPT — Content Skills para Claude Code

7 skills para producir contenido orgánico y pauta con IA — instaladas en tu computadora, listas para usar.

Parte del producto **Sistema de Contenido con Claude** de [BeyondGPT](https://beyondgpt.com).

---

## Las 7 skills

| Skill | Qué hace |
|---|---|
| `/build-my-business` | Claude te entrevista en 8 secciones y genera tu CLAUDE.md automáticamente |
| `/competitor-intel` | Agentes que analizan 3–5 competidores en paralelo y mapean el territorio |
| `/research-brief` | De tema vago a 3 briefs listos para producir |
| `/content-scripter` | De brief a filming card lista para grabar — en tu voz |
| `/hook-generator` | 6 hooks en 6 formatos probados para cualquier tema |
| `/repurpose` | Un script → caption, LinkedIn, carrusel, hilo, email |
| `/content-calendar` | Un mes de contenido con lógica de progresión |

---

## Instalación

### Opción A — Claude web (skills 03–07)

1. Abrí el archivo `.md` de la skill que querés usar
2. Copiá el contenido completo
3. Pegalo en Claude como prompt de inicio de conversación
4. Seguí las instrucciones que te da Claude

> **Nota:** `/build-my-business` y `/competitor-intel` requieren Claude Code — no funcionan en Claude web porque generan archivos y corren agentes en paralelo.

---

### Opción B — Claude Code (todas las skills)

**Requisito previo: tener Claude Code instalado**

```bash
npm install -g @anthropic-ai/claude-code
```

**Instalar las skills:**

```bash
# Opción 1 — Descargar el repo como ZIP
# Ir a este repo → botón verde "Code" → Download ZIP
# Descomprimir el archivo
# Copiar los archivos a tu carpeta de skills:

cp ~/Downloads/beyondgpt-content-skills-main/skills/*.md ~/.claude/skills/
```

```bash
# Opción 2 — Clonar el repo (si sabés usar git)
git clone https://github.com/beyondgpt/beyondgpt-content-skills.git
cp beyondgpt-content-skills/skills/*.md ~/.claude/skills/
```

**Verificar que funcionan:**

Abrí Claude Code en tu carpeta de proyecto y escribí:
```
/build-my-business
```

Si Claude arranca la entrevista, está todo bien.

---

## Orden de uso recomendado

```
SETUP (una vez)
/build-my-business   → genera tu CLAUDE.md
/competitor-intel    → mapea tu territorio

PRODUCCIÓN SEMANAL
/research-brief      → 3 briefs
/content-scripter    → filming card
/hook-generator      → 6 hooks
/repurpose           → 5 formatos
/content-calendar    → mes completo (una vez por mes)
```

---

## Estas skills son la base

Sin conexión a datos externos, sin APIs adicionales. Funcionan con tu CLAUDE.md y WebSearch nativo de Claude.

El sistema completo — conectado a performance data, Airtable, Meta API, análisis de competidores en tiempo real — está en **BeyondGPT School**.

→ [Anotate en la lista de espera de BeyondGPT School](https://app.youform.com/forms/ipd6vu1h)

---

*by [BeyondGPT](https://beyondgpt.com) · [@beyond_gpt](https://instagram.com/beyond_gpt)*
