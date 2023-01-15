# script-redemarrage-journalier-ubuntu-vps
Un script permettant de redémarrer votre vps sous ubuntu de manière journalière avec les tâches cron.

# Utilisation

Ouvrez le fichier de configuration de cron pour l'utilisateur en cours en utilisant la commande crontab -e. <br>
Ajoutez une nouvelle ligne au fichier en utilisant le format suivant :   <br>
>        # Edit this file to introduce tasks to be run by cron. 
>        # 
>        # Each line represents a single cron job to be run once a day  
>        # For more information see the manual pages of crontab(5) and cron(8)  
>        #  
>        # m h  dom mon dow   command 
>        0 3 * * * /chemin/vers/script.sh 

 

<br>
<strong>  0 3 * * * /chemin/vers/script.sh  </strong><br>
Ici, tous les jours à 3 heures du matin le script.sh se situant dans /chemin/vers/ sera executé. 
<br>
