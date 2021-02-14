# Système de gestion d'établissement sportif

## Préambule

    Dans le cadre de ce kata, il sera question de réaliser une application qui offrira des une satisfaction au niveau de l'expérience utilisateur
     attendues par un grand nombre de clients.
    La solution proposée devra répondre aux exigences suivantes:
    - Gestion des adhérents: abonnemens, abonnés, cartes abonnements
    - Plannings
    - Pointage grâce au code barre
    - Notification aux premiers adhérents (par sms ou par email)

## Besoins métiers

    1) Abonnements:
        - Les premiers adhérents doivent bénéficier d'une semaine gratuite après leur inscription et peuvent annuler pendant cette semaine leur inscription
        - L'inscription devra être prise en compte à partir de la deuxième semaine.
        - Une fois l'inscription effectuée, le prélèvement sera effectué directement dans le compte de du client  même si ce dernier
        veut résilier son abonnement. Dans ce cas, la résiliation sera effective dès la fin du mois en cours.
        - L'inscription s'élève au prix de 22.99€/mois et 5€ pour les suppléments(coaching, accompagnements, suivi etc)
        - La résiliation de l'abonnement se fait à tout moment

## Spécifications

Il serait plus judicieux d'adopter l'approche clean architecture / TDD pour effectuer ce kata.

## Comment l'utiliser

> npm install : installation des packages
> npm start : Démarrage du serveur
> npm run test : exécuter les tests
