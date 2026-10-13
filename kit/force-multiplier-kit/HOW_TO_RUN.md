# HOW TO RUN IT
Same 3 files + same prompt. Different boxes.

---

## Every tool, same order

1. New chat / project / gem / workspace
2. Upload your 3 files
3. Paste one prompt from `OPERATOR_PROMPTS.md`
4. Paste the new job
5. Read GAPS before you trust the artifact

---

## Where the files go

| Tool | Files | Prompt |
|---|---|---|
| ChatGPT | Project files, or attach on the message | Project instructions, or first message |
| Claude | Project knowledge | Project instructions, or first message |
| Gemini | Gem knowledge | Gem instructions |
| Grok | Attach on the message | Custom instructions, or first message |
| Cursor / Claude Code | A folder in the repo | Rule file or first message |
| Local model (LM Studio, Ollama, Open WebUI) | RAG folder or pasted context | System prompt |

Custom GPTs are a wrapper. Wrappers change. Your files do not.

---

## If the tool only takes one upload

Put the three files in a zip, or paste the two smaller ones into the chat and attach the workbook.

---

## After the first job

If the model did something you would never send:

- That rule lives only in your head. Type it once into the chat, or add it to your notes file and re-upload.
- Do not add poetry to the prompt. Add the missing file content.

If the model copied your layout and asked the right gap question, it is working.
