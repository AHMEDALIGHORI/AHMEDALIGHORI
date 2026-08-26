<!--
  Ahmed Ali Ghori — GitHub profile README
  ─────────────────────────────────────────────────────────────
  Palette:  ink #10100F · ember #EF4D2F · volt #D7FF3F · bone #F6F6F0 · ash #B8B8B0
-->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&pause=900&color=D7FF3F&center=true&vCenter=true&width=780&height=46&lines=Immersive+frontend+%C3%97+applied+AI;Three.js+%C2%B7+R3F+%C2%B7+GSAP+%C2%B7+WebGL;RAG+%C2%B7+computer+vision+%C2%B7+Python;Building+trustworthy+AI+for+the+Ummah" alt="Immersive frontend × applied AI">
</p>

<p align="center">
  <a href="https://ahmed-ali-portfolio-amber.vercel.app"><img src="https://img.shields.io/badge/PORTFOLIO-EF4D2F?style=for-the-badge&logo=vercel&logoColor=10100F" alt="Portfolio"></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/ahmed-ali-ghori-85a24b338"><img src="https://img.shields.io/badge/LINKEDIN-D7FF3F?style=for-the-badge&logo=linkedin&logoColor=10100F" alt="LinkedIn"></a>
  &nbsp;
  <a href="mailto:ahmed@plantpot.studio"><img src="https://img.shields.io/badge/EMAIL-10100F?style=for-the-badge&logo=gmail&logoColor=D7FF3F" alt="Email"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-OPEN%20TO%20WORK-D7FF3F?style=flat-square&labelColor=10100F" alt="Open to work">
  <img src="https://img.shields.io/badge/HYDERABAD-PAKISTAN-EF4D2F?style=flat-square&labelColor=10100F&logo=googlemaps&logoColor=EF4D2F" alt="Hyderabad, Pakistan">
  <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FAHMEDALIGHORI&query=%24.public_repos&label=PUBLIC%20REPOS&color=D7FF3F&labelColor=10100F&style=flat-square&logo=github&logoColor=D7FF3F" alt="Public repositories">
</p>

---

## Flagship Projects

### [Noor Islamic Companion](https://github.com/AHMEDALIGHORI/noor-islamic-companion) — AI-powered Islamic learning companion

<p align="center">
  <img src="https://img.shields.io/badge/Bilingual-English+%7C+Urdu-0F6B52?style=flat-square" alt="Bilingual">
  <img src="https://img.shields.io/badge/RAG-Multilingual+Embeddings-0F6B52?style=flat-square" alt="RAG">
  <img src="https://img.shields.io/badge/Sources-28+Verified+Records-0F6B52?style=flat-square" alt="Verified Sources">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT">
</p>

A bilingual (English + Urdu) Islamic learning companion with **source-grounded AI answers**. Every response is grounded in verified Quran, Hadith, and Tafsir passages with exact citations. Built with React Native, tRPC, Hugging Face Inference Providers, and multilingual embeddings.

**Architecture:** Question → Semantic Search (cosine similarity) → Lexical Fallback → Hybrid Ranking → Llama Generation with Source Context → Grounded Answer with Citations

**Stack:** `React Native` `Expo` `TypeScript` `tRPC` `Hugging Face` `Llama 3.1/3.3` `NativeWind`

---

### [hf-rag-starter](https://github.com/AHMEDALIGHORI/hf-rag-starter) — Production-ready RAG starter

<p align="center">
  <img src="https://img.shields.io/badge/Single-Dependency-0F6B52?style=flat-square" alt="Single Dependency">
  <img src="https://img.shields.io/badge/Multilingual-50%2B+Languages-0F6B52?style=flat-square" alt="Multilingual">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT">
</p>

A minimal, production-ready RAG starter using Hugging Face Inference Providers and multilingual embeddings. Single class, zero config, works with any language.

```typescript
const rag = new RAGEngine({ hfToken: "hf_..." });
rag.addDocuments([{ id: "1", text: "Your knowledge base..." }]);
const result = await rag.query("Your question");
```

**Stack:** `TypeScript` `Hugging Face` `Embeddings` `Cosine Similarity`

---

### [quran-api-client](https://github.com/AHMEDALIGHORI/quran-api-client) — TypeScript Quran API client

<p align="center">
  <img src="https://img.shields.io/badge/Zero-Runtime+Dependencies-0F6B52?style=flat-square" alt="Zero Dependencies">
  <img src="https://img.shields.io/badge/Caching-Built-in-0F6B52?style=flat-square" alt="Caching">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT">
</p>

TypeScript client for Al Quran Cloud API with full surah metadata (114 surahs), built-in caching, bilingual text (Arabic + English), and zero runtime dependencies.

**Stack:** `TypeScript` `Al Quran Cloud API` `Zero Dependencies`

---

### [expo-audio-dock](https://github.com/AHMEDALIGHORI/expo-audio-dock) — Persistent audio player dock

<p align="center">
  <img src="https://img.shields.io/badge/Expo-50%2B-000020?style=flat-square&logo=expo" alt="Expo">
  <img src="https://img.shields.io/badge/Animated-Reanimated-3+-F472B6?style=flat-square" alt="Animated">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT">
</p>

Drop-in persistent audio player dock for Expo/React Native apps. Stays visible across navigation, shows progress, and animates smoothly.

**Stack:** `React Native` `Expo Audio` `Reanimated`

---

## Two disciplines, one workflow

