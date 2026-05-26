# From a PL Guy to an AI Bro

Slides for a talk given at MSR India on May 27, 2026 by Ramneet Singh.

The talk covers two projects:

- **Code Researcher** — a deep-research-style agent that resolves crashes in
  the Linux kernel by analysing code and commit history.
- **VerusLM-4B-Codex** — an early effort on end-to-end verified code
  generation with Verus for Rust.

## Files

- [slides.html](slides.html) — the rendered deck (open in any modern browser).
- [slides.md](slides.md) — the source the slides were authored from.
- [images/](images/) — figures used in the deck.
- [code-researcher-paper/](code-researcher-paper/) — LaTeX source of the
  Code Researcher paper, included for reference.

## Viewing the slides

Open `slides.html` directly, or serve the folder locally:

```sh
python3 -m http.server 8000
# then open http://localhost:8000/slides.html
```

Navigate with `Space` / `→` / `←` (or `PageDown` / `PageUp`). `Home` and
`End` jump to the first and last slide; `F` toggles fullscreen.

## License

See [LICENSE](LICENSE).
