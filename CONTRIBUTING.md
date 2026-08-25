# Guide de contribution — ThinkandCodeFocus

Merci de contribuer à un projet ThinkandCodeFocus ! Ce guide s'applique à tous nos repos, sauf indication contraire dans un `CONTRIBUTING.md` local.

## Avant de commencer

1. Vérifie qu'une issue existe déjà pour ce que tu veux faire (bug ou feature). Sinon, ouvre-en une avec le template approprié.
2. Attends une validation/assignation avant de commencer un gros chantier, pour éviter le travail en double.

## Workflow

1. **Fork ou branche** : crée une branche depuis `main` avec un nom explicite : `feat/nom-fonctionnalite`, `fix/nom-bug`, `chore/nom-tache`.
2. **Commits** : messages clairs, au format `type: description courte` (ex: `fix: corrige le calcul de la TVA sur le panier`).
3. **Tests** : toute nouvelle fonctionnalité ou correction de bug doit être couverte par un test quand c'est possible.
4. **Pull Request** : ouvre une PR vers `main`, remplis le template, lie l'issue concernée (`Closes #123`).
5. **Revue** : au moins **une review approuvée** est requise avant merge. Les checks CI doivent être verts.
6. **Merge** : squash-merge par défaut, sauf indication contraire du repo.

## Style de code

- Respecte le linter/formatter déjà configuré dans le repo (ESLint/Prettier, Pint, Checkstyle, etc.). Lance-le avant de pousser.
- Pas de code commenté laissé dans la PR finale.
- Les secrets (clés API, tokens, mots de passe) ne doivent **jamais** être commités — utilise les variables d'environnement (`.env`, non versionné).

## Signaler un problème de sécurité

Ne pas ouvrir d'issue publique pour une faille de sécurité — voir [SECURITY.md](SECURITY.md).

## Questions

Pour toute question, ouvre une discussion sur le repo concerné ou contacte l'équipe via [think-and-code.com](https://think-and-code.com).
