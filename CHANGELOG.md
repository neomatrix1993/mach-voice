# Changelog

Notable user-visible changes to the Mach macOS app are recorded here. Service,
website, plan, and pricing details can change separately; check
[usemach.app](https://usemach.app) for current information.

This project follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

## [1.1.2] - 2026-08-26

### Improved

- Kept the Live Translate limit explanation visible instead of returning to an
  empty conversation screen.
- Added an in-app request for more Live Translate time through the signed-in
  Mach account.
- Added an immediate retry path after an allowance resets or additional access
  is approved.

## [1.1.1] - 2026-08-25

### Improved

- Made Live Translate language and audio controls work reliably over full-screen
  apps on secondary displays.
- Replaced background processes and system helpers with a focused list of useful
  call, browser, and media audio sources.
- Added a visible close control for quickly hiding and reopening Live Translate.

## [1.1.0] - 2026-08-24

### Added

- Introduced Live Translate for meetings, calls, videos, radio, and other audio
  playing on your Mac.
- Added compact rolling cards that keep each original phrase paired with its
  translation.
- Added automatic source-language detection, searchable target-language
  selection, and the option to hide original captions.
- Added reliable Stop and Start controls for longer translation sessions.

## [1.0.7] - 2026-07-27

### Improved

- Made dictation startup clearer and faster while keeping connection attempts
  bounded and recoverable.
- Improved recovery after sleep, network changes, expired authorization, and
  stale connections.
- Added privacy-safe reliability diagnostics that exclude transcript and audio
  content.

## [1.0.6] - 2026-07-25

### Added

- Added 87 language and regional dictation options.
- Added Multilingual mode for natural code-switching across ten languages.
- Added optional Latin-script output for supported languages, including
  Hinglish and Romaji.

### Improved

- Preserved mixed-language speech during Refined cleanup and formatting.
