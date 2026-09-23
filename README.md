# ThinkLab

Compare DeepSeek V4.1 outputs across four reasoning modes side by side.

## What it does

Send one prompt to DeepSeek in default, low, high, and max thinking modes at the same time. Each response renders in its own card with the response time, prompt tokens, and completion tokens displayed at the top. Markdown and LaTeX are rendered cleanly.

## How to run

1. Clone this repo or download index.html
2. Open index.html in any modern browser
3. Click the gear icon and paste your DeepSeek API key
4. Write a prompt or pick a preset, select modes, click Run comparison

The API key is stored only in your browser localStorage and sent only to api.deepseek.com.

## Built with

- Vanilla HTML, CSS, JavaScript
- DeepSeek chat completions API
- marked.js for markdown rendering
- KaTeX for LaTeX rendering
- OpenCode as the build tool
