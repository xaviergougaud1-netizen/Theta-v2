# Thêta — v3.1

Web-app personnelle, 100 % locale, hors ligne, installable sur Android.


## Nouveautés v3.39.1
- Notes : le bouton « Déplacer » 📁↗ est aligné en haut avec le ＋, même quand la note a des sous-éléments ou des photos.

## Nouveautés v3.39
- **Vignettes de cycle sur les notes** : ⋯ du dossier › « 🏷️ Vignettes de cycle (C1, C2, C3) » (activé d'office pour le dossier Travail, sous-dossiers compris). Dans la fiche d'une note, « Cycle(s) concerné(s) » : C1, C2, C3, ou « Tous ». Les vignettes s'affichent sous la note ; filtre Tous / C1 / C2 / C3 en haut de la liste ; la recherche trouve « C2 ». Champ `cyc` sur la note, `cycles` sur le dossier.

## Nouveautés v3.38
- **Événements informatifs** : dans la fiche d'un événement avec heure (y compris ceux des agendas en lecture seule), « ℹ️ Informatif » pour celui-ci ou pour tous ceux du même nom. Il reste affiché (bordure en pointillés) mais ne bloque plus le créneau : tâches et 💡 suggestions peuvent y passer. Les événements créés dans Thêta sont envoyés à Google Agenda comme « Disponible ». « 🕐 Bloque le créneau » annule. Réglages `infEv` et `infTitles`, propres à chaque appareil.

## Nouveautés v3.37
- **＋ sous chaque liste** (Tâches : sous chaque groupe, Notes : sous la liste du dossier) : réglage « Sous les listes », activé par défaut. Sous « Aujourd'hui » et « Demain », la tâche reçoit déjà la date. Sur Jour et Agenda, le ＋ reste en haut. Réglages › Bouton ＋ : Sous les listes, En haut, Flottant, Caché (`plusMode`).
- **Appui long** sur 🎙️ ou sur Jour : menu Ajouter ; sur Tâches, Notes, Agenda : nouvelle tâche, note ou événement.
- **Raccourcis de l'icône de l'appli** (appui long sur l'icône) : Nouvelle tâche, Nouvelle note, Nouvel événement, Aujourd'hui (`?new=tache|note|evenement`). Android les met à jour seul sous un jour environ.

## Nouveautés v3.36
- **Bouton ＋ réglable** : Réglages › Bouton ＋ (ajouter) — Caché, En haut (petit ＋ à droite du titre, par défaut) ou Flottant (au-dessus du micro). Il ouvre le menu Ajouter : tâche, événement, rappel, note. Réglage `plusMode`, propre à chaque appareil.

## Nouveautés v3.35
- **Micro dans la barre de navigation**, à gauche (« Dicter ») ; il dicte selon l'écran affiché. Plus de bouton ＋ flottant sur Jour, Tâches, Notes et Agenda (il reste dans Rappels, Habitudes et Bibliothèques, seul moyen d'y ajouter) ; ✏️ dans Notes pour écrire une note.
- **Événement → tâche** : « ✅ Changer en tâche » dans la fiche (titre, date, heure, durée, lieu et notes repris ; Annuler possible).
- **Masquer un événement** à la journée ou sur plusieurs jours : 👁 sur sa ligne ou « 🙈 Masquer » dans sa fiche, pour celui-ci ou tous ceux du même nom ; 👁 en haut de l'agenda pour les revoir (estompés) et les réafficher. Réglages `hidEv` et `hidTitles` ; les masqués comptent toujours pour le temps libre et la décharge.
- **Listes repliables** (Jour : rappels, tâches, en retard, ce mois-ci, accompli ; Tâches : chaque groupe) : toucher le titre ; mémorisé (`fold`).
- **Tâches compactes** (par défaut) et **taille du texte** (4 crans) dans Réglages › Apparence. Zoom CSS sur `#main` et `#sheet`, annulé sur les frises horaires pour garder le glissement juste.
- **Agenda** : tirer la barre du bas d'un événement ou d'une tâche pour changer la durée ; en déplaçant, l'horaire s'affiche et s'aimante au quart d'heure.
- Bilan de la semaine retiré.

## Nouveautés v3.34
- **Tâches : « 📅 Quel jour ? »** remplace la date limite, les propositions « Quand la faire ? » et l'échéance. Un seul jour où faire la tâche : Aujourd'hui, Demain, Mercredi, Dimanche (toujours le prochain, jamais le jour même), Jour choisi, Un mois ou Sans date. Les anciennes dates limites restent enregistrées et peuvent être retirées depuis la fiche.

## Nouveautés v3.33
- **Copier vers plusieurs dates** : dans « Copier l'événement », « 📅 Plusieurs dates » ouvre un mini-calendrier ; coche les jours (l'original est entouré), une copie est créée pour chacun.
- **Réglage des suggestions 💡** : Réglages › Organisation de la journée › « 💡 Suggestions dans les créneaux libres » (écran Jour).

