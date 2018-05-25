# Modèles de citation des différents types de documents

## Citer un ouvrage imprimé

### Modèle bibliographie

Auteur \[NOM prénom\], *Titre de l’ouvrage, complément du titre*, tomaison \[vol. X\], édition \[X<sup>e</sup> éd.\], autre responsabilité (préface, traduction, éditeur…) \[Nom prénom (préf., trad., éd.)\], ville de publication, éditeur, année d’édition, pagination globale.

### Modèle minimal note de bas de page

Auteur \[NOM prénom\], *Titre de l’ouvrage, complément du titre*, éditeur, année d’édition, numéro des pages concernées.

### Dans la bibliographie

DUGUIT Léon, _L’État‎, le droit objectif et la loi positive_, Moderne Franck (préf.), Paris, Dalloz, 2003, 623 p.

BAUDRY-LACANTINERIE Gabriel, _Précis de droit civil_, vol. 1, 14<sup>e</sup> éd., Paris, Sirey, 1926, 914 p.

DALLOZ Édouard, VERGÉ Charles, VERGÉ Charles fils _et al._, _Code des lois politiques et administratives_, vol. 2, Bureau de la Jurisprudence
Générale, 1891, 1432 p.

### En note de bas de page

DUGUIT Léon, _L’État‎, le droit objectif et la loi positive_, Dalloz, 2003, p. 68 s.

BAUDRY-LACANTINERIE Gabriel, _Précis de droit civil_, Sirey, 1926, p. 8-12.

DALLOZ Édouard, VERGÉ Charles, VERGÉ Charles fils _et al._, _Code des lois politiques et administratives_, Bureau de la Jurisprudence
Générale, 1891, p. 686-712.

### Notes

Pour tous les types de documents, les noms des responsabilités secondaires (préfacier, traducteur, directeur, éditeur…) sont en minuscules.

### Notes CSL
* si le livre est imprimé, ne pas mentionner d'URL, c'est un critère d'affichage pour la mention `En ligne` des livres électroniques - voir infra
* s'il n'y a pas d'auteur, Zotero affiche le nom de l'éditeur avec le même formatage que les noms d'auteur, pour prendre en compte le cas des actes publiés d'un colloque = pour colloque ne pas mentionner d'auteur
* le rôle de préfacier n'existe pas dans Zotero : si applicable, on utilise le rôle `editorial-director`
Ce champ n'existe pas en standard dans Zotero, il faut utiliser le champ `Extra` et saisir sous la forme :

```
editorial-director: Moderne || Franck
```
---
## Citer un ouvrage numérique

### Modèle bibliographie

Auteur \[NOM prénom\], *Titre de l’ouvrage, complément du titre* \[en ligne\], tomaison \[vol. X / t. X\], édition \[X^e^ éd.\], autre responsabilité (préface, traduction, éditeur…) \[Nom prénom (préf., trad., éd.)\], ville de publication, éditeur, année d’édition, pagination globale, \[consulté le …\], URL

### Modèle minimal note de bas de page

Auteur \[NOM prénom\], *Titre de l’ouvrage, complément du titre* \[en ligne\], éditeur, année d’édition, pagination globale (en bibliographie) ou numéro des pages
concernées (en notes de bas de page), \[consulté le …\].

### Dans la bibliographie

