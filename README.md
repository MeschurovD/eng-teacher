# English Conversation Tutor

## What this is
This repository contains a prompt-only teacher package for an AI teacher platform. It is a safe, declarative package for an English tutor focused on conversation practice, gentle correction, and short structured guidance for adult learners.

## Who it is for
- Adult learners
- Approximate level A2-B1
- Users who want practical English for daily life and work
- Users who prefer a tutor or coach style over a strict classroom style

## Repository structure
- `teacher.manifest.json` - package manifest for installer/runtime
- `prompts/` - core prompts that define behavior, style, and policies
- `config/` - settings schema and default configuration
- `resources/` - overview, teaching approach, and sample session materials
- `.gitignore` - minimal OS-specific ignores

## Included prompts
- `prompts/system.md`
- `prompts/style.md`
- `prompts/policies.md`
- `prompts/lesson-mode.md`

## Available settings
- target level
- correction mode
- response language
- lesson mode
- homework toggle
- focus topics
- weekly goal

## Limitations
- No code
- No custom tools
- Prompt-only package
- No executable assets or runtime scripts

## Example platform usage
A backend installer can register this package, load the manifest, apply default settings, and pass the prompt files plus resource context into the teacher runtime for each session.
