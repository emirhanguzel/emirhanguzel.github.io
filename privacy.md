---
layout: default
title: Privacy policy — Mosslight Local Publisher
---

# Privacy policy

**Mosslight Local Publisher** is a private, owner-operated Windows tool for managing the operator's own YouTube channel. This notice describes the local application's Google data access and storage. Last updated: **31 October 2026**.

## Data accessed

With the operator's Google authorization, the tool can access the selected channel's identity and settings; video information, processing and publication status; and YouTube Analytics reports. Reports can include views, watch time, engagement, subscriber changes, traffic sources and monetary metrics when available. The tool receives a Google access credential and, when granted, a renewable authorization credential. It does not request the operator's Google password.

The application requests video-upload, YouTube read-only, Analytics read-only and monetary Analytics read-only permissions. These permissions are used for the visible channel-management functions described on the [home page](index.html).

## How data is used

Channel identity is checked before uploads. Video status is used to verify processing and publication, avoid duplicate uploads, and recover interrupted work. Analytics reports are used to assess the channel's own content and record progress. Monetary data is used to distinguish real reported advertising revenue from estimates or unavailable information.

Google API data is not sold or used to target advertising by this application. The local application does not use Google API data to train generalized artificial-intelligence or machine-learning models. Its use and transfer of Google API data follows the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements.

## Storage, security and retention

The local application stores reports, work records and media on the operator's Windows computer. Its renewable Google credential is encrypted with Windows DPAPI for the current Windows user. Credentials are kept separately from public documentation and are not intentionally written into reports, source code or publication descriptions. The local operation panel listens on the loopback address rather than being offered as a public service.

Local records remain until the operator deletes them; the application does not currently apply an automatic retention period. Windows encryption and channel checks reduce specific risks but are not a guarantee against every form of unauthorized access.

## Sharing and separately connected services

Videos and their publication metadata are sent to YouTube when an authorized upload is performed. API requests and authorization exchanges are sent to Google. The local uploader does not automatically send its Google credentials or raw API reports to advertising networks, vidIQ or an external AI API.

The operator may separately authorize integrations, use an assistant, or choose to share selected local results for analysis. Those separate services and account choices have their own privacy practices. They are not required by the local uploader and are not covered by this application's local-storage description.

This public documentation is hosted by GitHub Pages. GitHub may process technical information about visits under its [privacy statement](https://docs.github.com/site-policy/privacy-policies/github-privacy-statement). This documentation adds no advertising pixels, sign-up forms or analytics scripts.

## Revocation and deletion

The operator can revoke the app's permission through [Google Account connections](https://myaccount.google.com/connections). To remove the local copy, the operator can delete the encrypted credential file and the local reports or media they no longer want to keep. Revocation or deletion of local files does not itself remove uploaded YouTube videos; those can be managed separately in YouTube Studio.

## Children

This management tool is for the adult channel operator. It does not offer accounts to children or ask viewers for personal information. The classification and privacy controls for videos published on YouTube are managed separately on YouTube.

## Questions and changes

Questions about the local tool can be raised through the [project's GitHub issues](https://github.com/emirhanguzel/emirhanguzel.github.io/issues). Public issues should not contain credentials, private reports or personal information. This notice will be revised when the application's data practices change.

[Home](index.html) · [Terms of use](terms.html)
