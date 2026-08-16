<p align="center">
  <a href="README.md">English</a> | <a href="README_DE.md">Deutsch</a> | <a href="README_ZH.md">中文</a> | <a href="README_FR.md">Français</a> | <a href="README_IT.md">Italiano</a>
  &nbsp;&nbsp;
  <a href="SERVICES.md">
    <img src="https://img.shields.io/badge/Collaboration-7F52FF?style=flat-square" alt="Collaboration" valign="middle" />
  </a>
</p>

---

## Site web

<p align="center">
  <a href="https://arn-c0de.github.io/website/">
    <img src="https://img.shields.io/badge/arn--c0de.github.io-000000?style=for-the-badge&logo=githubpages&logoColor=white" alt="Site web" />
  </a>
</p>

<p align="center">
  Projets, builds et contacts — tout au même endroit.
</p>

---

> **Note (août 2026) :** Je travaille actuellement beaucoup sur des projets privés. Le profil peut donc sembler inactif, mais je reste joignable.

Intérêts personnels : systèmes embarqués, déploiement backend, intégration serveur, applications Android et applications web.

**Langues :** allemand (langue maternelle) · anglais (courant)
**Focus :** Kotlin, Python, C (ESP32, SDR, Wi-Fi) · **Apprentissage :** Rust, C++ (Windows)

Si tu as besoin d'aide, souhaites collaborer ou contribuer à l'un de mes projets, tu peux utiliser les options de contact ci-dessous ou ouvrir une issue dans le dépôt concerné.

---

## Sur quoi je travaille en ce moment

