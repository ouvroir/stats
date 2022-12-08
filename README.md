# stats
Museum data analysis

Ce répertoire de travail utilise un sous-module pour les données qui ne sont pas en accès ouvert.

## Cloner le répertoire :

```bash
git clone --recursive https://github.com/ouvroir/stats.git`
```

## Mettre à jour le répertoire et ses sous-modules

```bash
git pull --recurse-submodules
```

## Mettre à jour le HEAD du sous-module

```bash
git submodule update --rebase --remote
```
## Ajout d’un sous-module :

```bash
git submodule add https://github.com/path/submodule.git src/_name
git submodule update --init --recursive
```
