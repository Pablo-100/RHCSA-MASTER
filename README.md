# 🎓 RHCSA Master Guide
### Red Hat Certified System Administrator — EX200

> **Développé par / Developed by : TBINI MUSTAPHA AMIN**

---

## 🇫🇷 Français

### Description
Guide de préparation complet à la certification **RHCSA (EX200)** de Red Hat. Un fichier HTML autonome — aucune installation requise, fonctionne hors ligne.

### Statistiques
| Métrique | Valeur |
|----------|--------|
| 🖥️ Commandes | 125+ |
| 📚 Chapitres | 12 |
| 💡 Exemples avec outputs | 270+ |
| 🌍 Langues | Français / English |
| ⚡ Dépendances | Aucune |

### Fonctionnalités
- 🌙 **Mode sombre / clair** — switch instantané, mémorisé
- 🇫🇷🇬🇧 **Bilingue FR/EN** — basculez en un clic
- 🔍 **Recherche en temps réel** — filtrez parmi 125+ commandes
- 💻 **Terminal simulé** — chaque exemple avec son output réel
- 📍 **TOC latéral** — navigation rapide entre chapitres
- ↑ **Retour en haut** — bouton flottant

### Chapitres couverts

| # | Chapitre | Commandes clés |
|---|----------|----------------|
| 01 | 📁 Fichiers & Navigation | `ls`, `find`, `grep`, `tar`, `vim`, `awk`, `sed` |
| 02 | 👤 Utilisateurs & Groupes | `useradd`, `usermod`, `passwd`, `chage`, `sudo` |
| 03 | 🔒 Permissions & ACL | `chmod`, `chown`, `umask`, `setfacl`, `chattr` |
| 04 | 💾 Stockage & LVM | `fdisk`, `mkfs`, `mount`, `lvcreate`, `swap`, `dd` |
| 05 | 🌐 Réseau | `ip`, `nmcli`, `ss`, `ssh-keygen`, `tcpdump` |
| 06 | ⚙️ Services systemd | `systemctl`, `journalctl`, `cron`, `at`, `dnf` |
| 07 | 🔄 Processus | `ps`, `top`, `kill`, `nice`, `lsof`, `watch` |
| 08 | 🛡️ SELinux | `getenforce`, `semanage`, `restorecon`, `audit2allow` |
| 09 | 🔥 Pare-feu | `firewall-cmd`, zones, rich rules, nftables |
| 10 | 📦 Containers Podman | `podman run`, `buildah`, `skopeo`, pods |
| 11 | 🚀 Boot & Recovery | GRUB2, targets, reset root, dracut, kdump |
| 12 | 📝 Scripting Bash | variables, boucles, fonctions, getopts, trap |

### Utilisation
```bash
# Ouvrir dans le navigateur
firefox rhcsa-tbini.html
# ou simplement double-cliquer sur le fichier
```

### Sujets critiques pour l'examen
- ✅ Reset du mot de passe root (`rd.break` + `touch /.autorelabel`)
- ✅ LVM — créer, étendre, redimensionner
- ✅ SELinux — contextes, booleans, semanage
- ✅ firewall-cmd — `--permanent` + `--reload`
- ✅ systemctl — `enable --now`, unit files
- ✅ Swap — partition et fichier swap
- ✅ Podman + systemd (`loginctl enable-linger`)
- ✅ Cron et permissions ACL

---

## 🇬🇧 English

### Description
Complete preparation guide for the **RHCSA (EX200)** Red Hat certification. A standalone HTML file — no installation required, works fully offline.

### Statistics
| Metric | Value |
|--------|-------|
| 🖥️ Commands | 125+ |
| 📚 Chapters | 12 |
| 💡 Examples with outputs | 270+ |
| 🌍 Languages | French / English |
| ⚡ Dependencies | None |

### Features
- 🌙 **Dark / Light mode** — instant switch, saved automatically
- 🇫🇷🇬🇧 **Bilingual FR/EN** — toggle with one click
- 🔍 **Real-time search** — filter across 125+ commands
- 💻 **Simulated terminal** — each example with real output
- 📍 **Side TOC** — quick navigation between chapters
- ↑ **Back to top** — floating button

### Chapters Covered

| # | Chapter | Key Commands |
|---|---------|--------------|
| 01 | 📁 Files & Navigation | `ls`, `find`, `grep`, `tar`, `vim`, `awk`, `sed` |
| 02 | 👤 Users & Groups | `useradd`, `usermod`, `passwd`, `chage`, `sudo` |
| 03 | 🔒 Permissions & ACL | `chmod`, `chown`, `umask`, `setfacl`, `chattr` |
| 04 | 💾 Storage & LVM | `fdisk`, `mkfs`, `mount`, `lvcreate`, `swap`, `dd` |
| 05 | 🌐 Networking | `ip`, `nmcli`, `ss`, `ssh-keygen`, `tcpdump` |
| 06 | ⚙️ systemd Services | `systemctl`, `journalctl`, `cron`, `at`, `dnf` |
| 07 | 🔄 Processes | `ps`, `top`, `kill`, `nice`, `lsof`, `watch` |
| 08 | 🛡️ SELinux | `getenforce`, `semanage`, `restorecon`, `audit2allow` |
| 09 | 🔥 Firewall | `firewall-cmd`, zones, rich rules, nftables |
| 10 | 📦 Podman Containers | `podman run`, `buildah`, `skopeo`, pods |
| 11 | 🚀 Boot & Recovery | GRUB2, targets, root reset, dracut, kdump |
| 12 | 📝 Bash Scripting | variables, loops, functions, getopts, trap |

### Usage
```bash
# Open in browser
rhcsa-master.vercel.app
# or simply double-click the file
```

### Critical Exam Topics
- ✅ Root password reset (`rd.break` + `touch /.autorelabel`)
- ✅ LVM — create, extend, resize
- ✅ SELinux — contexts, booleans, semanage
- ✅ firewall-cmd — `--permanent` + `--reload`
- ✅ systemctl — `enable --now`, unit files
- ✅ Swap — partition and swap file
- ✅ Podman + systemd (`loginctl enable-linger`)
- ✅ Cron and ACL permissions

---

## 📁 Fichiers / Files

```
rhcsa-tbini.html    ← Guide complet / Complete guide (standalone)
README.md           ← Ce fichier / This file
```

## 🔖 Licence / License

Usage libre pour la préparation à la certification.  
Free to use for certification preparation.

---

*RHCSA® is a registered trademark of Red Hat, Inc.*  
*Ce guide est un projet indépendant / This guide is an independent project.*

---

<div align="center">

**Made by TBINI MUSTAPHA AMIN · 2025**

`Linux` `RHCSA` `EX200` `Red Hat` `Certification`

</div>
