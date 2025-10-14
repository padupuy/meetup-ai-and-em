---
theme: "@ekino/slidev-theme-ekino"
transition: view-transition
title: L'IA dans la vie d'un Engineering Manager
highlighter: shiki
layout: cover

drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions

# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

# L'IA dans la vie d'un Engineering Manager

## Usages concrets et apprentissages

<br />
<br />
<br />

<SpeakerCard name="Pierre-Alexandre Dupuy" title="Lead @ ekino">
  <p>📬 pierre-alexandre.dupuy@ekino.com</p>
</SpeakerCard>

---

# Contexte : l'IA omniprésente mais risquée

> _"Avant de plonger dans mes usages concrets de l'IA, il est crucial de rappeler les enjeux liés à sa popularisation rapide."_

<br />

<v-clicks>

- L'IA fait désormais partie du quotidien : ChatGPT, Claude, Gemini, Mistral...
- Les usages explosent, y compris dans le monde professionnel.
- [Danger du « Shadow AI »](https://siecledigital.fr/2025/06/20/shadow-ai-un-salarie-sur-trois-utilise-lia-sans-en-parler-a-sa-direction/) : utilisation d'outils via des comptes personnels.
- Risque majeur de fuites de données sensibles non maîtrisées.
- Bonnes pratiques : privilégier les comptes enterprise ou internes (confidentialité, RGPD, aucun réentraînement sur vos données).
- L'IA doit être testée sur des side projects, jamais sur des projets clients.

</v-clicks>

---

# Impact écologique : un coût invisible

> _"L'essor de l'IA a un impact environnemental considérable, souvent méconnu, qu'il est indispensable d'intégrer dans notre réflexion."_

<br />

<v-clicks>

- D'après le [Shift Project (octobre 2025)](https://theshiftproject.org/app/uploads/2025/09/Synthese-RF-PIA-1.pdf) : la croissance de l'IA menace les objectifs climatiques.
- Les data centers sont passés de 165 TWh (2014) à 420 TWh (2024), et pourraient atteindre 1 500 TWh/an d'ici 2030.
- L'IA représente déjà 15 % de la consommation énergétique mondiale des serveurs.
- Une large part repose encore sur des sources fossiles.
- Utiliser l'IA, c'est aussi penser sobriété numérique et mesurer son impact environnemental.

</v-clicks>

---

# Qui suis-je ?

<div class="grid grid-cols-2 gap-12 items-center">

<div>

## Pierre-Alexandre Dupuy

- 👨‍💻 **35 ans**, 15 ans dans le web
- 🚀 **Lead chez ekino** (30% EM, 70% Tech Lead)
- 👨‍👧‍👧 Papa de 2 filles
- 🚴 Vélotafeur convaincu
- ⏰ Partisan de la semaine à 4/5ème




</div>

<div class="flex justify-center flex-col gap-4">

<img src="/illustration-pierre-alexandre-dupuy.png" class="rounded-full w-80 h-80 object-cover shadow-xl" />

</div>
</div>

<br />

> _"Il ne faut pas se définir uniquement par son travail"_
>
> — Antoine Brette

---

# Engineering Manager : Un rôle multiple

<div class="flex flex-col items-center justify-center h-full">

<img src="/Engineering_manager.png" class="w-[450px] h-auto" alt="Engineering Manager responsibilities diagram" />

<div class="mt-8 text-center text-gray-600 text-lg">

_Un rôle aux multiples facettes qui nécessite de jongler entre plusieurs responsabilités_

</div>

</div>

---

# Le défi permanent : rester technique

<div class="grid grid-cols-2 gap-8">

<div>

### Comment rester "hands-on" ? 🤔

<br />

Selon les entreprises, le rôle varie :

- **Hands-off** : Management pur
- **Hands-on** : Management + technique

<br />

### Chez ekino : rôle hybride "Lead"

- 30% Engineering Management
- 70% Tech Lead
  - dont 80% de revue de code 😁

</div>

<div class="flex items-center justify-center">

<div class="bg-yellow-50 rounded-xl p-8 shadow-lg border-2 border-yellow-200">

### 💡 La solution ?

<br />

**L'IA comme assistant** pour :

- ⏱️ Gagner du temps sur les tâches managériales
- 🔧 Rester technique et productif
- 🎯 Se concentrer sur l'essentiel

<br />

_→ L'IA permet de maintenir l'équilibre entre management et technique_

</div>

</div>

</div>

---

# Engineering Manager : tech lead

<div class="flex flex-col items-center justify-center h-full">

<img src="/Engineering_manager-coding.png" class="w-[450px] h-auto" alt="Engineering Manager responsibilities diagram" />

<div class="mt-8 text-center text-gray-600 text-lg">

Comment rester à jour sur les nouveautés technologiques ?

</div>

</div>

---

# Côté tech lead - Découverte d'Astro 🚀

<div class="grid grid-cols-2 gap-8">

<div>

### Le projet : alexandre-avocat.com

**Contexte :** Un site pour un ami avocat

**Stack découverte :** [Astro](https://astro.build/) - totalement nouveau pour moi

<br />

### Workflow de développement

1. 🎨 **Design complet** généré via bolt.new
2. 💻 **Polissage** avec VS Code + Copilot + Agent Claude Sonnet
3. 🚀 **CI/CD** GitHub Actions → déploiement OVH

</div>

<div class="flex items-center justify-center">

<img src="/david-alexandre-homepage.png" class="w-full h-auto" alt="alexandre-avocat.com homepage" />

</div>

</div>

---

# Côté tech lead - Résultats : Performance & Design

<div class="grid grid-cols-2 gap-8">

<div>

### Réalisations

- ⏱️ Site créé en **moins d'une semaine**
- 🎨 Design professionnel sans compétences design
- 🏆 Score Lighthouse excellent
- 🔄 Pipeline de déploiement automatisé

<br />

### Impact personnel

> _"Ce projet m'a permis de faire quelque chose d'impossible avant : créer un site avec un design pro sans compétences en design, et sans temps pour les side projects"_

</div>

<div class="flex items-center justify-center">

<img src="/david-alexandre-lighthouse.png" class="w-full h-auto" alt="Lighthouse performance scores" />

</div>

</div>

---

# Côté tech lead - Python & Whisper : Sous-titrage vidéo 🎬

<div class="grid grid-cols-2 gap-8">

<div>

### Le besoin initial

Ajouter des sous-titres à mes démos produit avec incrustation de ma tête

<br />

### Technologies découvertes

- **FFmpeg** - Manipulation vidéo
- **Whisper** (OpenAI) - Transcription IA
- **Python** - Orchestration
- Export **SRT** ou sous-titres incrustés

</div>

<div class="flex items-center justify-center">

<div class="bg-indigo-50 rounded-xl p-8 shadow-lg border-2 border-indigo-200">

### 🤖 Le process

1. 📹 Extraction audio de la vidéo
2. 🎯 Transcription avec Whisper
3. ⏱️ Génération des timecodes
4. 📝 Export SRT ou incrustation

<br />

_Stack totalement nouvelle pour moi !_

</div>

</div>

</div>

---

# Côté tech lead - Industrialisation & Évolutions 🛠️

<div class="grid grid-cols-2 gap-8">

<div>

### Professionnalisation du projet

- 🐳 **Docker** - Conteneurisation
- 📦 **Poetry** - Gestion des dépendances
- 🔍 **Ruff** - Linter + formatter
- 🔤 **Pyright** - Vérification des types
- ✅ **Pytest** - Tests unitaires

<br />

> _"Apprentissage express d'un écosystème totalement inconnu"_

</div>

<div>

### Évolutions futures

- 🎵 Intégration **pydub** pour gestion audio avancée
- 📢 **FFmpeg 8.0 "Huffman"** (août 2025) : support natif de Whisper !
- 🖥️ Ajout d'une **Web UI** pour modifier les ajuster les sous titres
- 💌 Analyze de **sentiment** pour éliminer les passages négatifs

<br />

### Impact

L'IA m'a permis de :
- Découvrir Python moderne
- Comprendre l'écosystème (Poetry, Ruff, etc.)
- Produire un outil fonctionnel rapidement

</div>

</div>

---

# Engineering Manager : côté management

<div class="flex flex-col items-center justify-center h-full">

<img src="/Engineering_manager-manager.png" class="w-[450px] h-auto" alt="Engineering Manager responsibilities diagram" />

<div class="mt-8 text-center text-gray-600 text-lg">

Comment gagner en efficacité pour me concentrer sur le fond ?

</div>

</div>

---

# Côté Management : IA & cérémonies agiles

### L'IA comme assistant quotidien pour l'animation des cérémonies

<br/>

- 💡 Idées d'icebreakers créatifs et personnalisés
- 🎨 Génération de visuels sur un thème spécifique pour dynamiser les réunions 
- 🎯 Formats de rétrospectives originaux et adaptés aux situations

<br/>

### Pour la veille technique :

<br/>

- 📄 Résumés d'articles techniques avec points essentiels à retenir
- 🎯 Synthèses attractives pour partager avec l'équipe et stimuler la lecture

<br />

Gain : Économie de temps significative sur les tâches préparatoires
Bénéfice : Impact positif sur l'engagement et la dynamique d'équipe

---

# Côté Management : IA & coaching d'équipe

### L'IA comme assistant pour le développement des collaborateurs :

<br/>

- Aide à la rédaction d'OKR et plans de développement personnalisés
- Suggestions de progression adaptées aux différents niveaux (L2, L3, Staff...)
- Reformulation d'e-mails professionnels et bilans d'évaluation annuelle
- Brouillon créatif pour structurer les idées rapidement et accélérer l'idéation

<br />

> _"Éviter les tirs gratuits quand on est énervé"_

---

# Apprentissages clés 🎓

<div class="grid grid-cols-2 gap-12">

<div>

### Côté Tech Lead

- 🚀 **Prototypage ultra-rapide**
- 🔍 **Découverte de stacks** complètes
- 🏗️ **Architecture overview** générée
- 💡 **Opportunités business** identifiées

</div>

<div>

### Côté Management

- 🎯 **Focus sur le fond** vs la forme
- ⏱️ **Gain de temps** significatif
- 💭 **Idéation accélérée**
- 🚀 **Onboarding projet** facilité

</div>

</div>

<br />

### Le vrai game-changer

<div class="text-center mt-8 p-6 bg-yellow-50 rounded-xl">

> _"L'IA comme assistant d'idéation en version extrêmement rapide :_
>
> _Je mets mes idées en vrac → J'affine → Je démarre"_

</div>

---

# Merci pour votre attention

<div class="flex flex-col items-center justify-center h-full gap-8">

<img src="/meetup-qr-code-openfeedback.png" class="w-[250px] h-auto" alt="QR Code OpenFeedback" />

<div class="text-center">

<p class="text-2xl font-bold text-gray-800 mb-4">
Votre feedback est précieux !
</p>

<p class="text-xl text-gray-600">
📱 Scannez le QR code pour partager vos retours et impressions
</p>

</div>

</div>

---
layout: thank_you
---
