---
title: How to create your own obsidian plugin
tags: [coding]
publish: true
image: 
description: 
---

## Getting things set up

In order to create an obsidian plugin, you need to have NodeJS installed, as well as a code editor.

In order to publish your plugin, you need to use Git, and have a GitHub Account

### With Git and Github

If you have a GitHub Account, just click the "Use this Template" Button and follow these Instructions:

![[Pasted image 20220605165000.png | 750]]

![[Pasted image 20220605165008.png | 750]]

Once you have your own Repository set up, just copy the following URL:

![[Pasted image 20220605165034.png | 750]]

Afterwards, you can clone the Repository locally using the following shell command. Just make sure you are in the correct Directory you want your Plugin to live in.

```bash
git clone <paste the url here>
```

Now you can finally open the Folder with your Code Editor.

### Without Git and Github

If you don’t plan on publishing your Plugin or don’t have a GitHub Account, you can also just download and unpack the Sample Plugin as a ZIP Archive:

![[Pasted image 20220605165252.png | 750]]

Now you can finally open the Folder with your Code Editor, too.

### Compiling and running the Plugin

There are a lot of files already, but only three of them really matter right now.

- `main.ts` File, which contains the plugin's code.
- `styles.css` File, which contains a corresponding Style Sheet
- `manifest.json` File, which contains important information, like the version and name of the plugin.

Obsidian cannot execute TypeScript files directly, you'll have to compile them into JS first.

