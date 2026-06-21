# Migration Notes for SC-Jiang.github.io

This folder is a Hugo Blox version of Songchen Jiang's academic homepage, adapted from the uploaded `hytn.github.io-main` template.

## Keep the same website URL
To keep `https://sc-jiang.github.io/`, push this repository content to the existing GitHub repository `SC-Jiang.github.io` (or `sc-jiang.github.io`). The public URL is determined by the repository name, not by the site generator.

## GitHub Pages setting
After pushing, go to GitHub repository Settings -> Pages and set Source to **GitHub Actions**. This repository includes `.github/workflows/deploy.yml`, which builds Hugo and deploys the generated `public/` folder.

## Files already customized
- `config/_default/hugo.yaml`: baseURL changed to `https://sc-jiang.github.io/`
- `config/_default/params.yaml`: identity, tagline, and header options changed
- `config/_default/menus.yaml`: navigation changed to Home / Research / Publications / Projects / Teaching / Awards / Contact
- `config/_default/languages.yaml`: English-only version retained; the template's Chinese demo content was removed
- `data/authors/me.yaml`: profile, biography, education, interests, awards, links
- `content/_index.md`: homepage sections rewritten for Operations Research / Supply Chain Analytics
- `content/publications/`: converted from the current homepage publication list
- `content/projects/`: added three research project cards
- `assets/media/authors/me.jpg`: replaced by the current homepage photo

## Deployment workflow
1. Back up the current repository.
2. Delete the old Jekyll files from the repository working tree, except `.git`.
3. Copy all files from this Hugo Blox folder into the repository root.
4. Commit and push to `main`.
5. In GitHub Pages settings, select **GitHub Actions**.
6. Check the Actions tab. When the workflow succeeds, the site should appear at `https://sc-jiang.github.io/`.

## Important
Do not copy the Hugo Blox files into a subfolder. They must be at the repository root, with files such as `go.mod`, `hugoblox.yaml`, `config/`, `content/`, and `.github/` directly under the root.

## Bilingual update

This package enables English/Chinese switching in Hugo Blox.

Key changes:
- `config/_default/languages.yaml` now defines both `en` and `zh`.
- `config/_default/params.yaml` has `language_switcher: true` for header and footer.
- `data/authors/me_zh.yaml` contains placeholder Chinese profile information for Songchen Jiang.
- `content/zh/` mirrors the English homepage, publications, and projects. Some Chinese pages intentionally contain placeholder text copied or adapted from the English version.

Recommended editing locations for Chinese content:
- Homepage sections: `content/zh/_index.md`
- Chinese author profile: `data/authors/me_zh.yaml`
- Chinese publication entries: `content/zh/publications/*/index.md`
- Chinese project entries: `content/zh/projects/*/index.md`
