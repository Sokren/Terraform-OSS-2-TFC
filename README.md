# Terraform OSS to Terraform Cloud

Nous allons voir comment migrer de `Terraform OSS` vers `Terraform Cloud` (`TFC`) afin dans un premier temps d'utiliser `TFC` comme `backend` pour les `statefiles` puis de le relier à github afin de n'utiliser que `TFC`
Cette démo sert aussi à utiliser `TFC` pour centraliser les `statefiles`

## Lien vers la vidéo explicative

Lien

## Comment utiliser le repo

1. Télécharger le repo et désarchiver le fichier zip

2. Editer le fichier `providers.tf` avec vos identifiants Azure

3. lancer le déploiement

4. Dans TFC créer votre workspace

5. Se connecter à TFC

6. Renommer `terraform-cloud.tf.demo` en `terraform-cloud.tf`

7. A l'intérieur du fichier `terraform-cloud.tf` remplacer `YOUR_ORG` par votre ogranisation et `YOUR_WORKSPACE` par votre workspace

8. Initialisé `Terraform`

Voilà votre `statefile` est envoyé vers TFC
