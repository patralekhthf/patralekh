# PatraLekh

**Tailor your resume to any job, on your own machine.**

PatraLekh is a free desktop app that rewrites your resume and cover letter for a
specific job description using AI. It runs entirely on your computer and talks
directly to the AI provider you choose with **your own API key** — your resume,
your documents, and your job descriptions never pass through anyone else's
servers.

> The name *PatraLekh* (पत्रलेख) means "letter-writer" — *patra* (letter/document)
> + *lekh* (writing).

---

## Download

Grab the latest build for your system from the
**[Releases page](../../releases/latest)**:

| Your computer | File |
|---|---|
| Mac (Apple Silicon — M1/M2/M3/M4) | `PatraLekh-vX.Y.Z-macos-arm64.zip` |
| Mac (Intel) | `PatraLekh-vX.Y.Z-macos-intel.zip` |
| Windows | `PatraLekh-vX.Y.Z-windows.zip` |
| Linux | `PatraLekh-vX.Y.Z-linux.zip` |

Unzip it and double-click **PatraLekh**. Your browser opens automatically at
`http://localhost:8080`.

**First launch:**
- **macOS** may say the developer "cannot be verified" — right-click the app,
  choose **Open**, then **Open** again. One time only.
- **Windows** SmartScreen may warn — click **More info → Run anyway**. One time
  only.

---

## Setup (about 5 minutes, once)

Open **Settings** in the app:

1. **API Keys** — paste your own key from
   [Anthropic](https://console.anthropic.com),
   [Google Gemini](https://aistudio.google.com/app/apikey), or OpenAI. Click
   **Test** to confirm it works. You pay the provider directly for what you use.
2. **Knowledge Base** — copy the provided prompt, paste it into Claude or ChatGPT
   along with your existing resumes and career documents, and upload the
   `KNOWLEDGE_BASE.md` it produces. This is what PatraLekh knows about you.
3. **System** — click **Download & install** next to Pandoc to enable Word
   (`.docx`) output (no admin rights needed), and pick where generated resumes
   are saved.
4. **Rules** *(optional)* — add any personal rules, e.g. "always include my
   portfolio link".

Then paste a job description on the home page and click **Generate**.

---

## What you need

- **An API key** from Anthropic, Google, or OpenAI (you create and pay for this).
- That's it. No Go, no Python, no install wizard — PatraLekh is a single
  self-contained app. Pandoc (for Word output) installs from inside the app.

## Privacy

Everything stays on your computer. Your keys, knowledge base, and history live
in a local app-data folder and are sent only to the AI provider you pick, only
when you generate a resume.

---

*PatraLekh is free to download and use. You are responsible for your own AI
provider costs.*
