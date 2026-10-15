# Afterclass — 你的英语练习室

A bilingual English practice site for a ninth-grade student in the United States. Static HTML/CSS/JavaScript, no build step or API key.

## Features
- 6 original themes × 6 skills = 36 lessons; vocabulary, grammar, reading, listening, speaking, writing.
- Two approximately 25-minute practice groups per theme.
- Multiple-choice feedback with Chinese explanations and a latest-attempt mistake notebook.
- Device English text-to-speech, speaking timer, optional local recording and self-checks.
- Auto-saved writing drafts and transparent rule-based structure hints, not AI grading.
- Browser-local progress, validated JSON export/import with latest-record merge and history deduplication.
- Responsive desktop/mobile layout and keyboard-accessible controls.

## Run
From this directory:

```sh
python3 -m http.server 8080 --bind 0.0.0.0
```

Open `http://localhost:8080`. Microphone recording requires HTTPS or localhost and browser permission. Speech voice availability depends on the device. Recordings remain in memory and are not part of backups.

## GitHub Pages
Publish the `main` branch, root folder, from Settings → Pages. The published index.html is a self-contained bundle with CSS, JavaScript and the font embedded; it works under a project Pages URL.

## Tencent CloudStudio
Import this repository or upload these files to an HTML-CSS-JS application. Run the server command above, expose port 8080 through CloudStudio's preview interface, and use its application sharing/publishing controls. CloudStudio account access is required; preview availability can depend on the workspace remaining active.

## Data
Progress is saved only under the current origin in localStorage. Changing the host, browser, device, or clearing site data does not migrate progress automatically. Use **备份与设置 → 下载 JSON 备份**, then import on the destination site. Backups include drafts and notes; treat them as personal files. No learning data is committed to this repository.

## Learning limits
A2–B2 labels describe approximate content progression, not a standardized placement test. Completion is practice completion, not proficiency certification. Listening uses synthesized speech. Writing checks count words, punctuation and connectors; they do not evaluate truth, argument quality or grammatical correctness. Original lesson scenarios and sample responses are practice materials, not sourced research claims or work to submit as school assignments.

## Font
Source Serif 4 is bundled under the SIL Open Font License; see `FONT-LICENSE.txt`.
