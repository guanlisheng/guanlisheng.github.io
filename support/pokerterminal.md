---
layout: default
title: "Poker Terminal — Support"
description: "Help for Poker Terminal: configuring the terminal URL, remote control troubleshooting, external display and network issues."
permalink: /support/pokerterminal/
---

# Poker Terminal Support

[中文]({{ '/support/pokerterminal-zh/' | relative_url }}) · [Marketing]({{ '/marketing/pokerterminal/' | relative_url }}) · [Privacy Policy]({{ '/privacy/pokerterminal/' | relative_url }})

## Quick start

1. Launch the app; it loads the built-in demo terminal address by default.
2. Open **Settings** on the main screen and replace the address with your own HTTPS tournament terminal.
3. Once connected, you can view level, blinds, ante, countdown, entrant count and scoring data.
4. If an independent external display is available, the tournament page fills that display while iPhone keeps the control UI.

## Changing the terminal address

- Main screen → **Settings** → **Terminal URL**.
- Only `https://` addresses are supported. Save and return to reload.
- The address is stored locally and is never uploaded.

## Remote control does not work

Remote control depends on the target page exposing a compatible **TerminalRemote** interface:

- If the page does not expose it, the remote buttons are disabled, but the page still displays.
- If the interface exists but nothing responds, make sure the page finished loading and try a manual refresh.
- The interface is implemented by the terminal page; the app cannot enable remote control for incompatible pages.

## TV does not show the tournament page independently

- An independent external display requires iOS and the receiving device to support a separate display scene.
- If the system only offers **screen mirroring**, the TV mirrors the whole iPhone screen. This is system behavior.
- Check the external display settings in Control Center, or try a receiver that supports independent display.

## Network and loading issues

- **Stuck loading**: confirm the terminal URL is reachable and the device is online.
- **Connection error**: check that the URL is HTTPS, the certificate is valid, and the terminal service is running.
- **Blank page**: try manual refresh; if it persists, open the terminal page directly to verify it works.
- If the terminal is on a local network, iOS may request **Local Network** permission. Allow it and retry.

## Contact

If the above does not resolve your issue, email:

**your-email@example.com**

Please include iOS version, device model, terminal URL type (public/LAN) and a screenshot of any error. Do not send login credentials or sensitive tournament data.

## Links

- [Privacy Policy]({{ '/privacy/pokerterminal/' | relative_url }})
- [Marketing page]({{ '/marketing/pokerterminal/' | relative_url }})
- [All apps]({{ '/marketing/' | relative_url }})
