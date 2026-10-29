# LEO

A voice assistant for Windows. Say "Halo Leo", talk in Indonesian, and LEO opens apps, searches the web,
controls the laptop and answers out loud. The listening and the speech-to-text run on your laptop; only
the text goes to the AI you pick (Claude, Codex or Gemini).

This repository only holds the installers. Download the latest one from
[Releases](https://github.com/RafieGun/LEO-releases/releases/latest).

## Install

1. Download `LEO-Setup-<version>.exe` and run it. No admin rights needed.
2. The installer isn't code-signed yet, so Windows may show "Windows protected your PC".
   Click **More info**, then **Run anyway**.
3. On first start LEO opens its Configuration window. Connect one brain:
   - **Gemini**: free. Paste a key from [Google AI Studio](https://aistudio.google.com/apikey).
   - **Claude**: sign in with your Claude account, or use an Anthropic API key.
   - **Codex**: sign in with ChatGPT. Needs the Codex CLI installed.
4. LEO downloads its speech models (about 700 MB) the first time. The island at the top of the screen
   shows when it's ready.

Windows 10 or 11, 64-bit. About 1.5 GB of disk space plus the speech models.

## Updates

LEO checks this page twice a day. When there's a new version it tells you on the island, and you
install it from Configuration > General with one click. Your settings, history and keys stay.

## Privacy

- API keys are stored in Windows Credential Manager, not in LEO's files.
- Settings, conversation history and the optional voice clips stay in `%APPDATA%\LEO` on your laptop.
- Gemini's free tier: Google may use what you send to improve its products.
