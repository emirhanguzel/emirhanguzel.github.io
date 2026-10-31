---
layout: default
title: Mosslight Local Publisher
---

# Mosslight Local Publisher

A private Windows desktop tool for the operator of **Mosslight Wonder Lab**.

The tool prepares original videos locally, uploads reviewed videos to the operator's authorized YouTube channel, checks their processing and visibility, and collects channel performance reports. It uses Google's official authorization flow and YouTube APIs.

This is an operator tool. It does not provide children's accounts, a public sign-up service, a hosted video editor, or a way for viewers to connect their Google accounts. The children's videos are published on [Mosslight Wonder Lab on YouTube](https://www.youtube.com/@MosslightWonderLab).

## What authorization enables

- Uploading videos to the channel selected in Google's consent screen.
- Reading the authorized channel's identity, videos and settings.
- Reading YouTube Analytics reports for performance analysis.
- Reading monetary Analytics reports when Google makes them available. An empty or unavailable report is not reported as earned revenue.

The software checks the expected channel identity before uploading. A local quality review is required before a video can be published. It does not promise viewers, subscribers, YouTube Kids inclusion, Partner Program acceptance, or advertising income.

## Local storage and control

Video files and reports are stored on the operator's computer. The renewable Google authorization credential is encrypted for the current Windows user with Windows DPAPI. Authorization can be revoked in the operator's Google Account. Revoking access does not delete videos already published on YouTube.

Read the [Privacy policy](privacy.html) and [Terms of use](terms.html) before authorizing the tool.

## Contact

The operator maintains this documentation through the [project's GitHub issues](https://github.com/emirhanguzel/emirhanguzel.github.io/issues). Do not include passwords, authorization codes, tokens, private reports or personal information in a public issue.

Last updated: 31 October 2026.
