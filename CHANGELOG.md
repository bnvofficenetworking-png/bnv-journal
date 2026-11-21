# BNV Journal de Trading — historique des versions

## Version 2026.1 — 21 novembre 2026 (version définitive 2026)

### Calculs (vérifiés à la main sur des trades d'essai et sur les 100 trades d'exemple)
- Espérance = P&L total ÷ nombre de trades (un trade à 0 $ compte 0).
- Drawdown et séries gagnantes / perdantes dans l'ordre réel des clôtures.
- R1 du profil actif partout : PR1 (capital opérationnel × risque %) ou PR2 (phase 1 puis phase 2 selon les pertes du jour).
- Les trades de Backtest ne consomment plus les limites de perte du compte.
- Taux de réussite = gagnants ÷ (gagnants + perdants) : les trades à 0 $ sont exclus, sur tous les écrans.
- Jours comptés à la date de clôture partout (Dashboard, mois, année, jours, semaines, liste).
- Consistance du mois = 100 % − (meilleur jour gagnant ÷ profit total du mois).
- Durée de détention au-delà d'un an affichée en années et mois.

### Dashboard et Calculateur
- Sélecteur « Compte affiché » : Réel + Démo (par défaut), Réel, Démo, Backtest, Tous.
- Calculateur de position toujours synchronisé avec le Dashboard (capital, profil LP1 / LP2, risque %) ; saisies manuelles conservées.
- Correctif : une erreur quand le mois en cours n'a aucun trade bloquait le Calculateur et la Mesure du processus.

### Page d'accueil
- Vraie page d'accueil : barre du haut, présentation, chiffres, fonctionnalités, gestion du risque, étapes, pied de page avec avertissement sur les risques.
- Image de fond animée (graphique de bougies, globe, bandeau des marchés), dessinée pour BNV.
- « Connexion » et « Créer un compte » seulement en haut à droite ; chacun ouvre sa propre fenêtre, toujours entièrement visible.
- Bouton pour afficher / masquer le mot de passe.
- Icône d'onglet, description et aperçu de partage (réseaux sociaux, moteurs de recherche).
