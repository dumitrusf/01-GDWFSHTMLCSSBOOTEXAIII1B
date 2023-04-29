# 01-GDWFSHTMLCSSBOOTEXAIII1B_262381_20211020144218
Évaluation d'entraînement - Créer un site web avec HTML, CSS et le Framework Bootstrap

<br>

---
## Projet X-STATION

**__Livrable Attendu pour l'examen de ce bloc_**

- Un site internet présente de nombreux intérêts pour une association, surtout en termes de visibilité.
Alors une association vous demande vos services dans la création d'un site vitrine (c’est à vous de
choisir une association, qu’elle soit réelle ou fictive, l’important sera votre code):

**L'association sera fictive en faveur de deux grandes comme Microsoft et Sony = donnant lieu à X-STATION**

Le projet X-STATION présente de nombreux intérêts pour une association, qui sont en l'occurrence deux
associations représentant une même association, par une co-fusion, notamment en termes de
visibilité, tels que :

### les intérêts en termes de visibilité sont les suivants: 

- la première page sera relative a X-STATION et sa union abstrait: va présenter THE NEW UNION X-STATION de manière abstraite, cette union signifiera
la fin de l'exclusivité des jeux vidéo et la force financière et commerciale entre Playstation et XBOX
et en suite ont va avoir les avantages que chacune de ces deux sociétés a fourni précédemment
une visibilité publique, leurs deux plus grands efforts de marketing tels que PSPLUS et Game Pass,
Une section évidemment pour acheter des articles de base comme la console PS5 et la New XSX 
et leurs jeux exclusives les plus TOP.

- la deuxième page sera publicitaire en rendent plus de visibilite a la association avec le nouvelle 
service TNU: la deuxième page présentera TNU (The new Union) grâce à la union entre PS & XBOX,
ce sera un nouveau service de streaming méconnaissable auquel on pourra s'abonner tous les six mois, 
cela nous donnera plus d'avantages que psplus et game pass, à part la vidéo jeux, nous aurons 
service streaming de tv comme Netflix, Paramount, HBO et bien beaucoup plus encore, également un 
énorme et merveilleux service cloud.


## Modalité pédagogique adoptée

- Fait en Mobile First avec SASS 

=

```
@mixin responsive($key) {
  @if mas-has-key($breakpoints, $key) {
    @media screen and (min-width: map-get($breakpoints, $key)) {
      @content;
    }
  } @else {
    @media screen and (min-width: $key) {
      @content;
    }
  }
}
```

---

- Dépôt git avec commit réguliers

=

### Norme de validation stricte pour le référentiel:

```
Ce référentiel suit une norme de validation stricte, également connue sous le nom de 
[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.3/).
Ce guide explique notre approche des types et du format de commit. 
Les clauses doivent suivre une syntaxe stricte pour être correctement traitées par les éléments 
d'automatisation tels que les outils de publication et les sites Web de lecture de code.

Cette norme est toujours conforme à 
[la dernière spécification Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.3/).
```

### format des messages:

Le commit commence par un type, suivi d'une description courte et concise de l'objectif du commit.
Le type est l'un des types prédéfinis décrits ci-dessous.

<type>(<scope>): <subject>

<body>

<footer>


### Types

Les types de commit suivants sont pris en charge :

* build: Modifications affectant la construction du système ou les dépendances externes
(Exemple scope: Gulp, Brocoli, NPM).

* ci: Changements vers les fichiers et scripts de configuration ci (intégration continue)
(Exemple scope: Travis, Circle, BrowserStack, SauceLabs).

* docs: Un changement de documentation qui n'affecte pas le code.

* feat: une nouvelle fonctionnalité.

* fix: Une correction de code erronée (Bugfix).

* perf: Changements de code qui améliorent les performances.

* refactor: Un changement de code qui ne corrige pas un bogue ou n'ajoute pas de fonctionnalité.

* style: Un changement qui n'affecte pas la signification du code
(format d'espace blanc, format d'indentation, etc.)

* test: Une modification qui ajoute des tests utiles ou manquants, ou qui corrige des tests existants
ou met à jour des structures de test.

* chore: Autres changements qui ne modifient pas le code ou les fichiers de test.

* reverts: retourner ou changer un commit à un état précédent.

#### Ambit (Scope)

Une scope fait référence à la catégorie ou au segment du dépôt qui sera affecté par 
cette validation. 
Ceci est facultatif et dépend du commit (si le commit n'affecte pas le scope du dépôt, le scope
peut être entièrement omise).

#### Sujet

Le sujet doit consister en une seule chaîne courte et impérative décrivant le changement. 
Écrire un sujet à la première personne du présent simple est préférable.
N'ajoutez pas de point à la fin du sujet.

