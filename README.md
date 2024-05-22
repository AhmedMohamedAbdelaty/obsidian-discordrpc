## Obsidian Discord Rich Presence Plugin

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/lukeleppan/obsidian-discordrpc/Build%20Release?logo=github&style=for-the-badge) ![GitHub release (latest by date)](https://img.shields.io/github/v/release/lukeleppan/obsidian-discordrpc?style=for-the-badge) ![GitHub All Releases](https://img.shields.io/github/downloads/lukeleppan/obsidian-discordrpc/total?style=for-the-badge)

Update your Discord Status to show your friends what you are working on in Obsidian. With Discord Rich Presence.

![Rich Presence Preview](https://raw.githubusercontent.com/lukeleppan/obsidian-discordrpc/master/assets/presence.gif)

### Usage

After enabling the plugin in settings, your Discord status should show that you are using Obsidian.md.

If Discord isn't open, then you will see "Reconnect to Discord" at the botton of the screen. You can click that to attempt to reconnect. It will only connect if Discord is open.

You can also reconnect to discord rich presence via the `Reconnect to Discord` command in the command palette. If there is an issue.

### Features

- Updates your Discord Status with Obsidian info, **Vault Name** and/or **Current File Name**.
- Allows you to customise what info is shown.

#### New Feature: Note Sharing Link

![Note Sharing Link Screenshot](https://github.com/AhmedMohamedAbdelaty/obsidian-discordrpc/assets/73834838/e1136c07-89c5-459c-93c3-31f702fc17e7)

- Adds a button with the text "Note Link" to the Discord Rich Presence if the current file contains a `share_link` tag and the `public_note` tag is set to "true".
![Screenshot](https://github.com/AhmedMohamedAbdelaty/obsidian-discordrpc/assets/73834838/46512190-fc4d-464a-8cd3-ba0b3906feb8)
- This feature is useful for sharing notes publicly using the [Share Note](https://obsidian.md/plugins?id=share-note) plugin. If a note is shared, the link will be displayed in the Discord status, making it easier for others to access the shared note directly.
    - The `public_note` tag is used to determine whether the note is shared or not (you should set it to "true" **manually** if you want to share the note).

### Settings

#### Vault Name Settings

- Toggle whether or not to show **Vault Name**
- Set a custom **Vault Name** to show publicly

#### File Name Settings

- Toggle whether or not to show **Current File Name**
- Toggle whether or not to show the current file **extension**

#### Time Settings

- Toggle Whether or not to use the total time you have been using Obsidian, instead of the time spent editing a single file.

#### Notice Settings

- Toggle whether or not to show **Connection Notices**

### Contributors

#### @leoccyao

- Added the disconnect feature
- Made the plugin much more user friendly

### Issues

If you have any issues or suggestions please create an **issue** or a **pull request**.

### Compatibility

This plugin currently requires Obsidian v0.9.10+

### Install

You can install the plugin via the Community Plugins tab within Obsidian.

#### Manually installing the plugin

- Copy over `main.js`, `manifest.json` to your vault `VaultFolder/.obsidian/plugins/your-plugin-id/`.
