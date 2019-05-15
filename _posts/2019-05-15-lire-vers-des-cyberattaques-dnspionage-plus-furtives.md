---
author: Bacar
layout: post
layout: post-full
title:  "Vers des cyberattaques DNSpionage plus furtives"
tags: [text]
date:   2019-05-15
category: [Ordinateur]
---
<br/>
**Le groupe de pirates informatiques DNSpionage qui a attaqué le système de noms de domaine (DNS) en novembre dernier a étoffé ses moyens d'intrusion. D'après les chercheurs en sécurité de Cisco Talos, des outils rendant ces cyberattaques plus furtives vont être utilisés.**

<br/>

<br/>
Le groupe à l'origine des attaques du système de noms de domaine (DNS), connues sous le nom de DNSpionage, a renforcé ses méthodes en introduisant de nouveaux outils et d'autres malwares afin de concentrer ses attaques et rendre ses activités plus furtives. Cette semaine, les chercheurs en sécurité de Cisco Talos - à qui l'on doit la découverte de DNSpionage en novembre dernier - a mis en garde contre les nouveaux exploits et les nouvelles capacités de ces attaques. « Le développement en continu du malware DNSpionage montre que le groupe responsable des attaques cherche à se doter de nouveaux outils pour éviter la détection. Le tunnelage DNS est une méthode d'exfiltration couramment employée par certains pirates et les exemples récents de DNSpionage montrent qu'il faut surveiller le DNS aussi étroitement que les proxy ou les webblogs d'une entreprise », ont écrit les chercheurs en sécurité de Talos. « Le DNS est l'équivalent du répertoire téléphonique de l'Internet, et s'il est altéré, il devient difficile pour chacun de discerner si ce qu'il voit en ligne est légitime ».
<br/>

<br/>
Dans leur premier rapport, les chercheurs de Talos avaient indiqué que l'attaque DNSpionage visait diverses entreprises du Moyen-Orient ainsi que les domaines utilisés par l'administration des Emirats Arabes Unis. L'attaque s'appuyait aussi sur deux sites Web d'offres d'emploi malveillants qui servaient à compromettre leurs cibles en leur transmettant des documents Microsoft Office avec des macros intégrées. Le malware supportait également la communication HTTP et DNS avec les attaquants. Dans une campagne DNSpionage distincte, les attaquants ont utilisé la même adresse IP pour rediriger les DNS légitimes de domaines .gov et d'entreprises privées. A chaque fois qu'il a pu compromettre un DNS, l'attaquant a soigneusement généré des certificats « Let's Encrypt » pour les domaines redirigés. « Ces derniers fournissent gratuitement à l'utilisateur des certificats X.509 pour le protocole TLS (Transport Layer Security) », a déclaré Talos.
<br/>

**Un nouvel outil d'administration à distance **

<br/>
Cette semaine, Cisco a fait savoir que les auteurs des attaques DNSpionage avaient créé un nouvel outil d'administration à distance qui prenait en charge la communication HTTP et DNS avec le serveur de commande et de contrôle des attaquants (C2). « Dans notre message précédent à propos de DNSpionage, nous avons montré que les auteurs du malware utilisaient des macros malveillantes intégrées dans un document Microsoft Word. Dans le nouvel échantillon localisé au Liban et identifié fin février, l'attaquant a utilisé un document Excel avec une macro similaire ». Talos explique que « le malware supporte la communication HTTP et DNS avec le serveur C2 ». Les chercheurs ajoutent que « la communication HTTP est cachée dans les commentaires du code HTML », précisant que « cette fois cependant, le serveur C2 reproduit la plate-forme GitHub au lieu de Wikipedia ». De plus « si la communication DNS adopte la même méthode que celle décrite dans notre article précédent, le développeur a ajouté de nouvelles fonctionnalités dans cette version et, supprimant cette fois le mode debug », précisent encore les chercheurs.
<br/>

