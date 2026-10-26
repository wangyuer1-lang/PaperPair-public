# PaperPair quick start

[Project overview](../README.md) · [中文说明](quick-start.zh-CN.md)

This guide describes the current preview workflow. Public installer downloads are not available yet. Check the [project overview](../README.md) or [Afdian project page](https://afdian.com/a/paperpair) for release updates.

## 1. Import a paper

Open PaperPair and choose **Import PDF**. Prefer a PDF with selectable text. PaperPair creates a local reading copy and preserves the original file.

With the optional Zotero plugin, you can also choose **Open in PaperPair** from a paper attachment. Use a plugin that matches your operating system and PaperPair version.

## 2. Choose your language and AI workflow

In **Reading Agent**, choose **Translate into**. Use **Set default** to remember a language for new papers. You can still edit the reading instructions.

**Local agent:** Choose **Copy Prompt** and give the complete task to an agent with access to local files. It handles translation, alignment, layout review and submission back to PaperPair. This route needs no PaperPair API key. Copying the prompt does not launch an AI; wait for PaperPair to confirm that it received the result.

**API:** In **API Settings**, enter an OpenAI-compatible endpoint, model and your own API key. Choose **Run Instruction** to start. Any model charges come from your selected provider.

## 3. Adjust the reading layout

- **By sentence / By paragraph** organizes the flow; both modes keep each translated line adjacent to its original.
- **Line order** puts the translation or original first.
- **Contents** jumps to headings; drag its divider to adjust the width.
- **Theme** changes the reading palette.
- **Reading Layout** adjusts font sizes, line spacing, paragraph spacing and width.
- Select a translated line to revise it.

## 4. Review and save

Compare with **Original Pages**, especially for columns, equations, unusual symbols and mixed graphics. Regenerate **PDF Preview** after layout changes to inspect the actual exported result.

Use **Bookshelf** to resume a saved paper, **Save a Copy** to create a portable `.paperpair` document, or **Export PDF** for a separate bilingual reading PDF. With Zotero, **Save to Zotero** creates a new attachment.

OCR and Word import are not integrated. Text inside images is not automatically translated. Check important terminology, numbers and conclusions against the original.