COURBE Patrick et GOUTTENOIRE Adeline, *Droit de la famille* \[en ligne\], 7<sup>e</sup> éd., Paris, Sirey, 2017, 572 p., \[consulté le 9 janvier
2017\], [http://www.dalloz-bibliotheque.fr/bibliotheque/Droit_de_la_famille-58206.htm](http://www.dalloz-bibliotheque.fr/bibliotheque/Droit_de_la_famille-58206.htm)

MÉLIN-SOUCRAMANIEN Ferdinand et PACTET Pierre, *Droit constitutionnel*\[en ligne\], 34<sup>e</sup>éd., Paris, Sirey, 2015, 680 p., \[consulté le 20 janvier 2017\],
[http://www.dalloz-bibliotheque.fr/bibliotheque/Droit_constitutionnel-38072.htm](http://www.dalloz-bibliotheque.fr/bibliotheque/Droit_constitutionnel-38072.htm)

### En note de bas de page

COURBE Patrick et GOUTTENOIRE Adeline, *Droit de la famille* \[[en ligne](http://www.dalloz-bibliotheque.fr/bibliotheque/Droit_de_la_famille-58206.htm)\],
Sirey, 2017, p. 98-105, \[consulté le 9 janvier 2017\].

MÉLIN-SOUCRAMANIEN Ferdinand et PACTET Pierre, *Droit constitutionnel*\[[en ligne](http://www.dalloz-bibliotheque.fr/bibliotheque/Droit_constitutionnel-38072.htm)\],
Sirey, 2015, spéc. p. 18, 54 et 101-103, \[consulté le 20 janvier 2017\].

### Notes

* exceptionnellement, pas de point final après l’URL
* en note de bas de page, il est recommandé que la mention « \[en ligne\] » soit un lien hypertexte reprenant l’URL complète
* lorsque le document dispose d’un DOI, il se substitue à l’URL

### Notes CSL
* pas possible d'afficher un lien hypertexte dont l'intitulé soit différent de l'URL à laquelle il renvoie : c'est Word qui génèrera l'affichage du lien hypertexte à partir du libellé
* pas possible que la mention [en ligne] en note de bas de page soit un lien hypertexte reprenant l'URL complète

<!--

Citer des travaux universitaires imprimés\
(thèses et mémoires)
==========================================

Il s’agit ici des éditions de dépôt dans les bibliothèques
universitaires, c’est-à-dire des éditions non-commerciales. Les éditions
de thèses et mémoires publiées chez des éditeurs commerciaux sont
traitées comme des ouvrages.

Auteur \[NOM Prénom\], *Titre, complément du titre*, nom du/des
directeur(s) \[Nom Prénom (dir.)\], Intitulé du diplôme, discipline, nom
de l’université, année, pagination globale (en bibliographie) ou numéro
des pages concernées (en notes de bas de page).

### Dans la bibliographie

AUBIN Gérard, *La seigneurie en Bordelais au 18^eme^ siècle d'après la
pratique notariale (1715-1789)*, Jaubert Pierre (dir.), thèse de
doctorat, droit, université de Bordeaux I, 1981, 958 p.

RADÉ Christophe, *Le droit à l’insertion dans la loi du 1^er^ décembre
1988 relative au revenu minimum d’insertion*, Laborde Jean-Pierre
(dir.), mémoire de DEA, droit social, université de Bordeaux I, 1991, 93
p.

### En note de bas de page

AUBIN Gérard, *La seigneurie en Bordelais au 18^eme^ siècle d'après la
pratique notariale (1715-1789)*, thèse de doctorat, droit, université de
Bordeaux I, 1981, 1^ère^ partie.

RADÉ Christophe, *Le droit à l’insertion dans la loi du 1^er^ décembre
1988 relative au revenu minimum d’insertion*, mémoire de DEA, droit
social, 1991, université de Bordeaux I, p. 74.

NB :

- l’intitulé du diplôme, de la discipline et le nom de l’université sont
repris de la page de titre ou de couverture ;

- le niveau d’étude (par ex. diplôme d’étude approfondi) peut être
abrégé (DEA).

Citer des travaux universitaires numériques\
(thèses et mémoires)
============================================

Auteur \[NOM Prénom\], *Titre, complément du titre* \[en ligne\], nom
du/des directeur(s) \[Nom Prénom (dir.)\], intitulé du diplôme,
discipline, nom de l’université, année, pagination globale (en
bibliographie) ou numéro des pages concernées (en notes de bas de page),
\[consulté le …\], URL

### Dans la bibliographie

MANGEMATIN Céline, *La faute de fonction en droit privé* \[en ligne\],
Malabat Valérie (dir.), thèse, droit, université Montesquieu-Bordeaux
IV, 2012, 770 p., \[consulté le 20 janvier 2017\],
[*http://www.theses.fr/2012BOR40027*](http://www.theses.fr/2012BOR40027)

LESTRADE Éric, *Les principes directeurs du procès dans la jurisprudence
du Conseil Constitutionnel* \[en ligne\], Mélin-Soucramanien Ferdinand
(dir.), thèse, droit, université Montesquieu-Bordeaux IV, 2013, 714 p.,
\[consulté le 9 janvier 2017\],
[*http://www.theses.fr/2013BOR40033*](http://www.theses.fr/2013BOR40033)

### En note de bas de page

MANGEMATIN Céline, *La faute de fonction en droit privé* \[[*en
ligne*](http://www.theses.fr/2012BOR40027)\], thèse, droit, université
Montesquieu-Bordeaux IV, 2012, p. 88, \[consulté le 20 janvier 2017\].

LESTRADE Éric, *Les principes directeurs du procès dans la jurisprudence
du Conseil Constitutionnel* \[[*en
ligne*](http://www.theses.fr/2013BOR40033)\], thèse, droit, université
Montesquieu-Bordeaux IV, 2013, p. 105-120 et 178, \[consulté le 9
janvier 2017\].

NB :

- exceptionnellement, pas de point final après l’URL.

- en note de bas de page, il est recommandé que la mention « \[en
ligne\] » soit un lien hypertexte reprenant l’URL.

- les URL du site *theses.fr*, portail de diffusion de l’ensemble des
thèses numériques en France, sont uniques et pérennes.

Citer des travaux universitaires microfichés\
(thèses et mémoires)
=============================================

Nom du docteur \[NOM Prénom\], *Titre, complément du titre*
\[microfiche\], nom du/des directeur(s) \[Nom Prénom (dir.)\], intitulé
du diplôme, discipline, nom de l’université, année.

### Dans la bibliographie

SAINT-PAU Jean-Christophe, *L’anonymat et le droit* \[microfiche\],
Conte Philippe (dir.), thèse de doctorat : droit, université
Montesquieu-Bordeaux IV, 1998.

MAUBLANC Jean-Pierre, *L’interprétation de la loi fiscale par le juge de
l’impôt* \[microfiche\], Lamarque Jean (dir.), thèse de doctorat, droit,
université de Bordeaux I, 1984.

### En note de bas de page

SAINT-PAU Jean-Christophe, *L’anonymat et le droit* \[microfiche\],
thèse de doctorat, droit, université Montesquieu-Bordeaux IV, 1998.

MAUBLANC Jean-Pierre, *L’interprétation de la loi fiscale par le juge de
l’impôt* \[microfiche\], thèse de doctorat, droit, université de
Bordeaux I, 1984.

NB :

- pas de mention de la pagination.

Citer des contributions à un ouvrage\
(articles de mélanges, d’ouvrage collectif…)
============================================

Deux modèles sont proposés, avec ou sans guillemets pour le titre de la
contribution.

Contributeur \[NOM Prénom\], Titre de la contribution, complément du
titre, in responsable(s) du document principal \[Nom Prénom\], *Titre du
document principal, complément du titre*, édition, ville d’édition,
éditeur, année d’édition, pages de la contribution \[p. X-X\].

ou

Contributeur \[NOM Prénom\], « Titre de la contribution, complément du
titre », in responsable(s) du document principal \[Nom Prénom\], *Titre
du document principal, complément du titre*, édition, ville d’édition,
éditeur, année d’édition, pages de la contribution \[p. X-X\].

### Dans la bibliographie

BOIS DE GAUDUSSON Jean (du), Réflexions sur les nouveaux développements
du constitutionalisme en Afrique, in Aubin Gérard (éd.), *Liber
amicorum, études offertes à Pierre Jaubert*, Talence, Presses
universitaires de Bordeaux, 1992, p. 179-187.

ou

BOIS DE GAUDUSSON Jean (du), « Réflexions sur les nouveaux
développements du constitutionalisme en Afrique », in Aubin Gérard
(éd.), *Liber amicorum, études offertes à Pierre Jaubert*, Talence,
Presses universitaires de Bordeaux, 1992, p. 179-187.

### En note de bas de page

BOIS DE GAUDUSSON Jean (du), Réflexions sur les nouveaux développements
du constitutionalisme en Afrique, in *Liber amicorum, études offertes à
Pierre Jaubert*, Presses universitaires de Bordeaux, 1992, p. 179-187.

ou

BOIS DE GAUDUSSON Jean (du), « Réflexions sur les nouveaux
développements du constitutionalisme en Afrique », in *Mélanges
Jaubert*, Presses universitaires de Bordeaux, 1992, p. 179-187.

\
Citer un article de revue imprimée
==================================

Deux modèles sont proposés, avec ou sans guillemets encadrant le titre
de l’article.

Auteur \[NOM prénom\], « Titre de l’article, complément du titre »,
*Titre de la revue*, partie, mois année, numéro, pagination globale (en
bibliographie) ou numéro de paragraphe ou des pages concernées (en notes
de bas de page)

ou

Auteur \[NOM prénom\], Titre de l’article, complément du titre, *Titre
de la revue*, partie, mois année, numéro, pagination globale (en
bibliographie) ou numéro de paragraphe ou des pages concernées (en notes
de bas de page)

### Dans la bibliographie

HAUSER Jean, « Le préjudice d’être né, question de principe », *Droit et
patrimoine*, janvier 2001, n° 89, p. 6-8.

GOGOS-GINTRAND Amélie, « Le pacte commissoire : une institution
dangereuse par nature », *Revue de la recherche juridique. Droit
prospectif*, septembre 2011, n° 1, p. 401-422.

ou

AUZERO Gilles, Le dispositif d’allègement des cotisations sociales,
*Droit social*, décembre 1999, n° 12, p. 1026-1033.

AGOSTINI Éric, Le vin dans tous ses états, *Revue Lamy Droit des
affaires*, avril 2008, n° 26, p. 65-68.

### En note de bas de page

HAUSER Jean, « Le préjudice d’être né, question de principe », *Droit et
pat.*, 2001, p. 7.

GOGOS-GINTRAND Amélie, « Le pacte commissoire : une institution
dangereuse par nature », *Rev. rech. jurid., droit prospect.*, 2011, p.
403.

ou

AUZERO Gilles, Le dispositif d’allègement des cotisations sociales,
*Droit soc.*, 1999, p. 1027.

AGOSTINI Éric, Le vin dans tous ses états, *Rev. Lamy Droit aff.*, 2008,
p. 66.

NB : on se réfèrera utilement à la façon dont chaque revue prescrit de
référencer ses contenus, ainsi que l’abréviation recommandée par la
revue. Par défaut, une liste des abréviations recommandées figure en
annexe de ce document.

Citer un article de revue numérique
===================================

Deux modèles sont proposés, avec ou sans guillemets encadrant le titre
de l’article.

Auteur \[NOM prénom\], « Titre de l’article, complément du titre »,
*Titre de la revue* \[en ligne\], partie, mois année, numéro, pagination
globale (en bibliographie) ou numéro de paragraphe ou des pages
concernées (en notes de bas de page), \[consulté le …\], URL

ou

Auteur \[NOM prénom\], Titre de l’article, complément du titre, *Titre
de la revue* \[en ligne\], partie, mois année, numéro, pagination
globale (en bibliographie) ou numéro de paragraphe ou des pages
concernées (en notes de bas de page), \[consulté le …\], URL

### Dans la bibliographie

DAUGAREILH Isabelle, « L’audace retenue du Comité européen des droits
sociaux », *Revue de droit sanitaire et social* \[en ligne\], juillet
2005, n° 4, p. 555-564, \[consulté le 16 mars 2017\],
[*www.dalloz.fr*](http://www.dalloz.fr)

DUPRAT Jean-Pierre, « Le parlement évaluateur », *Revue internationale
de droit comparé* \[en ligne\], avril 1998, n° 2, p. 552-576, \[consulté
le 16 mars 2017\], [*www.persee.fr*](http://www.persee.fr)

ou

PONTHOREAU Marie-Claire, Trois interprétations de la globalisation
juridique, *Actualité juridique droit administratif* \[en ligne\],
janvier 2006, n° 1, p. 20-25, \[consulté le 16 mars 2017\],
[*www.dalloz.fr*](http://www.dalloz.fr)

CAPDEPON Yannick, Ne pas soulever un moyen de droit équivaut à y
renoncer, *Semaine juridique édition générale* \[en ligne\], juillet
2010, n° 28, p. 1444, \[consulté le 16 mars 2017\],
[*www.lexisnexis.com*](http://www.lexisnexis.com)

*\
*

### En note de bas de page

DAUGAREILH Isabelle, « L’audace retenue du Comité européen des droits
sociaux », *RDSS* \[en ligne\], 2005, p. 556, \[consulté le 16 mars
2017\].

DUPRAT Jean-Pierre, « Le parlement évaluateur », *RIDC* \[en ligne\],
1998, p. 555, \[consulté le 16 mars 2017\].

ou

PONTHOREAU Marie-Claire, Trois interprétations de la globalisation
juridique, *AJDA* \[en ligne\], 2006, p. 22, \[consulté le 16 mars
2017\].

CAPDEPON Yannick, Ne pas soulever un moyen de droit équivaut à y
renoncer, *JCP G* \[en ligne\], 2010, p. 1444, \[consulté le 16 mars
2017\].

Citer les actes publiés d’un colloque
=====================================

Responsabilité du colloque \[NOM prénom (fonct.)\], *Titre du colloque*,
lieu d’édition, éditeur, année, pagination globale (en bibliographie) ou
numéro des pages concernées (en notes de bas de page).

### Dans la bibliographie

BONIS-GARÇON Évelyne (dir.), *Pour une refonte du droit des peines:
quels changements si les préconisations de la Commission Cotte étaient
suivies ?*, Paris, LexisNexis, 2016, 226 p.

ALLINNE Jean-Pierre et SOULA Mathieu (dir.), *La mort pénale : les
enjeux historiques et contemporains de la peine de mort*, Rennes,
Presses Universitaires de Rennes, 2015, 208 p.

SOCIÉTÉ FRANÇAISE POUR LE DROIT INTERNATIONAL, *Droit international et
droit communautaire, perspectives actuelles*, Paris, Pedone, 2000, 448
p.

CENTRE D’ÉTUDES ET DE RECHERCHES SUR LE DROIT DE LA MER,
*L'immobilisation forcée des navires*, Talence, Presses Universitaires
de Bordeaux, 1990, 175 p.

### En note de bas de page

BONIS-GARÇON Évelyne (dir.), *Pour une refonte du droit des peines:
quels changements si les préconisations de la Commission Cotte étaient
suivies ?*, 2016, p. 14.

ALLINNE Jean-Pierre et SOULA Mathieu (dir.), *La mort pénale : les
enjeux historiques et contemporains de la peine de mort*, 2015, p. 150.

SOCIÉTÉ FRANÇAISE POUR LE DROIT INTERNATIONAL, *Droit international et
droit communautaire, perspectives actuelles*, 2000, p. 37.

CENTRE D’ÉTUDES ET DE RECHERCHES SUR LE DROIT DE LA MER,
*L'immobilisation forcée des navires*, 1990, p. 3.

**\
**

Citer une contribution\
parmi les actes publiés d’un colloque
=====================================

Auteur \[NOM prénom\], Titre de la contribution, in Responsabilité du
colloque \[NOM prénom (fonct.)\], *Titre du colloque*, lieu d’édition,
éditeur, année, pagination globale (en bibliographie) ou numéro des
pages concernées (en notes de bas de page).

### Dans la bibliographie

MALABAT Valérie, Simplifier mais comment ?, in BONIS-GARÇON Évelyne
(dir.), *Pour une refonte du droit des peines : quels changements si les
préconisations de la Commission Cotte étaient suivies ?*, Paris,
LexisNexis, 2016, p. 89-93.

GAUTRON Jean-Claude et GRARD Loïc, Le droit international dans la
construction de l’Union européenne, in SOCIÉTÉ FRANÇAISE POUR LE DROIT
INTERNATIONAL, *Droit international et droit communautaire, perspectives
actuelles*, Paris, Pedone, 2000, p. 11-152.

### En note de bas de page

MALABAT Valérie, Simplifier mais comment ?, in BONIS-GARÇON Évelyne
(dir.), *Pour une refonte du droit des peines : quels changements si les
préconisations de la Commission Cotte étaient suivies ?*, 2016, p. 90.

GAUTRON Jean-Claude et GRARD Loïc, Le droit international dans la
construction de l’Union européenne, in SOCIÉTÉ FRANÇAISE POUR LE DROIT
INTERNATIONAL, *Droit international et droit communautaire, perspectives
actuelles*, 2000, p. 57.

**\
**

Citer une norme juridique
=========================

PAYS, AUTEUR, *Intitulé de la norme*, Journal Officiel / Bulletin
Officiel, n°, date de publication, page de départ, numéro NOR.

### Dans la bibliographie

FRANCE. MINISTÈRE DE L’ENSEIGNEMENT SUPÉRIEUR ET DE LA RECHERCHE,
*Décret n° 2013-805 du 3 septembre 2013 portant création de l’Université
de Bordeaux*, Journal officiel, n°206, 5 septembre 2013, p. 15020,
ESRS1317830D.

FRANCE. MINISTÈRE DE L’ÉDUCATION NATIONALE, *Décret du 13 juillet 1949
approuvant une délibération du conseil de l’université de Bordeaux
portant création à Fort-de-France d’un institut d’études juridiques,
politiques et économiques de cette université*, Journal officiel, 16
juillet 1949, p. 6921.

### En note de bas de page

MINISTÈRE DE L’ENSEIGNEMENT SUPÉRIEUR ET DE LA RECHERCHE, *Décret n°
2013-805 du 3 septembre 2013 portant création de l’Université de
Bordeaux*, Journal officiel, n°206, 5 septembre 2013.

MINISTÈRE DE L’ÉDUCATION NATIONALE, *Décret du 13 juillet 1949
approuvant une délibération du conseil de l’université de Bordeaux
portant création à Fort-de-France d’un institut d’études juridiques,
politiques et économiques de cette université*, Journal officiel, 16
juillet 1949.

NB : le pays n’est indiqué que s’il est utile pour différencier des
institutions de pays différents. S’il est systématiquement absent, il
sous-entend la nationalité française des institutions concernées.

Citer un site en ligne, un blogue
=================================

AUTEUR, *Titre de la page d'accueil, complément du titre* \[en ligne\],
\[consulté le…\], URL

### Dans la bibliographie

MAÎTRE ÉOLAS, *Journal d’un avocat : Instantanés de la justice et du
droit* \[en ligne\], \[consulté le 5 octobre 2014\],
[*www.maitre-eolas.fr*](http://www.maitre-eolas.fr)

GROUPE D’INFORMATION ET DE SOUTIEN DES IMMIGRÉ.E.S, *Gisti* \[en
ligne\], \[consulté le 5 octobre 2014\],
[*www.gisti.org*](http://www.gisti.org)

### En note de bas de page

MAÎTRE ÉOLAS, *Journal d’un avocat* \[en ligne\], \[consulté le 5
octobre 2014\].

GROUPE D’INFORMATION ET DE SOUTIEN DES IMMIGRÉ.E.S, *Gisti* \[en
ligne\], \[consulté le 5 octobre 2014\].

**\
**

Citer un article ou une page\
d’un site en ligne, un blogue
=============================

AUTEUR, « Titre de l’article ou de la page », sur *Titre de la page
d'accueil* \[en ligne\], publié le …, \[consulté le…\], URL

ou

AUTEUR, Titre de l’article ou de la page, sur *Titre de la page
d'accueil* \[en ligne\], publié le …, \[consulté le…\], URL

### Dans la bibliographie

MAÎTRE ÉOLAS, « Pour en finir avec la séparation des pouvoirs », sur
*Journal d’un avocat : Instantanés de la justice et du droit* \[en
ligne\], publié le 21 février 2017, \[consulté le 21 mars 2017\],
[*www.maitre-eolas.fr*](http://www.maitre-eolas.fr)

ou

GROUPE D’INFORMATION ET DE SOUTIEN DES IMMIGRÉ.E.S, Pour en finir avec
le délit de solidarité, sur *Gisti* \[en ligne\], publié le 12 janvier
2017\], \[consulté le 21 mars 2017\],
[*www.gisti.org*](http://www.gisti.org)

### En note de bas de page

MAÎTRE ÉOLAS, « Pour en finir avec la séparation des pouvoirs », sur
*Journal d’un avocat : Instantanés de la justice et du droit* \[en
ligne\], publié le 21 février 2017, \[consulté le 21 mars 2017\].

ou

GROUPE D’INFORMATION ET DE SOUTIEN DES IMMIGRÉ.E.S, « Pour en finir avec
le délit de solidarité », sur *Gisti* \[en ligne\], publié le 12 janvier
2017, \[consulté le 21 mars 2017\].

NB : pour les sites d’institutions, le nom de la page d’accueil du site
sera souvent le même que celui de l’institution.

Citer un brevet
===============

Brevet \[nationalité\] n° XXX, *Titre du brevet*, date complète de
publication du brevet déposé.

### Dans la bibliographie et en note de bas de page

Brevet américain n° US D709251 S, *Set of hamster wheels,* 15 juillet
2014.

Brevet américain n° US Des. 430708, *Playground for small animal such as
hamster*, 5 septembre 2000.

Brevet européen n° EP3155925, *Boîtier d’attache sucette*, 19 avril
2017.

Citer un courriel, une contribution\
à une liste de diffusion
====================================

Auteur \[NOM Prénom\], *Sujet du courriel* \[courriel\], date de l’envoi
\[JJ mois AAAA\], heure de l’envoi \[hh:mn\] \[consulté le...\] sur
\[nom de la liste de diffusion éventuelle\].

### Dans la liste des ressources

GASNAULT Jean, *Quel logiciel de veille pour une direction juridique ?*
\[courriel\], 5 juin 2017, 18:04 \[consulté le 6 juin 2017\] sur
Jurisconnexion.

HOURQUEBIE Fabrice, *Re: Guide de la rédaction biblio : projet confirmé*
\[courriel\], 9 novembre 2016, 18:06, \[consulté le 12 novembre 2016\].

### En note de bas de page

GASNAULT Jean, *Quel logiciel de veille pour une direction juridique ?*
\[courriel\], 5 juin 2017.

HOURQUEBIE Fabrice, *Re: Guide de la rédaction biblio : projet confirmé*
\[courriel\], 9 novembre 2016.

NB : ce type de références rejoint préférentiellement la liste des
ressources utilisées, plutôt que la bibliographie.

Citer un entretien oral
=======================

Personne interrogée \[NOM Prénom\], *Titre ou sujet de l’entretien*
\[entretien\] mené par Nom Prénom, lieu, date \[JJ mois AAAA\],
éventuellement pagination de la transcription si elle est jointe en
annexe au travail de recherche.

### Dans la liste des ressources

GRANGER Sabrina, *Modalités de publication d’un guide bibliographique*
\[entretien\] mené par Gravier Pierre, Pessac, 13 novembre 2016.

### En note de bas de page

GRANGER Sabrina, *Modalités de publication d’un guide bibliographique*
\[entretien\] mené par Gravier Pierre, Pessac, 13 novembre 2016.

NB : ce type de références rejoint préférentiellement la liste des
ressources utilisées, plutôt que la bibliographie.

Recommandations particulières
=============================

**Citation de documents en langue étrangère**

Si un texte en langue étrangère doit être cité, il est plus approprié de
le traduire, même pour l’anglais et même s’il est supposé que le
lectorat comprend l’anglais. On recherche alors l’œuvre traduite pour la
citer. À défaut, notamment pour les articles, on effectue la traduction
en terminant la citation par \[nous traduisons\] et en donnant la
version originale du texte en note de bas de page, notamment si la
formulation en langue étrangère a de l’importance (concept propre à une
langue, concept différent en français...).

**Cas particuliers concernant les auteurs**

Les noms des auteurs seront séparés par des virgules, sauf le nom des
deux derniers qui sont séparés par « et ». On mentionnera un maximum de
trois auteurs pour un document donné. Pour un plus grand nombre
d’auteurs, le nom du troisième est suivi de « *et al.* » :

> DALLOZ Édouard, VERGÉ Charles, VERGÉ Charles fils *et al*., *Code des
> lois politiques et administratives*, tome 2, Bureau de la
> Jurisprudence Générale, 1891, 1432 p.

On respecte habituellement l’ordre des auteurs tel qu’indiqué sur la
page de titre, de haut en bas puis de gauche à droite. Un auteur, dont
l’omission nuirait à la bonne compréhension de la référence ou de son
choix, peut exceptionnellement être placé en quatrième position avant la
mention « *et al.* ».

Les civilités (madame, monsieur…), qualités ou titres (professeur,
docteur, conseiller d’État, avocat…) ne sont pas mentionnées en
complément du nom.

Les responsabilités secondaires (traducteur, préfacier, éditeur
scientifique…) ne sont mentionnées que lorsqu’elles apportent une
information particulière sur le document exploité. Elles sont alors
mentionnées à leur place indiquée dans les modèles, après le titre, en
abrégé.

**Cas particuliers concernant les titres**

La fin des titres ou sous-titre d’une longueur excessive peut être
abrégée par \[…\].

**Cas particuliers concernant les éditions**

La mention de l’édition est réduite au minimum, en employant des
chiffres arabes : « XII^e^ édition revue et corrigée » devient dans les
références bibliographiques : « 12^e^ éd. ».

**Cas particuliers concernant la publication**

La page de titre peut mentionner plusieurs éditeurs et plusieurs villes
de publication. On ne cite alors qu’un seul éditeur et sa ville, en
retenant de manière privilégiée l’éditeur français et la ville qui lui
est liée.

Pour la date de publication, on retient par ordre de préférence :

- la date de publication mentionnée sur la page de titre

> - la date de dépôt légal (parfois précédée de « DL ») mentionnée au
> verso de la page de titre ou dans les dernières pages du document
>
> - la date de copyright souvent précédée de © et souvent mentionnée au
> verso de la page de titre
>
> - la date d’impression souvent mentionnée dans les toutes dernières
> pages du document

Si ces informations manquent, on notera à leur place :

- pas de lieu identifiable (sans lieu) : \[s.l.\]

- pas d’éditeur identifiable (sans nom) : \[s.n.\]

- pas de date identifiable (sans date) : \[s.d.\]

Si un de ces éléments peut être deviné, on le mentionnera entre
crochets : \[Paris\], Dalloz, 1959. Pour résoudre ces difficultés, les
catalogues de bibliothèques restituent ces informations de manière
validée et structurée.

**Cas particuliers concernant la pagination**

En bibliographie, pour un livre ou une thèse, on mentionne la pagination
totale du document, en se référant simplement à la dernière page
numérotée du document. L’abréviation de « pages » est placée après leur
nombre (347 p.). Pour un article ou une contribution à un ouvrage
collectif, on mentionne la tranche de pages concernée et l’abréviation
de « pages » est placée avant cette indication (p. 47-58).

En note de bas de page, on mentionne les pages concernées par la
citation. L’abréviation de « pages » est placée avant la page ou la
tranche concernée (p. 49). On peut employer les abréviations suivantes :

p\. 8-12 Pages 8 à 12

p\. 8 ; 12 Pages 8 et 12

p\. 47 s. Page 47 et suivantes

spéc. p. 47 Spécialement page 47

> *passim* En différents endroits du document, qu’on choisit de ne pas
> lister

**Utilisation des termes latins de renvoi**

Les termes latins qui suivent renvoient toujours, soit à l’auteur cité
précédemment, soit à l’œuvre citée précédemment. Leur emploi
s’accompagne donc d’une grande vigilance, notamment quand plusieurs de
ces termes se succèdent.

*Idem*, abrégé en *Id.*, signifie « le même ». Cette abréviation est
employée pour indiquer qu’il s’agit du même auteur que pour la citation
précédente.

> BARCKHAUSEN Henri, *Essai sur le régime législatif de Bordeaux au
> Moyen-âge*, Bordeaux, Gounouilhou, 1890, 34 p.
>
> *Id.*, *Rapport de la commission de la Faculté sur le projet de
> réorganisation de la Licence en droit*, Bordeaux, Cadoret, 1889, 11 p.

*Ibidem*, abrégé en *ibid.*, signifie « au même endroit ». Cette
abréviation est employée pour indiquer qu’il s’agit du même auteur ET de
la même œuvre que pour la citation précédente. Sans mention particulière
de page, il s’agit également de la même page. Avec mention d’une page,
il s’agit d’une page différente.

> BENZACAR Joseph, *Fondements juridiques de la délimitation du cru
> bordelais : l'appellation et la marque « Bordeaux »*, Bordeaux,
> discours, 1910, p. 3.
>
> *Ibid.*
>
> *Ibid.*, p. 7.

*Loco citato*, abrégé en *loc. cit.*, signifie « passage cité ». Cette
abréviation est employée pour indiquer qu’il s’agit du même auteur ET de
la même œuvre ET de la même page que pour la citation précédente[^6].

*Opere citato*, abrégé en *op. cit.*, signifie « œuvre citée ». Cette
abréviation est employée pour indiquer qu’il s’agit de la dernière œuvre
citée de cet auteur.

> TRAISSAC Élisabeth, Un projet de ville dans le Médoc au XVIII^e^
> siècle, *Bulletin et mémoires de la Société archéologique de
> Bordeaux*, 1972, tome LXVI, p. 167-175.
>
> BEDEL Vanina, *La maréchaussée dans la généralité de Guyenne au
> XVIII^ème^ siècle (1720-1790)*, Guyon Gérard (dir.), thèse de
> doctorat, droit, Université Montesquieu-Bordeaux IV, p. 201.

TRAISSAC Élisabeth, *op. cit.*

Au fur et à mesure de la rédaction du document et de ses réécritures, la
manière dont un terme latin renvoie à la précédente citation peut être
modifiée. Toute insertion de citation dans une partie de document déjà
rédigée doit conduire à vérifier que la nouvelle citation ne s’intercale
pas entre un terme latin de renvoi et sa citation de référence.

Abréviations conseillées – Codes
================================

La liste suivante ne peut être exhaustive, elle ne recense notamment pas
toutes les variantes de titres portés par les codes au long de leur vie
éditoriale et chez les différents éditeurs.

Le document de recherche comprendra, avant son introduction, une liste
des abréviations de codes utilisées.

Par exception, lorsqu’un code est cité de manière habituelle, il peut
l’être en note de bas de page avec pour seule information son
abréviation.

Cependant, lorsqu’un code étranger est cité, le pays producteur de la
législation est cité comme auteur du document, afin de le différencier
du code français. Ainsi :

BELGIQUE, *Code civil*, 4^e^ éd., Philippe Denis et Dehasse Delphine
(éd.), Bruylant, Bruxelles, 2006, 428 p.

  Code administratif                                                C. adm.
  ----------------------------------------------------------------- -----------------
  Code civil                                                        C. civ.
  Code constitutionnel et des droits fondamentaux                   C. const.
  Code de commerce                                                  C. com.
  Code de justice administrative                                    CJA
  Code de l’action sociale et des familles                          CASF
  Code de l’avocat                                                  C. avocat
  Code de l’éducation                                               C. éduc.
  Code de l’énergie                                                 C. énergie
  Code de l’entrée et du séjour des étrangers et du droit d’asile   Ceseda
  Code de l’environnement                                           C. envir.
  Code de l’organisation judiciaire                                 COJ
  Code de l’urbanisme                                               C. urb.
  Code de la communication                                          C. communic.
  Code de la consommation                                           C. consom.
  Code de la construction et de l’habitation                        CCH
  Code de la copropriété                                            C. copr.
  Code de la fonction publique                                      C. fonc. publ.
  Code de la mutualité                                              C. mut.
  Code de la nationalité                                            C. nat.
  Code de la propriété intellectuelle                               CPI
  Code de la route                                                  C. route
  Code de la santé publique                                         CSP
  Code de la sécurité sociale                                       CSS
  Code de procédure civile                                          C. pr. civ.
  Code de procédure fiscale                                         C. pr. fisc.
  Code de procédure pénale                                          C. pr. pén.
  Code des associations                                             C. assoc.
  Code des assurances                                               C. assur.
  Code des baux                                                     C. baux
  Code des marchés publics                                          C. marchés pub.
  Code des ports maritimes                                          C. ports mar.
  Code des postes et télécommunications                             C. P et T
  Code des procédures civiles d’exécution                           C. pr. exéc.
  Code des procédures collectives                                   C. pr. coll.
  Code des relations entre le public et l’administration            CRPA
  Code des sociétés                                                 C. soc.
  Code des transports                                               C. trans.
  Code du sport                                                     C. sport
  Code du tourisme                                                  C. tourisme
  Code du travail                                                   C. trav.
  Code du vin                                                       C. vin
  Code électoral                                                    C. élect.
  Code forestier                                                    C. for.
  Code général de la propriété des personnes publiques              CGPPP
  Code général des collectivités territoriales                      CGCT
  Code général des impôts                                           CGI
  Code minier                                                       C. minier
  Code monétaire et financier                                       C. mon. fin.
  Code pénal                                                        C. pén.
  Code rural et de la pêche maritime                                C. rur.
  Code rurale et forestier                                          C. rur. et for.
  Livre des procédures fiscales                                     LPF
  Nouveau code de procédure civile                                  NCPC

Abréviations conseillées – Juridictions
=======================================

Les jugements et arrêts sont cités sous la forme : Juridiction, date du
jugement ou de l’arrêt, numéro de référence, éventuellement nom des
parties, commentaires éventuels. Ainsi :

CE, 19 mai 1933, Benjamin

Soc., 26 juin 2013, n° 12-15.208

Crim., 25 juin 2008, n° 07-80.261

Cons. const., 16 juin 1999, n° 99-411

CEDH, 7 oct. 1988, série A, n° 141-A

Le document de recherche comprendra avant son introduction une liste des
abréviations de juridictions.

Lorsqu’une juridiction étrangère, portant le même nom qu’une juridiction
française, est citée, elle est précédée du nom du pays concerné.

  Conseil constitutionnel                       Cons. Const.
  --------------------------------------------- ------------------
  Conseil des prud’hommes                       Cons. prud.
  Conseil d’État                                CE
  Conseil d’État, assemblée du contentieux      CE ass.
  Conseil d’État, plénière                      CE plén.
  Conseil d’État, section                       CE sect.
  Cour administrative d’appel                   CAA
  Cour d’appel                                  \[Ville\]
  Cour d’assises                                C. assises
  Cour d’assises des mineurs                    C. assises. min.
  Cour de cassation                             Cass.
  Cour de cassation, première chambre civile    1^re^civ.
  Cour de cassation, deuxième chambre civile    2^e^ civ.
  Cour de cassation, troisième chambre civile   3^e^ civ.
  Cour de cassation, chambre commerciale        Com.
  Cour de cassation, chambre sociale            Soc.
  Cour de cassation, chambre criminelle         Crim.
  Cour de cassation, chambre des requêtes       Req.
  Cour de cassation, chambre mixte              Ch. mixte
  Cour de cassation, chambre réunies            Ch. réun.
  Cour de cassation, assemblée plénière         Ass. plén.
  Cour de discipline budgétaire et financière   CDBF
  Cour de justice de l’Union européenne         CJUE
  Cour de justice de la Communauté européenne   CJCE
  Cour des comptes                              C. comptes
  Cour européenne des droits de l’homme         CEDH
  Cour internationale de justice                CIJ
  Cour permanente de justice internationale     CPJI
  Juge de proximité                             J. prox.
  Tribunal administratif                        TA
  Tribunal arbitral du sport                    TAS
  Tribunal correctionnel                        T. Corr.
  Tribunal de commerce                          T. Com.
  Tribunal de grande instance                   TGI
  Tribunal de police                            T. Pol.
  Tribunal des affaires de Sécurité Sociale     TASS
  Tribunal des conflits                         T. Confl.
  Tribunal des enfants                          T. enfants
  Tribunal d’instance                           TI
  Tribunal paritaire des baux ruraux            TPBR

Abréviations conseillées – Revues
=================================

Il n’est matériellement pas possible d’établir une liste d’abréviations
recommandées, du fait du nombre des revues juridiques et de leurs
fréquents changements de nom, fusions, scissions…

Il est recommandé d’établir une liste des abréviations utilisées en
début de document de recherche pour les revues les plus utilisées. À
cette fin, il est recommandé de se reporter à la manière dont les revues
préconisent de se citer elles-mêmes, en recourant à leur site et
indications aux auteurs.

Les bibliothèques universitaires de l’université Toulouse 1 Capitole
proposent un tableau présentant les abréviations juridiques les plus
courantes, notamment pour les revues :

[*http://ressscd.ut-capitole.fr/scd/abrev/*](http://ressscd.ut-capitole.fr/scd/abrev/)

Version imprimée en 2017,

par le service imprimerie de l’université de Bordeaux, à Pessac,\
pour le compte de l’Urfist de Bordeaux.

![](media/image3.png){width="1.879699256342957in"
height="1.2879418197725285in"}

[^1]: COLLARD Anne et MONBALLIN Michèle, *Référentiel pour l'élaboration
    et la rédaction d'un travail scientifique en sciences humaines*,
    3^e^ édition, Namur, Presses universitaires de Namur, 2014, p. 15.

[^2]: *Ibid*, p. 10.

[^3]: PACTEAU Bernard, Où on voit le Conseil d'État rejuger même si
    c'est sans se déjuger, *RFDA,* 2010, n° 2, p. 297-300.

[^4]: AGUESSEAU Henri François (d'), Mercuriales, in *Œuvres complètes
    du chancelier d'Aguesseau*, tome premier, Paris, chez les libraires
    associés, 1759, 620 p. cité dans PACTEAU Bernard, Où on voit le
    Conseil d'État rejuger même si c'est sans se déjuger, *RFDA*, 2010,
    n° 2, p. 297-300.

[^5]: BALZAC Honoré (de), *Scènes de la vie privée*, tome 4, Paris,
    Furne, 1845, p. 517.

[^6]: L’abréviation *eoc. loc.* (*eodem loco*, signifiant : au même
    endroit) a la même valeur.
