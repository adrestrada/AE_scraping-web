# Scraping-web

On désire afficher la météo actuelle d'une ville donnée. Pour cela, on utilise la service offert par un organisme météo tel que meteo.gc.ca.

Dans ce cas, on peut faire l'appel en utilisant l'url suivante (montreal):

https://meteo.gc.ca/city/pages/qc-147_metric_f.html

On pourra utiliser le module requests et l'appel retourne la page web avec toutes les informations.

Effectuer l'appel directement sur votre fureteur et verifier avec l'inspecteur les ID et class.
Pour le scraping de la page, on utilisera le module BeautifulSoup4.  Les ID à rechercher sont les suivants:

Prévision météo
Emplacement (location)
Température actuelle
2. Afficher les informations sur l'emplacement et les températures indiquées.
