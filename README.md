# kodict_core

A Korean Dictionary bot for searching language and vocabulary information from Krdict and DeepL.

```
pip install kodict-core
```

## kodict_core

- fetch_all(text)
  - Searches National Institute of Korean Language's Korean-English Learners' Dictionary (한국어기초사전)
  - Uses API for Hangul/Hanja and Scraper for English
  - Searches DeepL Translate for fallback

<br />

## Services using kodict_core

- [`kodict-dpy`](https://github.com/coffeebank/kodict-dpy) - A Discord bot using `kodict_core` (GPL-3.0 License)
