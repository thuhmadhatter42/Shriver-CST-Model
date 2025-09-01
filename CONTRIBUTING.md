# Contributing to CST

Thanks for your interest in **Shriver’s Complex Substrate Theory (CST)**.

---

## How to Contribute

### 1. Issues
- Open one Issue per change with a descriptive title.
- Prefix with tags:
  - `[theory]` — conceptual work, ontology, axioms
  - `[math]` — derivations, equations, parameterization
  - `[numerics]` — code, simulations, plots
  - `[docs]` — writing, figures, README
- Keep Issues scoped; use checklists for subtasks.

### 2. Branching & Versioning
- `main` → stable releases only.
- `dev/*` → active work branches (e.g. `dev/halo-solver`).
- Tags follow semantic versioning:
  - `v2.0.0` — major release
  - `v2.1.0` — minor iteration (new section, figure, JSON expansion)
  - `v2.1.1` — patch (typos, formatting)

### 3. Style Guide
- **Markdown:** wrap lines ~100 characters.
- **Math:** use fenced LaTeX math (`$$ ... $$` or inline `$ ... $`).
- **Figures:** commit vector (SVG/PDF) first; include script that generates them.
- **JSON/Code:** indent with 2 spaces; keep keys snake_case.

### 4. Reproducibility
- Every figure must have a regeneration script/notebook.
- Notebooks should run end-to-end without manual edits.

### 5. Commit Messages
Use concise, present-tense messages:
- `Add φ free-energy equation scaffold`
- `Move draft to paper/draft/`
- `Fix typo in black-hole section`

---

## Roadmap
- **v2.1.0**: Derive φ-based ΔT_{μν} forms consistent with solar-system bounds.
- **v2.2.0**: Implement toy halo solver + lensing integrals.
- **v2.3.0**: Mock pipeline for environment-dependent redshift residuals.
- **v3.0.0**: ArXiv-ready manuscript with figures, bounds, and code release.
