codex "
Analyze this repository and explain WHY it consumes a lot of tokens when you work on it.

Focus ONLY on:
- which files are opened most often
- cross-file dependencies (what imports what)
- entry points (routes, handlers, services)
- large or mixed-responsibility files
- repeated patterns across files

Output:

1. Top 5 reasons this repo causes high token usage
2. Specific files or folders responsible
3. Example flow (e.g. route → service → db → utils) showing token expansion
4. What should be precomputed or summarized to reduce tokens

Be concrete. Reference actual file paths.
Do NOT rewrite code.
"
