# Mach privacy overview

Mach is designed to process voice and selected Mac audio while minimizing
retained content. This page is a plain-language product overview, not the legal
privacy policy. The current, controlling policy is always published at
[usemach.app/privacy](https://usemach.app/privacy).

## What happens during audio processing

1. Mach captures audio only after you start dictation or Live Translate.
2. Dictation uses the microphone you selected. Live Translate uses the Mac
   audio source shown in its controls and does not use your microphone for the
   translation stream.
3. Audio is sent securely to Mach's backend and processing providers for
   transcription, selected refinement, or translation.
4. Dictation text is returned to the focused app. Live Translate displays paired
   original and translated phrases in the current session.

Mach uses a managed cloud workflow. Dictation and Live Translate are not
offline, on-device-only processes.

## What Mach retains

Mach stores the account and usage metadata needed to operate the service, enforce
usage limits, diagnose reliability, and keep account status in sync. Dictation
event records can include metadata such as timing, status, selected language,
mode, and word count.

Raw audio and transcript text are not stored in Mach backend analytics tables by
default. Service providers may process content as needed to deliver the service,
subject to their role in Mach's processing workflow.

## Other data Mach processes

Depending on the features you use, Mach may process account information, device
identifiers, authentication state, app preferences, usage counts, diagnostics,
and billing-related information.

Mach works with service providers for functions such as authentication, hosting,
network infrastructure, observability, speech recognition, and language-model
processing. The current Privacy Policy describes this processing in more detail.

## Security measures

Mach uses HTTPS for network traffic, production authentication, server-side usage
checks, and signed Mac app releases. No connected service can guarantee perfect
security; Mach's approach is to limit retained dictation content and keep
production access paths narrow.

See [SECURITY.md](../SECURITY.md) to report a suspected vulnerability privately.

## Your choices

You can stop dictation or Live Translate, sign out of Mach, or revoke permissions
such as Microphone, Accessibility, and System Audio Recording in **System
Settings → Privacy & Security**. Some features will stop working when their
required permissions are revoked.

For account deletion, privacy questions, or data requests, email
[hello@usemach.app](mailto:hello@usemach.app) from the address associated with
your Mach account.

## Learn more

- [Privacy Policy](https://usemach.app/privacy)
- [Terms of Service](https://usemach.app/terms)
- [Mach Support](https://usemach.app/support)
- [Mach website](https://usemach.app)
