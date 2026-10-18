# 🚗 ASK LOCATION — Location de véhicules FiveM
![ASK LOCATION - AsakiDev](ask_location_banner.png)

**ASK LOCATION** est un script gratuit de location de véhicules pour FiveM, développé par **AC STUDIO / AsakiDev**.

## ✨ Fonctionnalités principales

- 🚗 **Location de véhicules** — Configurable.
- 👤 **PNJ loueur** — Interaction avec un PNJ pour accéder au service de location.
- 🎨 **Interface moderne** — Design sombre avec des accents verts, aux couleurs du studio.
- ⏱️ **Durées configurables** — Personnalisation des durées et des tarifs de location.
- 📍 **Configuration complète** — Véhicules, prix et points d'apparition personnalisables.
- 🕒 **Compteur de location** — Affichage du temps restant en haut de l'écran, uniquement lorsque le joueur est dans son véhicule loué.
- ⚠️ **Expiration automatique** — Avertissement avant la fin de la location et suppression automatique du véhicule.
- 🔒 **Sécurité serveur** — Vérification des paiements, des distances, des offres et des points d'apparition.
- 🚘 **Une location par joueur** — Impossible de louer plusieurs véhicules simultanément.
- 🚀 **Optimisation** — Contrôles adaptés à la proximité du PNJ et surveillance active uniquement lorsque nécessaire.

---

## 🔧 Compatibilité

### Frameworks

- 🟢 ESX Legacy
- 🟢 QBCore
- 🟢 Qbox
- 📦 Standalone — Adaptateur disponible pour connecter un système d'argent personnalisé.

### Intégrations

- Systèmes de clés configurables.
- Systèmes de carburant configurables.
- Véhicules GTA V natifs.

### Prérequis

- Serveur FiveM fonctionnel.
- **OneSync activé.**
- Framework compatible ou adaptateur Standalone configuré.

---

## 📥 Téléchargement

### 🟢 100 % GRATUIT

**[📥 Télécharger ASK LOCATION](https://github.com/asakidevpro-sudo/ask_location)**

Le script est disponible gratuitement sur GitHub.

---

## ⚙️ Installation

1. Téléchargez l'archive `ask_location.zip` depuis GitHub.
2. Extrayez le contenu de l'archive.
3. Placez le dossier `ask_location` dans les ressources de votre serveur FiveM.
4. Configurez les véhicules, tarifs, durées et points de location selon vos besoins.
5. Ajoutez cette ligne dans votre `server.cfg` :

```cfg
ensure ask_location
```

6. Redémarrez le serveur.

**Important :** assurez-vous que les dépendances nécessaires sont démarrées avant ASK LOCATION.

---

## 🎮 Fonctionnement

1. Le joueur se rend auprès du PNJ loueur.
2. Il ouvre l'interface de location.
3. Il sélectionne un véhicule parmi les modèles disponibles.
4. Il choisit la durée de location.
5. Le paiement est effectué.
6. Le véhicule apparaît au point configuré.
7. Le joueur profite de sa location avec un compteur affichant le temps restant lorsqu'il conduit le véhicule.
8. À l'expiration, le véhicule est automatiquement supprimé.

Aucun retour au PNJ n'est nécessaire.

---

## 🔐 Sécurité et performances

ASK LOCATION intègre plusieurs mécanismes destinés à sécuriser et optimiser son fonctionnement :

- Validation des paiements côté serveur.
- Contrôle des distances d'interaction.
- Vérification des offres de location.
- Validation des points d'apparition.
- Limitation à une location active par joueur.
- Surveillance adaptée à l'activité du joueur.

---

## 📜 Licence

ASK LOCATION est distribué sous **licence MIT**.

L'utilisation, la modification et la redistribution sont autorisées dans le respect des conditions de cette licence.

Consultez le fichier `LICENSE` pour davantage d'informations.

---

## 💚 Crédits

**Développement : AC STUDIO — AsakiDev**

Ce script est proposé gratuitement à la communauté FiveM.

Si vous appréciez notre travail, n'hésitez pas à laisser une ⭐ sur le dépôt GitHub !

**Merci pour votre soutien !**
