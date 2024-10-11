## Données et code
Projet __Comment les enseignants évaluent-ils leurs pratiques ? Analyse des indicateurs mobilisés dans des projets de recherche menés par des enseignants en France__

**Auteurs**: Ignacio Atal, Maëlle Crosse, Elsa Chusseau, Marine Lanteri, Cyril Drouot

A des fins de reproductibilité, et en vue de promouvoir la science ouverte, vous trouverez dans ce repo l'ensemble des données et des codes produits dans le cadre du projet de recherche.

Pour toute question: ignacioatalch@gmail.com

### Indicateurs_donnees_propres.csv
Une ligne par indicateur:
- `defi`: numéro unique du défi
- `Intitulé`: intitulé du défi
- `cat_defi`: catégorie du défi selon la thématique éducative
- `nb_coauteurs`: nombre de co-auteurs du défi correspondant
- `Indicateur`: identifiant unique de l'indicateur au sein du défi
- `Quelle.donnée....`, `Exemples.de.réponses...`, `Afin.de.suivre...`, `Qui.peut.renseigner...`, `Champ.d.app...`: verbatims extraits des tableaux des indicateurs de chaque défi servant de base pour le codage
- `clarte_cons`: consensus trouvé par l'équipe de recherche à la question: _"Est-ce que l'énoncé de l’indicateur est clair/compréhensible ?"_
- `cible_cons`: consensus trouvé par l'équipe de recherche à la question: _"Est-ce que l'indicateur permet d’évaluer précisément le ou les objectifs (pédagogiques/éducatifs) du Défi ?"_
- `qua_cons`: consensus trouvé par l'équipe de recherche à la question: _"Est-ce que l’indicateur est quantitatif ou qualitatif ?"_
- `finpro_cons`: consensus trouvé par l'équipe de recherche à la question: _"Est-ce que l'indicateur permet de rendre compte de l’atteinte d’une finalité pédagogique ou de la mise en place d’un processus pédagogique ?"_
- `clarte_rev1`, `clarte_rev1`, `clarte_rev2`, `cible_rev1`, `cible_rev2`, `qua_rev1`, `qua_rev2`, `finpro_rev1`, `finpro_rev2`: réponses données par les anotateurs 1 et 2 pour chacune des 4 questions de la grille d'analyse
- `rev_id_12`: identité des anotateurs 1 et 2 (dans l'ordre)

### Defis_donnees_propres.csv
Une ligne par défi
- `defi`: numéro unique du défi
- `Intitulé`: intitulé du défi
- `nb_coauteurs`: nombre de co-auteurs du défi correspondant
- `cat_defi_cons`: consensus trouvé par l'équipe de recherche concernant la catégorie du défi selon la thématique éducative
- `cat_defi_rev1`,`cat_defi_rev2`: réponses données par les anotateurs 1 et 2 pour la catégorie du défi

### Coauteurs_donnes_propres.csv
Une ligne par co-auteur
- `user_id`: numéro unique par co-auteur
- `Genre`: genre
- `is_teaching`: est-ce que la personne est enseignant·e
- `is_preservice`: est-ce que la personne est étudiant·e en vue de devenir enseignant·e
- `is_formateur`: est-ce que la personne est formateur·rice ou accompagnateur·rice pédagogique d'enseignant·es: formateur·rice, conseiller pédagogique, ingénieur pédagogique, ...
- `is_directeur`: est-ce que la personne est personnel d'encadrement dans un établissement éducatif (directeur, principal, proviseur, ...
- `is_inspecteur`: est-ce que la personne a une mission d'encadrement à un niveau territorial: inspecteur·rice, rôle au niveau d'une académie de l'éducation nationale, VP université, ...
- `is_researcher`: est-ce que la personne est chercheur·se académique/universitaire sur des thématiques en lien avec l'éducation et la formation
- `is_other`: est-ce que la personne a un autre rôle (membre associatif, accompagnant éducatif et social, psychologue scolaire, ...)
- `teaching_level`: pour les personnes avec le rôle enseignant ou preservice, dans quel secteur de l'éducation elles enseignent (primaire, secondaire, supérieur, autre)
- `trainer_support_level`: pour les personnes avec le rôle formateur, directeur ou inspecteur, dans quel secteur de l'éducation ils agissent