I design and build the surface **and** the intelligence underneath it. Most of my work sits where those two meet: a WebGL interface that has to feel effortless, wired to a retrieval pipeline or vision model that has to be correct.

<table>
<tr>
<td width="50%" valign="top">

### ◆ Creative engineering

Cinematic, motion-led interfaces where scroll, camera, and light are part of the argument — not decoration bolted on at the end.

WebGL scenes and shader work · smooth-scroll choreography · page transitions · responsive design systems · accessible motion

`Three.js` `React Three Fiber` `GSAP` `Lenis` `Next.js`

</td>
<td width="50%" valign="top">

### ◆ Applied AI

Prototypes that do real inference on real inputs — speech, documents, video frames — and stay honest about their confidence.

Retrieval-augmented generation · vector search · computer vision · speech-to-text · evaluation and guardrails

`Python` `FastAPI` `OpenCV` `RAG` `Vector DBs`

</td>
</tr>
</table>

---

## More work

<table>
<tr>
<td width="50%" valign="top">

### [Webgel Studio](https://github.com/AHMEDALIGHORI/Webgel-Studio-WEBGEL)

A 16-page creative studio experience where WebGL heroes, smooth-scroll choreography, page transitions, and grain-driven art direction work as one visual system.

`Three.js` `GSAP` `Lenis` `WebGL`

</td>
<td width="50%" valign="top">

### [PlantPot Studio](https://github.com/AHMEDALIGHORI/PlantPot)

An explorable 3D portfolio built as a miniature world — React Three Fiber scenes, animated environments, orbit controls, and scene-led navigation.

`Next.js` `React Three Fiber` `Drei` `TypeScript`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [VisionAI Pro](https://github.com/AHMEDALIGHORI/VisionAi-)

Real-time computer-vision experiments: product recognition, gesture control, and sign-language input.

`Python` `OpenCV`

</td>
<td width="50%" valign="top">

### [Qitchen](https://github.com/AHMEDALIGHORI/qitchen-animated-restaurant-website)

A responsive restaurant experience shaped through cinematic food imagery, restrained typography, and motion that supports the dining narrative.

`HTML` `CSS` `Responsive UI` `Motion Design`

</td>
</tr>
</table>

<details>
<summary><b>Client work</b> — ten shipped healthcare practice sites</summary>

<br>

A production series of responsive clinic websites, each with its own information architecture, service taxonomy, and local-SEO structure.

[Glisten Dental](https://github.com/AHMEDALIGHORI/glisten-dental) ·
[Dentique](https://github.com/AHMEDALIGHORI/dentique-dental-clinics) ·
[The Dental Clinic](https://github.com/AHMEDALIGHORI/The-Dental-Clinic) ·
[GM Dental](https://github.com/AHMEDALIGHORI/gm-dental-clinic) ·
[Yasir Dental Care](https://github.com/AHMEDALIGHORI/yasir-dental-care) ·
[Patel Dental](https://github.com/AHMEDALIGHORI/patel-dental-clinic) ·
[The Care Medical Center](https://github.com/AHMEDALIGHORI/the-care-medical-center) ·
[Rajput Dental & Physio](https://github.com/AHMEDALIGHORI/rajput-dental-and-physio-clinic) ·
[Durrani's Dental](https://github.com/AHMEDALIGHORI/durranis-dental-clinic) ·
[Dental Works](https://github.com/AHMEDALIGHORI/dental-works)

</details>

---

## Open Source Impact

| Project | What it solves | Stack |
|---------|---------------|-------|
| **[hf-rag-starter](https://github.com/AHMEDALIGHORI/hf-rag-starter)** | Production-ready RAG with multilingual embeddings | TypeScript, Hugging Face |
| **[quran-api-client](https://github.com/AHMEDALIGHORI/quran-api-client)** | Typed Quran API with caching and bilingual text | TypeScript, Zero deps |
| **[expo-audio-dock](https://github.com/AHMEDALIGHORI/expo-audio-dock)** | Persistent audio player for Expo apps | React Native, Reanimated |

---

## On GitHub

<p align="center">
  <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fgithub-contributions-api.jogruber.de%2Fv4%2FAHMEDALIGHORI%3Fy%3Dlast&query=%24.total.lastYear&label=CONTRIBUTIONS%20%2F%20YEAR&color=EF4D2F&labelColor=10100F&style=flat-square" alt="Contributions in the last year">
  <img src="https://img.shields.io/badge/MEMBER%20SINCE-2024-D7FF3F?style=flat-square&labelColor=10100F" alt="Member since 2024">
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AHMEDALIGHORI&days=90&bg_color=10100F&color=F6F6F0&line=EF4D2F&point=D7FF3F&area=true&area_color=EF4D2F&hide_border=true&custom_title=Contribution%20Activity%20%E2%80%94%20Last%2090%20Days" alt="Contribution activity over the last 90 days" width="98%">
</p>

---

## Let's build something trustworthy

I take on immersive websites, interactive portfolios, product launches, and AI-enabled prototypes — with a focus on source grounding and educational accuracy. Comfortable owning both the interface and the model behind it.

<p align="center">
  <a href="mailto:ahmed@plantpot.studio"><img src="https://img.shields.io/badge/START%20A%20CONVERSATION-EF4D2F?style=for-the-badge&logo=maildotru&logoColor=10100F" alt="Start a conversation"></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/ahmed-ali-ghori-85a24b338"><img src="https://img.shields.io/badge/CONNECT-D7FF3F?style=for-the-badge&logo=linkedin&logoColor=10100F" alt="Connect on LinkedIn"></a>
</p>
