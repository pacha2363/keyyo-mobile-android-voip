


# Introduction #

Cette foire aux question a pour but de rassembler le maximum d'unformation concernant l'usage de l'application Keyyo VoIP pour Android.

# La VoIP - Cela sert à quoi ? #

La VoIP - voix sur IP - est une technologie de téléphonie à travers Internet. Associée au protocole SIP, elle permet de téléphoner, moyennant un compte SIP / VoIP Keyyo.

Pour que cela fonctionne, votre téléphone doit donc avoir une connexion data internet. Cela nécessite donc que le téléphone soit **connecté** en Wi-Fi. Sans cela seul les appels GSM seront possibles.

# Quels sont les mobiles supportés #
Les mobiles supportés sont
  * HTC Desire HD 2.2 et 2.2.1
  * Samsung Galaxy S 2.2
  * Samsung Galaxy Teos 2.2

D'autres terminaux sont compatibles mais non testés
  * Nexus One - 2.2 et 2.2.1
  * HTC Desire - 2.1 et 2.2
  * HTC Legend - 2.1
  * Motorola Defy - 2.2
  * Samsung Spica - 2.1
  * Sony Ericsson Xperia X10 - 2.1
  * Et d'autres encore ...

En théorie, tout téléphone doté d'Android 1.6 minimum supporte l'application Keyyo VoIP. Le support exact peut être différent en fonction des constructeurs.

# Puis-je utiliser l'application en 3G #

L'application ne fonctionnera pas sur réseau mobile (3G/Edge) du fait de limitation physique du réseau. Elle est testée et validée sur les réseaux Wi-Fi

# Puis-je appeler de l'étranger en VoIP ? #

Oui ! Et c'est une des fonctionnalités de la VoIP. Dès que vous avez une connexion Wi-Fi disponible, l'accès au service de téléphonie VoIP est automatique avec Keyyo VoIP. Il n'y a aucun surcoût. Le seul peut-être nécessaire est le coût de connexion au Hotspot Wi-Fi.

Cela fonctionne aussi en sens inverse. Préférez la VoIP lorsque vous appelez vers l'étranger pour diminuer vos coûts de communication.

# Comment utiliser mon compte SIP / VoIP #

Rendez vous sur votre espace client Keyyo Mobile, les instructions détaillées s'y trouvent

# Comment passer un appel SIP / VoIP ? #

Dès que vous avez une connexion Wi-Fi disponible et que l'icône représentant un téléphone doté de la mention IP est visible dans la barre de notification, vous êtes en mesure de passer un appel VoIP.

Composer alors normalement votre numéro ou choisissez un contact. Juste avant de composer ce numéro, le mobile vous demandera par quel canal passer : VoIP ou GSM.

# Je dois faire le 0 pour sortir #
Dans les offres Keyyo Centrex, vous devez ajouter le 0 pour sortir avant de composer le numéro. Ce mode de fonctionnement n'est pas compatible avec le GSM.

Pour utiliser votre carnet d'adresse de manière indifférente sur le mobile et en VoIP, vous avez 2 solutions :
  1. Préfixer tous vos numéro par le code du pays. Par exemple +33 pour la France
  1. Ajouter un filtre dans les réglages de l'application Keyyo VoIP pour ajouter le 0 automatiquement

# Ajouter un filtre dans l'application Keyyo VoIP #
Les filtres sont applicables par compte. Par exemple, si vous utilisez une offre Keyyo Centrex et une offre Keyyo Home au sein de la même application, vous devez composer le 0 pour sortir avec l'offre Keyyo Centrex.

Pour ajouter automatiquement le 0 sans avoir à le composer à chaque fois, réalisez les opérations suivantes
  * Ouvrez l'application Keyyo VoIP
  * Depuis l'écran principal, suivez le parcours suivant
  * _Touche Menu > Options > Filtres_
  * Sélectionnez le compte concerné _celui du bas correspond à votre ligne GSM_
  * Ajoutez maintenant une règle en fonction de vos besoins


Pour notre exemple, le filtre a créer aura les propriétés suivantes
  * Filtre de réécriture
  * Numéro commençant par 0
  * Règle : préfixer avec 0

Pour les plus avancés avec l'informatique, l'application supporte les expressions régulières dans les filtres.

Vous pourrez alors composer le numéro 01 82 83 28 28 de manière indifférente avec vous 2 comptes. Keyyo VoIP aujoutera automatiquement un 0 pour une utilisation avec le compte Keyyo Centrex

# Quel codec choisir ? #

Keyyo VoIP supporte les codecs G711 (PCMU, PCMA), G722 (VoIP HD), G729, GSM, Speex et iLBC. Le codec G711 est le plus commun sur les plateformes VoIP. L'usage d'un codec dépend d'une négociation entre votre appareil et celui de votre correspendant. Ce n'est donc pas parce que vous avez activé le G722 ou le G729 que celui-ci sera utilisé à chaque communication.

Pour activer / désactiver un codec, un appui long sur son titre. Il vous reste ensuite à les classer par ordre de priorité

Le codec G729 est également activable mais nécessite une licence. Pour l'utiliser en toute légalité, nous vous recommandons d'acheter la licence auprès de [Synapse Global](http://www.synapseglobal.com/g729_codec_license.html).