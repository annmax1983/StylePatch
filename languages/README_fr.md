# StylePatch

Manuel officiel · Multilangue : [English](../README.md) | [中文](README_zh.md) | [Español](README_es.md) | [Deutsch](README_de.md) | [日本語](README_ja.md) | Français

> Ce document est le manuel officiel de StylePatch, accessible via le bouton « Manuel d'utilisation » dans le panneau de l'extension.

Une extension légère qui vous permet de personnaliser instantanément la couleur de fond, la couleur du texte, la couleur des liens, la police, les filtres et la taille de police de n'importe quelle page web — pour une lecture plus confortable.

✅ Disponible sur le Chrome & Edge Web Store · ✅ Zéro suivi, toutes les données stockées localement · ✅ Paramètres indépendants par site

---

## Liste des fonctionnalités

### 🆓 Fonctionnalités gratuites

| Fonctionnalité | Description |
|---------|-------------|
| 🎨 **Couleur de fond, du texte et des liens** | Choisissez n'importe quelle couleur via le sélecteur natif ou saisissez directement un code hexadécimal ; la couleur des liens s'ajuste automatiquement pour la lisibilité |
| 🔠 **Taille de police** | Ajustement de 80 % à 150 % via CSS zoom |
| 🔤 **Famille de police** | Changez la police de la page — polices système ou Google Fonts chargées depuis le web (Roboto, Open Sans, Noto Sans SC…) |
| 🌗 **Filtres de couleur** | Mode niveaux de gris et teinte sépia chaude pour une lecture plus agréable |
| 👁️ **Thèmes prédéfinis** | Clair, Ton chaud, Vert, Sombre — application en un clic |
| 🔄 **Activation globale** | Activez/désactivez l'extension globalement sans perdre vos réglages |
| 🚫 **Liste noire par site** | Excluez des sites spécifiques de la personnalisation |
| 💾 **Paramètres par site** | Enregistrez des styles différents pour différents sites, restaurés automatiquement lors des visites (5 sites max en gratuit) |
| ⚡ **Prévisualisation en temps réel** | Toutes les modifications s'appliquent instantanément pendant que vous ajustez, sans rechargement de la page |
| 🌍 **Interface multilingue** | Prend en charge l'anglais, le chinois, l'espagnol, l'allemand, le japonais et le français |
| 🔒 **Permissions minimales** | Uniquement `storage` + `host_permissions` — aucun accès superflu |
| 🏗️ **Manifest V3** | Construit sur l'architecture service worker du Manifest V3 |
| 🔄 **Réinitialisation en un clic** | Restaurez l'apparence originale de n'importe quel site instantanément |

### ⭐ Fonctionnalités Premium (licence requise)

| Fonctionnalité | Description |
|---------|-------------|
| ♾️ **Configurations illimitées** | Enregistrez des styles pour un nombre illimité de sites (gratuit : 5 sites max) |
| 📤 **Exporter toutes les configurations** | Téléchargement en un clic de tous vos styles de sites sous forme de fichier JSON structuré |
| 📥 **Importer des configurations** | Restaurez instantanément tous les styles depuis un fichier de sauvegarde — idéal pour la migration entre appareils |
| 💾 **Sauvegarde et restauration** | Exportez avant une réinstallation système, importez sur un nouvel appareil — tous les réglages préservés |
| 🔄 **Migration entre appareils** | Configurez StylePatch sur un nouvel ordinateur en quelques secondes, chaque apparence personnalisée est restaurée |