**IA de RTS pour [Project Nova / Hashkrieg](https://github.com/VibecodingGermany/Project_Nova)** — comportement des NPC et gestion des objectifs (goal management) : ce qu'une IA adverse décide de poursuivre, et quand elle y renonce.

- **Gestion des objectifs** — des objectifs hiérarchisés et concurrents plutôt que des scripts figés. Ils sont réévalués pendant la partie et abandonnés dès qu'ils ne rapportent plus.
- **Comportement des NPC** — ordre de construction et économie, composition de l'armée, expansion vs. défense vs. attaque, comportement de siège et de déplacement.
- **Mesure** — les changements de comportement sont vérifiés avec des chiffres, pas au ressenti : un laboratoire de simulation headless dédié ([Nova.AiLab](https://github.com/arn-c0de/Nova.AiLab)) fait s'affronter les branches et rend compte du résultat. Un run vert du laboratoire est un diagnostic, pas une preuve — ce qui n'a pas été observé en partie réelle est noté comme non observé.

**FLUID — recherche sur l'UI fluide / générative** — une base de connaissances pour un OS d'interface piloté par agent : un shell où une IA compose l'interface à l'exécution au lieu de livrer des écrans figés — entièrement en local (llama.cpp / vLLM / Ollama), adossé à un modèle cloud (Claude, Gemini, GPT), ou hybride.

- **Périmètre** — 167 documents reliés entre eux et tracés jusqu'à leurs sources : protocoles (A2UI, MCP, AG-UI), architecture, génération d'UI fiable, état, sécurité, latence et coût — plus un plan de bureau fluide dans le navigateur, où une seule saisie compose l'app dont on a besoin.
- **État** — la recherche et les décisions avant la première ligne de code. Chaque affirmation est marquée vérifiée, partielle ou spéculative ; la majorité est partielle. Une conception, pas un système en production.

---

## Stack technique

<table>
<tr>
<td width="50%" valign="top">

### Langages & frameworks
Kotlin · Python · C · Flask · FastAPI

### Machine learning
PyTorch · ResNet18

</td>
<td width="50%" valign="top">

### Embarqué & matériel
ESP32 · Raspberry Pi · Arduino · ESP8266 · ATmega<br>
HackRF One · RTL-SDR · LoRa

</td>
</tr>
<tr>
<td colspan="2">

### Outils & plateformes
Windows · Linux · Docker · Git · GitHub · GitLab · VS Code · IntelliJ IDEA · Blender

</td>
</tr>
</table>

---

## Statistiques GitHub

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/arn-c0de/arn-c0de@output/profile-3d-contrib/profile-night-rainbow.svg" alt="Calendrier 3D" />
</p>

<p align="center">
  <a href="https://awesome-github-stats.azurewebsites.net/index.html??cardType=level-alternate&theme=github-dark&fontFamily=&preferLogin=false">
    <img alt="Statistiques GitHub de arn-c0de" src="https://awesome-github-stats.azurewebsites.net/user-stats/arn-c0de?cardType=level-alternate&theme=github-dark&fontFamily=&preferLogin=false" />
  </a>
</p>

---

## Projets sélectionnés

### IA & finance
- [![Issues](https://img.shields.io/github/issues/arn-c0de/ANPS-TradeMeUp?style=flat-square&color=blue)](https://github.com/arn-c0de/ANPS-TradeMeUp/issues) [**ANPS-TradeMeUp**](https://github.com/arn-c0de/ANPS-TradeMeUp) - Système de prédiction d'actualités financières alimenté par LLM pour des prévisions de marché à court et moyen terme, avec analyse en temps réel et tableau de bord Dash. **Licence :** propriétaire, source disponible (strict).

- [![Issues](https://img.shields.io/github/issues/arn-c0de/Crawllama?style=flat-square&color=blue)](https://github.com/arn-c0de/Crawllama/issues) [**CrawlLama**](https://github.com/arn-c0de/Crawllama) - Agent IA local qui répond aux questions via Ollama et intègre la recherche web et RAG.

- [![Issues](https://img.shields.io/github/issues/arn-c0de/A-AIO-process-optimization-and-training?style=flat-square&color=blue)](https://github.com/arn-c0de/A-AIO-process-optimization-and-training/issues) [**A-AIO-process-optimization-and-training**](https://github.com/arn-c0de/A-AIO-process-optimization-and-training) - Dépôt de test et de prototypage pour expérimenter des concepts AOI/IA et les transformer en composants propres et reproductibles. **Licence :** propriétaire. **Aucune autorisation n'est accordée pour utiliser, copier, modifier ou distribuer ce logiciel sans accord écrit préalable.**

- ![Private](https://img.shields.io/badge/access-private-lightgrey?style=flat-square) **JobFinder** - Espace de travail auto-hébergé pour collecter, dédupliquer et gérer des offres d'emploi, des missions freelance et des appels d'offres publics. **Actuellement privé** — versions de test et collaboration sur demande, voir [Contact sécurisé](SECURE-CONTACT.md).

### IoT & embarqué

- [![Issues](https://img.shields.io/github/issues/arn-c0de/ESP-ProMicro-HidKey?style=flat-square&color=blue)](https://github.com/arn-c0de/ESP-ProMicro-HidKey/issues) [**ESP-ProMicro-HidKey**](https://github.com/arn-c0de/ESP-ProMicro-HidKey) - Émulateur de clavier USB HID multi-mots de passe pour Arduino Pro Micro (ATmega32U4). Différentes séquences de boutons déclenchent des mots de passe prédéfinis, saisis automatiquement via USB.

- [![Issues](https://img.shields.io/github/issues/arn-c0de/ESP32-Multi-OS-Launcher?style=flat-square&color=blue)](https://github.com/arn-c0de/ESP32-Multi-OS-Launcher/issues) [**ESP32-Multi-OS-Launcher**](https://github.com/arn-c0de/ESP32-Multi-OS-Launcher) - Lanceur de firmware minimal permettant d'installer et de basculer entre plusieurs builds ESP32 depuis une carte SD. Conçu pour les projets où plusieurs applications sont trop volumineuses pour tenir simultanément dans la mémoire flash.

### Sécurité & cryptographie
- [![Issues](https://img.shields.io/github/issues/arn-c0de/GPG-Meister?style=flat-square&color=blue)](https://github.com/arn-c0de/GPG-Meister/issues) [**GPG-Meister**](https://github.com/arn-c0de/GPG-Meister) - Application desktop local-first autour de GnuPG pour gérer les clés PGP, chiffrer et signer des messages, et exporter des sauvegardes de clés chiffrées. Interface disponible en anglais et en allemand. **Licence :** MIT.

- ![Private](https://img.shields.io/badge/access-private-lightgrey?style=flat-square) **anon-WebMirror** - Mise en miroir de sites web axée sur la confidentialité via Tor, avec protection anti-fuite fail-closed. **Actuellement privé** — versions de test et collaboration sur demande, voir [Contact sécurisé](SECURE-CONTACT.md).

### Sécurité réseau
- [![Issues](https://img.shields.io/github/issues/arn-c0de/fritzdump?style=flat-square&color=blue)](https://github.com/arn-c0de/fritzdump/issues) [**FritzDump**](https://github.com/arn-c0de/fritzdump) - Outil de capture live pour FRITZ!Box qui diffuse les données pcap vers Wireshark, ntopng, un fichier ou stdout, avec prise en charge de la connexion PBKDF2 et une suppression optionnelle des charges utiles limitée aux métadonnées. **Licence:** MIT.

### Jeux
- [![Issues](https://img.shields.io/github/issues/arn-c0de/ZombieEscape-Preview?style=flat-square&color=blue)](https://github.com/arn-c0de/ZombieEscape-Preview/issues) [**ZombieEscape**](https://github.com/arn-c0de/ZombieEscape-Preview) - Jeu de survie zombie en monde ouvert pour Android qui transforme les rues et bâtiments réels en carte de survie. Il s'agit d'un dépôt de préversion proposant des informations de production, des versions alpha, bêta et de test jouables à évaluer, des aperçus du développement ainsi que des possibilités de contact pour contribuer — le dépôt principal est privé. Phase actuelle : implémentation de fonctionnalités, correction de bugs et polissage.

- [![Issues](https://img.shields.io/github/issues/arn-c0de/Nova.AiLab?style=flat-square&color=blue)](https://github.com/arn-c0de/Nova.AiLab/issues) [**Nova.AiLab**](https://github.com/arn-c0de/Nova.AiLab) - Mon propre laboratoire de simulation IA headless pour [Project Nova / Hashkrieg](https://github.com/VibecodingGermany/Project_Nova). Il exécute l'IA RTS du jeu sans client, mesure la branche actuellement extraite et transforme chaque run en rapports lisibles sur le développement, le siège et les déplacements — avec un journal de comportement tenu à la main : ce qui s'est amélioré, ce qui s'est dégradé, et ce qui est déjà réfuté. Un outil, délibérément gardé hors du dépôt du jeu afin que chaque branche puisse être mesurée sans y intégrer l'instrument de mesure. **Licence :** Propriétaire — les mainteneurs et contributeurs de Project Nova peuvent l'utiliser pour mesurer des branches, mais pas le redistribuer.

### Simulation de vol
- [![Issues](https://img.shields.io/github/issues/arn-c0de/InteractiveChecklists?style=flat-square&color=blue)](https://github.com/arn-c0de/InteractiveChecklists/issues) [**InteractiveChecklists**](https://github.com/arn-c0de/InteractiveChecklists) - Application compagnon et autonome pour DCS World

---

## Projets à partager

Des projets d'autres personnes que j'apprécie personnellement, que je souhaite faire connaître ou auxquels je contribue moi-même.

- [![Stars](https://img.shields.io/github/stars/VibecodingGermany/Project_Nova?style=flat-square&color=blue)](https://github.com/VibecodingGermany/Project_Nova) [**Project Nova**](https://github.com/VibecodingGermany/Project_Nova) *(titre de travail en cours de changement : « Hashkrieg »)* - Jeu de stratégie en temps réel dans la tradition de Command & Conquer, développé avec Unity 6 et C# sur un cœur de simulation déterministe et indépendant d'Unity (lockstep). Développement entièrement ouvert — contributeurs et testeurs bienvenus.

---

## Réseaux sociaux

<p align="center">
  <a href="https://x.com/arn_c0de">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
  <a href="https://www.youtube.com/@git-arn-c0de">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
</p>

---

## Contact

> [!IMPORTANT]
> **SimpleX Chat**
> Me joindre ici :
> https://smp19.simplex.im/a#12EFYcsND4k7C7Gz1wUT7mKrt5-u84PqnHTBUZXw0eg
>
> **Matrix :** actuellement indisponible

<table>
<tr>
<td width="50%" valign="top">

### Problèmes de sécurité & vulnérabilités

**arn-c0de@protonmail.com**

Pour les sujets liés à la sécurité, les rapports de vulnérabilité ou les signalements sensibles.

Pour les sujets critiques comme les vulnérabilités, la divulgation responsable ou l'alerte confidentielle, tu peux utiliser des canaux sécurisés comme l'e-mail PGP ou un chat privé. Voir [Contact sécurisé](SECURE-CONTACT.md).

</td>
<td width="50%" valign="top">

### Demandes générales

**GitHub Issues**

Pour les bugs, demandes de fonctionnalités et discussions générales, utilise l'issue tracker du dépôt concerné.

</td>
</tr>
</table>

---

## Licence

Copyright (c) 2026 arn-c0de. Tous droits réservés.


---

<p align="center">
  <em>Tous les projets liés à la sécurité sont strictement destinés à l'éducation et à la recherche.</em>
</p>
