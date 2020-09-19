# oh-my-posh

## About

A theme engine for Powershell in Windows Terminal inspired by the work done by Chris Benti on [PS-Config][chrisbenti-psconfig] and [Oh-My-ZSH][oh-my-zsh] on OSX and Linux (hence the name).

## Prerequisites

You should use Windows Terminal to have a brilliant terminal experience on Windows.

Windows Terminal can be acquired from the Microsoft Store, the [Windows Terminal repo](https://github.com/microsoft/terminal), or via [Chocolatey][chocolatey]:

The fonts I use are Powerline fonts, there is a great [repository][nerdfonts] containing them.

## Installation

You need to use the [PowerShell Gallery][powershell-gallery] to install oh-my-posh.

Install posh-git and oh-my-posh:

```powershell
Install-Module oh-my-posh -Scope CurrentUser
```

Enable the prompt:

```powershell
# Alternatively set the desired theme:
Set-Theme Powerlevel10k-Classic
```

Edit your PowerShell profile. Append the following lines to your PowerShell profile:

```powershell
Import-Module oh-my-posh
Set-Theme Powerlevel10k-Classic
```

Replace the files in $profile/Modules/oh-my-posh with files from this repo.

## Themes

### Agnoster

![Agnoster Theme][img-theme-agnoster]

### Paradox

![Paradox Theme][img-theme-paradox]

### Sorin

![Sorin Theme][img-theme-sorin]

### Darkblood

![Darkblood Theme][img-theme-darkblood]

### Avit

![Avit Theme][img-theme-avit]

### Honukai

![Honukai Theme][img-theme-honukai]

### Fish

![Fish Theme][img-theme-fish]

### Robbyrussell

![Robbyrussell Theme][img-theme-robbyrussell]

### Pararussel

![Pararussel Theme][img-theme-pararussell]

### Material

![Material Theme][img-theme-material]
![Material Theme][img-theme-material2]

### Star

![Star Theme][img-theme-star]

### Zash

![Star Theme][img-theme-zash]

### Lambda

![Lambda Theme](./img/lambda.png)

### Emodipt

![Emodipt Theme][img-theme-emodipt]


## Based on work by

* [Chris Benti][chrisbenti-psconfig]
* [Keith Dahlby][keithdahlby-poshgit]
* [Jan De Dobbeleer][JanDeDobbeleer-oh-my-posh]
