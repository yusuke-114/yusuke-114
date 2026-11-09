# Hi, I'm Yusuke 👋

I build macOS apps, and tools that let Claude Code run in more places.

![Profile views](https://komarev.com/ghpvc/?username=yusuke-114&color=blue)

## Claude Code tools

- **[Steward](https://github.com/yusuke-114/Steward)**: drive Claude Code on your Mac from Telegram. Start sessions, switch projects and approve tool calls from your phone. Works with an API key, Bedrock, Vertex AI or a company gateway.
- **[claude-xcode-agent](https://github.com/yusuke-114/claude-xcode-agent)**: Claude Code as the coding agent in Xcode 27, with your own API key or gateway. A small wrapper between Xcode's ACP adapter and `claude` that supplies credentials and keeps your global settings out of Xcode.
- **[cchat](https://github.com/yusuke-114/cchat)**: a lightweight terminal chat built on `claude -p`. Each turn is its own process, chained with `--resume`, so there's no long-running session to hang.

All three run the `claude` CLI you already have instead of reimplementing the agent, and none of them write your keys into `~/.claude/settings.json`.

## macOS apps on the App Store

<table>
  <tr>
    <td width="80" align="center"><a href="https://apps.apple.com/us/app/long-screenshot-ultra/id6804573865"><img src="https://raw.githubusercontent.com/yusuke-114/LongScreenShot/main/docs/assets/app-icon.png" width="64" alt="Long Screenshot icon"></a></td>
    <td><a href="https://apps.apple.com/us/app/long-screenshot-ultra/id6804573865"><b>Long Screenshot</b></a><br>Scrolling screenshots for macOS. Select an area, scroll, and get one seamless image.</td>
  </tr>
  <tr>
    <td width="80" align="center"><a href="https://apps.apple.com/us/app/keyflip/id6818039827"><img src="https://raw.githubusercontent.com/yusuke-114/KeyflipApp/main/docs/assets/app-icon.png" width="64" alt="Keyflip icon"></a></td>
    <td><a href="https://apps.apple.com/us/app/keyflip/id6818039827"><b>Keyflip</b></a><br>Switches your keyboard input source automatically whenever you move to another app.</td>
  </tr>
</table>

## Install with Homebrew

```bash
brew install --cask yusuke-114/tap/steward
brew install --cask yusuke-114/tap/longscreenshot
```
