# Nina Carducci - Optimisation SEO, Performances et Accessibilité

Ce projet dans le cadre de ma formation consiste en l'optimisation technique et référentielle du site portfolio de la photographe **Nina Carducci**. L'objectif principal était d'améliorer la vitesse de chargement, le référencement naturel (SEO), l'accessibilité ainsi que de corriger des bugs fonctionnels existants.

## 🚀 Objectifs de la mission

Suite à un audit initial, plusieurs axes d'amélioration ont été identifiés et traités :

1.  **Optimisation des performances :** Amélioration des scores Lighthouse (Desktop & Mobile).
2.  **SEO (Référencement) :** Mise en place des balises méta et optimisation pour les moteurs de recherche.
3.  **Référencement Local :** Implémentation de Schema.org pour l'activité à Bordeaux.
4.  **Réseaux Sociaux :** Ajout des métadonnées Open Graph et Twitter Cards.
5.  **Accessibilité :** Corrections basées sur les recommandations WCAG (Audit Wave).
6.  **Débogage :** Correction de fonctionnalités cassées dans la galerie et les filtres.

## 🛠 Actions réalisées

### 1. Performance et Optimisation des médias
- Conversion des images au format **WebP** pour réduire leur poids sans perte de qualité visible.
- Redimensionnement des images pour correspondre à leur taille d'affichage.
- Mise en place du **Lazy Loading** pour différer le chargement des images hors écran.
- Minification des fichiers CSS et JavaScript.

### 2. SEO & Référencement Local
- Réécriture et optimisation des balises `<title>` et `<meta description>` pour chaque contenu.
- Ajout des balises **Schema.org** (JSON-LD) pour le référencement local avec les informations suivantes :
  - **Adresse :** 68 avenue Alsace-Lorraine, 33200 Bordeaux
  - **Téléphone :** 05 56 67 78 89
  - **Horaires :** Lundi au Vendredi, 10h - 19h
- Hiérarchisation correcte des titres (H1, H2, H3).

### 3. Accessibilité (A11Y)
- Ajout des attributs `alt` pertinents sur toutes les images.
- Optimisation des contrastes de couleurs pour la navigation.
- Correction de la structure sémantique du HTML.

### 4. Corrections de Bugs (Fixes)
- **Navigation Modale Galerie :** Correction du script pour permettre la navigation entre les images (précédente/suivante) à l'intérieur de la lightbox.
- **Filtres de Catégorie :** Correction de la classe CSS active (`.active`) sur les boutons de filtre. Désormais, la catégorie sélectionnée s'affiche bien avec le fond doré, identique au filtre par défaut.

## 💻 Installation et Lancement

Ce site est statique (HTML/CSS/JS). Pour le visualiser localement :

1.  Clonez le repository :
    ```bash
    git clone https://github.com/andy123-glitch/Nina-Carducci-Dev.git
    ```
2.  Ouvrez le fichier `index.html` dans votre navigateur.
    *Recommandation : Utilisez une extension comme "Live Server" sur VSCode pour simuler un serveur local.*

## 📊 Rapports d'intervention

Un rapport détaillé avant/après est disponible, incluant :
- Les scores **Lighthouse** (Performance, SEO, Accessibilité).
- Les résultats de l'audit **Wave**.
- La liste exhaustive des modifications apportées.

## 🔗 Liens utiles

- **Site original (Avant optimisation) :** [nina-carducci.github.io](https://nina-carducci.github.io)
- **Code source optimisé :** [GitHub Repository](https://github.com/andy123-glitch/Nina-Carducci-Dev)
