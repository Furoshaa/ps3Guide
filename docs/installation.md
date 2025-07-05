---
sidebar_position: 1
---

# Installation

Decouvrez comment brancher et **installer votre console en moins de 2 minutes**.

## Branchment

Commencez par **debaler votre console** ou **achetez en une** sur **[workshop.furosha.com](https://workshop.furosha.com)**.

Vous serez presenter avec votre **console PS3**, **une manette** ainsi que trois cables dont une cable **d'alimentation a deux broche (ou trois pour une fat)**, un cable **video (HDMI ou Composite)** ainsi qu'un cable **mini-USB vers USB** pour brancher la manette. 

![docusaurus](/img/docusaurus.png)

:::danger[Surchauffe]
Attention, pour eviter les surchauffe, veillez a ne pas mettre la console dans une endroit confine comme un meuble TV. La console doit avoir suffisement d'espace pour respirer convenablement et refroidir efficacement.
:::

:::tip[Foutu]
Vous etes foutu monseigneur
:::

### What you'll need

- [Node.js](https://nodejs.org/en/download/) version 18.0 or above:
  - When installing Node.js, you are recommended to check all checkboxes related to dependencies.

## Generate a new site

Generate a new Docusaurus site using the **classic template**.

The classic template will automatically be added to your project after you run the command:

```bash
npm init docusaurus@latest my-website classic
```

You can type this command into Command Prompt, Powershell, Terminal, or any other integrated terminal of your code editor.

The command also installs all necessary dependencies you need to run Docusaurus.

## Start your site

Run the development server:

```bash
cd my-website
npm run start
```

The `cd` command changes the directory you're working with. In order to work with your newly created Docusaurus site, you'll need to navigate the terminal there.

The `npm run start` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.

Open `docs/intro.md` (this page) and edit some lines: the site **reloads automatically** and displays your changes.
