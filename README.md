• Vous avez reçu la demande d’une autre équipe qui souhaiterait utiliser un de vos playbook de
déploiement de WordPress, mais sous forme de rôle car sous cette forme ils pourront mieux variabiliser et adapter à leur situation
• Leur objectif est que votre rôle possède un playbook tests afin de leur permettre de tester 
rapidement votre rôle et ainsi l’intégrer à leur process de déploiement, exactement comme le rôle wordpress
• Utilisez le rôle docker précédemment crée afin de créer un nouveau rôle qui permettra de déployer 
l’application wordpress à l’aide de deux containers docker (mysql + wordpress) 
• Déployez vos différents container à l’aide du module docker_container, ces containers devront appartenir à un meme réseau « wordpress » que vous devez au préalable créer à partir du module ansible « docker-network »
• Variabilisez un maximum de paramètres de ce role afin qu’il puisse etre utilisé par différentes entreprises fonction du besoin, on devra pouvoir personnaliser lors du déploiement : • Le nom du réseau dans lequel sera crée les container
• Le nom des container
• Le port sur lequel consommer l’application 
• Le nom du volume dans lequel sera sauvegardé le BDD mysql (vous devrez mettre en place la persistence)
• A la fin de votre travail, poussez votre rôle sur github et sur la galaxy ansible (wordpress_role) et 
envoyez nous votre rapport détaillé de mise en œuvre en PDF via l’intranet (Partage de 
documents)
