# EZR と RStudio の実行環境・standalone 版 / EZR and RStudio runtime environment, standalone edition

[EZR](https://www.jichi.ac.jp/usr/hema/EZR/statmed.html) をブラウザーの中の RStudio から使う実行環境です。ほかのアプリを入れずに使えます。使う R の版の Release から Zip を落とし、展開して中の手順書（`HOW_TO_USE_Mac.html`・`HOW_TO_USE_Windows.html`）を見てください。

> この環境は、EZR の開発元とは関係の無い、非公式の配布環境です。EZR の開発元が作ったり、確かめたり、勧めたりしたものではありません。この環境についての問い合わせは、EZR の開発元には送らず、この環境を配った人に送ってください。

A runtime environment for using [EZR](https://www.jichi.ac.jp/usr/hema/EZR/statmed.html) from RStudio in your browser. You install no other app. Download the Zip from the Release for your R version, extract it, and follow the guide inside (`HOW_TO_USE_Mac.html` or `HOW_TO_USE_Windows.html`).

> This environment is an unofficial distribution and is not affiliated with the developer of EZR. It was not made, checked or endorsed by the EZR developer. Please send questions about this environment to the person who gave it to you, not to the EZR developer.

- R 4.5.3: [r453-v0.1.0](https://github.com/keiimai/ezr_standalone_release/releases/tag/r453-v0.1.0)
- R 4.6.1: [r461-v0.1.0](https://github.com/keiimai/ezr_standalone_release/releases/tag/r461-v0.1.0)

| R | 日本語版 / Japanese | 英語版 / English |
|---|---|---|
| 4.5.3 | [ezr_standalone_r453_jp](https://github.com/keiimai/ezr_standalone_r453_jp) | [ezr_standalone_r453_en](https://github.com/keiimai/ezr_standalone_r453_en) |
| 4.6.1 | [ezr_standalone_r461_jp](https://github.com/keiimai/ezr_standalone_r461_jp) | [ezr_standalone_r461_en](https://github.com/keiimai/ezr_standalone_r461_en) |

## AI の使用 / Use of AI

デモ動画は、AI を道具として使って作りました。台本・字幕・画面の録画と編集は Anthropic の [Claude Opus 5.5](https://www.anthropic.com/claude/opus)（[Claude Code](https://code.claude.com/docs/en/overview) で使用）、ナレーションの音声は Google の [Gemini](https://ai.google.dev/gemini-api/docs/speech-generation)（`gemini-3.8-flash-tts`）で作り、ナレーションと場面の時刻合わせと音声の確認には `gemini-3.5-flash` を使いました。画面は、実際に操作して録ったものです（RStudio と EZR の画面の一部は、コンテナから先が同じ Docker Desktop 版の環境で録った画面を使いました）。

The demo videos were made with AI as a tool. The script, subtitles, screen recording and editing were done with [Claude Opus 5.5](https://www.anthropic.com/claude/opus) by Anthropic (used through [Claude Code](https://code.claude.com/docs/en/overview)), the narration voice was generated with Google's [Gemini](https://ai.google.dev/gemini-api/docs/speech-generation) (`gemini-3.8-flash-tts`), and `gemini-3.5-flash` was used to align the narration with the scenes and to check the audio. The screens were recorded by actually operating the environment (some RStudio and EZR screens were recorded with the Docker Desktop edition, which is the same from the container on).
