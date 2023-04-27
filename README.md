# naoki-bot-perso
Voici le bot Naoki fait par betaaaaa avec beaucoup moins d'erreurs et toutes les commandes marchent
<h1 align="center">🔗 Naoki V2 🚀</h1>

**NOTE:** \
Ce bot n'a pas été fait par moi, j'ai simplement retiré la plus grande partie des bugs qui étaient présents et le rendait inutilisable.

---
## <a id="menu"></a>🔱 » Menu

- [🔰・Fonctionnalitées](#features)
- [🌌・Discord](https://discord.gg/nANSkCyehT)
- [🎉・Lancement](#setup)
- [⚙・Config](#config)

## <a id="features"></a>🛠 » Features

```
> Commandes Admin
> Commandes Modération
> Commandes Gestion
> Commandes Anti Raid
> Commandes Jeux
> Commandes Utilitaires
> Commandes Musiques
> Commandes Logs
> Commandes Owners
> Système de Tickets
> Système de Pfp
> Système de Soutien
```

## <a id="setup"></a> 📁 » Setting up 

1. Installez [Nodejs](https://nodejs.org/ko/blog/release/v16.19.0/)
2. Ouvrez le fichier [config.js](https://github.com/002-sans/Naoki-Bot-Perso/blob/main/config.js) avec le bloc-note ou autre
3. Ouvrez un terminal dans le répertoire des fichiers
4. Entrez la commande `npm i && node index`

# <a id="config"></a>⚙ » Config

Pour configurer le fichier [config.js](https://github.com/002-sans/Naoki-Bot-Perso/blob/main/config.js), vous pouvez suivre l'exemple ci-dessous:

```js
module.exports = {
    app: {
        px: '+',
        token: 'NzgxMjA0ODUyOTEwOTgxMTYz.GkAM43.t0y1bsPwdKBkfIoU_LWh04eOtNcekjPbCFwRz0',
        owners: '843204602686078976',
        betaa: '843204602686078976',
        color: '#FF0000',
        footer: 'sltcv ?',
        maxserver: '1',
        maxVol: '150',
        everyoneMention: false,
        hostedBy: true,
        discordPlayer: {
            ytdlOptions: {
                quality: 'highestaudio',
                highWaterMark: 1 << 25
            }
        }
    }
}
```
