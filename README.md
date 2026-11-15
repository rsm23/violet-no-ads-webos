# No Ads Purple for LG webOS

![No Ads Purple](https://github.com/rsm23/violet-no-ads-webos/releases/latest/download/icon.png)

Install and update through **webOS Homebrew Channel**. This repository distributes install packages and catalog metadata; the development repository is private.

## Add to Homebrew Channel

1. Open Homebrew Channel and go to **Settings → Add Repository**.
2. Enter this complete URL:

   ```text
   https://github.com/rsm23/violet-no-ads-webos/releases/latest/download/apps.json
   ```

3. Return to the app catalog and select **No Ads Purple**.
4. Select **Install** or **Update**. Installation does not launch the app.

The launcher and Homebrew catalog both show **No Ads Purple** with the matching typographic icon. An already installed copy with the same app ID is updated in place. If the installed version matches, Homebrew Channel disables Update; pressing **5** on the app details page enables Reinstall.

The PC does not need to be running. Future releases use the same repository URL. Do not install updates while this app is playing a stream.

## Features

- Twitch TV navigation, sign-in, chat, quality selection and remote controls.
- Original full-quality playback, with temporary alternate playback during detected ad breaks.
- BetterTTV global and channel emotes.
- Automatic claims for available channel-point bonus chests and eligible earned time-based Drops.

Ad avoidance depends on Twitch continuing to serve the alternate stream. In-stream sponsorships remain part of the broadcast. Drops still require the necessary watch time, eligibility and any game-account linking.

## Manual install

Download the `.ipk` from [Releases](https://github.com/rsm23/violet-no-ads-webos/releases/latest) and install it using webOS Dev Manager. Each release includes a SHA-256 checksum in its manifest and release notes, plus third-party notices. The app does not need root to run; Homebrew Channel itself must already be available to use the catalog method.

This is an unofficial app, unaffiliated with Twitch or BetterTTV. It loads Twitch's remotely served TV interface; that website is not bundled in the package.
