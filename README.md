<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Devasai Pranatheswar Choppa, Data Analyst at NextGenTek USA, Boston. Healthcare data and applied AI." width="100%">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/typing-dark.svg">
  <img src="assets/typing-light.svg" alt="Building clinical AI agents. Turning messy health data into decisions. Data Analyst to AI Engineer." width="640">
</picture>

Data Analyst at NextGenTek USA · Boston  
MS Analytics (Applied Machine Intelligence), Northeastern · B.Tech CS, Lendi / JNTU

<a href="mailto:pranathesw@gmail.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/email-dark.svg">
    <img src="assets/email-light.svg" alt="Email pranathesw@gmail.com" height="32">
  </picture>
</a>
&nbsp;
<a href="https://www.linkedin.com/in/devasai-pranatheswar">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/linkedin-dark.svg">
    <img src="assets/linkedin-light.svg" alt="LinkedIn: linkedin.com/in/devasai-pranatheswar" height="32">
  </picture>
</a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divider-dark.svg">
  <img src="assets/divider-light.svg" alt="" width="100%">
</picture>

## What I build

- Clinical agents that answer from a protocol, score the draft, and flag a person when the source does not support the claim.
- Genomics and neuro-data tools that keep an evidence trail: ACMG triage, EEG conversion, and neural-privacy audits.
- Analytics pipelines that score a delayed hospital discharge and show a placement step a person can approve.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divider-dark.svg">
  <img src="assets/divider-light.svg" alt="" width="100%">
</picture>

## Featured work

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/TechieGoku2623/Sentinal_RAG">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/cards/sentinel-rag-dark.svg">
    <img src="assets/cards/sentinel-rag-light.svg" alt="Sentinel-RAG. Guideline answers that flag a clinician instead of guessing. Stack: LangGraph, Chroma, FastAPI.">
  </picture>
</a>

**Problem.** A fluent answer about a dose can still be wrong.

**Approach.** A LangGraph loop retrieves the clinic's own guidelines from Chroma, drafts with Groq, and scores grounding in code.

**Result.** High confidence is returned. Medium confidence widens the retrieval and retries. Low confidence is marked FLAG for a clinician. The bundled corpus is a fictional diabetes guideline.

