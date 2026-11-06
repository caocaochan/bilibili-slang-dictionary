# Bilibili Slang Dictionaries

Chinese–English slang, memes, fandom terms, and other useful expressions found in Bilibili comments.

## BOOX built-in dictionary

Download [`bilibili_slang_boox.zip`](bilibili_slang_boox.zip) and extract it into the device's `Storage/dicts/` folder. The archive contains a `Bilibili Slang` folder with PyGlossary-generated `.ifo`, `.idx`, `.dict.dz`, and `.syn` files. In the BOOX dictionary app, select the dictionary under **Preferred Dictionary**. If it does not appear immediately, restart the dictionary app or reboot the device.

## Yomitan

Download [`bilibili_slang.zip`](bilibili_slang.zip) and import it from Yomitan's **Dictionaries** settings.

For automatic updates, add this stable dictionary index URL in Yomitan:
`https://raw.githubusercontent.com/caocaochan/bilibili-slang-dictionary/main/index.json`
The index points to the ZIP attached to the latest GitHub release, so the URL
does not change between releases.

## MDict-compatible apps

Download [`bilibili_slang.mdx`](bilibili_slang.mdx) and add it to an MDict-compatible dictionary app. MDX is not for the BOOX built-in dictionary; use the StarDict BOOX package above for NeoReader.

## Contents

- 18,950 dictionary terms with tone-marked readings and concise English definitions, including 82 curated terms from Chinese web novels and external glossaries
- Simplified and traditional lookup forms
- No per-word frequency ranks or metadata
- BOOX package: PyGlossary StarDict output with dictzip-compressed definitions and synonyms
- MDict package: MDX 2.0, 30,827 Simplified and Traditional headwords
- Yomitan package: dictionary format 3

The original candidates were selected from a Bilibili comment corpus and filtered against large Chinese dictionaries. This release also includes 82 useful terms curated from a Chinese web-novel corpus and external slang, gaming, ACGN, and web-novel glossaries. Example comments informed the original Bilibili definitions; source examples are not included in the dictionary. No word-frequency ranks or metadata are included. Some obscure names and ambiguous expressions were skipped; a few pinyin or gloss choices may still need correction.

## Files

- `bilibili_slang_boox.zip` — extract under `Storage/dicts/` for BOOX
- `bilibili_slang.mdx` — load in an MDict-compatible app
- `bilibili_slang.zip` — import this file into Yomitan
- `index.json` — stable Yomitan update index; use its raw GitHub URL above
- `README.md` — project and installation notes

No license is specified for reuse.
