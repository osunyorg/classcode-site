# Classcode

## Hugo

Pour installer Hugo
```
brew install hugo
```
Mise à jour avec
```
brew upgrade hugo
```

## Template osuny hugo
https://github.com/noesya/osuny-hugo-template

Pour faire la mise à jour :
```
git remote add template git@github.com:noesya/osuny-hugo-template.git
git fetch --all
git merge template/main --allow-unrelated-histories
```

## Theme
https://github.com/noesya/osuny-hugo-theme

Pour cloner avec le thème
```
git clone git@github.com:noesya/classcode-site.git --recurse-submodules
```
Pour récupérer le thème
```
git pull --recurse-submodules
```

## Commands

Pour lancer le site
```
yarn
hugo server
```
