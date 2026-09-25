## Nice to meet you! 👋
- ⚡ Fun fact: I've installed networking hardware inside the DMZ, within shouting distance from North Korean soldiers 🪖
- 📫 How to reach me: Lsha0730@gmail.com
- 🛠️ Languages: JavaScript/TypeScript, Python, Java, C, C++, Rust, SQL, HTML, CSS
- 🛠️ Frameworks: React.js, Node.js, Express.js, NestJS, React Router, Firebase, Supabase, TailwindCSS, CMake
- 🛠️ Tools & Testing: Git, Docker, gRPC/protobuf, Chrome MV3, Wrangler/Cloudflare R2, JUnit, Chai, Mocha, Figma, Stripe, SendGrid

## Most Recent Projects

### [Incoming @ *](https://incoming.lincolnlee.xyz) — AI-tailored resumes from any job post 📄
<ul>
  <li>🧩 Custom LaTeX DSL as <code>%</code> comments (<code>switch / select / rank / gen / option / end</code>) — Overleaf still compiles untouched, web editor is canonical preview. Parser/renderer in <code>packages/shared</code>, multi-file <code>\input</code> closure, defaults resolution</li>
  <li>✒️ Chrome extension (MV3 SidePanel) + React (Vite/Monaco) + Express + Supabase Auth/Postgres. Press <b>Create Resume</b> on a job page → scrape → batched LLM draft → one-by-one review → compile to PDF</li>
  <li>🖨️ Separate renderer service over <code>texlive/texlive</code> + <code>latexmk</code> (pdflatex/xelatex/lualatex) + poppler JPG export, Docker Compose stack</li>
  <li>Built using: TypeScript, React, Express.js, Supabase, OpenAI API, Chrome MV3, Docker, LaTeX</li>
</ul>

### [Pacer](https://trypacer.app) — Website text-to-speech that’s actually good 🗣️
<ul>
  <li>🔊 Manifest V3 Chrome extension + API backend for reading page text aloud with sentence highlighting and scroll sync</li>
  <li>🧠 Static parser built for arbitrary real sites (manifest/checksum-backed fixtures in <code>test/fixtures/real-pages</code>), local TTS runtime + cloud model calls routed through backend (no keys in extension)</li>
  <li>🚀 Public install at <code>/install</code>, releases versioned in <code>apps/web/public/releases/extension.json</code>, ZIPs in Cloudflare R2 served via <code>downloads.trypacer.app</code> with SHA-256 + size in catalog</li>
  <li>Built using: JavaScript/TypeScript, Chrome MV3, Express.js, Supabase, Wrangler/Cloudflare R2</li>
</ul>

### [Express.cpp](https://github.com/lsha0730/Express.cpp) — Sub-millisecond Express.js in C++ ⚡
<ul>
  <li>⚡ Multi-threaded C++20 web framework with Express-style routing for CPU-heavy / time-sensitive services</li>
  <li>🧱 CMake + Conan (<code>fmt, nlohmann_json</code>), headers in <code>include/express</code>, CTest suite</li>
  <li>Built using: C++20, CMake, Conan, Boost/Asio-style net layer</li>
</ul>

### [MUNSuite.com](https://munsuite.com) — Model UN conference management 🧑‍⚖️
<ul>
  <li>✒️ Full-stack web app to streamline Model UN voting procedures and the collection of speaker analytics for event staff</li>
  <li>🌐 3,000 users internationally across Canada (every major BC conference), USA, and Europe</li>
  <li>Solo-built from-scratch on React.js, Express.js, Node.js, TypeScript, Firebase, Stripe, SendGrid, Figma</li>
</ul>

## Hackathon Wins

### Lucid.ai — Hack the North 2022
🏆 Winner (1 of 12 among 210 projects)  
Text-to-narrated-movie generator with GPT-3 + Stable Diffusion + TTS — I built frontend/UI + client/API architecture.  
[Devpost](https://devpost.com/software/lucid-ai-95nerk) | [Repo](https://github.com/underHA/htn-2022)

### Pitch.ai — nwHacks 2022
🏆 1st Place (122 projects) + OpenAI Award  
Auto-generates live presentations from presenter audio — I built frontend/UI + API architecture + pitch.  
[Devpost](https://devpost.com/software/pitch-ai) | [Repo](https://github.com/underHA/nwhacks-2022/)

### Chatif.ai — Produhacks 2023
🏆 Most Technically Complex + SAP Award  
Q&A over any website without custom model training, via scraping + AI tree traversal.  
[Devpost](https://devpost.com/software/chatif-ai)

### Eyelexa — Hackcamp 2021
🏆 Most Creative UI/UX (33 projects)  
Image-to-speech reader for the visually impaired — I built the frontend.  
[Devpost](https://devpost.com/software/eyelexa-reading-assistant) | [Repo](https://github.com/underHA/hackcamp-2021/)
