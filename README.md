# CICD
![CI](https://github.com/LaboneeyDhanure/CICD/actions/workflows/ci.yml/badge.svg)

## 🚀 CI/CD Pipeline Flow

```mermaid
flowchart LR
    A[Developer push code] --> B[GitHub Repo]
    B --> C[CI: Build & Test]
    C --> D[CD: Deploy to Server/Cloud]
    D --> E[Application Running]

**Important tips**
- The triple backticks must be exactly like above, with `mermaid` on the opening fence.
- `flowchart LR` = left → right. You can use `TB` (top→bottom) or change shapes/labels.
- If it doesn’t render: check for extra indentation or that the README.md is on the default branch.

---

# 3) (Optional) Add a prettified diagram image (Draw.io / Figma / Excalidraw)
**Why:** images look nicer in slides/docs and let you use colors/icons.

**How to create & add**
1. Draw the flow in diagrams.net (Draw.io) / Figma / Excalidraw.
2. Export as **PNG** or **SVG** (SVG is best for crispness).
   - Recommended size: 1200px wide for good readability.
3. Commit file to `docs/pipeline.png` in your repo.
4. Add to `README.md`:
```markdown
![CI/CD Diagram](docs/pipeline.png)

