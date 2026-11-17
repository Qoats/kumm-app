# kumm-app

Dépôt de publication de l'application web [Kumm](https://github.com/Qoats/Kumm) sur **https://app.kumm.fr** (GitHub Pages).

Il ne contient pas de code : le workflow `Application web (GitHub Pages)` récupère le code public de
[Qoats/Kumm](https://github.com/Qoats/Kumm), construit l'application en mode statique (`npm run build:pages`), ajoute les horaires
théoriques ouverts de [transport.data.gouv.fr](https://transport.data.gouv.fr) (CTS : Licence Ouverte 2.0, SNCF : ODbL) puis publie le tout.
Aucune API CTS, aucun jeton, aucun temps réel, aucun secret.

- Mise à jour automatique chaque jour (horaires et dernier code), ou à la demande : *Actions → Run workflow* (le champ `ref` permet de
  construire une autre branche de Qoats/Kumm).
- Procédure complète (DNS, domaine, retour arrière) : [docs/GITHUB-PAGES.md](https://github.com/Qoats/Kumm/blob/main/docs/GITHUB-PAGES.md).

Le code et ses licences sont dans [Qoats/Kumm](https://github.com/Qoats/Kumm) (licence MIT).
