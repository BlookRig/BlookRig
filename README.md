<h1 align="center">BlookRig</h1>
<h3 align="center">Take Blooket Raids to the Next Level.</h3>

---

[![LICENSE](https://img.shields.io/github/license/BlookRig/BlookRig.svg)](https://github.com/BlookRig/BlookRig/blob/main/LICENSE)
[![STARRED](https://img.shields.io/github/stars/BlookRig/BlookRig.svg)](https://github.com/BlookRig/BlookRig/stargazers)
[![FORKED](https://img.shields.io/github/forks/BlookRig/BlookRig.svg)](https://github.com/BlookRig/BlookRig/network)

---

## Introduction:

BlookRig is a program that actively searches for active Blooket game codes and automatically raids them with open-sourced cheating scripts. It's designed to emulate traditional cryptocurrency mining software in terms of visual and technical designs.

## Installation:

### Cloud Providers

[![Remix on Glitch](https://binbashbanana.github.io/deploy-buttons/buttons/remade/glitch.svg)](https://glitch.com/edit/#!/import/github/BlookRig/BlookRig)
[![Run on Replit](https://binbashbanana.github.io/deploy-buttons/buttons/remade/replit.svg)](https://replit.com/github/MyBooty165/BlookRig/BlookRig)
[![Deploy to Render](https://binbashbanana.github.io/deploy-buttons/buttons/remade/render.svg)](https://render.com/deploy?repo=https://github.com/BlookRig/BlookRig)

### Local Hosting

> [!IMPORTANT]
> **Please Remember:** Make sure you have <a href="https://git-scm.com">Git</a> and <a href="https://nodejs.org">Node.JS</a> installed on your computer before downloading.

Open Git Bash, or any terminal on your OS and run this:

```
git clone https://github.com/BlookRig/BlookRig.git
cd BlookRig
```

Install packages

```
npm install
```

Run Program (Make sure <a href="#config">configurations</a> have been set first)

```
node index.js
```

# Config

In BlookRig, there is a file called `config.json`. This file contains the configuration files needed to fully run the program. 

You only need to change this:

`autoupdate` - Whether you want the program to automatically update itself to the latest version when ran. Set it to `false` if you don't want that.

`bnode` - Provide a valid Blooket BSID Node here, or put `local` to automatically set it as your own BSID (For local BSID, you have to be logged into Blooket).

`threads` - How many resources the miner can use, set it to `1` for 1 thread, or `max` to use all threads.

`record` - Records your C/s (Codes per Second) to a public record (for analytics purposes). Set to `false` to not record.

`autoraid` - Whether you want the program to automatically raid all active codes or to save it locally, if not, put it as `false`.
