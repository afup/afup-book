Cas particulier du e-commerce
=============================

Le terme « CMS » signifie « Content Management System » (système de gestion de contenu), et l'idée répandue lorsque ce terme est employé est qu'il s'agit d'un système de gestion de texte.
Or, la définition même d'un outil e-commerce est de gérer des produits et les ventes associées, donc des contenus.

La mise en place d'une solution e-commerce complète est complexe de part le volume fonctionnel minimum. Outre les fonctionnalités basiques (affichage d'un catalogue, gestion des clients), certaines fonctionnalités sont très sensibles, et demandent du temps et de l'énergie pour être mise en place de manière propre (panier, tunnel de paiement, intégration de système de paiement en ligne).

Fort heureusement, dans l'écosystème PHP, il existe nombres d'outils libres permettant de mettre en place des solutions e-commerce complètes :

Magento
-------

<table>
	<tr>
		<th>Site web</th>
		<td>http://www.magentocommerce.com/fr/</td>
	</tr>
	<tr>
		<th>Version courante</th>
		<td>1.6</td>
	</tr>
	<tr>
		<th>Licence</th>
		<td>Open Software License (OSL) v3.0 (voir également http://www.magentocommerce.com/license/)</td>
	</tr>
</table>


Développé initialement par la société Varien (qui sera renommé en Magento, Inc par la suite), Magento est une solution e-commerce complète dont le panel fonctionnel se veut le plus large possible, pour couvrir nativement la plupart des besoins des utilisateurs de ce genre d'outils :

  * Catalogue de produits
    * Produits physiques, groupés, virtuels, …
  * Gestion des clients
    * Compte client
    * Commentaires sur les produits
  * Commande
  * Paiement en ligne
  * Promotions / Outils de marketing
  * Multi-site / Multi-langue
  * CMS

Malgré cette couverture fonctionnelle très importante, Magento a tout de même pensé son architecture pour permettre une extensibilité maximale.

Basé sur le Zend Framework, Magento dispose de son propre framework donnant nombres de portes d'entrée au développeurs.

La principale d'entre elle est un système de configuration permettant de surcharger presque l'intégralité du système, de l'ORM au interfaces en passant par les contrôleurs et les « widgets » de présentation. Ainsi, il est possible d'adapter le fonctionnement de Magento aux moindres besoins client.

Magento propose également l'installation de modules via un installeur intégré, et un catalogue d'extensions permettant de trouver une solution pour presque tout les besoins : 

  * Interaction avec les ERP courants
  * Interaction avec les API des logisticiens
  * Intégration avec les API bancaires de tout pays
  * ...

Toutefois, les implémentations mises en place pour permettre cette extensibilité ont un coup en terme de performance, et Magento est gourmand en ressource pour fonctionner de manière optimale, et cette contrainte doit être prise en compte lors du choix de l'hébergement, puisque l'architecture recommandée consiste en 2 serveurs applicatifs et un serveur de base de données.

Autre inconvénient génant : la barrière d'entrée. Autant pour les utilisateurs que pour les développeurs, il est compliqué d'entrer dans la logique de Magento sans une formation professionnelle.

Du côté de la communauté de développeurs, elle est importante et plutôt réactive, mais la documentation est très disparate et il est difficile de trouver une documentation exhaustive.

PrestaShop
----------

paragraphe sur PrestaShop

OSCommerce
----------

paragraphe sur OSCommerce