# Privacy Policy — Komodo

**Last updated:** October 21, 2026

Komodo is a private-by-default AI chat app. **We (the developer) collect no data**: there are no accounts, no analytics, no crash reporting, no advertising, and no server of ours. Komodo has no backend to send anything to.

That is a statement about what *we* collect. It is not a promise that nothing ever leaves your phone — three features can put data on the network, each one you switch on yourself, and they are listed in full below.

## What we collect

Nothing:

- **No personal information** — no name, email or address is requested or stored
- **No usage data** — no analytics, telemetry, diagnostics or event tracking
- **No identifiers** — no device or advertising identifier is read
- **No location data** — no location service is used
- **No third-party SDKs** — no analytics, attribution, ad or tracking framework ships in the app

Your chats, character cards, downloaded models and settings live only in Komodo's own storage on your iPhone. Deleting a chat, a card or a model removes it; deleting the app removes the rest.

## On-device AI (the default)

Chats run against a model on your iPhone: either a model you downloaded (MLX) or Apple's on-device foundation model through Apple's own Foundation Models framework, which is subject to [Apple's privacy terms](https://www.apple.com/legal/privacy/). In this mode your prompts and the replies are processed locally and nothing is transmitted.

## The three things that can leave the device

All three are opt-in, and each is visible where it is used.

**1. Model downloads (Hugging Face).** To run a model offline, Komodo downloads it from the public Hugging Face repository (huggingface.co). That is an ordinary web request: Hugging Face sees the download — including your IP address, under their standard logging — and Komodo adds no account details, no token and no device identifier to it, unless you paste an access token of your own to unlock a gated repository. Downloading is something you start; nothing downloads by itself.

**2. Web search (off until you switch it on).** The globe in a chat lets a reply use live search. Komodo sends the search query — which is condensed from the message you wrote — to DuckDuckGo's public endpoints (`html.duckduckgo.com`, `lite.duckduckgo.com`), and may fetch a page from the result set so its text can be read into the conversation. Those requests are sent without cookies or caching, and Komodo's search traffic is not tied to an identity: DuckDuckGo sees a query, an IP address and a generic browser user agent.

**3. Remote endpoints you add (Komodo Pro).** Komodo can talk to any OpenAI-compatible server you designate — a runner on your own network (Ollama, LM Studio, mlx_lm.server) or a hosted provider. **Chats that use such an endpoint are not private**: every message in that chat — your prompts, attachments and the full history — is sent to that server, along with the API token you supplied, and it is stored and used by whoever runs it, under their terms, not ours. Adding an endpoint requires ticking that acknowledgement first. Unencrypted `http://` is permitted only for a server on your local network; anything further away must use `https://`. Komodo cannot secure, vouch for, or delete data on a third-party server.

## Purchases

Komodo Pro is an optional one-time in-app purchase processed by Apple through the App Store. Komodo never sees or stores payment details; the purchase and its receipt are handled by Apple and iCloud under Apple's privacy terms. The entitlement is verified on-device from Apple's StoreKit transaction data, and the record is kept only on this device — it is not uploaded anywhere.

## App Privacy on the App Store

Komodo's App Privacy is declared as **"Data Not Collected"**: neither Komodo nor any third party in the app collects data that is linked to you or your device and used for anything (analytics, advertising, app functionality, or anything else). The network traffic described above is content *you* direct to services *you* choose; it is not collection by the developer.

## Children

Komodo is a general-purpose AI tool with access to unrestricted open-weight models and user-imported character cards. It is not directed at children, and we collect no data from anyone, of any age.

## Changes to This Policy

Changes are published by updating this file and the date above. Because nothing is collected, a change can only restate what the app already does — anything that *would* start collecting data means the policy, the App Store privacy label and the app's own on-screen summary change together.

## Contact

Questions about this policy — or a report about anything in the app — go to the issue tracker:
[https://github.com/Jacknjill10101/Komodo/issues](https://github.com/Jacknjill10101/Komodo/issues)
