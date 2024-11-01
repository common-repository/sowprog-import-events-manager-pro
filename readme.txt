=== Plugin Name ===
Contributors: A31V
Tags: events, import
Requires at least: 3.4
Tested up to: 4.9.1
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Import and schedule daily import of events into Events Manager from Sowprog.

== Description ==

Import and schedule daily import of events into <a href="http://wp-events-plugin.com">Events Manager</a> from <a href="http://sowprog.com/">Sowprog</a>.

Define your import preferences to categorize events, display prices and ticket stores, status of the event and daily import.

You'll need a Sowprog account to run the import. This account is free and open to anyone. 


== Installation ==

1. Make sure Events manager is installed.
1. Copy the plugin folder sowprog_import_eventsmanagerpro to /wp-content/plugins/ directory
1. Activate the plugin through the 'Plugins' menu in WordPress

You'll find a SOWPROG menu item under Tools menu.
Here you will be able to configure and launch the import the events aimed to you from Sowprog.

Ce plugin permet d’importer les événements publiés sur Sowprog vers Events manager (http://wp-events-plugin.com)

Pré-requis :
*Wordpress
*Events Manager

Contactez nous ou créez un compte Agenda sur Sowprog. Dès qu’il sera validé vous pourrez importer les événements. 

Pour installer le plugin Sowprog, dans le panneau d’administration worpdress, cliquez sur Extensions puis ajouter.
Cliquez sur Envoyer et sélectionnez le fichier sowprog_import_eventsmanagerpro.zip
Activez le plugin

Dans le menu Outils, cliquez sur SOWPROG (TEM)
Si vous souhaitez tout réimporter, cochez Vérifier tous les événements.
Saisissez votre identifiant et votre mot de passe Sowprog.
Choisissez vos préférences d’import et cliquez sur importer.

Attendez, le premier import peut-être long.
Si vous avez décoché la case Publier directement à l’import, vos événements sont en brouillon, sinon ils sont déjà en ligne !
Vos préférences sont sauvegardées.

Pour le prochain import, pensez à décocher la case Vérifier tous les événements.



== Changelog ==

= 1.0 =
Fixed rsvp default value
Better import of locations

= 0.9 =
Fixed php log notices
Fixed cron import

= 0.8 =
Better handling of scheduled auto import
Image is correctly updated

= 0.7 =
Version 1.2 of sowprog API used
Punchline used as excerpt

= 0.5 =
Imports can be scheduled daily
