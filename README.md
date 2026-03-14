# 🛠️ CRAFT Prompt Builder
A lightweight, fully offline HTML tool that helps you write better prompts for any Large Language Model (LLM) — ChatGPT, Claude, Gemini, Mistral, and more — using the CRAFT framework.
No installation. No API keys. No backend. Just open the HTML file in your browser and start building.

What is the CRAFT Framework?
CRAFT is a structured prompt-writing methodology that breaks a prompt into five focused dimensions:
LetterDimensionPurposeCContextBackground, situation, constraints, and relevant dataRRoleThe persona and expertise the AI should adoptAActionThe precise task and deliverable you needFFormatHow the output should be structuredTToneThe voice, energy, and style of the response
By filling in each dimension intentionally, you give the LLM everything it needs to produce expert-level, targeted output — instead of vague, generic answers.

How It Works

Fill in the five CRAFT fields — guided placeholders walk you through each one
Pick a Format from presets (Numbered List, Table, Report, Action Plan, Email, JSON, etc.) or describe your own
Select Tone chips — stack multiple tones like Analytical + Direct + Strategic
Click Generate Prompt (or press ⌘ + Enter)
Copy the generated prompt and paste it into any LLM

The built-in prompt engine reads your inputs, detects your domain (product, engineering, marketing, finance, etc.), and assembles a rich, structured prompt complete with role authority framing, context enrichment, task clarity, quality guardrails, and a smart closing call-to-action.

Features

✅ 100% offline — single HTML file, no server, no API, no dependencies to install
⚡ Instant generation — prompt builds and renders with a typewriter animation
🧠 Intelligent domain detection — auto-detects your industry from the context and adds relevant framing
🎯 Quality guardrails — automatically injects professional constraints like "back claims with reasoning" and "avoid generic advice"
📋 One-click copy — copy the full generated prompt to your clipboard
🎨 Format presets — 10 common output formats to pick from
🎭 Multi-tone stacking — combine tones for blended, precise voice instructions
⌨️ Keyboard shortcut — Cmd/Ctrl + Enter to generate
📱 Responsive — works on desktop and mobile browsers


Getting Started
bash# Clone the repo
git clone https://github.com/ABHASGUP/craft-prompt-builder.git

# Open in your browser — that's it
open craft-prompt-builder.html
Or just download the HTML file directly and open it. No build step. No npm install. No setup.

Example Output
Given inputs like:

Context: "PM at a Series B fintech startup, receipt scanning feature at 12% adoption vs 40% target..."
Role: "Senior growth PM with 12 years in B2B SaaS, ex-Stripe, ex-Notion..."
Action: "Analyze root causes and create a 30-day activation improvement plan..."
Format: Action Plan
Tone: Analytical + Strategic + Direct

The tool generates a complete, structured prompt with labeled sections — Role, Context, Task, Quality Standards, Tone, and a closing call-to-action — that you paste directly into any LLM and get a detailed, expert response.

Who Is This For?

Product Managers writing prompts for strategy, research, and prioritization
Marketers generating campaign briefs, copy, and positioning prompts
Developers structuring technical analysis and code review prompts
Founders drafting investor narratives, GTM plans, and hiring docs
Analysts building research and data interpretation prompts
Anyone who wants more accurate, useful answers from AI tools


Tech Stack

Pure HTML + CSS + Vanilla JavaScript
No frameworks, no libraries, no build tools
Google Fonts (Syne, Outfit, JetBrains Mono) loaded via CDN — works offline if fonts are cached


License
MIT — free to use, modify, and distribute.

Built with the CRAFT framework in mind — because better prompts lead to better answers.
