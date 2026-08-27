# Mach features

Mach combines native Mac dictation with live translation. It is designed to
keep you in the app where you are already writing, listening, or working.

For current plans and availability, visit [usemach.app](https://usemach.app).

## Dictation in Mac apps

Place the cursor in an editable text field, hold `Fn`, speak, and release. Mach
returns the finished text to the app you were using. Use `Fn + Space` when you
want to dictate hands-free.

Mach works in most Mac apps with editable text fields. Password fields and some
specialized controls can prevent automatic text insertion.

## Refined and Verbatim output

- **Refined** removes fillers, repairs punctuation and grammar, applies useful
  structure, and adapts the result to your settings and current app.
- **Verbatim**, shown as **Pure STT (verbatim)** in some versions of the app,
  keeps the output close to the speech-recognition result without AI cleanup.

Refined mode is still dictation. It is intended to preserve your meaning rather
than answer questions or invent information.

## Shortcuts and feedback

- Hold `Fn` for push-to-talk dictation.
- Press `Fn + Space` to start or stop hands-free dictation.
- Double-tap the push-to-talk shortcut to keep a session open hands-free.
- Press `Esc` to cancel without inserting text.
- Customize both shortcuts in Dictation Settings.
- Choose whether Mach plays sound feedback or shows the dictation overlay.

## Languages and writing systems

Mach offers 87 language and regional dictation options. Choose a focused
language for the most predictable single-language result.

Multilingual mode supports natural code-switching between English, Spanish,
French, German, Hindi, Russian, Portuguese, Japanese, Italian, and Dutch. Mach
preserves each language instead of intentionally translating the whole
dictation into one language.

Where available, Refined mode can write selected languages with Latin letters.
Examples include Hindi as Hinglish and Japanese as Romaji. Romanization changes
the writing system, not the language or meaning.

## Personalization

- **Tone:** choose Auto, Casual, Professional, or Neutral.
- **Custom dictionary:** add names, products, abbreviations, and specialist
  terms with their preferred spelling.
- **Input device:** select the microphone you want Mach to use.
- **App context:** let Refined output adapt its structure and tone to the app
  where the text will appear.

## Live Translate

Live Translate turns audio playing on your Mac into readable translation while
the conversation or media continues. It can help with:

- meetings and calls;
- interviews and research;
- videos, radio, podcasts, and live streams;
- lectures, workshops, and training; and
- customer support and formal appointments.

Each completed phrase stays paired with its translation in a scrollable series
of cards. You can choose automatic source detection, select a target language,
and hide the original captions when you only want to read the translation.

Live Translate captures the Mac audio source you select. It does not use your
microphone for the translation stream. Read the [Live Translate guide](docs/live-translate.md)
for setup and privacy details.

## Privacy and control

Mach processes audio only after you start dictation or Live Translate. Both
features provide explicit ways to start, finish, or cancel a session. You can
revoke macOS permissions at any time, although the related feature will stop
working.

Read the [privacy overview](docs/privacy.md) and the controlling
[Mach Privacy Policy](https://usemach.app/privacy).

## Requirements

- macOS 14 or later for Mach dictation
- macOS 14.2 or later for Live Translate
- An internet connection
- Microphone and Accessibility access for dictation
- macOS System Audio Recording access for Live Translate

See the [installation guide](docs/installation.md) to get started.

## See Mach in practice

- [Dictation examples](docs/examples.md)
- [Common use cases](docs/use-cases.md)
- [Supported languages](docs/languages.md)
- [Frequently asked questions](docs/faq.md)
- [Troubleshooting](docs/troubleshooting/README.md)
