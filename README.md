# suivicarte
# 📦 Hub de Suivi de Colis Universel
Ce projet est un outil simple et léger pour suivre vos colis (Colissimo, DPD, etc.) sans publicité, avec une carte interactive.
## 🛠️ Comment ça fonctionne ?
 * **API Track123 :** L'application utilise l'API de Track123 pour agréger les données de suivi.
 * **Sécurité :** Pour des raisons de sécurité, la clé API a été retirée de ce dépôt public. Pour faire fonctionner votre propre instance, vous devez créer un compte gratuit sur Track123 et insérer votre clé dans la variable TRACK123_KEY au début du fichier index.html.
 * **Carte interactive :** Le script analyse les données de suivi. Si une ville ou un lieu est détecté dans les étapes, une carte interactive (Leaflet + OpenStreetMap) se centre automatiquement sur la position probable du colis.
 * **Système d'alerte API :** Une bannière d'information s'affiche en haut du site pour vérifier immédiatement si votre clé API est correctement configurée. Une fenêtre modale vous demande également si vous souhaitez masquer ce message lors de vos prochaines visites.
 * **Conception :** Code assisté par IA.
## 🚀 Version hébergée
 * Si vous ne voulez pas déployer le projet vous-même, vous pouvez tester la version déjà en ligne ici : https://suivicarte.netlify.app/
 * **Attention :** Cette version hébergée utilise une clé API limitée à 50 colis uniques par mois. Si le quota est atteint, merci de déployer votre propre instance avec votre propre clé.
## 📢 Appel à la communauté
 * Je suis à la recherche de généreux contributeurs ! Si vous travaillez dans la tech ou la logistique et que vous disposez d'une clé API professionnelle (ou avec un gros quota) pour un agrégateur de suivi de colis, et que vous souhaitez m'aider à faire sauter cette limite pour tout le monde, contactez-moi par mail : **louigii53@gmail.com**. Merci d'avance pour votre aide !
