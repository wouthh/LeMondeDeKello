# Le Monde de Kello

Historical Delphi/Object Pascal console adventure for Windows, featuring character classes, combat, dialogue and a manually encoded map. Preserved source; current build compatibility is unverified.

## Statut

**Projet historique — non maintenu.** Aucun exécutable ancien n’a été lancé et aucune compilation actuelle n’est revendiquée.

## Chronologie

Développement initial : vers 2013, selon le souvenir du propriétaire. Publication sur GitHub : 5 juillet 2018 (UTC), attestée par l’historique du dépôt. Le premier commit est daté du 6 juillet dans son décalage horaire enregistré (+02:00). La date de publication ne constitue pas une preuve de la date de création.

## Fonctionnalités présentes dans le code

- Création de personnage, classes et statistiques.
- Combats, dialogues, boutiques et progression dans une histoire.
- Carte encodée manuellement, avec des déclarations et traitements explicites par coordonnées.
- Sauvegarde de l’état du jeu.

Il s’agit d’une application console Windows en Delphi/Object Pascal, et non d’une interface à formulaires VCL. Cette description repose sur les sources conservées, pas sur une exécution récente.

## Parcours du code

- [Point d’entrée du projet](leMondeDeKelloWoutAlan.dpr) : déclaration de l’application console et lancement de l’écran titre.
- [Classes de personnage](Liste%20des%20unit%C3%A9es/Creation%20de%20personnage/Classe/classe.pas) et [combats](Liste%20des%20unit%C3%A9es/Combat/combat.pas) : règles et présentation de ces parties du jeu.
- [Carte](Liste%20des%20unit%C3%A9es/Map/map.pas) : représentation et affichage explicites des cases.
- [Histoire](Liste%20des%20unit%C3%A9es/Menu/histoire.pas) : présentation du récit.
- [Sauvegarde](Liste%20des%20unit%C3%A9es/Sauvegardement/sauvegarder.pas) : persistance historique du jeu.

Les noms de fichiers et l’organisation d’origine sont conservés. La carte illustre une approche très manuelle ; aucun décompte approximatif de variables n’est présenté comme un fait.

## Provenance

Les crédits historiques mentionnent plusieurs contributions au code, au scénario et aux tests. Ils ne permettent pas d’établir une répartition précise des contributions ni une attribution exclusive.

## Licence et ressources

Le fichier [LICENSE](LICENSE) existant est conservé sans modification. La provenance et les droits de redistribution de tous les sons, ressources compilées et éléments auxiliaires ne sont pas établis ; aucune extension de licence n’est revendiquée.

## Limites de vérification

La version exacte de l’outillage Delphi d’origine et la compatibilité actuelle de compilation ne sont pas établies. Les fichiers compilés et les ressources ne constituent pas une distribution actuelle vérifiée. Cette présentation ne fournit ni procédure d’installation validée, ni capture d’écran, ni résultat de test de l’application.
