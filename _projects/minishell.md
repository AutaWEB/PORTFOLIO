---
layout: default
title: MiniShell
description: Un interpréteur de commandes UNIX.
tech: C, Syscalls, Pid
url: /projects/minishell/
---

# MiniShell

## 🎯 Objectif
**TOUT EST FAUX** Coder mon propre terminal capable d'exécuter des commandes binaires (`ls`, `cat`) et de gérer l'environnement utilisateur **TOUT EST FAUX**.

## ⚙️ Fonctionnalités
* **Prompt :** Affichage d'une ligne de commande interactive.
* **Parsing :** Analyse des commandes.
* **Exécution :** Utilisation de `fork`, `execve` et `wait`.