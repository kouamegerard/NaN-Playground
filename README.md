# NaN-Playground

#Variables et constantes

Dans Swift, il existe deux façons de le faire: des variables et des constantes. Une variable est un magasin de données dont la valeur peut être modifiée à tout moment, et une constante est un magasin de données que vous définissez une fois et que vous ne pouvez jamais modifier.

--------------------------------------------------------
#Types de données
Il existe de nombreux types de données et Swift les traite toutes individuellement. Vous avez déjà vu l'un des types les plus importants lorsque vous avez affecté du texte à une variable, mais dans Swift, cela s'appelle un String- littéralement une chaîne de caractères.
Maintenant que nous avons des variables de deux types différents, vous pouvez voir le type sécurité en action.
Avant de continuer, veuillez supprimer ces deux lignes de code à l'origine de l'erreur, sinon rien dans votre terrain de jeu ne fonctionnera à l'avenir!

Cela ajoute des nombres croissants avant le point décimal, tout en conservant le même nombre de chiffres après. Mais si vous regardez dans le volet des résultats, vous remarquerez que lorsque vous ajoutez plus de nombres avant le point, Swift supprime les chiffres après. Ceci est dû au fait qu’il dispose d’un espace limité dans lequel stocker votre numéro.
Exemple:
//Float
var longitude: Float
longitude = -54.0327654
longitude = -540.0327654
longitude = -5401.0327654
longitude = -54012.0327654
longitude = -540123.0327654
longitude = -5401234.0327654

Maintenant, essayez de changer le Floatpour être un Doubleet vous verrez Swift imprimer le nombre correct à chaque fois:

//Double
var longitude: Double
longitude = -54.0327654
longitude = -540.0327654
longitude = -5401.0327654
longitude = -54012.0327654
longitude = -540123.0327654
longitude = -5401234.0327654
#

#Booléen
Swift a un type de données intégré qui peut stocker si une valeur est true ou false, appelée un Boolraccourci pour Boolean.
 Les bancs n'ont pas d'espace pour "peut-être" ou "peut-être", seulement des absolus: vrai ou faux. Par exemple:


#


#
#
#
#
#
#
#
#
#
#
#
#
#
#
#



