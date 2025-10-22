# Suivi de kilométrage Volvo EX 30

Application web pour suivre le kilométrage de votre véhicule par rapport à votre quota annuel.

## Fonctionnalités

- Calcul automatique du kilométrage attendu par rapport au temps écoulé
- Comparaison avec votre kilométrage actuel
- Projection du kilométrage annuel à votre rythme actuel
- Sauvegarde automatique des données dans le navigateur (localStorage)
- Compatible iOS avec icône d'application personnalisée
- Interface responsive adaptée aux mobiles

## Lancement du serveur

### Méthode 1 : Ligne de commande

```bash
python3 -m http.server 8000
```

Puis ouvrez votre navigateur sur [http://localhost:8000](http://localhost:8000)

### Méthode 2 : Via Zed Editor

1. Ouvrez le projet dans Zed
2. Appuyez sur `Cmd+Shift+P` (macOS) ou `Ctrl+Shift+P` (Linux/Windows)
3. Tapez `task spawn`
4. Sélectionnez "Lancer serveur web"

Le serveur démarre automatiquement dans un terminal intégré.

## Arrêt du serveur

### Si lancé en ligne de commande

Appuyez sur `Ctrl+C` dans le terminal où le serveur tourne.

### Si lancé via Zed

Fermez simplement l'onglet du terminal dans Zed, ou appuyez sur `Ctrl+C` dans le terminal.

## Installation sur iOS

1. Ouvrez l'application dans Safari sur votre iPhone/iPad
2. Appuyez sur le bouton **Partager** (icône de partage)
3. Sélectionnez **"Sur l'écran d'accueil"**
4. Appuyez sur **Ajouter**

L'application sera installée sur votre écran d'accueil avec l'icône de la Volvo.

## Technologies utilisées

- React 18 (via CDN)
- Tailwind CSS (via CDN)
- Babel Standalone (compilation JSX côté client)
- localStorage API pour la persistance des données