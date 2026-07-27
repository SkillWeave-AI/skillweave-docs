# SkillWeave Docs

Public documentation site for SkillWeave, served at **https://docs.skillweave.xyz**.

- **Canonical:** Forgejo `skillweave/skillweave-docs` (this repo).
- **GitHub mirror:** under the `LangeVC` org (`LangeVC/skillweave-docs`).
- **Build/deploy:** Forgejo-first. A push to `main` builds MkDocs on the
  self-hosted runner and publishes to the Caddy-served `/srv/docs/skillweave/site`
  on langevc-prod-01, then purges the Cloudflare cache (see
  `.forgejo/workflows/deploy.yml`).

This is currently a **scaffold** — theme, brand system, and pipeline are in place;
the documentation content is authored in a separate step.
