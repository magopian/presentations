Passer de nose à py.test sur un gros projet chez Mozilla
========================================================

Présentation pour `Djangocong 2015 <http://rencontres.django-fr.org/2015/>`_
sur l'utilisation de pytest à la place de nose sur un gros project chez
Mozilla.

py.test est un "test runner" similaire au populaire nose. Ces dernières années,
py.test s'est fait de plus en plus connaître, est toujours très activement
maintenu et développé, et a des fonctionnalités très attractives. Nous allons
tout d'abord voir pourquoi utiliser py.test au lieu de nose, faire un rapide
récapitulatif sur comment écrire des tests avec py.test (et voir que c'est plus
pythonique), et enfin voir comment passer une grosse base de code de nose à
py.test (spoiler : c'est facile).