> Voir les [tarifs VKT](https://annmax1983.com/pricing.html) pour les options de licence. Licence individuelle à partir de 2,99 $/mois ou 9,99 $ à vie.

---

## Aperçu

<p align="center">
  <img src="screenshot/en.png" alt="Aperçu StylePatch" width="640">
</p>

---

## Navigateurs compatibles

| Navigateur | Statut | Version minimum |
|---------|--------|-----------------|
| Google Chrome | ✅ Entièrement pris en charge | Chrome 95+ |
| Microsoft Edge | ✅ Entièrement pris en charge | Edge 95+ |
| Autres navigateurs basés sur Chromium | ✅ Compatibilité de base | Installer uniquement via la boutique officielle d'extensions |

---

## Installation

Pour votre sécurité, n'installez StylePatch que via les boutiques officielles d'extensions :

1. Ouvrez le **Chrome Web Store** ou **Microsoft Edge Add-ons**
2. Recherchez : `StylePatch`
3. Cliquez sur **« Ajouter à Chrome »** / **« Ajouter à Edge »**
4. Cliquez sur l'icône StylePatch dans votre barre d'outils pour commencer

> ⚠️ N'installez pas depuis des sites tiers. Les versions non autorisées peuvent compromettre la sécurité de vos données.

---

## Utilisation

1. Cliquez sur l'**icône StylePatch** dans la barre d'outils de votre navigateur
2. **Choisissez les couleurs** — Utilisez le sélecteur natif ou saisissez un code hexadécimal
3. **Sélectionnez un préréglage** — Clair, Ton chaud, Vert ou Sombre
4. **Ajustez la taille de police** — Glissez le curseur de 80 % à 150 %
5. **Choisissez une police** — Sélectionnez une police système ou chargez une Google Font depuis le web
6. **Appliquez un filtre** — Niveaux de gris ou teinte protectrice optionnels
7. **Enregistrez** — Cliquez sur **Appliquer et enregistrer** pour sauvegarder les paramètres pour ce site
8. **Réinitialisez** — Cliquez sur ↺ pour restaurer l'apparence par défaut du site
9. **Exclure** — Cliquez sur « Exclure ce site » pour ajouter un domaine à la liste noire
10. **Activer/Désactiver** — Utilisez le commutateur ON/OFF pour désactiver sans perdre les réglages

### Gestionnaire de configurations

Cliquez sur **⚙ Gestionnaire de configurations** en bas du popup pour ouvrir la page de configuration :

- **Consultez** tous les sites configurés avec leurs paramètres de couleur et de police
- **Exportez** toutes les configurations en fichier JSON de sauvegarde
- **Importez** un fichier de sauvegarde pour restaurer les réglages sur un autre appareil ou après une réinstallation
- **Supprimez** des configurations de sites individuelles

---

## FAQ

1. **Les styles ne s'appliquent pas après modification ?**
   Fermez les autres extensions similaires (mode sombre / protection des yeux) qui pourraient être en conflit, puis rafraîchissez la page.

2. **Les paramètres sauvegardés disparaissent après la réouverture du navigateur ?**
   Assurez-vous d'avoir cliqué sur « Appliquer et enregistrer ». En mode navigation privée, activez l'autorisation de StylePatch pour les fenêtres privées.

3. **Comment transférer mes paramètres sur un nouvel appareil ?**
   Ouvrez le gestionnaire de configurations (⚙), cliquez sur Exporter pour télécharger un fichier de sauvegarde, puis importez-le sur le nouvel appareil.

4. **Pourquoi `www.example.com` et `example.com` partagent les mêmes paramètres ?**
   C'est volontaire — les domaines sont matchés sans tenir compte du `www.` initial, pour que votre style s'applique de manière cohérente sur les deux adresses.

5. **Je ne trouve pas StylePatch sur la boutique d'extensions ?**
   Vérifiez votre région réseau. Le lien vers la boutique officiel est disponible sur [www.annmax1983.com](https://www.annmax1983.com).

---

## Confidentialité

StylePatch respecte les principes de confidentialité dès la conception et ne collecte aucune donnée utilisateur :

1. **Permissions demandées** — seulement deux :
   - `storage` : Sauvegarde vos couleurs personnalisées, la taille de police, la liste noire de sites et les préférences de thème en local. Aucun contenu de page web n'est stocké.
   - `host_permissions` : Utilisé uniquement pour injecter des styles CSS personnalisés afin de modifier l'apparence des pages. Ne lit pas le texte du DOM, les images, les cookies, les identifiants ou les données de formulaire.

2. **Pas de suivi** — Aucun accès à l'historique de navigation, aucun traqueur tiers intégré, aucune transmission automatique de données externes.

3. **Les données restent locales** — Toutes les données de configuration n'existent que sur votre appareil. Les données ne quittent votre navigateur que lorsque vous exportez manuellement un fichier de sauvegarde, ou quand vous choisissez une Google Font (dans ce cas, le fichier de police est téléchargé depuis fonts.googleapis.com).

- [Politique de confidentialité complète](https://annmax1983.github.io/StylePatch/privacy-policy.html)
- [Détails complémentaires sur la confidentialité](https://www.annmax1983.com)

---

## Avertissement relatif au droit d'auteur

1. Cette extension ajuste uniquement en local le style de rendu visuel des pages web pour une lecture confortable. Tous les droits d'auteur des textes, images et contenus de chaque site appartiennent à leurs éditeurs respectifs.
2. La modification du style d'affichage des pages ne confère aux utilisateurs aucun droit d'auteur sur le contenu des sites. Il est strictement interdit d'utiliser cette extension pour contourner les paywalls, les restrictions d'adhésion ou les protections anti-copie des sites web.
3. Les utilisateurs doivent se conformer aux lois locales et aux conditions d'utilisation des plateformes lors de l'utilisation de cette extension. Toute utilisation illégale engage la responsabilité de l'utilisateur.

---

## Avis sur le code source

> ⚠️ **Ce dépôt ne publie pas le code source.** Il contient uniquement la documentation d'utilisation, les notes de version et les ressources d'assistance. L'extension est distribuée exclusivement via le Chrome Web Store. Aucun package d'installation hors ligne ni code source destiné aux utilisateurs finaux n'est fourni.

---

## Licence

Copyright © 2026 StylePatch. Tous droits réservés.

Ce logiciel est un logiciel propriétaire fermé. Sans autorisation écrite officielle, les actions suivantes sont strictement interdites :
- Décompiler, cracker ou modifier le code du programme
- Reconditionner, redistribuer, partager ou revendre commercialement
- Intégrer le programme dans d'autres logiciels pour une distribution groupée

Les contrevenants s'exposent à des poursuites judiciaires.

---

## ❤️ Soutenir

Si StylePatch vous est utile, offrez un café au développeur !

**[👉 Cliquez ici pour soutenir](https://ko-fi.com/annmax?buyACoffee=true&ref=stylepatch)**