#### Corp

Le corps doit être composé d'une, deux ou trois phrases. 
Le corps peut être utilisé pour donner un contexte supplémentaire, répertorier les limitations,
expliquer le quoi mais pas le comment, répertorier les comportements supplémentaires et 
spécifier la maintenance future.

#### Pie de Page

Les références aux éléments associés, tels que les numéros de issues associés,
sont incluses dans le pied de commit de validation. Le format du pied de commit de validation
doit respecter le modèle suivant : `Closes #Num`.

### Exemples

Ces exemples montrent comment écrire des commits basés sur le type.

```
docs: Documenter l'utilisation correcte du serveur

Nous avons reçu de nombreuses demande de soutien de part des utilisateurs qui utilisent le serveur
incorrectement. Cela documente l'utilisation correcte du serveur.
```

```
feat: ajouté un lecteur vidéo

Un lecteur vidéo a été ajouté afin que les utilisateurs puissent regarder les vidéos du site.
```

```
fix: Correction du bogue du bouton de mise à jour

Parfois, le bouton d'actualisation ne fonctionne pas correctement. Code ajouté pour résoudre ce 
problème.
```

```
refactor: Nous restructurons la structure de la base de données

Nous avons restructuré la structure de la base de données.
```

```
style: Améliorer la lisibilité du code

Plusieurs parties du code ont été refactorisées pour améliorer la lisibilité sans
modifier le comportement.
```

```
test: Ajouter des tests au code existant

Des tests ont été ajoutés à la partie existante du code pour assurer la stabilité de l'application.
```
---

## Barème et critères d’évaluation

```
1. Interface utilisateur claire et bien pensée (4 points):

  Définir la structure générale. Avant de commencer à créer le site Web, vous devez identifier les
  principaux sujets qui couvriront le site et comment ils sont liés les uns aux autres.
  Cela aidera à décider combien de sections et de sous-sections existeront, la hiérarchie entre elles
  et comment le contenu sera organisé de la meilleure façon pour rendre la navigation la plus 
  intuitive possible pour l'utilisateur.


---

2. Structure sémantique html et utilisation des méta pour optimiser le référencement (4 points).


  Toutes les étiquettes appropriées, correctement insérées.

  Tous les métas bien positionnés dans leur position appropriée, les microdonnées et les liens bien
  dirigés vers ce qu'ils pointent.

  Utilisez le chemin relatif pour rendre notre site Web plus rapide et plus facile à entretenir.

---

3. Intégration mobile first (4 points).


  Design, box logic, responsive et min-width pour avoir un bon Mobile first

---

4. Utilisation de git / branch / commit réguliers avec des message clairs et concis (5 points)


  Conventional commit et SemVer a Installer sur Visual Studio Code

---

5. Déploiement de la réalisation en ligne (3 points)

```


---

## nouvelle règle

<br>

Le site contiendra deux page, a chaque développement de page creer une branche en la nommant comme la page a développer.

1. ère page page X-STATION = dev/X-STATION

2. e page The New Union = dev/TNU

et puis en suite, numéroter notre ticket soit depuis Trello soit depuis github (ca depende), dans le commit parai que les premiere commits.

si pour example pour le navbar: dev/X-STATION/Navbar soit dev/X-STATION/sec-1




Ce qui suit est la licence Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported 
(CC BY-NC-ND 3.0), une licence largement utilisée pour fournir des espaces gratuits pour partager 
de l'art, des œuvres et des connaissances à des fins non commerciales : 

### Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported (CC BY-NC-ND 3.0) 
Cette licence permet aux utilisateurs de : 

* Partage : copiez et redistribuez le matériel sur n'importe quel support ou format 
Dans les conditions suivantes : 

* Attribution : Vous devez donner un crédit approprié indiquant qui a fait le travail original. 

* Non commercial : Vous ne pouvez pas utiliser le matériel à des fins commerciales. 

* Aucun dérivé : Le matériel ne peut être modifié, transformé ou adapté. Pour les exceptions suivantes :

* Aucune restriction supplémentaire - Vous pouvez combiner le matériel avec le travail et/ou 
le modifier pour répondre aux exigences des projets. 

Cette licence s'applique exclusivement au travail de Dumitru Stefan Fernando, 
"X-Station The New Union".

Cela signifie que l'utilisateur ne peut pas utiliser l'œuvre à des fins commerciales, ni modifier,
transformer ou adapter l'œuvre.

Ce travail ne peut être partagé et redistribué qu'intact, sans imposer de restrictions supplémentaires.