<br/>
Talos trouve que le domaine utilisé pour la campagne C2 est « étrange ». « La précédente version de DNSpionage essayait d'utiliser des domaines ayant une apparence légitime afin d'éviter la détection. Cependant, cette nouvelle version utilise le domaine 'coldfart[.]com', plus facile à repérer que d'autres campagnes APT qui tentent généralement de se fondre dans un trafic plus adapté aux environnements d'entreprise. Le domaine était également hébergé aux États-Unis, ce qui est inhabituel pour toute attaque à visée d'espionnage ». Les chercheurs de Talos ont aussi découvert que DNSpionage s'était doté d'une phase de reconnaissance, qui sert à vérifier que la charge utile est lâchée sur des cibles spécifiques plutôt que téléchargée sans distinction sur chaque machine. « Ce niveau d'attaque renvoie également des informations sur l'environnement du poste de travail, y compris des informations spécifiques sur la plate-forme, le nom de domaine et le nom de l'ordinateur local, plus des informations concernant le système d'exploitation », écrit encore Talos. Ces informations sont essentielles pour faciliter le ciblage des victimes par le malware et pour éviter les chercheurs ou les bacs à sable. Encore une fois, cela montre que les attaquant se sont dotés de nouvelles des capacités, et qu'ils prennent désormais les empreintes numériques de la victime. Cette nouvelle tactique indique un niveau de sophistication supplémentaire et vise probablement à rendre la campagne plus discrète.
<br/>

**Une cyberattaque DNS différente de Sea Turtle**

<br/>
Talos fait remarquer que plusieurs rapports sur les attaques DNSpionage ont été rendus publics. En janvier, le Département de la sécurité intérieure des États-Unis a émis une alerte pour prévenir les utilisateurs sur cette menace. « En plus de la multiplicité de ces rapports, nous avons également découvert de nouvelles preuves montrant que les acteurs à l'origine de la campagne DNSpionage continuent de modifier leurs tactiques, probablement pour améliorer l'efficacité de leurs opérations », a déclaré Talos. En avril, Cisco Talos a découvert un malware non documenté, développé en .NET. Sur les échantillons analysés, l'auteur a signé son malware de deux noms différents en texte clair : « DropperBackdoor » et « Karkoff ». « Le malware est léger par rapport à d'autres autres logiciels malveillants et il permet l'exécution de code à distance depuis le serveur C2. Il n'y a pas de zone d'ombre et le code peut être facilement désassemblé », a encore écrit Talos.
<br/>

<br/>
Selon Talos, il y a une différence entre l'attaque DNSpionage et l'autre attaque DNS « Sea Turtle », dont le groupe a rendu compte ce mois-ci. « Dans l'attaque Sea Turtle, les auteurs sont soutenus par un État. Ils attaquent les DNS pour cibler des entreprises et récolter des informations d'authentification afin d'accéder à des réseaux et des systèmes sensibles à l'insu des victimes. Cette méthode témoigne de compétences uniques dans la manipulation du DNS », a déclaré Talos. « En prenant le contrôle du DNS des victimes, les attaquants peuvent changer ou falsifier les données que les victimes reçoivent d'Internet, modifier illégalement les enregistrements de noms DNS pour diriger les utilisateurs vers des serveurs sous leur contrôle et tout cela à l'insu des utilisateurs qui visitent ces sites », a expliqué Talos. « Même si l'attaque Sea Turtle se limite à cibler des organisations impliquées dans la sécurité nationale de pays du Moyen-Orient et d'Afrique du Nord, et sans vouloir exagérer les conséquences de cette campagne spécifique, nous craignons que le succès de cette opération ne conduise les acteurs à attaquer plus largement le système DNS mondial », a déclaré le groupe Talos à propos de cette attaque.
<br/>

Source: <https://www.lemondeinformatique.fr/actualites/lire-vers-des-cyberattaques-dnspionage-plus-furtives-75107.html> 

