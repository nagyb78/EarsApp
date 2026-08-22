# Privacy Policy — Ears

_Last updated: 22 August 2026_

Ears is a macOS application that records meetings and writes them up as notes,
together with a companion Chrome extension, **Ears for Meetings**. This policy
describes what each of them does with information.

## The Chrome extension

The extension runs only on Google Meet, Microsoft Teams and Zoom pages in the
browser.

**What it reads.** The participant names shown on the meeting page, and which
participant the page is currently highlighting as speaking. It also detects when
a call starts and ends.

**Where that goes.** To `http://localhost:8756` — the Ears application running
on the same computer. That is the only destination the extension ever contacts.

**What it does not do.** It does not read, record or transmit the audio or video
of a call. It does not read pages other than the three meeting services above.
It has no account, no analytics, no tracking and no advertising. It does not
store anything itself.

**What the developer receives from the extension: nothing.** No information the
extension reads is sent to the developer or to any third party. The extension
talks only to the Ears app on the same computer; it plays no part in
registration and never contacts the licence service.

## Registering Ears

Ears asks for an email address the first time it runs. Registering is optional —
the app works either way — and this is what happens if you do.

**What is sent, to the licence service at getlicence.app:** your email address, a
random identifier generated for that installation, and the app and macOS
versions. Nothing else.

**Why:** to issue the licence the app holds, and to renew it. The app checks in
roughly every thirty days, when you open it or after a meeting finishes, which
also tells me an installation is still in use. If you tick the separate box for
it, the address is also used to email you occasionally about Ears; leaving it
unticked means the address is used for licensing only.

**What is never sent:** your meetings, recordings, transcripts, notes,
screenshots or anything said in a call. The licence service never sees them.

**Deleting it:** Settings ▸ Licence ▸ Delete my registration removes your email
address and that installation from the service entirely. Nothing on your Mac is
affected and Ears keeps working.

## The Ears application

Meetings are recorded and stored as files on your own Mac, in folders you
choose.

Transcription, summarising and screenshot reading can run entirely on your Mac,
or through a third-party provider that you configure with your own API key. If
you choose a provider, the relevant content — audio for transcription, transcript
text for summarising, meeting screenshots for speaker identification — is sent to
that provider under their terms, at your instruction. Ears sends nothing
anywhere unless you have configured a provider, and the developer never receives
your recordings, transcripts or notes.

Deleting a meeting in Ears removes its files from your Mac.

## Recording other people

Ears records meetings. Whether you may record a conversation, and whether you
must tell the other participants, depends on where you and they are. That
responsibility is yours, not the application's.

## Contact

Questions about this policy: **hello@getears.app**

## Changes

If this policy changes, the date above changes with it, and the previous version
remains in this repository's history.
