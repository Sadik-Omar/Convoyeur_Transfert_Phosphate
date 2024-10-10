# Projet : Dimensionnement et Contrôle-Commande d’un Convoyeur de Transfert de Phosphate Sec

Ce projet fait partie du module **Architecture et Technologie des Systèmes** à l'ENSAM-Meknès, année 2024. Il concerne le dimensionnement et la gestion du contrôle-commande d'un convoyeur de transfert de phosphate sec, en collaboration avec l'OCP, pour un site situé au bord de la mer.

## Objectifs du Projet

L'objectif est de concevoir un convoyeur CJL capable de transporter du phosphate sec entre une tour de décharge et une unité de mise en stock. Le projet couvre à la fois le dimensionnement du moteur, la sélection des composants mécaniques et électriques, ainsi que la programmation du système de contrôle-commande.

### Caractéristiques Principales du Convoyeur

- **Débit** : 2200 T/H, soit une capacité journalière de 52800 T.
- **Largeur de bande** : 1600 mm
- **Vitesse de bande** : 1,60 m/sec
- **Hauteur du convoyeur (H)** : 8,2 m
- **Longueur du convoyeur (L)** : 83 m
- **Atmosphère** : Humide et corrosive (bord de mer)

### Éléments Clés à Étudier

1. **Dimensionnement du moteur asynchrone** :
   - Puissance à calculer en tenant compte des conditions de démarrage et de fonctionnement.
   - Sélection du moteur, réducteur et frein à partir des catalogues de SEW.
   - Utilisation d'un variateur de vitesse de la marque **Schneider** pour le contrôle du convoyeur.

2. **Système de protection et de sécurité** :
   - Protection contre le déport de bande et la rupture de bande.
   - Intégration d'un frein électromécanique pour immobiliser le convoyeur à l'arrêt.
   - Installation d'un arrêt d'urgence à câble sur toute la longueur du convoyeur.

3. **Contrôle-Commande par API Siemens S7-1200** :
   - Gestion des asservissements entre les convoyeurs CJL, B1/C1 (tour de décharge) et B2/C2 (mise en stock).
   - Programmation du démarrage et de l'arrêt du convoyeur avec des relais de sortie, entrées TOR et paramètres à programmer sur le variateur.

4. **Équipements électriques** :
   - Installation de luminaires LEDs le long du convoyeur.
   - Prises 220V réparties uniformément tous les 10m.
   - Conception et dimensionnement de l'armoire électrique (référence Schneider à spécifier).

### Livrables du Projet

Le projet nécessite la remise d'un dossier technique complet comprenant :

- **Dimensionnement du moteur asynchrone** avec méthode de calcul et justification des paramètres choisis.
- **Références du moteur, réducteur et frein** (catalogue SEW) et du variateur (catalogue Schneider).
- **Schémas électriques complets** réalisés sous **AUTOCAD ELECTRICAL 201x**.
- **Plan de l’armoire** de contrôle-commande avec sa référence Schneider.
- **Nomenclature des équipements** (boutons poussoirs, relais, disjoncteurs, etc.).

### Contraintes

- **Environnement corrosif** : Le convoyeur est exposé à des conditions de bord de mer, nécessitant des matériaux résistants à la corrosion.
- **Système de sécurité renforcé** : Protection contre la défaillance du système de transport et arrêt d'urgence en cas de problème.
- **Alimentation électrique** : Puissance triphasée 3x660V + N + T.

---

**Équipe :**
Omar Sadik  
Yassine el koulfa
ENSAM Meknès - 2024
