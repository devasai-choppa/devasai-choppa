<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-hud-dark.svg">
  <img src="assets/hero-hud-light.svg" alt="Devasai Pranatheswar Choppa. Data Analyst at NextGenTek USA, Boston. Healthcare data and applied AI." width="100%">
</picture>

Data Analyst at NextGenTek USA · Boston  
MS Analytics (Applied Machine Intelligence), Northeastern · B.Tech CS, Lendi / JNTU

<a href="mailto:pranathesw@gmail.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/email-dark.svg">
    <img src="assets/email-light.svg" alt="Email pranathesw@gmail.com" width="189" height="28">
  </picture>
</a>
&nbsp;
<a href="https://www.linkedin.com/in/devasai-pranatheswar">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/linkedin-dark.svg">
    <img src="assets/linkedin-light.svg" alt="LinkedIn: linkedin.com/in/devasai-pranatheswar" width="96" height="28">
  </picture>
</a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/terminal-dark.svg">
  <img src="assets/terminal-light.svg" alt="Demo terminal. Identity, focus areas, the six public repos, and a scripted validate line that is not a measured result." width="900">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divider-datastream-dark.svg">
  <img src="assets/divider-datastream-light.svg" alt="" width="100%">
</picture>

## What I build

<table>
<tr>
<td width="52%" valign="top">

**Agents.** LangGraph `retrieve → generate → reflect → output`. A Python score plus a temperature-0 verdict. FLAG is a state.

**Warehouse.** DuckDB `raw` → dbt marts → LightGBM. The build fails if a label leaked. A referral waits on a person.

**Evidence.** One ACMG node per code. EEG `resample_poly` with an append-only chain. A policy field needs a character span.

</td>
<td width="48%" valign="top">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/neural-net-dark.svg">
  <img src="assets/neural-net-light.svg" alt="Diagram: clinical text in, validated insight out. Four layers. Not a measured model." width="100%">
</picture>

</td>
</tr>
</table>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divider-datastream-dark.svg">
  <img src="assets/divider-datastream-light.svg" alt="" width="100%">
</picture>

## Featured work

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/devasai-choppa/Sentinal_RAG">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/project-cards/sentinel-rag-dark.svg">
    <img src="assets/project-cards/sentinel-rag-light.svg" alt="Sentinel-RAG. Child retrieve. Parent draft. Reflect or FLAG. LangGraph, Chroma, FastAPI.">
  </picture>
</a>

`retrieve → generate → reflect → output`

Child hit in Chroma, parent context to Llama 3.1 8B. Empty context, an off-corpus query, or `CONTRADICTED` is FLAG. The in-repo corpus is a fictional diabetes guideline. Not a device.

