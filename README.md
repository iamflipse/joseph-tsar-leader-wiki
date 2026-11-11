# Communicate Like a Leader Wiki — Joseph Tsar's Full Training

A curated wiki distilling **Joseph Tsar**'s (@joseph_tsar_, Elite Speak) video *How To Communicate Like A Leader [Full Training]* ([X post](https://x.com/joseph_tsar_/status/2120562177765446076), 2026-11-11, ~25.5 min).

**Public copy:** https://iamflipse.github.io/joseph-tsar-leader-wiki/ (read-only; static build served from the `gh-pages` branch)

## Contents

- **7 concept pages**: Articulate Ascent, Speech Is a Sport, the three high-quality problems, Intention, Focus, Body & Breath, the two spiritual laws (Source, Release).
- **Practice**: a pre-speaking routine built only from the drills in the video, plus a key-quotes page with timestamps.
- **No full transcript** is published. This is the creator's content; pages summarise and quote briefly, and every page links to the original post.

## Layout

- `src/` — markdown source pages
- `book/` — mdbook-generated static site (committed for GitHub Pages)
- `tools/mdbook` — mdbook v0.4.21 binary (aarch64 Linux, built from source)

## Rebuild + republish

```sh
./tools/mdbook build -d book
git add -A && git commit -m "update" && git push origin main
# republish: recreate orphan gh-pages branch with book files at root + tools/mdbook, force push
```
