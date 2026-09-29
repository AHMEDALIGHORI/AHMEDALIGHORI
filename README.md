<!--
  Ahmed Ali Ghori — GitHub profile README
  ─────────────────────────────────────────────────────────────
  Palette:  ink #10100F · ember #EF4D2F · volt #D7FF3F · bone #F6F6F0 · ash #B8B8B0
  Design intent: clarity, credibility, fast scanning.

  Assets
    assets/hero.svg        dark-theme banner (animated)
    assets/hero-light.svg  light-theme banner (animated)
  The two banners swap automatically with the reader's GitHub theme.

  Deliberate omissions
    · github-readme-stats — its public instance answers 503, so the card
      could only ever render broken.
    · The activity-graph card — that deployment now answers 402 Payment Required.
    · Star and follower counters — not a signal yet; the live repository and
      contribution counts below are the honest ones.
-->

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/hero.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg">
    <img src="./assets/hero.svg" alt="Ahmed Ali Ghori — immersive frontend developer and applied AI builder. Hyderabad, Pakistan. Open to work." width="100%">
  </picture>
</p>

<p align="center">
  <a href="https://ahmed-ali-portfolio-amber.vercel.app"><img src="https://img.shields.io/badge/PORTFOLIO-EF4D2F?style=for-the-badge&logo=vercel&logoColor=10100F" alt="Portfolio"></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/ahmed-ali-ghori-85a24b338"><img src="https://img.shields.io/badge/LINKEDIN-D7FF3F?style=for-the-badge&logo=linkedin&logoColor=10100F" alt="LinkedIn"></a>
  &nbsp;
  <a href="mailto:ahmed@plantpot.studio"><img src="https://img.shields.io/badge/EMAIL-10100F?style=for-the-badge&logo=gmail&logoColor=D7FF3F" alt="Email"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OPEN%20TO%20WORK-D7FF3F?style=flat-square&labelColor=10100F" alt="Open to work">
  <img src="https://img.shields.io/badge/HYDERABAD%2C%20PAKISTAN-EF4D2F?style=flat-square&labelColor=10100F&logo=googlemaps&logoColor=EF4D2F" alt="Based in Hyderabad, Pakistan — PKT, UTC+5">
  <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FAHMEDALIGHORI&query=%24.public_repos&label=PUBLIC%20REPOS&color=D7FF3F&labelColor=10100F&style=flat-square&logo=github&logoColor=D7FF3F" alt="Public repositories">
  <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fgithub-contributions-api.jogruber.de%2Fv4%2FAHMEDALIGHORI%3Fy%3Dlast&query=%24.total.lastYear&label=CONTRIBUTIONS%20LAST%20YEAR&color=EF4D2F&labelColor=10100F&style=flat-square&logo=github&logoColor=EF4D2F" alt="Contributions in the last year">
</p>

---

## I build interfaces people remember — and AI systems people can trust.

I'm **Ahmed Ali Ghori**, a frontend-focused software engineer and applied AI builder. I work where **cinematic web experiences** meet **source-grounded AI**: the interface has to feel effortless, and the system underneath it has to be correct.

- **Frontend** — motion-led products, WebGL scenes, design systems, accessible interaction detail
- **AI** — retrieval-augmented generation, multilingual retrieval, computer vision, speech, evaluation
- **Product** — turning ambiguous ideas into focused, shippable software with an architecture that survives review

> My best work connects a memorable interface to a dependable system underneath it.

---

## Building now

