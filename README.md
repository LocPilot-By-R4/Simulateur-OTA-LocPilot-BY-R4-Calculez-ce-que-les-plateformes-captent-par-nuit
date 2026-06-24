# Simulateur OTA LocPilot — V21 tracking UTM WhatsApp

Version indépendante prête pour GitHub Pages.

## Contenu

- `index.html` : page autonome avec CSS et JavaScript intégrés
- `logo.jpg` : logo LocPilot
- `og-locpilot-simulateur.png` : image de partage social
- `README.md` : instructions

## Déploiement GitHub Pages

1. Créer un dépôt GitHub, par exemple `simulateur-ota-locpilot`.
2. Déposer les fichiers `index.html`, `logo.jpg`, `og-locpilot-simulateur.png` et `README.md` à la racine.
3. Aller dans **Settings > Pages**.
4. Choisir la branche `main`, dossier `/root`.
5. Attendre la publication du lien GitHub Pages.

## Fonctionnement

Le simulateur raisonne sur une réservation type :

> 1 nuit = 1 canal = 1 calcul.

Le propriétaire choisit une plateforme, renseigne son prix moyen par nuit et indique combien de nuits similaires sont concernées. Le résultat affiche ce que les OTA captent par nuit et ce qu’un canal direct LocPilot pourrait récupérer.

## Tracking léger sans cookie

Cette version ne charge pas Google Analytics ni Meta Pixel. Elle récupère uniquement les paramètres UTM présents dans l’URL, ainsi que le référent navigateur quand il existe.

Ces informations sont automatiquement intégrées dans le message WhatsApp envoyé par le prospect :

- `utm_source`
- `utm_medium`
- `utm_campaign`
- `utm_content`
- `utm_term`
- référent éventuel
- URL de la page
- date de simulation

## Liens de diffusion conseillés

Remplacer le domaine si le dépôt change.

### Groupe propriétaires / location saisonnière

`https://locpilot-by-r4.github.io/Simulateur-OTA-LocPilot-BY-R4-Calculez-ce-que-les-plateformes-captent-par-nuit/?utm_source=facebook&utm_medium=groupe&utm_campaign=simulateur_ota&utm_content=groupe_proprietaires`

### Groupe LocPilot

`https://locpilot-by-r4.github.io/Simulateur-OTA-LocPilot-BY-R4-Calculez-ce-que-les-plateformes-captent-par-nuit/?utm_source=facebook&utm_medium=groupe&utm_campaign=simulateur_ota&utm_content=groupe_locpilot`

### Page LocPilot

`https://locpilot-by-r4.github.io/Simulateur-OTA-LocPilot-BY-R4-Calculez-ce-que-les-plateformes-captent-par-nuit/?utm_source=facebook&utm_medium=page&utm_campaign=simulateur_ota&utm_content=page_locpilot`

### Profil personnel Jonathan

`https://locpilot-by-r4.github.io/Simulateur-OTA-LocPilot-BY-R4-Calculez-ce-que-les-plateformes-captent-par-nuit/?utm_source=facebook&utm_medium=profil&utm_campaign=simulateur_ota&utm_content=profil_jonathan`

### Page R4 Consulting

`https://locpilot-by-r4.github.io/Simulateur-OTA-LocPilot-BY-R4-Calculez-ce-que-les-plateformes-captent-par-nuit/?utm_source=facebook&utm_medium=page&utm_campaign=simulateur_ota&utm_content=page_r4_consulting`

## WhatsApp

Le bouton d’audit ouvre WhatsApp avec un message pré-rempli contenant :

- coordonnées du prospect ;
- plateforme simulée ;
- prix par nuit ;
- nombre de nuits ;
- valeur captée par nuit ;
- potentiel récupérable ;
- origine du lead ;
- URL de la page ;
- date de simulation.

Numéro configuré : `+33 7 84 29 82 02`.

## Remarque

Simulation indicative, sans valeur contractuelle. Les frais peuvent varier selon les plateformes, contrats, options activées, modes de paiement et paramètres de chaque annonce.
