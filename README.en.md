<p align="center"><img src="assets/koko.png" width="112" alt="koko, the white-haired book-holding mascot" /></p>

<h1 align="center">PaperPair</h1>

<p align="center"><strong>Read research papers like bilingual subtitles.</strong><br />One translated line, followed by its matching original.</p>

<p align="center"><a href="README.md">中文</a> · <a href="examples/bilingual-reading-zh-en.pdf">Sample PDF</a> · <a href="https://afdian.com/a/paperpair">koko on Afdian</a></p>

PaperPair is a desktop reader for bilingual research papers. Import a text-based PDF, translate it with your own agent or an OpenAI-compatible API, and read corresponding source and translated lines together. Keep your reading copy in a local bookshelf or export a separate PDF with selectable text.

**This is the public product overview and sample repository. Public application downloads are not available yet. The application source remains private while release preparation continues.**

## What it does

- Pairs one translated line with its corresponding original line, with either language on top.
- Organizes reading by sentence or paragraph while retaining paired physical lines in both modes.
- Offers an external local-agent workflow through **Copy Prompt**, or API-based translation through **Run Instruction**.
- Provides 17 target-language choices, a saved default, and editable instructions.
- Includes chapter navigation, paired translated headings when available, and an adjustable contents panel.
- Saves translations, manual corrections and reading position in a local bookshelf.
- Offers six reading themes plus font-size, spacing and reading-width controls.
- Preserves extracted visual material and recognized display equations, and exports a new reading PDF.
- Provides optional Zotero integration to open a paper and save the bilingual PDF as a new attachment.

Windows and macOS preview versions use an English interface. Target languages are independent of the interface language.

## Real export example

<p>
  <a href="assets/bilingual-reading.png"><img src="assets/bilingual-reading.png" width="49%" alt="Chinese-English paired text from an actual PaperPair PDF export" /></a>
  <a href="assets/figures-and-equations.png"><img src="assets/figures-and-equations.png" width="49%" alt="Preserved synthetic illustration and equation in the exported PDF" /></a>
</p>

[Bilingual PDF](examples/bilingual-reading-zh-en.pdf) · [Source PDF](examples/synthetic-source-en.pdf) · [Sample provenance](examples/README.md)

The sample uses a deliberately synthetic document and manually supplied translations. It demonstrates actual PDF-engine output, not a real study or evidence of model translation quality. These are PDF pages, not desktop screenshots.

## Bring your own AI

**Copy Prompt** prepares a paper-specific task for an agent with local file access. It does not start an AI by itself. This workflow does not require a PaperPair API key, but it does require a suitable agent and permissions. A remote chatbot cannot directly access or update a local bookshelf without an explicit file-transfer workflow.

Alternatively, configure your endpoint, model and key in **API Settings**, then use **Run Instruction**. AI accounts, subscriptions and API usage are supplied by the user.

## Current scope

Text-based PDFs are the primary input. OCR and Word import are not integrated. Complex columns, inline equations, unusual fonts and mixed text/graphics can require comparison with the original. Text inside images is not automatically translated. Use **Original Pages** to compare and **PDF Preview** to inspect the final export.

The original PDF is preserved. Working copies are local, with no automatic cloud sync. Cloud translation sends relevant content to the provider you select.

## Creator and updates

PaperPair is made under the creator identity **koko**. This repository and [koko's Afdian page](https://afdian.com/a/paperpair) are project information and update channels. Suggestions and reproducible problems are welcome in [Issues](https://github.com/wangyuer1-lang/PaperPair-public/issues).

koko is a fictional brand character; the mascot artwork was created with AI assistance. The project plans to open its source later, with timing and licensing to be announced. This overview repository is not an application source release and does not grant an application source-code license.

Updated: 2026-10-26.