[▶ Demo](https://github.com/devasai-choppa/Sentinal_RAG/blob/main/sentinel-rag/docs/demo.gif) · [📐 Architecture](https://github.com/devasai-choppa/Sentinal_RAG/blob/main/sentinel-rag/docs/ARCHITECTURE.md) · [📄 README](https://github.com/devasai-choppa/Sentinal_RAG/blob/main/sentinel-rag/README.md)

</td>
<td width="50%" valign="top">

<a href="https://github.com/devasai-choppa/Clear-Bed">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/project-cards/clearbed-dark.svg">
    <img src="assets/project-cards/clearbed-light.svg" alt="ClearBed. Stay mart, leakage gate, then a human interrupt. dbt, DuckDB, LightGBM.">
  </picture>
</a>

`raw → dbt marts → LightGBM → interrupt`

Stuck-risk, barrier type, and avoidable days. The quality report fails on a leaked label, high nulls, or too few stays. `sent` is recorded only after approval. Nothing is transmitted. Stays are synthetic. The CMS Care Compare file is the national nursing-home catalog.

[▶ Demo](https://github.com/devasai-choppa/Clear-Bed/blob/main/docs/walkthrough.gif) · [📐 Architecture](https://github.com/devasai-choppa/Clear-Bed#architecture) · [📄 README](https://github.com/devasai-choppa/Clear-Bed)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/devasai-choppa/acmg-triage">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/project-cards/acmg-triage-dark.svg">
    <img src="assets/project-cards/acmg-triage-light.svg" alt="acmg-triage. One ACMG node per code. Cache only. Refusal path. Python, FastAPI, DuckDB.">
  </picture>
</a>

`rules → VCEP → cache → refuse`

Pydantic `GraphState`, one node per ACMG/AMP code, literature from a committed cache only. No live LLM. Conflict or an uncovered variant is refused. Concordance with the rules-only baseline is 0.670 on 100 designed probes.

[▶ Demo](https://github.com/devasai-choppa/acmg-triage/blob/main/demo/out/acmg-triage-demo.gif) · [📐 Architecture](https://github.com/devasai-choppa/acmg-triage/blob/main/src/acmg_triage/graph.py) · [📄 README](https://github.com/devasai-choppa/acmg-triage)

</td>
<td width="50%" valign="top">

<a href="https://github.com/devasai-choppa/neuroprivacy">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/project-cards/neuroprivacy-dark.svg">
    <img src="assets/project-cards/neuroprivacy-light.svg" alt="neuroprivacy. Span offsets scored against two state statutes. Python, Pydantic, rules.">
  </picture>
</a>

`span → offset → rule → statute`

Deterministic extract. A true field with no character offset is a citation gap. Rules cover Colorado HB24-1058 and California SB 1223. Field F1 is 1.000 on 20 hand labels. The live hold-out is open. Not a legal opinion.

[▶ Demo](https://github.com/devasai-choppa/neuroprivacy/blob/main/demo/out/neuroprivacy-demo.gif) · [📐 Architecture](https://github.com/devasai-choppa/neuroprivacy/blob/main/src/neuroprivacy/scoring.py) · [📄 README](https://github.com/devasai-choppa/neuroprivacy)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/devasai-choppa/eeg-harmonize">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/project-cards/eeg-harmonize-dark.svg">
    <img src="assets/project-cards/eeg-harmonize-light.svg" alt="eeg-harmonize. EDF, unit check, montage, resample, provenance. NumPy, SciPy, EDF.">
  </picture>
</a>

`read → units → montage → resample_poly`

A bad unit scale is rejected. Each step is appended to a DuckDB provenance chain. The clips are designed. TUH transfer was not run, and TUH is not in the repository.

[▶ Demo](https://github.com/devasai-choppa/eeg-harmonize/blob/main/demo/out/eeg-harmonize-demo.gif) · [📐 Architecture](https://github.com/devasai-choppa/eeg-harmonize/blob/main/src/eeg_harmonize/convert.py) · [📄 README](https://github.com/devasai-choppa/eeg-harmonize)

</td>
<td width="50%" valign="top">

<a href="https://github.com/devasai-choppa/Hamsa">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/project-cards/hamsa-dark.svg">
    <img src="assets/project-cards/hamsa-light.svg" alt="Hamsa. P-256, AES-GCM, catalog price, UPI intent. FastAPI, React, WebCrypto.">
  </picture>
</a>

`P-256 → HKDF → AES-GCM → verify_line`

Non-exportable device key. Per-message content key, with conversation, message, and sender bound as additional data. Unknown SKU, bad quantity, or missing stock is rejected. Price is copied from `price_paise`. UPI is an intent. The app does not hold the money.

[▶ Demo](https://github.com/devasai-choppa/Hamsa/blob/main/demo/hamsa-demo.gif) · [📐 Architecture](https://github.com/devasai-choppa/Hamsa/blob/main/docs/architecture.md) · [📄 README](https://github.com/devasai-choppa/Hamsa)

</td>
</tr>
</table>

## Genomics and neuro

<table>
<tr>
<td width="40%" valign="top">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/dna-helix-dark.svg">
  <img src="assets/dna-helix-light.svg" alt="Helix diagram. One rung is marked VARIANT. Not a real variant call." width="100%">
</picture>

</td>
<td width="60%" valign="top">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/brain-eeg-dark.svg">
  <img src="assets/brain-eeg-light.svg" alt="Wireframe brain and five EEG channels. Noisy traces align, then separate. Designed geometry, not a recording." width="100%">
</picture>

</td>
</tr>
</table>

## Where it goes deep

The cards above are the map. The bounds below are the systems.

**Retrieval loop.** [Sentinel-RAG](https://github.com/devasai-choppa/Sentinal_RAG) splits each guideline into a 500-word parent and 100-word children. Chroma stores both. Embeddings are `all-MiniLM-L6-v2`. Search hits the child. Generation reads the parent. The compiled LangGraph is `retrieve → generate → reflect → output`, with Llama 3.1 8B through Groq on the generate step. Live generation needs `GROQ_API_KEY`.

`reflect` blends a Python score (context coverage, uncertainty, specificity, contradiction) with a second model call at temperature 0. That call returns `SUPPORTED`, `PARTIALLY_SUPPORTED`, or `CONTRADICTED`. Empty context, a query that misses the corpus, or `CONTRADICTED` is FLAG. A `SUPPORTED` verdict, or a corpus-grounded draft already at or above 0.75, is returned. Otherwise a score at or above 0.85 is returned, and a score at or above 0.75 retries retrieval up to 2 times. Bedside mode can skip the second call when the heuristic is already high. An old source year lowers the score. FLAG is written by `output` from a decision inside `reflect`. It is not a fifth node. The bundled corpus is a fictional diabetes guideline. Not a medical device.

**Warehouse and discharge model.** [ClearBed](https://github.com/devasai-choppa/Clear-Bed) loads Synthea into DuckDB `raw`. dbt builds `marts.feat_admission_snapshot` and `marts.fct_stay_labels`. LightGBM fits stuck-risk, barrier type, and avoidable days from that join. Categoricals are one-hot encoded. SHAP is read for the positive class. A quality report fails the build if a label column leaked onto the admission snapshot, if feature nulls are too high, or if the stay count is too small. The placement graph matches the national CMS Care Compare nursing-home file and interrupts until a person approves. Approve records `sent`. It does not transmit. Patients are synthetic.

**Evidence graph.** [acmg-triage](https://github.com/devasai-choppa/acmg-triage) keeps `GraphState` as a Pydantic model. Each ACMG/AMP rules code is its own node, then a VCEP overlay, then literature nodes that read only a committed cache. The runner is hand-rolled. There is no live LLM on this graph. Conflicting calls and variants outside the catalog are refused. Concordance with the rules-only baseline is 0.670 on 100 designed probes.

**Policy spans.** [neuroprivacy](https://github.com/devasai-choppa/neuroprivacy) extracts with deterministic rules. A field marked true without a character offset is a citation gap. The scorer covers Colorado HB24-1058 and California SB 1223. Mean field F1 is 1.000 on 20 hand-labeled samples. The live public-policy hold-out is still open. The output is not a legal opinion.

**EEG conversion.** [eeg-harmonize](https://github.com/devasai-choppa/eeg-harmonize) reads EDF, rejects a bad unit scale, drops non-canonical channels, resamples with `scipy.signal.resample_poly`, and appends each step to a provenance chain. The clips in the repo are designed. The TUH transfer was not run, and TUH is not in the repository.

**Encrypted cart.** [Hamsa](https://github.com/devasai-choppa/Hamsa) gives each browser device a non-exportable P-256 ECDH key. The shared secret goes through HKDF into an AES-256-GCM key. Each message has its own content key, with the conversation, message, and sender ids bound as additional data. Cart changes pass `verify_line`, which rejects an unknown SKU, a bad quantity, or stock the catalog does not have. The price is copied from `price_paise` on that catalog row. UPI is an intent to the merchant. The app does not hold the money.

**Classical ML, already measured.** [EEG motor imagery](https://github.com/devasai-choppa/EEG-Motor-Imagery-Classifier) trains on PhysioNet EEGMMIDB with MNE and PyTorch. The band is about 8–30 Hz. CSP + SVM is 47.7% on the same person. EEGNet is 32.2% leave-one-subject-out. Those are the numbers published in that README.

**Tools in the featured repos.** Python, SQL, DuckDB, pandas, dbt, LightGBM, LangGraph, Chroma, FastAPI, React, Next.js, Docker. Other imported libraries live in the public code and are not drawn on the orbit.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-orbit-dark.svg">
  <img src="assets/stack-orbit-light.svg" alt="Twelve tools from the featured repos orbit a DEVA mark: Python, SQL, DuckDB, pandas, dbt, LightGBM, LangGraph, Chroma, FastAPI, React, Next.js, Docker." width="600">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divider-datastream-dark.svg">
  <img src="assets/divider-datastream-light.svg" alt="" width="100%">
</picture>

## Research

**Crop Yield Forecasting and Fertilizer Recommendation Using Voting Classifier.** IJRTI, June 2023. Third author, with B. Chakradhar, D. Sai Veena, and A. Vivek, while at Lendi Institute of Engineering and Technology. [PDF](https://www.ijrti.org/papers/IJRTI2306158.pdf)

### Latest posts

<!--BLOG-POST-LIST-->
<!-- BLOG-POST-LIST:START -->
No public RSS feed is connected yet.
<!-- BLOG-POST-LIST:END -->

## Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="profile-3d-contrib/profile-hud-dark.svg">
  <img src="profile-3d-contrib/profile-hud-light.svg" alt="3D contribution skyline for devasai-choppa">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=devasai-choppa&show_icons=true&hide_border=true&title_color=00F5D4&text_color=C9D1D9&icon_color=F72585&bg_color=0D1117">
  <img src="https://github-readme-stats.vercel.app/api?username=devasai-choppa&show_icons=true&hide_border=true&title_color=0C7C78&text_color=0B1F33&icon_color=C2185B&bg_color=F4F7F8" alt="GitHub stats for devasai-choppa" height="165">
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=devasai-choppa&layout=compact&hide_border=true&langs_count=6&title_color=00F5D4&text_color=C9D1D9&icon_color=F72585&bg_color=0D1117">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=devasai-choppa&layout=compact&hide_border=true&langs_count=6&title_color=0C7C78&text_color=0B1F33&icon_color=C2185B&bg_color=F4F7F8" alt="Most used languages for devasai-choppa" height="165">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=devasai-choppa&hide_border=true&background=0D1117&stroke=0D1117&ring=00F5D4&fire=F72585&currStreakNum=E6EDF3&sideNums=E6EDF3&currStreakLabel=8B9BAB&sideLabels=8B9BAB&dates=5C6E7E">
  <img src="https://streak-stats.demolab.com?user=devasai-choppa&hide_border=true&background=F4F7F8&stroke=F4F7F8&ring=0C7C78&fire=C2185B&currStreakNum=0B1F33&sideNums=0B1F33&currStreakLabel=3E5568&sideLabels=3E5568&dates=6C8194" alt="GitHub contribution streak for devasai-choppa" height="150">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="dist/github-contribution-grid-snake-dark.svg">
  <img src="dist/github-contribution-grid-snake.svg" alt="Animated GitHub contribution snake for devasai-choppa">
</picture>

## Activity

<!--RECENT_ACTIVITY-->
<!--START_SECTION:activity-->
1. 💪 Opened PR [#1](https://github.com/devasai-choppa/AEON-7080/pull/1) in [devasai-choppa/AEON-7080](https://github.com/devasai-choppa/AEON-7080)
<!--END_SECTION:activity-->

## Open to Data and AI roles in Boston and remote

<a href="mailto:pranathesw@gmail.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/email-dark.svg">
    <img src="assets/email-light.svg" alt="Email pranathesw@gmail.com" width="189" height="28">
  </picture>
</a>
&nbsp;
<a href="https://www.linkedin.com/in/devasai-pranatheswar">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/linkedin-dark.svg">
    <img src="assets/linkedin-light.svg" alt="LinkedIn: linkedin.com/in/devasai-pranatheswar" width="96" height="28">
  </picture>
</a>
