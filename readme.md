# DNN Language Pack for (FR-FR)

## Release management
All pull requests should be merged into the develop branch.

When the language pack is ready for a new version:
- Create a branch called `release/x.x.x` where x.x.x is the version of the release (DNN version)
- Wait a few minutes and you should see a new commit on that branch that updates the manifest automatically with the version taken from that branch.
- When that commit is in, create a pull request from `release/x.x.x` that targets `master`, this will automate the packaging and publish the release.
- Optionally another pull request can be created from `release/x.x.x` targetting `develop` in order to also update the latest published version on the develop branch

## Standardization

Some words in english have multiple possible french translations, for that reason we keep here a table of the preferred (when it makes sense) translation for some of these common words so we have some sort of familiar wording across the whole language pack.

| English | French |
|---------|--------|
| Container | Conteneur |
| Desktop Module | Module |
| Event Viewer (Should now be Admin Logs in english | Observateur d'événements |
| Friendly Name | Nom convivial |
| Flag | Drapeau (dans le contexte approprié) ou "Indicateur d'options" dans le context de "command flag" |
| ID | Identifiant (unless confusing in the context) |
| Recycle Bin | Corbeille |
| Required | Requis (ou Requise), ne pas utliser Obligatoire comme plusieurs services de traduction suggèrent. |
| Theme | Thème (ne pas utiliser le mot habillage) |
| Pane | Panneau |
| Prompt or Command Prompt | Invité de commandes |