## Nouveautés v3.32
- **Copier un événement** : dans la fiche d'un événement, « 📄 Copier à une autre date » ouvre une copie (titre, horaire, lieu, notes, agenda) : choisis la date (raccourcis +1 jour, +1 semaine, +2 semaines), change l'horaire si besoin, enregistre. Marche aussi pour les événements en lecture seule.
- **Agenda › Jour allégé** : plus de suggestions 💡 ni de « Rafale » dans les créneaux libres (elles restent sur l'écran Jour).

## Nouveautés v3.31
- **Tâches datées depuis un lien** : `…/Theta-v2/?add=TEXTE&type=tache&date=demain` ouvre « Reçu de Claude » avec « ✅ Tâche » présélectionné et la date remplie (`demain`, `aujourdhui`, `apres-demain` ou `AAAA-MM-JJ`) ; une tâche par ligne. La date reste modifiable dans la fiche.

## Nouveautés v3.30
- **Lien « Ajouter à Thêta »** : `…/Theta-v2/?add=TEXTE&dossier=NOM` ouvre la fiche « Reçu de Claude », préremplie, avec le dossier présélectionné (ou proposé à la création s'il n'existe pas).
- **Une note par ligne** : à la réception d'un texte de plusieurs lignes, choix entre une note par ligne ou une seule note.
- **Dossiers projet** (⋯ du dossier › 🧩 Dossier projet) : chaque note a un statut « À faire » ou « En cours » (toucher l'étiquette pour changer), les notes en cours passent en tête, et « 🤖 Envoyer à Claude » partage la liste triée.

## Nouveautés v3.1
- Écran Jour : semaine dans le bandeau du haut, « Ma journée » de 8 h à 20 h avec événements et créneaux libres (toucher un créneau pour y créer une tâche ou un événement), glisser fluide entre les jours, bloc « Ce mois-ci » séparé.
- Tâches : échéance « un mois » (ex. « préparer les bulletins en novembre »), photos, sous-étapes visibles avec ＋ et ✕ rapides.
- Notes : sous-dossiers visibles sur chaque dossier, sous-éléments visibles et modifiables directement, réorganisation fluide.
- Rappels : chaque mois, dernier jour ouvré du mois, chaque année, certains jours de la semaine, toutes les 2 semaines.
- Bibliothèque : recherche d'un livre par titre ou par genre (couverture et auteur remplis automatiquement).
- Lieux : suggestions d'adresses Google Maps (clé API à renseigner dans Plus › Google).
- Recherche et synchronisation déplacées dans le menu Plus ; journal retiré ; hauteur de la barre de navigation réglable.

## Nouveautés v3
- **Écran Jour** : frise des 7 prochains jours (glisser du doigt ou toucher un jour) ; tâches et rappels faits passent dans « Accompli », décochables ; vacances scolaires affichées.
- **🎙️ Thêta écoute** partout : Jour (tri automatique), Tâches (tout devient tâche), Notes (chaque phrase devient un élément du dossier).
- **📝 Notes** (ex-Todo) : 📸 photo directe, 🖼️ galerie, sous-éléments à cocher.
- **Tâches** : sous-étapes, répétition (chaque jour, lun → ven, chaque semaine, chaque mois).
- **🔍 Recherche** dans tout Thêta (loupe en haut de chaque écran).
- **Agenda** : lieu cliquable vers Google Maps ; vacances scolaires (Réglages › Organisation › zone).
- **Bibliothèques** : photos, scan du code-barres d'un livre ; prêts groupés par personne, par type ou par date.
- **Réglages** : choix de la police.
- **Google** : rappels envoyés dans Google Agenda avec alerte (le téléphone sonne même Thêta fermée) ; sauvegarde automatique quotidienne sur Google Drive (activer « Google Drive API » dans la console Google, puis Plus › Google Agenda › Autoriser Google Drive).
- **Partager vers Thêta** : depuis n'importe quelle app, bouton Partager › Thêta (après réinstallation de l'app sur l'écran d'accueil).

## Fichiers à mettre dans le dépôt GitHub

| Fichier | Rôle |
|---|---|
| `index.html` | Toute l'application |
| `manifest.json` | Nom, icônes, raccourcis (installation sur l'écran d'accueil) |
| `sw.js` | Fonctionnement hors ligne |
| `icon-192.png`, `icon-512.png` | Icônes (exigées par Android pour l'installation) |

Les cinq fichiers vont à la racine du dépôt `mon-organisateur` (le nom du dépôt peut rester tel quel ; pour une adresse en `/theta/`, renommer le dépôt en `theta`), GitHub Pages activé sur la branche `main`.
Adresse : `https://xaviergougaud1-netizen.github.io/mon-organisateur/`

**Mise à jour future** : remplacer `index.html` et changer le numéro `CACHE` en haut de `sw.js` (ex. `theta-v2.1.1`).

## Installer sur le téléphone

1. Ouvrir l'adresse dans Chrome sur Android.
2. Menu ⋮ › **Installer l'application** (ou « Ajouter à l'écran d'accueil »).
3. Un appui long sur l'icône propose les raccourcis : Aujourd'hui, Tâches, Agenda.

## Brancher Google Agenda (une seule fois, ~10 min)

1. https://console.cloud.google.com → créer un projet « Thêta ».
2. **API et services › Bibliothèque** → activer **Google Calendar API**.
3. **Écran de consentement OAuth** → Externe → nom de l'app + ton e-mail.
   Dans **Audience / Utilisateurs test**, ajouter `xavier.gougaud1@gmail.com`.
4. **Identifiants › Créer des identifiants › ID client OAuth** → type **Application Web**.
   Origines JavaScript autorisées : `https://xaviergougaud1-netizen.github.io`
5. Copier l'ID client (`…apps.googleusercontent.com`).
6. Dans l'app : **Plus › Google Agenda** → coller l'identifiant → **Se connecter à Google**.
   Si Google affiche « application non validée » : *Paramètres avancés › Accéder à Thêta*.
7. Cocher les agendas à importer (Principal, Famille, Todoist sont cochés d'office s'ils existent) et choisir l'agenda par défaut.

### Fonctionnement de la synchro
- **App → Google** : événements créés/modifiés/supprimés, et tâches datées (préfixe ✅, ✔️ une fois faites).
- **Google → App** : événements des agendas cochés, de J-30 à J+120 ; modifications et suppressions répercutées.
- Une tâche déplacée dans Google Agenda change aussi de date dans l'app.
- La session Google dure 1 h : la synchro est automatique pendant ce temps, ensuite un appui sur 🔄 la rouvre.
- Agendas en lecture seule (souvent Todoist) : importés mais non modifiables (🔒).

## Notes vocales : comment l'app range

Le micro 🎙️ est sur l'écran **Jour**. Touche-le, parle (aussi longtemps que tu veux), touche ⏹ : les propositions de rangement apparaissent juste en dessous. ⌨️ permet d'écrire au lieu de dicter. L'historique est dans **Plus › Notes**.

L'analyse se fait **sur le téléphone** (aucun envoi). Chaque note est découpée (dire « à la ligne », ou utiliser « puis », « ensuite »), puis chaque morceau est proposé avec son type ; tu valides ou corriges d'un geste.

| Tu dis… | L'app propose |
|---|---|
| « Conseil de cycle jeudi 17h » | 📅 Agenda, jeudi 17:00–18:00 |
| « Acheter des feutres pour la classe » | 📁 Todo › Travail › Achat pour la classe |
| « Pour le conseil des maîtres : parler de la kermesse » | 📁 Todo › Conseil des maîtres |
| « Rappelle-moi d'appeler maman demain soir » | 🔔 Rappel, demain 19:00 |
| « Corriger les évaluations vendredi, urgent » | 📋 Tâche, vendredi, priorité haute |
| « Arroser les plantes tous les lundis » | 🔔 Rappel chaque semaine |
| « Film à voir : Dune, conseillé par Julie » | 💡 Idée › Film |
| « J'ai prêté la BD Astérix à Paul » | 📚 Prêt à Paul |
| « Repeindre le portail » | 📁 Todo › Travaux |

Mots reconnus : aujourd'hui, demain, après-demain, ce soir, lundi…dimanche, le 12, le 12 octobre, 12/10, dans 3 jours, la semaine prochaine, 14h, 14h30, de 9h à 11h, midi, pendant 1h, urgent, pas urgent… Le nom de n'importe quel dossier Todo que tu crées est aussi reconnu.

## Fond d'écran
**Plus › Réglages › Fond d'écran** : quatre fonds zen dessinés dans l'app (Brume, Aube, Lac, Jardin), fonctionnant hors ligne, ou **📷 Depuis le téléphone** pour choisir n'importe quelle photo de ta galerie. Deux curseurs : *Voile* (atténue l'image pour la lisibilité) et *Flou*. La photo choisie est incluse dans l'export de sauvegarde.

## Données
- Tout reste dans Chrome sur le téléphone ; images dans IndexedDB (plusieurs centaines de Mo possibles).
- **Réglages › Exporter** : fichier `.json` complet (avec images). À faire régulièrement ; un bandeau le rappelle tous les 14 jours.
- **Réglages › Importer** pour restaurer ou passer sur un autre téléphone.

## Limites
- Notifications de rappel : seulement quand l'app est ouverte ou récemment en arrière-plan.
- Dictée : Chrome Android, avec connexion internet (service de reconnaissance Google).
- Synchro Google : nécessite internet ; hors ligne, les changements attendent (« ⏳ à synchroniser »).
