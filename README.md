# Abubakar_Mahir_P4_02092021
Testé avec un hébergement Github pages sans modifications du code source originel.
### lien vers le page non modifier :https://boubamahir2.github.io/Abubakar_Mahir_P4_starter/
### lien vers le page final : https://boubamahir2.github.io/Abubakar_Mahir_P4_02092021/
# Résultats initiaux


## Scores lighthouse avant

Accueil mobile :
- Performance: 34
- Accessibilité: 83
- Meilleures pratiques: 100
- SEO: 78

Accueil ordinateur :
- Performance: 67
- Accessibilité: 80
- Meilleures pratiques: 100
- SEO: 90

Contact mobile :
- Performance: 43
- Accessibilité: 75
- Meilleures pratiques: 92
- SEO: 72

Contact ordinateur :
- Performance: 59
- Accessibilité: 75
- Meilleures pratiques: 92
- SEO: 80

## Scores lighthouse après

Accueil mobile :
- Performance: 87 (+12)
- Accessibilité: 84 (+0)
- Meilleures pratiques: 87 (+1)
- SEO: 86 (+8)

Accueil ordinateur :
- Performance: 98 (+16)
- Accessibilité: 81 (+0)
- Meilleures pratiques: 93 (+0)
- SEO: 90 (+9)

Contact mobile :
- Performance: 93 (-6)
- Accessibilité: 74 (-2)
- Meilleures pratiques: 93 (+7)
- SEO: 92 (+11)

Contact ordinateur :
- Performance: 100 (+0)
- Accessibilité: 76 (+0)
- Meilleures pratiques: 93 (+0)
- SEO: 90 (+0)

## Scores Wave avant
Accueil
- Errors 5
- Contrast Errors 29
- Alerts 12

Contact
- Errors 9
- Contrast Errors 4
- Alerts 8
## Scores Wave apres
Accueil
- Errors 
- Contrast Errors 
- Alerts 

Contact
- Errors 
- Contrast Errors 
- Alerts 


# Validation W3C


# Points d'améliorations

## Performance

- Optimiser les images (poids et format)
- Ajouter des dimensions de bases aux images
- Mettre un cache plus long
- Optimiser les librairies tels que bootstrap

## Accessiblitée 

- Augmenter la lisibilité (couleurs)
- Améliorer l'ordre des titres HTML
- Ajouter un attribut lang à la balise <html>
- Ajouter un nom à la liste
- Remplacer les textes sous forme d'image par un vrai paragraphe HTML

## Meilleures pratique

- Changer de version les librairies avec des failles de sécurités (bootstrap 3.3.5 & jQuery 2.1.0)
- Faire correspondre la taille affiché de la vrai taille des images
- Bootstrap est mal intégré sur la page de contact
- Plusieurs erreur sont reporté dans la console
- Remplacer le lien de navigation "page 2" par un libelé plus parlant (contact) et renommer le fichier par la même occasion

## SEO

- Aucune meta description
- Contient des polices illisibles par leur taille
- Zones de touche (doigt) trop petites
- Balise <title> incomplète c'est juste un "."



## Errors in console before
- BootstrapValidation.js:912 Uncaught ReferenceError: jQuery is not defined
    at jqBootstrapValidation.js:912:5
- Uncaught ReferenceError: $ is not defined
    at formHandler.js:1:1

##    outils
- LightHouse
- wave
- web dev
