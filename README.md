<img width="150" height="150" align="left" style="float: left; margin: 0 10px 0 0;" alt="Assistant Personnel" src="https://cdn.discordapp.com/app-icons/520534231387078676/b046d7be3da8850247f3babf4657b1e1.png?size=256"> 

# Assistant Personnel - Bot Discord
[![NPM Version](https://img.shields.io/npm/v/npm.svg?style=flat)]()
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Discord Chat](https://img.shields.io/discord/308323056592486420.svg)](https://discord.gg/JfAV834G)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/cdnjs/cdnjs.svg?style=flat)]()
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)
[![Support via PayPal](https://cdn.rawgit.com/twolfson/paypal-github-button/1.0.0/dist/button.svg)](https://paypal.me/sofiyanifren?locale.x=fr_FR)

> Vous êtes libre d'ajouter une étoile ⭐ pour promouvoir le projet ! ^^

## Assistant Personnel - Guide d'installation

* Installation npm et packages nécessaires

<code>npm init
npm i --save discord.js twit</code>

* Créer un fichier config.json à la racine du projet et y ajouter les informations nécessaires. Pour l'obtention des clefs d'API, voir les url dans les crédits ci-dessous. TEXT_CHANNEL_NAME et VOCAL_CHANNEL_NAME sont à remplacer respectivement par le nom des chaînes sur lesquels vous souhaitez que le bot réponde. Il en est de même pour les clés d'accès Twitter. Le dernier message, lui, est paramétrable à souhait.

<code>{"BOT_TOKEN": "<DISCORD_BOT_TOKEN>",</code><br>
<code>"BOT_ID": "<DISCORD_BOT_TOKEN>",</code><br>
<code>"TEXT_CHANNEL": "<TEXT_CHANNEL_NAME>",</code><br>
<code>"VOCAL_CHANNEL": "<VOCAL_CHANNEL_NAME>",</code><br>
<code>"WEATHER_API_KEY": "<API_KEY_OPENWEATHERMAP>",</code><br>
<code>"TWITTER_API_KEY" : "<API_KEY_TWITTER>",</code><br>
<code>"TWITTER_API_KEY_SECRET" : "<API_KEY_SECRET_TWITTER>",</code><br>
<code>"TWITTER_ACCESS_TOKEN" : "<ACCESS_TOKEN_TWITTER>",</code><br>
<code>"TWITTER_ACCESS_TOKEN_SECRET" : "<ACCESS_TOKEN_SECRET_TWITTER>",</code><br>
<code>"BOT_MESSAGE_USE_THE_RIGHT_CHANNEL" : "Hello! Je ne réponds qu'aux commandes envoyées sur mon espace de discussion attitré!",</code><br>
<code>"BOT_MESSAGE_INVALID_COMMAND" : "Aïe! Je ne connais pas cette commande. Pour le détails des commandes, tepe *** !help ***"}</code>

## Assistant Personnel - Liste des fonctionnalités

### Gestion du serveur

* <code>!ping</code> Obtention d'un retour avec temps de latence, permet de tester le service
* <code>!invite <bot/user></code> Obtention d'un lien permettant d'inviter le bot sur son serveur (Option: bot) ou un lien d'invitation pour le serveur sur lequel le bot est actif

### Dev perso

* <code>!proverbe</code> Obtention d'un proverbe aléatoire parmi près de 2500 proverbes d'origine différentes
* <code>!advice</code> Obtention d'un conseil aléatoire (anglais)

### Utilitaires

* <code>!date <format></code> Obtention de la date du jour (Options : gregoire / hegire)
* <code>!meteo <nom_ville></code> Obtention de la météo (température extérieure) d'une ville donnée, en °C et °F
* <code>!convert <nombre> <origine></code> Conversion d'une unité (Options : gr / oz / lb / kg / st / inch / ft / yd / cm / km / mile / celsius / farenheit)

### Finances

* <code>!change <monnaie_origine> <monnaie_destination></code> Conversion (cours du jour) d'une monnaie donnée dans une monnaie d'arrivée (Options : sigles monétaires, tels USD, GBP, EUR,...

### Informatique

* <code>!domaine <mot></code> Obtention d'une liste de domaines suggérée en fonction d'un mot donné

### Recherche texte

* <code>!wiki <search/suggestions> <mot></code> Obtention du lien de recherche (Option: search) ou des suggestions Wikipedia (Option: suggestions) pour un mot donné. NB. Pour le moment, le service ne fonctionne qu'avec un seul mot recherché
* <code>!trad <mot> <origine> <destination></code> Traduction d'un mot d'une langue à une autre (Options : fr / en / ar / zh / de / hi / id / ga / it / ja / ko / pl / pt / ru / tr / vi / es)

### Maths

* <code>!nombre <nombre></code> Obtention d'un fait aléatoire à propos d'un nombre donné, en anglais (Si aucun nombre n'est donné, un fait est donné à propos d'un nombre aléatoire )
* <code>!convert <nombre> <origine> <destination></code> Conversion d'un nombre (Options : binary / octal / decimal / hexadecimal)


### Fun

* <code>!anime</code> Obtention d'une citation aléatoire d'anime, en anglais
* <code>!chat</code> Obtention d'une image de chat aléatoire

### Ambiance Coworking

* <code>!tweet <proverbe/advice></code> Tweet un proverbe (fr) ou un conseil (en) sur le compte Twitter associé au serveur

## Contributions

N'hésitez pas à contribuer en ouvrant une PR directement sur la branche DEV, elle sera examinée le plus rapidement possible !

Si vous souhaitez supporter le projet, c'est par ici : https://paypal.me/sofiyanifren?locale.x=fr_FR
  
## Crédits - API utilisées

* https://animechan.vercel.app/api
* http://api.aladhan.com/v1
* https://api.domainsdb.info/v1
* http://numbersapi.com/
* https://libretranslate.de/translate
* https://api.openweathermap.org
* https://fr.wikipedia.org/w/api.php
* https://thatcopy.pw/catapi/rest/
* https://api.adviceslip.com/advice
* https://www.frankfurter.app/
