---
author: Donalio
layout: post-full
title: Dans les coulisses de Tchap, la messagerie sécurisée de l’Etat français
featimg: 
tags: [text]
category: [Sécurité]
---
**Dans les coulisses de Tchap, la messagerie sécurisée de l’Etat français**

<br/>

**En dépit d’un premier couac au moment du lancement, ce nouvel outil de communication est une innovation de premier plan. Explications.**

<br/> 
Disponible depuis le 17 avril, la nouvelle messagerie gouvernementale Tchap a rapidement fait parler d’elle, mais pas vraiment en bien. Le jour suivant le lancement, un hacker a déniché une faille béante dans le contrôle d’accès, permettant à n’importe qui de créer un compte et de s’infiltrer dans des groupes de discussion. Il s’en est suivi une bonne rigolade sur Twitter et Facebook. Les professionnels de la critique facile ont été rassurés : visiblement, se disaient-ils, les projets informatiques du secteur public restent toujours aussi bancals.  

<br/>

Mais il serait dommage de réduire ce projet à ce fait divers numérique qui, par ailleurs, a été résolu en quelques heures seulement. Tchap est en réalité un projet très innovant qui mérite l’attention. Son objectif est de fournir une messagerie instantanée moderne et indépendante à tous les agents de la fonction publique d’Etat, soit environ 2,5 millions de personnes réparties dans des dizaines d’organismes : ministères, armée, administrations, académies, hôpitaux, etc. Jusqu’à présent, les déploiements de messageries instantanées dans la sphère publique restaient cantonnés à des usages opérationnels pour certains métiers ou dans certains secteurs. Exemple : l’application « Team on mission » pour les forces d’intervention. Tchap, à l’inverse, vise un usage quotidien et universel. Et à notre connaissance, la France est le seul pays à disposer à ce jour d’un tel outil.

<br/>

**Les origines de Tchap**

<br/>

Mais comment ce projet est-il né ? Et comment a-t-il été réalisé ? « A l’origine, l’impulsion est venue de la nouvelle équipe gouvernementale qui représente une nouvelle génération rompue aux pratiques numériques », nous explique Jérôme Ploquin, directeur de projet à la Direction interministérielle du numérique et du système d’information et de communication de l’Etat (DINSIC). En effet, il faut se souvenir qu’en 2017, Emmanuel Macron et La République en marche ont géré toutes leurs campagnes électorales depuis la messagerie Telegram. Celle-ci permettait assez facilement de diffuser la bonne parole aux militants et d’organiser les meetings. Une fois au pouvoir, la nouvelle équipe dirigeante a tout naturellement voulu doter l’appareil administratif d’une solution comparable, mais souveraine. Les objectifs étaient multiples : désengorger les boîtes e-mail, gagner en rapidité et en efficacité, développer le travail collaboratif, éliminer l'usage de messageries commerciales telles que WhatsApp ou Telegram.

<br/>

**Matrix, un système de communication décentralisé**

Mais ce qui peut apparaître simple sur le papier est en réalité un casse-tête. La fonction publique n’est pas un monolithe. Chaque secteur, chaque administration a sa propre infrastructure, ses propres systèmes, sa propre politique de sécurité, ses propres règles de gestion. Hors de question, dans ce cas, de déployer une messagerie unique et centralisée. Il fallait trouver une solution décentralisée s'appuyant sur un standard interopérable. Sur le marché, les technologies qui remplissent ce cahier des charges ne sont pas si nombreuses. « Il y a Jabber/XMPP, mais cette plateforme ne dispose pas de toutes les fonctions que nous recherchions et la communauté est en perte de vitesse. Matrix, en revanche, rentrait bien dans le cadre de nous nous étions fixé », explique Laurent Voillot, architecte et **RSSI** à la **DINSIC.**

<br/>

Matrix est la technologie sous-jacente de Tchap. Elle permet de mettre en place des infrastructures décentralisées de communications IP en temps réel et chiffrées de bout en bout : messagerie instantanée, appels voix, appels vidéo, en groupe ou en duo. Ce projet open source a été lancé en 2014 par une société américaine (Amdocs). Il est aujourd’hui piloté par une fondation à but non-lucratif de droit britannique. La plupart des développeurs impliqués dans ce projet travaillent pour la société New Vector, qui est également britannique et qui s’est spécialisée dans la fourniture de services autour de Matrix.

<br/>

L’architecture de Matrix repose sur la fédération de serveurs qui se synchronisent les uns par rapport aux autres. Ce principe permet à chaque administration d’avoir son propre serveur Matrix et de le gérer comme bon lui semble, tout en préservant la richesse fonctionnelle de l’application. Chaque administration peut, en particulier, utiliser son propre logiciel de sécurité pour analyser les pièces jointes. Contrairement aux textes des messages, celles-ci, en effet, ne sont pas chiffrées de bout en bout. Initialement, cette fonctionnalité n’existait pas dans Matrix. Elle a fait l’objet d’un développement spécifique avant d’être reversée à la communauté open source.  

<br/>

Dès le départ du projet, cet aspect ouvert et interopérable était d’ailleurs primordial dans le cahier des charges. Et c’est aussi l’une des raisons pourquoi la DINSIC n’a pas retenu la messagerie Citadel de Thales. Celle-ci s’appuie également sur Matrix, mais son code reste essentiellement propriétaire. Au total, Tchap représente une fédération d’une trentaine de serveurs. C’est certainement l’un des plus grands déploiements de Matrix à ce jour. Depuis son lancement, l’application compte déjà 11.000 utilisateurs. « Nous pensons qu'environ 15 à 20 % des agents vont venir assez rapidement sur Tchap en remplacement de messageries grand public déjà utilisées. L’élargissement du périmètre passera ensuite par la découverte et l’adoption de nouveaux usages, dans une logique de transformation numérique des missions des agents », estime Jérôme Ploquin.

<br/>

Tchap est-il vraiment sécurisé ?
Côté fonctionnalités, Tchap permet de dialoguer à deux ou de discuter en groupe, dans le cadre d’un salon privé ou public. Très prochainement, il sera même possible d’inviter des personnes extérieures, ce qui permettra de mieux collaborer avec les partenaires privés du secteur public. Un programme de bug bounty sera également mis en place dans les prochaines semaines. Ce qui devrait permettre, à l’avenir, d’éviter les mauvaises surprises comme celle qui a suivi le lancement de l’application. L’implémentation des communications voix et vidéo est également prévue à moyen terme.

<br/>

Sur Twitter, certains ont remis en cause la confidentialité réelle de la plateforme Tchap, en arguant que le système de notification reposait sur le service Google Firebase Messaging. Mais à la **DINSIC**, on se veut rassurant. « Aucune collecte de métadonnées n’est possible, car sur ce canal ne circulent que des identifiants alphanumériques. Il n’y a pas de message, ni de nom de personne ou de salon », souligne Jérôme Ploquin, tout en précisant que la plateforme Tchap disposait également d’une solution de notification alternative pour les flottes de téléphones sur lesquels Google Firebase Messaging était bloqué. Bref, tout semble donc en place pour un usage massif et sécurisé de Tchap. 

<br/>

source : <https://www.01net.com/actualites/dans-les-coulisses-de-tchap-la-messagerie-securisee-de-l-etat-francais-1680260.html>
