---
author: Rachad
layout: post-full
title: Faille de sécurité pour l'Iphone X
featimg: 
tags: [text]
category: [Sécurité]
---
Le 14 novembre, lors d’un concours à Tokyo, deux hackers ont prouvé que l’OS 12.1 de l’iPhone X comportait une faille de sécurité.

C’est par le navigateur Safari qu’ils sont parvenus à s’introduire dans le smartphone et à subtiliser une photo pourtant supprimée par l’utilisateur. Pour cela, ils ont utilisé un réseau Wi-Fi public sur lequel était connecté l’appareil. Informée, la firme de Cupertino n’a pour l’instant pas communiqué sur le problème.
L'accès à votre iPhone X est possible depuis un réseau Wi-Fi public

La nouvelle est tombée comme un couperet pour les détenteurs d'iPhone X. Ils sont nombreux à préférer la marque à la pomme pour la sécurité, mais le climat de confiance est à nouveau mis à mal. Cette fois, c'est l'accès à distance à la mémoire de l'appareil qui est en cause. En effet, deux hackers ont récemment réussi à pirater un iPhone X en passant par un réseau Wi-Fi public.

Richard Zhu et Amat Cama (du collectif Fluoroacétate) ont ainsi pu s'immiscer dans le tout dernier iOS de la marque (12.1), en exploitant les failles de sécurité du navigateur embarqué Safari. Leur action s'est déroulée dans le cadre d'un concours (Mobile Pwn2Own, le 14 novembre dernier), c'est pourquoi Apple en a été aussitôt informé. Les deux pirates se sont contentés de récupérer le premier élément disponible (une photo supprimée par l'utilisateur). Mais selon les sources, ils auraient pu tout aussi bien s'emparer d'autres données.
La faille de sécurité de l'iPhone X provient du compilateur juste-à-temps

C'est le programme JIT (compilateur juste-à-temps) qui est la porte d'entrée. Quelle est sa fonction ? Il a pour but d'accélérer l'iPhone X, en traduisant le codage informatique en même temps que l'exécution d'un programme. C'est un composant de l'environnement d'exécution, qui améliore les performances des applications Java. Mais comme le précise l'un des meilleurs spécialistes d'iPhone, tous les logiciels sont susceptibles de présenter une vulnérabilité aux attaques. Cependant, Apple s'applique depuis longtemps à proposer un niveau de sécurité élevé.

Pour cela, elle évite notamment l'utilisation des données personnelles le plus souvent possible. Son navigateur Safari, depuis plusieurs années, bloque les cookies poussés par les firmes publicitaires que l'utilisateur n'autorise pas directement. Tout est fait pour que les informations que vous laissez ne soient pas reliées à votre compte. Cependant, la lutte contre le tracking des régies publicitaires et réseaux sociaux n'a pas pu empêcher cette nouvelle faille de sécurité. Bref, il semblerait que toute donnée ayant été traitée par ce compilateur puisse être récupérée à distance.
Comment se protéger contre les hackers ?

Pour le moment, utilisez les moyens simples à votre portée. Coupez votre Wi-Fi lorsque vous vous approchez des réseaux publics et que vous n’en avez pas la nécessité. En effet, l'attaque ne peut se faire qu'à la condition que vous ayez connecté votre iPhone X à un réseau public. Puis videz régulièrement le contenu du dossier "Supprimés Récemment" en allant dans la zone suppression récente.

Ce serait un léger défaut de l’implémentation sur Safari qui serait à l'origine du problème de sécurité. Apple devrait proposer, comme à son habitude, un patch correctif pour la prochaine mise à jour de son iOS (la version 12.2).

Le problème principal est lié au fait que les pirates n'ont pas besoin d'avoir un accès physique à l'appareil. Ils passent ainsi toutes les barrières de sécurité mises en place dans le smartphone. En outre, les données compilées que vous supprimez sont automatiquement stockées dans la corbeille pendant environ un mois.

C'est cet endroit précis de l'OS que les deux chercheurs ont piraté, par l'application Photos. Toutefois, la faille toucherait potentiellement d'autres pans du système d'exploitation. Autre piste à creuser : chercher à désactiver le compilateur JIT, actif par défaut.
Safari et Sandbox à l'origine de la faille de sécurité

Le problème de sécurité ne concerne pas uniquement l'iPhone X. Il toucherait aussi d'autres modèles d'iPhone, ainsi que certains appareils qui fonctionnent sous Android. Par exemple, les deux hackers ont trouvé des failles de sécurité pour subtiliser des données sur le Samsung Galaxy 9 et sur le Xiaomi Mi 6. Par ailleurs, le défaut, qui serait lié à l'implémentation du compilateur JIT sur Safari se combine à un autre problème. En effet, les deux chercheurs ont aussi prouvé qu'ils avaient dû détourner la Sandbox pour pouvoir pénétrer librement dans l'OS.

Ils auraient ainsi réussi à leurrer ce dispositif de quarantaine, justement fait pour tester les lignes de code avant de leur ouvrir les portes du système d'exploitation. En soi, le sandboxing est complémentaire à l'analyse des signatures de virus parce qu'il détecte les attaques de type sans signature, ou jamais vues. Mais il ne serait visiblement pas totalement efficace. Ce qui pose la question plus large des failles informatiques courantes des réseaux domestiques et professionnels. Même Apple, qui fait d'énormes efforts en matière de sécurité pour protéger les données personnelles, n'est pas à l'abri.  


source : <https://www.journaldunet.com/solutions/expert/70124/faille-de-securite-de-l-iphone-x---exlications.shtml>
