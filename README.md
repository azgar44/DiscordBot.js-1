<img width="150" height="150" align="left" style="float: left; margin: 0 10px 0 0;" alt="Xiao" src="https://cdn.discordapp.com/icons/629960788840546304/a2514920e2623241e17644d8b4f38e3c.png?size=512">

# __*DiscordBot.js*__ - un exemple de bot avancé.
[![Statut de DiscordBot.js](https://top.gg/api/widget/status/629968935709835284.svg?righttextcolor=ffffff)](https://top.gg/bot/629968935709835284)
[![Total de serveurs connecté à DiscordBot.js](https://top.gg/api/widget/servers/629968935709835284.svg?rightcolor=7289da&righttextcolor=ffffff)](https://top.gg/bot/629968935709835284)
[![Total de vote de DiscordBot.js](https://top.gg/api/widget/upvotes/629968935709835284.svg?rightcolor=ff4500&righttextcolor=ffffff)](https://top.gg/bot/629968935709835284/vote)
[![Librairie de  DiscordBot.js](https://top.gg/api/widget/lib/629968935709835284.svg?rightcolor=2196f3&righttextcolor=ffffff)](https://discord.js.org/)
[![Propriétaire de DiscordBot.js](https://top.gg/api/widget/owner/629968935709835284.svg?rightcolor=d6af23&righttextcolor=ffffff)](https://top.gg/user/609174280734900226)
[![Serveur Support de DiscordBot.js](https://img.shields.io/discord/629960788840546304.svg?colorB=7289da&label=DiscordBot.js&logo=Discord&logoColor=fff&style=flat)](https://top.gg/servers/629960788840546304)
[![Site Web de DiscordBot.js](https://img.shields.io/website?down_message=offline&up_message=online&url=https%3A%2F%2Fdiscordbotjs.github.io)](https://discordbotjs.github.io)

### Qu'est ce que c'est DiscordBot.js ?

> *DiscordBot.js est un bot discord qui te permets faire pleins de chose avec, comme gérer la modération de ton serveur, te donner pleins d'informations sur ton serveur, utiliser des fonctionnalités Discord avec de simple commande...*

## Liste des commandes:

> _**Si une commande n'as pas d'exemple cela veut dire qu'il ne faut pas spécifier d'argument !**_

### Catégorie Information:
- +server-info : Affiche les informations d'un serveur.
  - Exemple: +server-info <ID d'un serveur connecté à DiscordBot.js ou rien>
- +user-info : Affiche des informations non personnel d'un membre.
  - Exemple: +user-info <Mention d'un membre, ID d'un membre ou rien>
- +bot-info : Affiche les informations de DiscordBot.js
- +channel-info : Affiche les informations d'un salon.
  - Exemple: +channel-info <Mention d'un salon, ID d'un salon ou rien>
- +role-info : Affiche les informations d'un rôle.
  - Exemple: +role-info <Mention d'un rôle ou ID d'un rôle>
- +config-info : Affiche les valeurs de la base de donnée.
- +server-list : Affiche quels serveurs utilises Discord Bot.js
- +ping : Affiche le pîng.
- +embed help : Envoie un message d'aide pour crée un embed.
- +poll help : Envoie un message d'aide pour crée un sondage.
- +xp help : Envoie un message d'aide pour le système de niveau.
- +music-help : Musique indisponible !
- +money help : Envoie un message d'aide pour le système d'argent.
- +say-markdown help : Envoie un message d'aide pour les markdown Discord.
- +setup-server help : Envoie un message d'aide pour la configuration de serveur.

### Catégorie Modération:
- +add-role : Ajoute un rôle à un membre.
  - Exemple: +add-role <Mention d'un rôle ou ID d'un rôle> <Mention d'un membre, ID d'un membre ou rien>
- +remove-role : Enleve un rôle à un membre.
  - Exemple: +remove-role <Mention d'un rôle ou ID d'un rôle> <Mention d'un membre, ID d'un membre ou rien>
- +report : Signale un membre d'un serveur.
  - Exemple: +report <Mention d'un membre ou ID d'un membre> <Raison>
- +mute : Mettre en sourdine un membre d'un serveur.
  - Exemple: +mute <Mention d'un membre ou ID d'un membre> <Raison>
- +unmute : Rendre la voix d'un membre d'un serveur.
  - Exemple: +unmute <Mention d'un membre ou ID d'un membre> <Raison>
- +kick : Kick un membre d'un serveur.
  - Exemple: +kick <Mention d'un membre ou ID d'un membre> <Raison>
- +ban : Ban un membre d'un serveur.
  - Exemple: +ban <Mention d'un membre ou ID d'un membre> <Raison>
- +unban : Déban un membre d'un serveur.
  - Exemple: +unban <ID d'un membre>

### Catégorie Configuration:
- +server-invite : Crée une invitation publique.
- +new-prefix : Change le prefix de DiscordBot.js
  - Exemple: +new-prefix Nouveau prefix
- +news : Crée un salon pour recevoir les actualités de DiscordBot.js
- +logs : Active/désactive les logs de DiscordBot.js
  - Exemple: +logs true ou false
- +logs-channel : Active/désactive les logs de DiscordBot.js
  - Exemple: +logs-channel <Mention d'un salon ou ID d'un salon>

### Catégorie Divers/Fun:
- **+bot-vote : Envoie un message pour voter pour DiscordBot.js**
- **+canary : Envoie un message pour inviter DiscordBot.js Canary**
- +chifoumi : Jouer à chifoumi avec DiscordBot.js
- +clear : Efface les messages.
  - Exemple: +clear <Nombre de messages [Max: 99]>
- +say : Parler en étant DiscordBot.js
  - Exemple: +say Message

### Catégorie Développeur:
- +join : Simule l'arrivé d'un membre sur un serveur.
- +quit : Simule le départ d'un membre sur un serveur.
- +news-description : Définit le message de l'actualité.
  - Exemple: +news-description Message
- +news-thumbnail : Définit l'image de l'actualité.
  - Exemple: +news-thumbnail <URL de l'image>
- +news-picture : Définit la vignette de l'actualité.
  - Exemple: +news-picture URL de la vignette
- +news-reset : Réinitialise les valeurs de l'actualité.
- +news-send-dbjs : Envoie l'actualité pour DiscordBot.js
- +news-send-dbjscanary : Envoie l'actualité pour DiscordBot.js Canary
- +xp setxp : Définit le nombre d'xp d'un membre.
  - Exemple: +xp setxp <Mention d'un membre ou ID d'un membre ou rien> <XP définit>
- +xp setlevel : Définit le nombre de niveaux d'un membre.
  - Exemple: +xp setlevel <Mention d'un membre, ID d'un membre ou rien> <Niveau définit>
- +xp delete : Supprime un membre de la base de donnée.
  - Exemple: +xp delete <Mention d'un membre ou ID d'un membre>
- +money add : Ajoute de l'argent sur le solde.
  - Exemple: +money add <valeur à ajoutés> <Mention d'un membre, ID d'un membre ou rien>
- +money remove : Supprime de l'argent sur le solde.
  - Exemple: +money remove <valeur à enlevés> <Mention d'un membre, ID d'un membre ou rien>

## Liste des Dependencies:

- [discord.js](https://www.npmjs.com/package/discord.js)<br>
- [parse-ms](https://www.npmjs.com/package/parse-ms)<br>
- [discord-leveling](https://www.npmjs.com/package/discord-leveling)<br>
- [canvas](https://www.npmjs.com/package/canvas)<br>
- [quick.db](https://www.npmjs.com/package/quick.db)<br>
- [long](https://www.npmjs.com/package/long)<br>
- [dblapi.js](https://www.npmjs.com/package/dblapi.js)<br>
- [hastebin.js](https://www.npmjs.com/package/hastebin.js)<br>
- [dotenv](https://www.npmjs.com/package/dotenv)<br>

<p align="center">© 2020 <a href="https://github.com/DiscordBotJs/DiscordBot.js">DiscordBot.js</a> - &lt;/&gt; with ❤ by <a href="https://github.com/AlexAnimateMP4">@AlexAnimateMP4</a></p>
