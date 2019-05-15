---
author: Asmed
layout: post
layout: post-full
title:  "Une faille dans WPA 3 rend vulnérable les réseaux WiFi domestiques"
tags: [text]
date:   2019-04-16 10:36:27
category: [Sécurite]
---

**La dernière itération du protocole de sécurité WPA3 visant à sécuriser les connexions WiFi domestiques est vulnérable à une faille découverte par deux chercheurs universitaires. Cette dernière permet un accès malveillant au réseau sans fil en usurpant son mot de passe.**  

<br/>

Jamais deux sans trois ? Après la découverte de la faille du protocole de sécurité WPA 2 fin 2017, c'est maintenant au tour de son successeur, WPA 3, d'être mis sur la sellette. Deux chercheurs, Mathy Vanhoef de l'université new-yorkaise d'Abou Dabi et Eyal Ronen des universités de Tel Aviv et de KU Leuven en Belgique ont en effet publié des travaux mettant en avant une vulnérabilité permettant à un individu malveillant de s'introduire sur un réseau WiFi domestique sans utiliser son mot de passe. « Cela permet à un adversaire de voler des informations sensibles telles que des cartes de crédit, un mot de passe, des courriels, etc., lorsque la victime n'utilise pas de couche de protection supplémentaire telle que HTTPS », alertent les chercheurs.  
<br/>
Mathy Vanhoef et Eyal Ronen ont indiqué travailler avec la Wi-Fi Alliance, l'organisation en charge de la standardisation et des projets liés à cette technologie réseau sans fil, pour permettre aux fournisseurs de terminaux de prendre les mesures correctives nécessaires pour palier le souci. « Malheureusement, nos attaques contre WPA 3 fonctionnent également contre EAP-pwd, ce qui signifie qu'un adversaire peut même récupérer le mot de passe d'un utilisateur lorsque EAP-pwd est utilisé. Nous avons également découvert des bugs sérieux dans la plupart des produits qui implémentent EAP-pwd. Celles-ci permettent à un adversaire de se faire passer pour n'importe quel utilisateur et d'accéder ainsi au réseau Wi-Fi sans connaître le mot de passe de l'utilisateur », ont précisé les chercheurs.  
<br/>

**L'installation des dernières mises à jour sécurité recommandée**  

<br/>
Les failles de conception dans WPA 3, détaillées dans un document complet, sont scindées en deux catégories : celles concernant des attaques contre les périphériques compatibles WPA 3 et d'autres exploitant des faiblesses de Dragonfly, le standard d’authentification simultanée SAE (Simultaneous Authentication of Equals) utilisé dans la dernière version du protocole de sécurité. Toutes ces attaques mettent à risque les réseaux domestiques (WPA 3-Personal) dont le mot de passe est partagé par tous les utilisateurs. Les vulnérabilités sont les suivantes : CertID VU871675 (attaque par rétrogradation en mode WPA3-Transtition conduisant à des attaques par dictionnaire), CertID VU871675 (attaque par rétrogradation du groupe de sécurité Dragonfly), CVE-2019-9494 (attaque par canal latéral basée sur le minutage Dragonfly), CVE-2019-9494 (attaque par canal latéral basée sur le cache Dragonfly), CertID VU871675 (attaque contre la consommation de ressources par exemple, déni de service Dragonfly)..  
<br/>
« Wi-Fi Alliance a immédiatement pris des mesures pour que les utilisateurs puissent compter sur WPA3-Personal pour offrir des protections de sécurité encore renforcées. WPA3-Personal inclut désormais des tests supplémentaires basés sur des éléments des dernières recherches. Wi-Fi Alliance communique de manière générale les instructions de mise en œuvre afin de garantir que les fournisseurs comprennent les considérations de sécurité pertinentes. Comme toujours, les utilisateurs Wi-Fi doivent s’assurer d’avoir installé les dernières mises à jour recommandées par les fabricants d’appareils », a prévenu dans un communiqué la Wi-Fi Alliance.  
<br/>
<br/>

Vous retrouverez l'article original en cliquant sur le lien ci-dessous.  
<br>
<https://www.lemondeinformatique.fr/actualites/lire-une-faille-dans-wpa-3-rend-vulnerable-les-reseaux-wifi-domestiques-74979.html> 

