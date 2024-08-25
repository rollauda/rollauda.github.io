## Ruby

Installer sur macos rbenv (un gestionnaire de versions Ruby) dans le terminal avec Homebrew :

```brew install rbenv```

Initialiser rbenv :

```rbenv init```

Suivez les instructions affichées pour ajouter rbenv à votre PATH.
Installer une version de Ruby :

```rbenv install 3.0.0  # Ou une version plus récente```

Définir la version de Ruby globalement : 

```rbenv global 3.0.0  # Utilisez la version que vous avez installée```

Redémarrer votre terminal ou ouvrir une nouvelle fenêtre.
Vérifier l'installation :

```ruby -v```

## Cloner ancien site

Aller sur https://github.com/just-the-docs/just-the-docs-template

use this template + Create a new repository

## Dans vscodium

Dans gemfile.lock

```
BUNDLED WITH
   3.3.4
````

Configurer config.yaml à partir de celui de l'année précédente en updatant les infos

Copier les fichiers de l'ancien site

Ajouter les fichiers modèles de leçons

**Redémarrer vscodium**


Installer Bundler :

```gem install bundler```

Update

```bundle update```

Tester en local :

```bundle exec jekyll serve```

(raccourci : :js)

## Mise en ligne du site

Publier le site avec github desktop

Sur la page github du repo, activer "pages"