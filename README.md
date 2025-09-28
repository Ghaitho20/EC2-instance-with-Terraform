# Mini-projet: Déployez une infra complète

  *  module pour créer une instance ec2 utilisant la dernière version de ubuntu bionic (qui
  s’attachera l’ebs et l’ip publique) dont la taille et le tag seront variabilisés
  *  un module pour créer un volume ebs dont la taille sera variabilisée
  *  un module pour une ip publique (qui s’attachera la security group)
  *  un module pour créer une security qui ouvrira le 80 et 443
  * Créez un dossier app qui va utiliser les 4 modules pour déployer une ec2, bien-sûr vous allez surcharger
  les variables afin de rendre votre application plus dynamique

