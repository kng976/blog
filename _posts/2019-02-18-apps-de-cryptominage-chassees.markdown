---
author: Djinani
layout: post
layout: post-full
title:  "8 apps de cryptominage chassées du Microsoft Store"
tags: [Apps de cryptominage]
date:   2019-02-18 05:36:27
category: Sécurité
---

**Microsoft a supprimé huit applications de minage de cryptomonnaie malveillant de sa boutique d'applications en ligne. Ces dernières minaient de la cryptomonnaie Monero à l'insu des utilisateurs.**

<br/>

C’est au mois de janvier que des chercheurs en sécurité de Symantec ont trouvé les applications de cryptomining dans le Microsoft Store. On ne sait pas combien d'utilisateurs ont téléchargé ou installé ces applications introduites dans le store entre avril et décembre 2018, mais celles-ci affichaient près de 1 900 évaluations. Ces applications de cryptojacking présentées comme des navigateurs, des moteurs de recherche, des téléchargeurs de vidéo YouTube, des VPN et des tutoriels d'optimisation IT, proviennent de trois comptes de développeur dénommés DigiDream, 1clean et Findoo. Cependant, les chercheurs de Symantec pensent que les applications ont été créées par une seule personne ou un même groupe d'attaquants, car elles ont toutes le même domaine backend d'origine.


<br/>

« Dès que les applications sont téléchargées et lancées, elles récupèrent une bibliothèque de mining JavaScript en déclenchant le Google Tag Manager (GTM) dans leurs serveurs de domaine », ont expliqué les chercheurs de Symantec dans un rapport publié vendredi. « Le script de mining est alors activé et commence à utiliser la majorité des cycles CPU de l'ordinateur pour exploiter Monero pour les opérateurs. Même si ces applications semblent respecter des politiques de confidentialité, aucune fonction de mining n’est mentionnée dans les descriptions de la boutique d’applications de Windows ».

<br/>

**Des apps publiées en tant que PWA**

<br/>

Toutes ces applications ont été publiées en tant qu'Applications Web Progressives (PWA). Les PWA fonctionnent comme une page Web, mais elles ont également accès au hardware des machines via des API, elles peuvent envoyer des notifications push, utiliser du stockage hors ligne et se comporter quasiment comme un programme natif. Sous Windows 10, ces apps s'exécutent indépendamment du navigateur, sous un processus autonome appelé WWAHost.exe. Une fois exécutées, elles appellent le Google Tag Manager (GTM), un service légal qui permet aux développeurs d'injecter dynamiquement du JavaScript dans leurs applications.

<br/>

Toutes les apps utilisent la même clé GTM unique, ce qui laisse penser qu'elles ont été créées par le même développeur. Le script chargé par les applications est une variante de Coinhive, un mineur de cryptomonnaie basé sur le Web utilisé dans le passé par des attaquants pour infecter des sites Web et détourner les ressources CPU des visiteurs. « Nous avons informé Microsoft et Google du comportement de ces applications », ont déclaré les chercheurs de Symantec. « Microsoft a retiré les applications de sa boutique. Le code JavaScript de mining a également été supprimé de Google Tag Manager ».

<br/>

**Les extensions de navigateurs pas épargnées**

<br/>

Cet incident montre que l'extraction de monnaie cryptographique reste une activité très intéressante pour les cybercriminels. Qu'il s'agisse de détourner les ordinateurs personnels des utilisateurs ou les serveurs des datacenters, ils sont toujours à l'affût de nouvelles solutions pour déployer des mineurs de crytomonnaie. Ces deux dernières années, les pirates ont lancé diverses attaques de mining par le biais d'applications Android hébergées sur Google Play, d'extensions de navigateur pour Google Chrome et Mozilla Firefox, d'applications de bureau ordinaires, de sites Web compromis et désormais en détournant des Apps Web Progressives de Windows 10.

<br/>

Des botnets sont également utilisés pour infecter les serveurs Linux et Windows avec des programmes de mining de cryptomonnaie en exploitant les vulnérabilités des applications et des plateformes Web populaires. On recommande généralement aux utilisateurs de télécharger leurs applications uniquement à partir de sources fiables, autant sur appareils mobiles que sur ordinateurs. Mais avec l’introduction d’applications malveillantes dans les boutiques apps officielles, ces précautions ne suffisent plus.

<br/>

source : <https://www.lemondeinformatique.fr/actualites/lire-8-apps-de-cryptominage-chassees-du-microsoft-store-74368.html>

