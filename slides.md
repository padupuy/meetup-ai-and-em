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

::logo::

<img src="/best.jpg" alt="BEST logo" style="width: 100px" />

---

# Contexte : l'IA omniprésente mais risquée

> Avant de plonger dans mes usages concrets de l'IA, il est crucial de rappeler les enjeux liés à sa popularisation rapide.

<br />

<v-clicks>

- L'IA fait désormais partie du quotidien : ChatGPT, Claude, Gemini, Mistral, Perplexity ...
- Les usages explosent, y compris dans le monde professionnel.
- [Danger du « Shadow AI »](https://siecledigital.fr/2025/06/20/shadow-ai-un-salarie-sur-trois-utilise-lia-sans-en-parler-a-sa-direction/) : utilisation d'outils via des comptes personnels.
- Risque majeur de fuites de données sensibles non maîtrisées.
- Bonnes pratiques : privilégier [les comptes entreprise](https://learn.microsoft.com/en-us/copilot/microsoft-365/enterprise-data-protection) 🛡️ ou internes (confidentialité, RGPD, aucun réentraînement sur vos données).
- L'IA doit être testée sur des side projects, jamais sur des projets clients.

</v-clicks>

---

# Impact écologique : un coût invisible

> L'essor de l'IA a un impact environnemental considérable, souvent méconnu, qu'il est indispensable d'intégrer dans notre réflexion.

<br />

<v-clicks>

- D'après le [Shift Project (octobre 2025)](https://theshiftproject.org/app/uploads/2025/09/Synthese-RF-PIA-1.pdf) : la croissance de l'IA menace les objectifs climatiques.
- La consommation énergétique mondiale des data centers est passée de 165 TWh (2014) à 420 TWh (2024) 📈
- L'IA représente déjà 15% de cette consommation et pourrait attendre **35%** en 2030 (1 500 TWh/an).
- Une large part repose encore sur des sources fossiles.
- Utiliser l'IA, c'est aussi penser sobriété numérique et mesurer son impact environnemental.

</v-clicks>

---

# Qui suis-je ?

<div class="grid grid-cols-2 gap-12 items-center">
<div>

## Pierre-Alexandre Dupuy

- 35 ans, 15 ans dans le web
- Lead chez ekino 
- Papa de 2 filles 
- Vélotafeur convaincu
- Partisan de la semaine à 4/5ème

</div>
<div class="flex justify-center flex-col gap-4">
  <img src="/illustration-pierre-alexandre-dupuy.png" class="rounded-full w-80 h-80 object-cover" />
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

_Réunions avec plein de ssssss_

</div>

</div>

---
layout: two-cols-header
---

# Définition du rôle de EM

::left::

Selon les entreprises, le rôle varie :

- **Hands-off** : Management pur
- **Hands-on** : Management + technique

::right::

<v-clicks>

Chez ekino : rôle hybride "Lead"

- 30% Management
- 70% Tech Lead
  - dont 80% de revue de code 😁

</v-clicks>

<style>
.two-cols-header {
  column-gap: 20px; /* Adjust the gap size as needed */
}
</style>

---
layout: two-cols-header
---

# Minute philosophique

On va essayer de répondre à 2 questions

::left::

### Côté tech lead : 

<br /> 

<v-clicks>

<div class="bg-yellow-50 rounded-xl p-8 shadow-lg border-2 border-yellow-200">

L'IA est-elle un levier pour rester hands-on malgré le passage au management ?

</div>

</v-clicks>

::right::

### Côté management : 

<br /> 

<v-clicks>

<div class="bg-yellow-50 rounded-xl p-8 shadow-lg border-2 border-yellow-200">

L'IA est-elle un levier pour un management plus humain ?

</div>

</v-clicks>


<style>
.two-cols-header {
  column-gap: 20px; /* Adjust the gap size as needed */
}
</style>

---

# Engineering Manager : tech lead

<div class="flex flex-col items-center justify-center h-full">

<img src="/Engineering_manager-coding.png" class="w-[450px] h-auto" alt="Engineering Manager responsibilities diagram" />

<div class="mt-8 text-center text-gray-600 text-lg">

_Parfait, il me reste 30mn pour coder aujourd'hui_

</div>

</div>

---
layout: image-right

# the image source
image: /david-alexandre-homepage2.png

# a custom class name to the content
class: pr-8
---

# Côté tech lead - Astro 🚀

**Contexte :** Un site pour un ami avocat

**Stack :** [Astro](https://astro.build/)

<br />

🤖 Workflow de développement

1. 🎨 Design + scaffolding complet généré via [bolt.new](https://bolt.new/)
2. 💻 Polissage avec VS Code + Copilot + Agent Claude Sonnet + 🙋‍♂️
3. 🚀 CI/CD GitHub Actions → déploiement OVH

---
layout: image-right

# the image source
image: /david-alexandre-lighthouse2.png

# a custom class name to the content
class: pr-8
---

# Côté tech lead - Astro 🚀

### Réalisations

- 🚀 Découverte de Astro
- ⏱️ Site créé en **moins d'une semaine**
- 🎨 Design professionnel **sans compétences** design
- 🏆 Score Lighthouse excellent
- 🔄 Pipeline de déploiement automatisé

<br />

> En tant que papa je n'ai plus de temps pour faire des side projects.  
> Grâce à l'IA j'ai pu aller au bout de mon idée très rapidement et sans y consacrer trop de charge mentale.  
> J'ai vu un cas concret de projet simple produit avec Astro

---

# Côté tech lead - Python

<div class="grid grid-cols-2 gap-8">

<div>

**Contexte :** Ajout de sous-titres à mes vidéos produit

**Stack :** Python & co

<br />

🤖 Workflow de développement

1. 📹 Extraction audio de la vidéo avec **FFmpeg**
2. 🎯 Transcription avec **Whisper** (OpenAI)
3. 🙊 Analyse des mots de remplissage (euhhh, humm, en fait) avec **Pydub**
4. 📝 Export **SRT** ou incrustation

</div>

<div class="flex items-center justify-center">
  <img src="/screencast-ekino.png" class="w-full h-auto" alt="Screencast" />
</div>
</div>

---

# Côté tech lead - Python

Côté DX

- 🐳 **Docker** - Conteneurisation
- 📦 **Poetry** - Gestion des dépendances
- 🔍 **Ruff** - Linter + formatter
- 🔤 **Pyright** - Vérification des types
- ✅ **Pytest** - Tests unitaires

<br />

> Apprentissage express d'un écosystème totalement inconnu.  
> Application de l'industrialisation du frontend à la stack Python.  
> Sentiment de puissance grâce au Vibe Coding qui permet de coder dans un langage inconnu

---

# Engineering Manager : côté management

<div class="flex flex-col items-center justify-center h-full">

<img src="/Engineering_manager-manager.png" class="w-[450px] h-auto" alt="Engineering Manager responsibilities diagram" />

<div class="mt-8 text-center text-gray-600 text-lg">

Le gros du boulot

</div>

</div>

---

# Côté Management

<div class="flex gap-8">
<div>

L'IA comme assistant pour l'animation des cérémonies agiles

- Idées d'icebreakers créatifs et **personnalisés**
- 🎨 Génération de visuels sur un thème spécifique pour dynamiser les réunions 
- Formats de rétrospectives originaux et adaptés aux situations

</div>
<div>
  <div class="flex items-center justify-center">
    <img src="/pa-tdf.png" class="max-w-[150px] w-full h-auto" alt="Screencast" />
  </div>
</div>
</div>

Progression des équipes et engagement

- Résumés d'articles techniques avec points essentiels à retenir
- Synthèses **attractives** pour partager avec l'équipe et stimuler la lecture

---

# Côté Management

Développement de carrière assisté par IA

- Aide à la rédaction d'OKR et plans de développement personnalisés
- Suggestions de progression adaptées aux différents niveaux (L2, L3, Staff...)
- Reformulation d'e-mails professionnels et bilans d'évaluation annuelle
- Brouillon créatif pour structurer les idées rapidement et accélérer l'idéation

<br />

> L'IA permet également d'éviter les tirs gratuits quand on est énervé

---
layout: image

# the image source
image: /manager-vibe-coding.png

---
---

# Ce qu'il faut retenir

<v-clicks>

L’IA, levier pour rester hands-on malgré le passage au management
- Accélère l’exploration de nouvelles stacks et outils.
- Accélère la revue de code, la génération de spécifications et facilite l’onboarding des projets.
- Facilite la création rapide de prototypes et la réalisation de side projects

L’IA, levier pour un management plus humain
- Permet de gagner du temps sur les fonctions à faible valeur ajoutée (rédaction, reformulation, synthèse), pour mieux se concentrer sur l’humain, l’accompagnement 
- Offre des idées personnalisées pour animer les équipes (icebreakers, rétrospectives).
- Accélère la définition de plans de développement et OKR personnalisés.
- Ne remplace pas les soft skills (écoute active, intuition, relation humaine, leadership, empathie)

</v-clicks>

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
