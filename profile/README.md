<div align="center">
  <img src="/assets/purpelab.png" alt="Logo" width="500">
</div>

# Bienvenue sur Purpelab 👋

Nous sommes des passionnés de **Purple Team** 🟣, et nous croyons fermement qu'il est essentiel de tester les règles de détection pour s'améliorer et mieux comprendre leur fonctionnement. Notre objectif est d'explorer et de perfectionner les méthodes de détection tout en testant et en contournant les mécanismes de sécurité pour renforcer la cybersécurité 🔐.

## Notre projet : ForgeLab ⚙️

**ForgeLab** est notre laboratoire dédié à la **Purple Team** 🟣, où nous testons les règles de détection Wazuh et tentons de les contourner. Ce projet nous permet de mieux comprendre les techniques de détection et de développer des stratégies pour améliorer les systèmes de sécurité existants.

### Objectifs de ForgeLab :
- Tester et améliorer les règles de détection Wazuh 🛡️.
- Expérimenter des techniques pour contourner ces règles et comprendre leurs limites 🔍.
- Partager nos découvertes et améliorer les pratiques de détection dans le domaine de la cybersécurité 🌐.


## Notre projet : WannaPurple 🦊

WannaPurple est un serveur C2 codé en C utilisant le protocole HTTPS pour communiquer avec ses implants.

L'implant C2 utilise le système de "beacon". Il n'est pas en liaison constante avec le serveur C2 : il envoie un signal à intervalle aléatoire pour récupérer des instructions ou transmettre les données collectées sur la cible.

La furtivité est la priorité du projet WannaPurple. Pour contourner les mesures de détection des antivirus et EDR, l'implant utilise des requêtes vers un document Google Docs (via l'API) afin de récupérer les instructions du serveur C2 (commandes chiffrées à exécuter, etc.). Il évite également les analyses heuristiques puisqu'il est capable de rester en sommeil et d'effectuer (toujours à intervalles aléatoires) des requêtes légitimes via l'API Google Docs et Google Drive.

Il sera testé sur des machines monitorées par un SIEM (Wazuh) avec des règles de détection robustes.


## Articles sur Medium 📝

Nous écrivons régulièrement des articles sur **Medium** 📚, où nous partageons des analyses intéressantes et des réflexions sur des sujets variés liés au **hacking** et à la **cybersécurité**. Nous revenons souvent sur des faits méconnus mais qui ont bouleversé l'histoire de la cybersécurité et du hacking. Nos articles couvrent des domaines tels que :
- **Intelligence économique** 🧠 : L'impact des données et de l'information dans le monde des affaires et de la politique.
- **Stratégie** 🎯 : Comment les entreprises et les gouvernements utilisent la cybersécurité dans leurs stratégies globales.
- **Géopolitique** 🌍 : Les relations internationales et leur influence sur la cybersécurité et les attaques informatiques.

### Suivez nos articles :
- [amaz974](https://medium.com/@amaz974)
- [CupOfCoffeeX](https://medium.com/@sraebisch)

## Comment contribuer 🤝

Si vous êtes passionné par la cybersécurité, les Purple Teams, ou tout autre sujet lié à notre domaine, n'hésitez pas à contribuer à nos projets ! Vous pouvez :
- Tester nos règles de détection et proposer des améliorations 🛠️.
- Partager vos propres découvertes et techniques 💡.
- Contribuer à nos articles ou proposer des idées pour de futurs sujets ✍️.

## Nous contacter 📬

- **Email** : [contact@purpelab.com](mailto:contact@purpelab.com)
- **Twitter** : [@Purpelab](https://twitter.com/Purpelab)

Merci de visiter notre profil GitHub et de suivre nos projets ! 🌟
