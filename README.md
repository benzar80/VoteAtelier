Projet final - Système de vote

Groupe Télécom : Lucas Delicourt, Aurélien Beaudoin (grp info), Maxence Buléon, Noah Davenel, Ervis Basha, Tom Béranger, Thomas Cazin

Pour commencer voici quelques ressources :

Lien vers le déploiement publique : https://benzar80.github.io/VoteAtelier/

Lien vers la vidéo : https://we.tl/t-JoEWAiDw2m

Lien vers le contrat : https://github.com/benzar80/VoteAtelier/blob/main/contracts/Voting.sol

Lien vers le App.jsx : https://github.com/benzar80/VoteAtelier/blob/main/client/src/App.jsx

Lien vers le App.css : https://github.com/benzar80/VoteAtelier/blob/main/client/src/App.css

Lien vers les tests  : https://github.com/benzar80/VoteAtelier/blob/main/test/VotingTest.js

Lien vers truffle-config : https://github.com/benzar80/VoteAtelier/blob/main/truffle-config.js

Explication et répartition du groupe :

Back-End (Lucas Delicourt, Aurélien Beaudoin, Maxence Buléon):
    
    *Création du code contract Voting.sol
    
    *Création des tests en .js
    
    *Améliorations du code Voting.sol dont ajout de nouvelles 
    
    fonctionnalités

Front-End (Noah Davenel, Tom Béranger, Thomas Cazin, Ervis Basha):
    
    *Création des fonctions pour la gestion Back-Front
    
    *Code HTML dont gestion des champs/boutons en fonction de l'état du vote
    
    *Code CSS

Gestion des relations et du projet global (Lucas Delicourt):
    
    *Utilisation de ganache
    
    *Utilisation de metamask
    
    *Utilisation de truffle
    
    *Utilisation de Node.js
    
    *Mise en place du déploiement publique


Contexte :

Ce projet consiste en la création d'un système de vote décentralisé basé sur la blockchain Ethereum. Il implémente un contrat intelligent pour gérer le processus de vote et une Dapp pour interagir avec le contrat. Le projet comprend également des tests unitaires pour le contrat intelligent et des fonctionnalités supplémentaires comme par exemple la possibilité de supprimer un utilisateur.

Fonctionnalités principales :
1. Enregistrement d'une liste blanche d'électeurs
Le système de vote permet à l'administrateur (le compte qui déploie le contrat intelligent) de gérer une liste blanche d'électeurs. Cette liste est utilisée pour contrôler l'accès au processus de vote. Seuls les électeurs enregistrés dans cette liste peuvent soumettre des propositions et voter.

Ajout d'électeurs : L'administrateur peut ajouter des électeurs en spécifiant leur adresse Ethereum.

Suppression d'électeurs : L'administrateur peut retirer des électeurs de la liste blanche en supprimant leur adresse Ethereum.

2. Gestion des propositions par les électeurs inscrits
Une fois que les électeurs sont inscrits sur la liste blanche, ils peuvent soumettre des propositions pour le vote. Les propositions sont des suggestions ou des idées soumises par les électeurs pour être votées par l'ensemble des électeurs.

Ajout de propositions : Les électeurs peuvent soumettre des propositions en fournissant une description textuelle de la proposition.

Consultation des propositions : Les électeurs peuvent consulter la liste des propositions soumises pour le vote.

3. Processus de vote sécurisé et transparent
Le processus de vote lui-même est sécurisé et transparent, grâce à la nature décentralisée et immuable de la blockchain Ethereum. Les électeurs peuvent voter pour les propositions en utilisant leur adresse Ethereum, et chaque vote est enregistré de manière transparente et vérifiable.

Voter pour une proposition : Les électeurs peuvent voter pour une proposition en sélectionnant la proposition et en soumettant leur vote.

Contrôle des doubles votes : Le système de vote empêche les électeurs de voter plusieurs fois pour la même proposition ou de voter pour plusieurs propositions.

4. Comptabilisation des votes et détermination du gagnant
Une fois que le processus de vote est terminé, le système de vote comptabilise automatiquement les votes et détermine la proposition gagnante. La proposition gagnante est celle qui a reçu le plus grand nombre de votes.

Comptage des votes : Le système de vote enregistre et comptabilise les votes pour chaque proposition.

Détermination de la proposition gagnante : Le système de vote détermine et annonce la proposition gagnante en fonction du nombre de votes reçus.

Consultation des résultats : Les électeurs peuvent consulter les résultats du vote, y compris le nombre de votes pour chaque proposition et la proposition gagnante.

En résumé, ce système de vote basé sur la blockchain Ethereum offre un processus de vote sécurisé, transparent et décentralisé, permettant aux électeurs de soumettre des propositions, de voter pour leurs préférences et de consulter les résultats du vote en toute confiance.



