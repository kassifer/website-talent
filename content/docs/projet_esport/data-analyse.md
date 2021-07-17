---
title: Data Analyse
---

## Appréhension de la partie analyse du sujet :

{{<tip "warning">}}

De façon générale, l'analyse consiste à tirer des informations factuelles utiles à l'apport de visibilité sur le sujet, afin de pouvoir prédire, contrôler ou décrire des éléments liés à la problématique. 

{{< /tip >}}

En effet, le but d'une analyse
est non seulement dans l'audit du situation à l'instant `T`, mais également dans le sondage de l'instant `T-1`, ainsi que `T+1`. L'idée est de retranscrire une image cohérente du futur en s'appuyant sur les fluctuations passées, 
la situation présente, et sur les situation connues similaire afin de produire une prédiction cohérente de l'instant `T+1`. 

{{< tip >}}

Une analyse a donc pour but de former une image cohérente du périmètre de la problématique, mais également d'aider les décisions 
stratégiques en fonction du réalisme de celle-ci afin de pouvoir prétendre à un pilotage efficient. 

{{< /tip >}}

## Premier analyse théorique : sur le sujet lui-même

Pour notre sujet : *"Les stratégies de développement de l'e-sport[^1] dans le monde"* ; il est, de prime abord et sans parler de data, intéressant de se poser plusieurs questions :
- Comment évolue l'**e-sport[^1]** de façon générale ?
	- Coté **utilisateur**...
	- Coté **spectateur**...
- Y'a-t-il des **variables d'influences** et d'autres qui ne le sont pas ?
- Si oui, quelles sont-elles ? Et si non, pourquoi ?
- A quoi peut-on s'attendre dans le futur ?

{{< tip >}}

Voici les premières pistes de réflexion concernant l'analyse, purement théorique afin de s'approprier le sujet, et de nous lancer dans des recherches plus abouties.

{{< /tip >}}

## Seconde analyse théorique : sur le périmètre du sujet

En nous posant les questions vues précédemment, cela amène a préciser quelques termes afin de s'assurer de la compréhension du sujet :

- Qu'est-ce que l'**e-sport[^1]** ?
- Est-il seulement **dématérialiser** ?
- Peut-on en vivre ?
- Si oui, par **quels moyens** ?

{{< tip >}}

C'est en affinant avec ce genre de question basique qu'un périmètre se précise. Il est très important de se poser les questions de bases et de bien y répondre afin d'embarquer dans l'univers du sujet avec un socle solide.

{{< /tip >}}

## Recherche de la data

Comme définit précédemment, on peut désormais avoir une idée plus précise du type de donnée que l'on souhaite trouver pour répondre à la problématique. 

{{< tip "warning" >}}

En l'occurrence, on cherche à déterminer une stratégie de développement, donc une mise en ouvre d'événements à but lucratif durant des période données. 

{{< /tip >}}

{{< tip >}}

On va donc chercher à produire une courbe d'évolution sur laquelle on s'attend à déceler des variations plus ou moins fortes pour lesquelles on cherchera à donner des explications pertinentes et justifiées.

{{< /tip >}}

### Où chercher ?

Dans un premier temps, il faut scruter les sites organisationnels des principaux acteurs (dans notre exemple on peut notamment parler de riot-games ou encore epic-games tout deux respectivement producteur des jeux League of Legends
et Fortnite) afin de déterminer leurs politiques quant aux données (retravaillées ou brut). On se rend compte que pour les données dans ce milieu, plusieurs acteurs secondaires paraissent intéressant à visiter : les plateformes de
streaming des matchs ainsi que les endroits physiques où se déroulent ses derniers afin d'obtenir des statistiques quantitatives.

{{< tip "warning">}}

Un site très important pour les data-sciences en général : kaggle qui propose une grande quantité de datasets (citant leurs sources la plupart du temps) afin de notamment proposer des concours de résolution de problématique via
la data-analyse/data-science pour ne pas dire l'intelligence artificielle de façon générale.

{{< /tip >}}

### Données trouvées :

{{< tip >}}

3 jeux de données principaux on été obtenu, ainsi qu'un jeu bonus pour voir l'effet du covid-19 sur cette même problématique :

{{< /tip >}}

&nbsp;&nbsp;&nbsp; `1 - ` Evolution des cash-prizes au cours du temps

&nbsp;&nbsp;&nbsp; `2 - ` Evolution de l'audience au cours du temps

&nbsp;&nbsp;&nbsp; `3 - ` Evolution de la fréquence des matchs e-sportifs au cours du temps

&nbsp;&nbsp;&nbsp; `4 - ` Evolution de l'audience durant la période covid-19

### Exploitation de la donnée

{{< tip >}}

3 Logiciels me paraissent éssentiels (gratuit et open-source) :

&nbsp;&nbsp;&nbsp; `a - ` RStudio

&nbsp;&nbsp;&nbsp; `b - ` Gephi

&nbsp;&nbsp;&nbsp; `c - ` IraMuTeQ

{{< /tip >}}

#### &nbsp; `→` *RStudio*

{{< tip >}}

IDE de développement en langage R, langage développé dans un premier temps spécifiquement pour les statistiques, puis avec l'accumulation d'une grande communauté (composé en grande partie d'économiste, biologiste, ingénieurs,
chercheurs, ... ) et de développement open source de package étendant les domaines de compétences de ce langage. Il est devenu une des références en data analyse via des packages ultra performant tel que 'dplyr' ou 'ggplot2'. 

{{< /tip >}}

Il permet de gérer efficacement la donnée pour en faire tout ce qu'il est possible de faire avec de la donnée à savoir :

{{< tip "warning" >}}
Nettoyage, analyse primaire, opérations statistiques globales, analyse complémentaire, data visualisation, IA (supervisé/non-supervisé)
{{< /tip >}}

Il fait donc partie des 3 géants de l'IA avec Python et TenserFlow.

#### &nbsp; `→` *Gephi*

Gephi est un outil de visualisation de réseau sous forme de cartographie de données. Il est extrêmement utilisé dans les domaines d'analyse d'influence, et de l'information en général.

#### &nbsp; `→` *IraMuTeQ*

IraMuTeQ est un outil quant à lui spécifique à l'analyse de la sémantique. Il permet d'effectuer des statistiques poussée en utilisant des procédés tel que la lématisation ou la vectorialisation du langage (word embedding).

### Echantillon des résultats de l'analyse

 `→` **Evolution des revenus générés par l'e-sport[^1]**

![Evolution des revenus générés par l'e-sport[^1]](/images/TID/RPS_revenu.png)

 `→` **Evolution des cash-prizes proposés en compétition e-sportive**

![Evolution des cash-prizes proposés en compétition e-sportive](/images/TID/RPT_gains.png)

 `→` **Fréquences des matchs e-sportifs**

![Fréquences des matchs e-sportifs](/images/TID/Hist_freq_match.png)

 `→` **Evolution du nombre de tournois pour les 6 plus grosses licences à compté des années 2000**

![Evolution du nombre de tournois pour les 6 plus grosses licences](/images/TID/evo_licence_tot_act.png)

 `→` **Evolution du nombre de tournois pour les 10 plus grosses licences de tous les temps**

![Evolution du nombre de tournois pour les 10 plus grosses licences](/images/TID/evo_licence_tot.png)

 `→` **Montant total des Cash-prizes proposés par licence**

![Montant total des Cash-prizes proposés par licence](/images/TID/gains_moy_licence.png)

[^1]: **e-sport** : sport éléctronique majoritairement découlant de jeux vidéo.
