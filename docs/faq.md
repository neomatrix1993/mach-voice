# Mach frequently asked questions

## What is Mach?

Mach is a native Mac app for dictation and live translation. Dictation turns
your voice into text in the focused app. Live Translate turns selected Mac
audio into readable translation while it plays.

## Which macOS version does Mach require?

Mach dictation requires macOS 14 or later. Live Translate requires macOS 14.2
or later because it uses macOS System Audio Recording.

## Does Mach need the internet?

Yes. Speech recognition, Refined cleanup, and Live Translate use online
services. Mach is not an offline, on-device-only product.

## Does Mach work in every app?

Mach works in most Mac apps with an editable text field. Accessibility
permission is required for automatic text insertion. Password fields and some
specialized or non-editable controls can block automatic insertion.

## What is the difference between Refined and Verbatim?

Refined removes filler, repairs punctuation and grammar, applies formatting,
and uses your tone, dictionary, language, and writing-system preferences while
aiming to preserve your meaning.

Verbatim, labeled **Pure STT (verbatim)** in some app versions, returns the
speech-recognition result without AI cleanup.

## Does Refined mode answer questions or follow commands?

Refined mode is dictation, not a general assistant. It cleans and presents the
words you supplied. A spoken request should remain a request rather than being
answered or expanded with invented information.

## Can I switch languages inside one sentence?

Yes. Multilingual mode preserves natural code-switching between English,
Spanish, French, German, Hindi, Russian, Portuguese, Japanese, Italian, and
Dutch. For other languages, select one focused language per dictation.

## Can Mach write Hindi or Japanese with Latin letters?

Yes, where **Writing style** is available. Hindi can use Hinglish, Japanese can
use Romaji, and other supported scripts can offer Latin output. Romanization
applies during Refined cleanup and changes the script rather than the meaning.

## Why does dictation need Microphone and Accessibility access?

Microphone access lets Mach capture your voice while dictation is active.
Accessibility access lets Mach insert the finished text into the focused app.
You can revoke either permission in macOS System Settings.

## Does Live Translate use my microphone?

No. Live Translate captures the Mac audio source shown in its controls. It uses
macOS System Audio Recording permission and does not use the microphone for the
translation stream.

## Does Live Translate join my meeting?

No. It works beside the call or media already playing on your Mac. It does not
join as a meeting bot.

## What happens when a Live Translate limit is reached?

Mach keeps a clear explanation visible. Use **Request more time** in the Live
Translate window to contact support through your signed-in account. Current
allowances and fair-use terms are published on the
[pricing page](https://usemach.app/pricing) and in the
[Fair Use Policy](https://usemach.app/terms#fair-use).

## What counts toward dictation usage?

Successful dictated output counts toward usage. Failed, empty, cancelled, and
timed-out dictations should not count. Check [Mach pricing](https://usemach.app/pricing)
for current plan allowances.

## Do I need an account?

Yes. Your Mach account keeps app access, usage, and plan status in sync.

## How do automatic updates work?

Mach normally checks for updates about once per day. Available updates can
download in the background and install when Mach quits. Choose **Check for
Updates…** in Mach for an immediate, visible check.

## What belongs in the custom dictionary?

Add names, product spellings, abbreviations, and specialist terms that are
repeatedly written incorrectly. Use one canonical spelling. Dictionary guidance
is applied during Refined cleanup and does not retrain speech recognition.

## Does Mach retain my dictated content?

Mach is designed not to store raw audio or transcript text in backend analytics
by default. Service providers process content as needed to deliver speech
recognition, refinement, and translation. Read the controlling
[Mach Privacy Policy](https://usemach.app/privacy) for current details.

## Where can I get help?

Start with the [troubleshooting index](troubleshooting/README.md). For product,
account, or privacy help, visit [Mach Support](https://usemach.app/support).
Report suspected vulnerabilities privately as described in
[SECURITY.md](../SECURITY.md).
