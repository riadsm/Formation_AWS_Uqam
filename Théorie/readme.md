## Coût d'un serveur AWS
En deux jours d'activité, j'ai dépensé 3$ US en serveur involontairement.

* Les serveurs qui roulent coutent de l'argent US$/heure.
* La version gratuite permet 1 serveur actif à la fois, plus que ça et vous le payer.
* **une instance, même arrêtée, a des frais : https://aws.amazon.com/fr/premiumsupport/knowledge-center/ebs-charge-stopped-instance/**
* Les addresses IP Elastic coûtent de l'argent si elles ne sont pas utilisées
* **Un serveur ne S'ÉTEINT PAS SEUL**
    Un serveur que vous fermez se réouvrira SEUL, sans votre intervention par défaut.
    
    Vous devez désactiver cette fonction vous-même
    
    Moi, j'ai supprimé tous les groupes "auto-scaling" sans considérer les répercussions, mais il y a **probablement** un moyen de gérer ça proprement.
* Vous pouvez avoir des informations sur vos dépenses, volontaires ou non dans le service **aws cost explorer**.
Vous pouvez choisir quand et comment afficher vos données.
<img src="https://github.com/hydraslahir/aws/blob/main/Théorie/images/i1.png">
