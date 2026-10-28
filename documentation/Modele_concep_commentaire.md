# Commentaire du modèle conceptuel

## Problématique

Cette recherche cherche à déterminer dans quelle mesure les différentes formes de capital (social, culturel, économique et politique) ont favorisé l'engagement des femmes dans le mouvement suffragiste ainsi que leur accès à des positions influentes au sein du champ féministe international.

Le modèle conceptuel a été construit afin de collecter et structurer les informations nécessaires pour analyser les trajectoires sociales, professionnelles, familiales et militantes des suffragistes.

---

# Présentation générale du modèle

Le modèle est organisé autour de la classe centrale **Suffragiste**, qui représente chaque militante étudiée.

Autour de cette entité principale on retrouve plusieurs entités permettant de documenter :

- le capital culturel ;
- le capital social ;
- le capital économique ;
- les relations familiales ;
- les formes d'engagement militant ;
- les responsabilités exercées au sein des organisations.

Cette structure permet d'établir des comparaisons entre les militantes, les pays et les périodes historiques.

---

# Classe Suffragiste

La classe **Suffragiste** constitue le cœur du modèle.

Elle regroupe les informations suivantes :

- nom ;
- date de naissance ;
- date de décès ;
- pays d'origine.

Cette entité contient également des informations nécessaires à l'étude des différentes formes de capital :

- niveau d'études ;
- formation universitaire ;
- origine sociale ;
- statut matrimonial ;
- présence de militants dans la famille.

Ces variables permettent de comparer les profils sociaux des militantes et d'identifier les facteurs favorisant leur engagement politique.

---

# Classe Profession

L'entité **Profession** est utilisée pour enregistrer l'activité professionnelle principale de chaque suffragiste.

Cette information permet d'étudier la place occupée par certaines catégories professionnelles au sein du mouvement suffragiste.

Les professions observées peuvent inclure :

- enseignante ;
- journaliste ;
- écrivaine ;
- médecin ;
- avocate ;
- universitaire ;
- autre profession.

Cette entité constitue un indicateur important du capital culturel.

---

# Classe Organisation

L'entité **Organisation** permet de documenter les différents réseaux auxquels les militantes appartiennent.

Ces organisations peuvent être :

- des associations féministes ;
- des organisations suffragistes ;
- des partis politiques ;
- des réseaux internationaux.

L'analyse de ces affiliations permet d'étudier le capital social des suffragistes ainsi que leur degré d'intégration dans les réseaux militants.

---

# Classe Fonction dirigeante

L'entité **Fonction dirigeante** enregistre les responsabilités assumées par les militantes au sein des organisations.

Les fonctions peuvent comprendre :

- présidente ;
- vice-présidente ;
- secrétaire ;
- trésorière ;
- membre du comité ;
- autre fonction.

Les dates de début et de fin permettent de reconstituer les trajectoires militantes et d'évaluer le niveau d'influence exercé par chaque personne.

Cette entité répond directement à la question portant sur l'accès à des positions influentes dans le mouvement féministe.

---

# Classe Type d'action

L'entité **Type d'action** sert à décrire les formes d'engagement politique pratiquées par les suffragistes.

Les principales catégories retenues sont :

- pétition ;
- publication ;
- manifestation ;
- politique institutionnelle ;
- désobéissance civile.

Cette information permet d'analyser les stratégies militantes privilégiées par les différentes catégories de suffragistes.

---

# Classe Famille

L'entité **Famille** documente l'environnement familial de chaque militante.

Les informations retenues sont :

- profession du père ;
- profession du conjoint ;
- présence d'autres militants dans la famille.

Cette entité permet d'étudier les ressources sociales et économiques transmises par le milieu familial.

Elle contribue également à comprendre l'influence éventuelle de la famille sur l'engagement politique.

---

# Relations entre les classes

## Relation « exerce »

Cette relation relie une suffragiste à une profession.

Elle permet d'étudier les liens entre activité professionnelle et engagement politique.

---

## Relation « appartient à »

Cette relation relie une suffragiste à une organisation.

Elle permet d'analyser l'insertion des militantes dans différents réseaux associatifs et politiques.

---

## Relation « occupe »

Cette relation relie une suffragiste à une fonction dirigeante.

Elle sert à identifier les militantes ayant acquis un rôle important au sein des organisations.

---

## Relation « pratique »

Cette relation relie une suffragiste aux différents types d'action qu'elle utilise.

Elle permet d'observer la diversité des modes de mobilisation.

---

## Relation « appartient à une famille »

Cette relation associe chaque suffragiste aux informations concernant son milieu familial.

Elle contribue à l'étude des déterminants sociaux de l'engagement militant.

---

# Cardinalités
permettent d'indiquer combien d'occurrences d'une entité peuvent être liées à une autre.

écrites comme cela (nb minimum de liens, nb maximum de liens)

(0,n) - 0 = facultatif / n = autent que nécessaire
(1,n) - 1 = obligatoire
(1,1)
(0,1)

Cardinalité minimale indique si une relation est obligatoire ou facultative. La cardinalité maximale indique le nombre maximal d'occurences pouvant être associées. Les cardinalités ont été définies d'après les caractéristiques du mouvement suffragiste et les informations nécessaires à la recherche.

# Justification du modèle

Le modèle a été volontairement simplifié afin de ne conserver que les informations directement utiles à la problématique de recherche.

Chaque entité correspond à une dimension théorique étudiée.

Cette structure permet de répondre aux principales questions de recherche concernant le recrutement social des suffragistes, leurs parcours éducatifs, leurs professions, leur intégration dans des réseaux militants et leur accès à des positions de pouvoir au sein du mouvement féministe international.

---

# Limites du modèle

Certaines informations biographiques sont parfois absentes des sources historiques. Il sera donc possible que certaines données soient inconnues pour certaines militantes.

Le modèle a néanmoins été conçu de manière suffisamment souple pour intégrer des informations partielles tout en conservant une structure homogène permettant les comparaisons entre individus, groupes sociaux et pays.