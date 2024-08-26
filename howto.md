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

## Créer repo dans github desktop

## copier les fichier (et cachés) de l'année précédente

Ajouter les fichiers modèles de leçons

## Dans vscodium

Mettre à jour config.yaml

Mettre à jour Gemfile :

```
source 'https://rubygems.org'

gem "jekyll", "~> 4.3.3" # installed by `gem jekyll`
# gem "webrick"        # required when using Ruby >= 3 and Jekyll <= 4.2.2

gem "just-the-docs", "0.9.0" # pinned to the current release
# gem "just-the-docs"        # always download the latest release

group :jekyll_plugins do
    gem "jekyll-pdf-embed"
  end
```
mettre à jour gmfile.lock : 

BUNDLED WITH
   3.0.0

gem install bundler

bundle install

bundle update --bundler

bundle update

Tester en local :

bundle exec jekyll serve

(raccourci : :js)

## Mise en ligne du site

Publier le site avec github desktop

Sur la page github du repo, activer "pages" 