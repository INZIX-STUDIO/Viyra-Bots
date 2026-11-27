# Viyra Bots Beta 1.0

**A local-first, multi-agent desktop workspace for Windows.** Create specialized AI agents, let them delegate tasks, and follow their work in a live browser.

[Download the Windows beta](https://github.com/INZIX-STUDIO/Viyra-Bots/releases/tag/Viyra-Bots-Beta-Public-Preview) · [Report a bug or suggest a feature](https://github.com/INZIX-STUDIO/Viyra-Bots/issues) · [License](./LICENSE)

> **Beta and closed source:** This repository hosts official compiled releases, documentation, and feedback. The application's source code is private. Read the [license](./LICENSE) before using the software.

## What Viyra offers

- **Multiple specialized agents:** Create agents with different roles and isolated execution sessions.
- **Agent delegation:** Agents can coordinate and delegate tasks to one another.
- **Self-evolved rules:** Agents can reflect on completed tasks and rejected actions, with a version timeline and rollback.
- **Live browser and watchers:** Follow browser work and configure page-event watchers.
- **Your choice of provider:** During setup, provide API credentials for an OpenAI-compatible provider, SerpAPI, and Composio.
- **Connected apps:** Use Composio to connect supported services, with authorization prompts for sensitive actions.

## Get started on Windows

**Requirements:** Windows 10 or 11; 4 GB RAM minimum (8 GB recommended for browser automation). Internet is needed for cloud AI providers and online integrations. Setup requires API credentials for an OpenAI-compatible provider, SerpAPI, and Composio.

1. Open the [Beta 1.0 public preview](https://github.com/INZIX-STUDIO/Viyra-Bots/releases/tag/Viyra-Bots-Beta-Public-Preview).
2. Under **Assets**, download **viyra_bots_windows_beta_1.0.zip**.
3. Extract the ZIP to a folder on your computer and run **Viyra.exe**.
4. During onboarding, enter the requested API credentials for your OpenAI-compatible provider, SerpAPI, and Composio, then create your first agent.

The current beta is available for Windows only. There is currently no macOS version.

### Optional: verify the download

In PowerShell, run the following in the folder containing the downloaded ZIP:

```powershell
Get-FileHash .\viyra_bots_windows_beta_1.0.zip -Algorithm SHA256
```

For this Beta 1.0 asset, compare the result with the SHA-256 digest shown by GitHub on the release asset:

```
1f10640f6b69a99a498c0bf403c59034729de815943e02f004fc979c1f01251c
```

A matching digest checks that the file matches the published asset; it does not establish that the software is safe.

## Privacy and external services

Viyra is a local-first application that runs on your computer. When you use an external service, information may be sent to the provider you configured for that service; entering API credentials does not mean all your data is shared. Whether a provider shares data further depends on its own practices and policies, and it may not share it at all. The public repository does not establish exactly what is stored locally, what is sent to each service, or how credentials are handled. Review each service's terms and privacy policy, and review authorization prompts before approving actions. Local-first design is not a guarantee of complete privacy or security.

## Feedback and contributions

For a bug or feature request, [open an issue](https://github.com/INZIX-STUDIO/Viyra-Bots/issues). For bugs, include the beta version, Windows version, steps to reproduce, expected and actual behavior, and any relevant error message. Remove API keys, personal information, and sensitive screenshots before posting.

This is a closed-source release repository; source-code contributions are not available here. Feedback and documentation improvements are welcome.

## License

Copyright © 2026 Viyra. All rights reserved. Viyra is proprietary, closed-source software; see [LICENSE](./LICENSE) for the terms.
