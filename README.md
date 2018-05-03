## Membre du groupe

* Thibault
* Mustapha
* Nathan
* Patrick
* Romain
* Enzo

## Partage des taches :

- Enzo et Mustapha : Back end
- Thibault et Nathan : BDD
- Romain et Patrick : Front end

### Gem

Une fois le fichier télécharger et dans le dossier de chaque app à l'ouverture, faire cette commande pour installer les Gem :

```
bundle install --without production
```

Selon la version de Ruby, il faudrat peut-être aller dans le gemfile pour supprimer ou commenter la ligne spécifiant la version de Ruby ou celle de Rails

### Lancement de l'app

Il suffit d'aller dans le dossier de l'app et de lancer sur son terminal `rails server` avant de se rendre sur son navigateur sur http://localhost:3000.

Avant ça, il faudrat peut-être faire un `rails db:migrate` sur son terminal.

## Pré-requis

Pour pouvoir visualiser le projet vous pouvez regarder sur le lien heroku.

## Construit avec

* Visual Studio Code, Sublime Text et un peu de RubyMine