[▶ Demo](https://github.com/TechieGoku2623/Sentinal_RAG/blob/main/sentinel-rag/docs/demo.gif) · [📐 Architecture](https://github.com/TechieGoku2623/Sentinal_RAG/blob/main/sentinel-rag/docs/ARCHITECTURE.md) · [📄 README](https://github.com/TechieGoku2623/Sentinal_RAG/blob/main/sentinel-rag/README.md)

</td>
<td width="50%" valign="top">

<a href="https://github.com/TechieGoku2623/Clear-Bed">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/cards/clearbed-dark.svg">
    <img src="assets/cards/clearbed-light.svg" alt="ClearBed. Who is still in a bed after they are medically ready to leave. Stack: dbt, DuckDB, LightGBM.">
  </picture>
</a>

**Problem.** A patient can be medically ready to leave and still occupy a staffed bed.

**Approach.** DuckDB and dbt build the stay. LightGBM plus SHAP score stuck-risk. A LangGraph agent matches CMS nursing homes and waits for a person to approve anything that would leave the building.

**Result.** The walkthrough is a Boston census against the national CMS Care Compare file. Patients in the demo are synthetic. This is not a medical device.

[▶ Demo](https://github.com/TechieGoku2623/Clear-Bed/blob/main/docs/walkthrough.gif) · [📐 Architecture](https://github.com/TechieGoku2623/Clear-Bed#architecture) · [📄 README](https://github.com/TechieGoku2623/Clear-Bed)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/TechieGoku2623/acmg-triage">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/cards/acmg-triage-dark.svg">
    <img src="assets/cards/acmg-triage-light.svg" alt="acmg-triage. An ACMG/AMP call with a trail, including a refusal. Stack: Python, FastAPI, DuckDB.">
  </picture>
</a>

**Problem.** A variant of uncertain significance needs a classification a reviewer can retrace, including a refusal.

**Approach.** A typed graph runs one node per ACMG/AMP code, applies a VCEP overlay, and reads literature only from a committed cache.

**Result.** On 100 designed probes, concordance with the rules-only baseline is 0.670. Turning the literature path on does not change that number. Conflicting and uncovered variants are refused.

[▶ Demo](https://github.com/TechieGoku2623/acmg-triage/blob/main/demo/out/acmg-triage-demo.gif) · [📐 Architecture](https://github.com/TechieGoku2623/acmg-triage/blob/main/src/acmg_triage/graph.py) · [📄 README](https://github.com/TechieGoku2623/acmg-triage)

</td>
<td width="50%" valign="top">

<a href="https://github.com/TechieGoku2623/neuroprivacy">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/cards/neuroprivacy-dark.svg">
    <img src="assets/cards/neuroprivacy-light.svg" alt="neuroprivacy. Consumer neural-data policies scored against two state laws. Stack: Python, Pydantic, rules.">
  </picture>
</a>

**Problem.** A consumer neural-data policy is hard to compare with a state statute line by line.

**Approach.** The extractor pulls span-cited fields from policy HTML and scores them with deterministic rules for Colorado HB24-1058 and California SB 1223.

**Result.** Mean field F1 is 1.000 against 20 hand-labeled sample policies. The live public-policy hold-out is still open. The output is not a legal opinion.

[▶ Demo](https://github.com/TechieGoku2623/neuroprivacy/blob/main/demo/out/neuroprivacy-demo.gif) · [📐 Architecture](https://github.com/TechieGoku2623/neuroprivacy/blob/main/src/neuroprivacy/scoring.py) · [📄 README](https://github.com/TechieGoku2623/neuroprivacy)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/TechieGoku2623/eeg-harmonize">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/cards/eeg-harmonize-dark.svg">
    <img src="assets/cards/eeg-harmonize-light.svg" alt="eeg-harmonize. One EEG schema, and a record of every conversion. Stack: NumPy, SciPy, EDF.">
  </picture>
</a>

**Problem.** The same EEG channel or annotation goes by different names across public corpora, so a conversion bug looks like a dataset effect.

**Approach.** A canonical record, unit checks, and an append-only provenance chain: read, check units, map channels, resample.

**Result.** Designed EDF clips convert, and a bad unit scale is rejected. The cross-dataset transfer matrix on TUH was not run. TUH is not in the repository.

[▶ Demo](https://github.com/TechieGoku2623/eeg-harmonize/blob/main/demo/out/eeg-harmonize-demo.gif) · [📐 Architecture](https://github.com/TechieGoku2623/eeg-harmonize/blob/main/src/eeg_harmonize/convert.py) · [📄 README](https://github.com/TechieGoku2623/eeg-harmonize)

</td>
<td width="50%" valign="top">

<a href="https://github.com/TechieGoku2623/Hamsa">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/cards/hamsa-dark.svg">
    <img src="assets/cards/hamsa-light.svg" alt="Hamsa. Indic shop orders inside an encrypted chat. Prices stay checked. Stack: FastAPI, React, WebCrypto.">
  </picture>
</a>

**Problem.** A shop order in Hindi or Tamil still has to become a cart, a price the model cannot invent, and a payment the app does not hold.

**Approach.** The browser encrypts chats with P-256 and AES-GCM. A FastAPI agent fills the cart, a verifier rejects invented prices, and UPI is an intent to the merchant.

**Result.** The local demo runs a guest order, an owner confirmation, and an encrypted chat. No user or revenue figures are claimed.

[▶ Demo](https://github.com/TechieGoku2623/Hamsa/blob/main/demo/hamsa-demo.gif) · [📐 Architecture](https://github.com/TechieGoku2623/Hamsa/blob/main/docs/architecture.md) · [📄 README](https://github.com/TechieGoku2623/Hamsa)

</td>
</tr>
</table>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divider-dark.svg">
  <img src="assets/divider-light.svg" alt="" width="100%">
</picture>

## Flagship: Sentinel-RAG

<details>
<summary>How the clinical protocol guardian decides to answer, retry, or flag</summary>

Sentinel-RAG answers only from guidelines the operator ingested, then scores the draft before anyone sees it. Research prototype. Not a medical device. Do not use it for a clinical decision.

```mermaid
flowchart LR
  retrieve["retrieve\nChroma top-k"] --> generate["generate\nGroq Llama 3.1 8B"]
  generate --> reflect["reflect\ndeterministic score"]
  reflect -->|"medium, retries left"| retrieve
  reflect -->|"high, or FLAG"| output["output"]
```

The compiled graph in `sentinel-rag/src/agent.py` has four nodes: `retrieve`, `generate`, `reflect`, `output`. FLAG is a decision inside `reflect`, written into the response by `output`. It is not a fifth node.

1. **Retrieve.** The query hits a local Chroma index of the ingested protocol documents.
2. **Generate.** The draft is written from those chunks. Live generation needs `GROQ_API_KEY`. The model pin in the repo is Llama 3.1 8B via Groq.
3. **Reflect.** Grounding is scored in code. Medium confidence widens retrieval and loops back to `retrieve`. High confidence, or a low score after retries, goes to `output`. A low score, a contradicted draft, or a query outside the corpus is marked FLAG for a clinician.

[▶ Watch the demo](https://github.com/TechieGoku2623/Sentinal_RAG/blob/main/sentinel-rag/docs/demo.gif) · [Full architecture](https://github.com/TechieGoku2623/Sentinal_RAG/blob/main/sentinel-rag/docs/ARCHITECTURE.md)

</details>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divider-dark.svg">
  <img src="assets/divider-light.svg" alt="" width="100%">
</picture>

## Tech stack

**Languages**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=py,ts&theme=dark">
  <img src="https://skillicons.dev/icons?i=py,ts" alt="Languages: Python and TypeScript" height="40">
</picture>

Python · TypeScript · SQL

**Data**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-data-dark.svg">
  <img src="assets/stack-data-light.svg" alt="Data tools: DuckDB, pandas, dbt, SQL" height="32">
</picture>

**ML and GenAI**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=sklearn&theme=dark">
  <img src="https://skillicons.dev/icons?i=sklearn" alt="scikit-learn" height="40">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-ml-dark.svg">
  <img src="assets/stack-ml-light.svg" alt="ML and GenAI tools: LightGBM, LangGraph, Chroma" height="32">
</picture>

**Cloud**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=docker&theme=dark">
  <img src="https://skillicons.dev/icons?i=docker" alt="Docker" height="40">
</picture>

**BI**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-bi-dark.svg">
  <img src="assets/stack-bi-light.svg" alt="BI: Streamlit" height="32">
</picture>

Streamlit is the dashboard in Sentinel-RAG and ClearBed.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divider-dark.svg">
  <img src="assets/divider-light.svg" alt="" width="100%">
</picture>

## Research and writing

**Crop Yield Forecasting and Fertilizer Recommendation Using Voting Classifier.** IJRTI, June 2023. Co-authored with B. Chakradhar, D. Sai Veena, and A. Vivek while at Lendi Institute of Engineering and Technology. [PDF](https://www.ijrti.org/papers/IJRTI2306158.pdf)

### Latest posts

<!--BLOG-POST-LIST-->
<!-- BLOG-POST-LIST:START -->
No public RSS feed is connected yet.
<!-- BLOG-POST-LIST:END -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divider-dark.svg">
  <img src="assets/divider-light.svg" alt="" width="100%">
</picture>

## Activity

<!--RECENT_ACTIVITY-->
<!--START_SECTION:activity-->
1. 💪 Opened PR [#1](https://github.com/TechieGoku2623/AEON-7080/pull/1) in [TechieGoku2623/AEON-7080](https://github.com/TechieGoku2623/AEON-7080)
<!--END_SECTION:activity-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=TechieGoku2623&show_icons=true&hide_border=true&title_color=E7EEF4&text_color=C5D0DA&icon_color=3CBBB4&bg_color=07131C">
  <img src="https://github-readme-stats.vercel.app/api?username=TechieGoku2623&show_icons=true&hide_border=true&title_color=0B1F33&text_color=334454&icon_color=0F6E6A&bg_color=F4F7F8" alt="GitHub stats for TechieGoku2623" height="165">
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=TechieGoku2623&layout=compact&hide_border=true&langs_count=6&title_color=E7EEF4&text_color=C5D0DA&icon_color=3CBBB4&bg_color=07131C">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TechieGoku2623&layout=compact&hide_border=true&langs_count=6&title_color=0B1F33&text_color=334454&icon_color=0F6E6A&bg_color=F4F7F8" alt="Most used languages for TechieGoku2623" height="165">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=TechieGoku2623&hide_border=true&background=07131C&stroke=07131C&ring=3CBBB4&fire=E3B15A&currStreakNum=E7EEF4&sideNums=E7EEF4&currStreakLabel=93A4B5&sideLabels=93A4B5&dates=6E8294">
  <img src="https://streak-stats.demolab.com?user=TechieGoku2623&hide_border=true&background=F4F7F8&stroke=F4F7F8&ring=0F6E6A&fire=C4841D&currStreakNum=0B1F33&sideNums=0B1F33&currStreakLabel=4E6272&sideLabels=4E6272&dates=7C8E9C" alt="GitHub contribution streak for TechieGoku2623" height="150">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="dist/github-contribution-grid-snake-dark.svg">
  <img src="dist/github-contribution-grid-snake.svg" alt="Animated GitHub contribution snake for TechieGoku2623">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divider-dark.svg">
  <img src="assets/divider-light.svg" alt="" width="100%">
</picture>

## Open to Data and AI roles in Boston and remote

<a href="mailto:pranathesw@gmail.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/email-dark.svg">
    <img src="assets/email-light.svg" alt="Email pranathesw@gmail.com" height="32">
  </picture>
</a>
&nbsp;
<a href="https://www.linkedin.com/in/devasai-pranatheswar">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/linkedin-dark.svg">
    <img src="assets/linkedin-light.svg" alt="LinkedIn: linkedin.com/in/devasai-pranatheswar" height="32">
  </picture>
</a>