**[Voice2Law](https://github.com/AHMEDALIGHORI/Voice2Law-Website)** — a bilingual **Urdu / English legal-information assistant** for Pakistan. Ask a legal question by voice or text, get an answer grounded in a governed corpus of Pakistani law with citations, then export a structured, lawyer-ready case handoff.

`React 18` `TypeScript` `Vite` `FastAPI` `Firebase auth` `Docker` `AWS + Azure deploy paths`

Test suites on both sides of the stack — API, case intake, core, and NLP client on the Node backend; governance and reliability on the Python service. Release gates are scripted, not promised: `typecheck → build → bundle budget`.

---

## Featured work

| Project | What it demonstrates | Stack |
| --- | --- | --- |
| **[Voice2Law](https://github.com/AHMEDALIGHORI/Voice2Law-Website)** | Bilingual voice + text legal assistant: governed corpus, cited answers, case-handoff export | React · TypeScript · FastAPI · Docker |
| **[Noor Islamic Companion](https://github.com/AHMEDALIGHORI/noor-islamic-companion)** | Bilingual (English/Urdu) learning companion that answers only from verified sources | React Native · Expo · tRPC · Drizzle · Hugging Face |
| **[hf-rag-starter](https://github.com/AHMEDALIGHORI/hf-rag-starter)** | Small, production-minded RAG foundation with multilingual embeddings — one runtime dependency | TypeScript · Hugging Face |
| **[quran-api-client](https://github.com/AHMEDALIGHORI/quran-api-client)** | Typed Al Quran Cloud client: caching, offline support, bilingual text, zero runtime dependencies | TypeScript · API design |
| **[expo-audio-dock](https://github.com/AHMEDALIGHORI/expo-audio-dock)** | Audio dock that stays visible and controllable across Expo navigation | React Native · Reanimated |

<details>
<summary><b>How the two grounded-AI projects actually work</b></summary>

<br>

**Noor** — Question → multilingual embedding (`paraphrase-multilingual-MiniLM-L12-v2`) → cosine similarity over pre-cached source embeddings → lexical fallback → hybrid ranking → top-8 passages injected into the prompt → answer returned with citations, relevance scores, and retrieval metadata. 28 verified source records, and a refusal policy: it does not present itself as a mufti and routes high-stakes questions to qualified scholars.

**Voice2Law** — React client → FastAPI NLP service → retrieval over a governed corpus of Pakistani law (`legal_data/family`, `legal_data/penal`) → cited answer with browser speech input and Urdu/English output. Both halves of the stack carry their own test suites, and dependency updates arrive as Dependabot pull requests.

</details>

---

## Visual engineering

- **[TEA — scroll-driven narrative](https://github.com/AHMEDALIGHORI/tea-scroll-narrative)** — a film scrubbed frame-by-frame by scroll position: 200+ preloaded frames driven by `GSAP` + `Lenis`, vanilla JavaScript, no framework.
- **[VisionAI Pro](https://github.com/AHMEDALIGHORI/VisionAi-)** — real-time computer vision in one pipeline: product recognition (`YOLOv8`), hand-gesture control and sign-language input (`MediaPipe`), built on `OpenCV` and `TensorFlow` / `Keras`.

<details>
<summary><b>Client work</b> — ten shipped practice websites</summary>

<br>

One Next.js foundation taken through ten deliveries for dental and medical practices. Each site carries its own information architecture, service taxonomy, conversion-focused copy, and local-SEO structure — same engineering baseline, ten different practices.

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

<details>
<summary><b>Also in the lab</b> — experiments and learning builds</summary>

<br>

**[mindscope](https://github.com/AHMEDALIGHORI/mindscope-emotion-screen-detection-rag)** webcam emotion detection with local vector-search recommendations ·
**[Urdu_LLM](https://github.com/AHMEDALIGHORI/Urdu_LLM)** language-model experiments for Urdu ·
**[Speech Therapy Project](https://github.com/AHMEDALIGHORI/Speech-Thearpy-Project)** speech tooling ·
**[NeuralMint](https://github.com/AHMEDALIGHORI/NeuralMint)** Ethereum + IPFS model marketplace ·
**[Fake-News-Detector](https://github.com/AHMEDALIGHORI/Fake-News-Detector)** ·
**[smart_vision_analytics](https://github.com/AHMEDALIGHORI/smart_vision_analytics)** vision analytics

</details>

---

## Toolbox

**Frontend & motion**

`TypeScript` `React` `Next.js` `React Native` `Expo` `Vite` `Three.js` `React Three Fiber` `GSAP` `Lenis` `WebGL` `Tailwind CSS` `NativeWind`

**AI & backend**

`Python` `FastAPI` `OpenCV` `MediaPipe` `TensorFlow` `RAG` `Vector Search` `Hugging Face` `Llama` `tRPC` `Drizzle` `MySQL` `Zod` `Docker`

**Engineering habits**

`Accessible UI` `Responsive Design` `Design Systems` `API Design` `Source Grounding` `Evaluation` `Performance Budgets` `Technical Writing`

---

## How I work

- **Grounding over guessing.** If a system cannot show where an answer came from, it is not finished.
- **Measure, then claim.** Typechecks, test suites, and bundle budgets live in repo scripts, not in prose.
- **One foundation, many ships.** A reusable baseline beats ten bespoke codebases — ten client sites prove it.
- **Accessibility is part of the brief.** Keyboard paths, contrast, and reduced-motion handling are engineering decisions, not a follow-up ticket.

---

## Open-source focus

I'm drawn to reusable tools that make software more useful, understandable, and trustworthy:

- multilingual, citation-aware retrieval
- developer-friendly TypeScript packages with no dependency drag
- interfaces that make complex systems feel simple
- documentation and examples that respect the reader's time

---

## Let's build something meaningful

I'm open to **frontend engineering**, **creative development**, **AI product prototyping**, and collaborations where design quality and technical quality matter equally.

Working from **Hyderabad, Pakistan (PKT / UTC+5)** · usually replies within a day.

<p align="center">
  <a href="mailto:ahmed@plantpot.studio"><img src="https://img.shields.io/badge/START%20A%20CONVERSATION-EF4D2F?style=for-the-badge&logo=maildotru&logoColor=10100F" alt="Start a conversation"></a>
  &nbsp;
  <a href="https://ahmed-ali-portfolio-amber.vercel.app"><img src="https://img.shields.io/badge/VIEW%20PORTFOLIO-D7FF3F?style=for-the-badge&logo=vercel&logoColor=10100F" alt="View portfolio"></a>
</p>

<p align="center"><sub>Building at the intersection of craft, clarity, and useful technology.</sub></p>


