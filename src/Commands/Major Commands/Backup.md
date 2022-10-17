---
label: Backup
icon: database
align: left
authors:
  - name: mrcrypticx
    link: https://twitter.com/mrcrypticxdev
    avatar: https://cdn.discordapp.com/avatars/503215722407657478/bae8263de249352f344bf5421734ab45.webp?size=1024
---

# Backup Commands

!!! :zap: Let's get started! :zap:
It is recommended to use our slash commands for better experience. Message commands doesn't have every property we support on slash commands. You can use the `;` prefix or `/` to the various commands.
!!!

## [!badge variant="primary" text="backup create"]

### Syntax

Syntax (example)  | Type
---    | ---
**;backup create ?n** `Croc's World` **?c** `crocodile` | Message Command
/backup create name:`Croc's World` custom-id:`crocodile` | Slash Command

![](https://im-an.explorer.workers.dev/mXnBxlc.png)

![](https://im-an.explorer.workers.dev/NSSW8P9.png)

### Properties
*Use `?` as a prefix to all message commands params below.*
\* means *optional*
<!-- - c - **customId** - A phrase to easily remember your backup.
- n - **Backup Name** - An optional name for your backup. -->

Parameter `:tools:`  | Info | Type
---    | --- | ---
[!badge variant="success" text="?c"]* |  A phrase to easily remember your backup. | Message Command
[!badge variant="success" text="?n"]*  | A name for your backup. | Message Command
[!badge variant="primary" text="name"]*  | A name for your backup. | Slash Command
[!badge variant="primary" text="custom-id"]* | A phrase to easily remember your backup. | Slash Command


## Permissions
- `Administrator` - Required to create a backup. This is by default.  ![](https://im-an.explorer.workers.dev/FQl06rX.png)


To disable the privilege of admins creating backups, you can run `;config edit owneronly true`. This will only allow the owner of the guild to interact with the bot's major features. ![](https://im-an.explorer.workers.dev/Nq5YO5n.png)

## [!badge variant="success" text="backup load"]
### Syntax

Syntax (example)  | Type
---    | ---
**;backup load ?c** `crocodile` | Message Command
/backup load backup-id:`h4Vtr` exclude:`roles`| Slash Command
/backup load backup-id:`blank` | Slash Command

![](https://im-an.explorer.workers.dev/AMGvWwi.png)

![](https://im-an.explorer.workers.dev/oYvEqAT.png)


### Properties
*Use `?` as a prefix to all message commands params below.*
<!-- [!badge variant="success" text="?c"] | That phrase that you set when you created the backup. | Message Command -->
Parameter   | Info | Type
---    | --- | ---
[!badge variant="primary" text="exclude"]  | Specify inputs you dont want to be deleted from the server. | Slash Command
[!badge variant="primary" text="backup-id"] | That unique Id you got when you created your backup. *You can also pass in your* [!badge variant="primary" text="CustomId"] *here*. | Slash Command


=== Property Option Info
- While using the load command you may have stumbled on an `exclude` prop which is used to specify certain existing inputs you don't want to delete from the server when loading the given backup. The options are as follows: [!badge variant="dark" text="roles"], [!badge variant="dark" text="bans"], [!badge variant="dark" text="emojis"], [!badge variant="dark" text="channels"], [!badge variant="dark" text="events"] & [!badge variant="dark" text="guild"].

- Using the [!badge variant="dark" text="blank"] option will display a "*delete everything*" state and you selelct the options you want to delete from the server.
===


