# Sujet

• Déployez wordpress en suivant les étapes suivantes

      Créez un deployment mysql avec un seul replicat


      Créez un service de type clusterIP pour exposer vos pods mysql

      Créez un deployment wordpress avec les bonnes variables d’environnement pour se connecter à la base de données mysql

      Votre deployment devra stocker les données de wordpress sur un volme mounté dans le /data de votre nœud

      Créez un service de type nodeport pour exposer le frontend wordpress

• Nous vous conseillons d’utiliser les manifests pour réaliser cet exercice

• Grâce à ce travail vous comprendrez mieux comment les fichiers contenu dans le chart wordpress

• A la fin de votre travail, poussez vos manifests sur github et envoyez nous le lien de votre repo à

eazytrainingfr@gmail.com et nous vous dirons si votre solution respecte les bonnes pratiques et si votre solution
bonne. Nous vous proposerons aussi notre solution/

# rendu 

Lancez les objets k8s avec les commandes suivantes:

kubectl apply -f fichier.yml

kubectl get pods (pour s'assurer que les pods tournes 

Consomez l'application votreIP:30008


