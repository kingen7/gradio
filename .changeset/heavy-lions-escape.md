---
"@gradio/markdown-code": patch
"@gradio/chatbot": patch
---

fix: Preserve custom tags containing underscores (e.g. `<tool_call>`) when `allow_tags=True` in `gr.Chatbot`
