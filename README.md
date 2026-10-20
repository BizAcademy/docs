# Documentation API BizConnectPay

Ce dossier est un projet Mintlify autonome. Il publie les guides MDX et génère
la référence interactive depuis `openapi.json`.

## Prévisualisation locale

Depuis ce dossier :

```bash
npx mint dev
```

La documentation est alors disponible sur `http://localhost:3000`.

## Vérifications avant publication

```bash
npx mint validate
npx mint broken-links
```

## Publication

Dans le tableau de bord Mintlify, connectez ce dépôt de documentation. Les
mises à jour de `docs.json`, des fichiers MDX et de `openapi.json` sont alors
publiées indépendamment du backend et du tableau de bord marchand.

Les secrets d'application, jetons et identifiants de production ne doivent
jamais être ajoutés à ce dossier.
