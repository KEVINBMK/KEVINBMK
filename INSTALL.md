# Installer le profil GitHub

## Étape 1 — Créer le dépôt spécial (si pas encore fait)

1. Va sur https://github.com/new
2. **Repository name** : `KEVINBMK` (exactement ton pseudo)
3. Coche **Public**
4. Coche **Add a README file** → NON (on a déjà le README)
5. Clique **Create repository**

## Étape 2 — Pousser les fichiers

```bash
cd github-profile
git init
git add .
git commit -m "Profil GitHub animé et coloré"
git branch -M main
git remote add origin https://github.com/KEVINBMK/KEVINBMK.git
git push -u origin main
```

## Étape 3 — Activer le snake animé

1. Va sur https://github.com/KEVINBMK/KEVINBMK/actions
2. Clique **Generate Snake Animation** → **Run workflow**
3. Attends 1–2 minutes
4. Rafraîchis ton profil : https://github.com/KEVINBMK

## Personnalisation

Dans `README.md`, modifie :
- L'email (`kevin.bmk@example.com` → ton vrai email)
- Le lien LinkedIn
- Les projets en vedette
- Les icônes sur https://skillicons.dev
