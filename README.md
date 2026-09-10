# Tally — support

**[Tally](https://tally-site-73y.pages.dev) reads your Jira Cloud worklogs as a timesheet, tracks
time locally, and logs the time that isn't in Jira yet.**

This repository is for **issues only**. There is no code here. Tally's source is private; whether it
is ever opened is a separate decision that this repository does not take.

- **[Report a bug](../../issues/new?template=bug.yml)**
- **[Request a feature](../../issues/new?template=feature.yml)**
- **[Ask a question](../../issues/new?template=question.yml)**

Prefer not to use GitHub? Email **tallytimesheet@gmail.com** — same person reads both. The
[support page](https://tally-site-73y.pages.dev/support/) has both doors on it.

## Install

- [Chrome Web Store](https://chromewebstore.google.com/detail/tally/anphjbkojkfpdbpidinnfhkofmppmike)
- [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/tally/eboeljobjlmakpliobdgfikdedkdkaia)

## Before you file

**Jira Cloud only.** Server and Data Center are not supported. The APIs differ enough that this is a
limit rather than a missing feature.

**Tally shows only what your own Jira permissions return.** A project you cannot browse, an issue
under issue-level security, and a restricted worklog are all correctly absent. If a view looks
emptier than you expect, that is the first thing to check.

**Diagnostics beat description.** Settings has a **Copy diagnostics** button, under About Tally:
version, browser, and the settings that change how Tally behaves. It never copies your Jira address,
an issue key, a summary or a name, and you can read every line before pasting it. On a Tally older
than 1.2.0 the version is in the same place.

## What to expect

One person reads these. Bugs are triaged with three labels — `bug`, `feature`, `question` — and
there is a pinned issue for what is planned next, which is the public face of the roadmap.

Store reviews are answered too, but they are a poor place to report a bug: the store does not tell
you when a developer replies, and there is no way to ask a follow-up question.

## Privacy

Tally has no account, no server, no analytics, no telemetry and no third-party code. The
[privacy policy](https://tally-site-73y.pages.dev/privacy/) lists every endpoint it calls, every key
it stores and every permission it asks for, with the reason for each.

Anything you put in an issue here is public. Please redact customer names and issue summaries.
