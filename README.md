# web-dataset-editor
A JSONL dataset editor.

This web editor has all code and styles(except fonts) embedded. Therefore, it can be run very easily. This was made pretty hastily for my satire dataset.

Features: 
  - Automatic newline (\n is not shown, but any newlines will be converted to \n)
  - Autosaving
  - Importing and exporting
  - More

This imports and exports in **prompt** and **completion** JSONL format. Prompt is the prompt(what the user says or asks), and completion is what the AI responds with.

The file loaded and exported is in [OpenAI messages format](https://developers.openai.com/api/reference/resources/beta/subresources/threads/subresources/messages/methods/create).
