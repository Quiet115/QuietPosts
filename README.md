# QuietPosts

Review a big collection of memes (photos and videos) and publish it to Instagram at a human pace. A Windows app, part of the Quietverse.

## What it does

- **Scan a folder** with thousands of files. You can pause it or close the app and it picks up where it left off.
- **Finds duplicates**: repeated or very similar photos and videos, even if the size or name changed. It keeps the best one.
- **Smart crop** for screenshots: suggests removing phone bars and colored borders, or keeping only the image of a post. The crop box has handles that snap to the edges it detects.
- **Video trim**: choose where a video starts and ends.
- **Watermark hiding**: finds watermarks in videos, including the ones that jump between corners, and lets you blur, fill in, cover or overwrite them with your own text. Nothing is hidden until you ask for it.
- **Fast review**: one file at a time with keyboard shortcuts. Publish, discard to a folder of your choice, undo, skip. Every key can be changed in Settings.
- **Human schedule**: publishes only inside your window (for example 08:00 to 24:00), with posts per hour, random variation, a daily cap and a gradual ramp-up.
- **Safety pause**: if Instagram asks to slow down or verify the account, QuietPosts pauses by itself and tells you.
- **Simulation mode** (on by default): runs the whole flow without publishing anything.
- Themes with your own palettes. English (default) and Spanish.

Your original files are never modified: crops, trims and hidden watermarks are applied to a copy when a file is published, and discarding only moves a file to the folder of its category (you can undo it).

## Install

1. Download `QuietPosts-<version>-win64.zip` from the [Releases page](https://github.com/Quiet115/QuietPosts/releases) and unzip it anywhere.
2. Install [ffmpeg](https://ffmpeg.org/download.html) and make sure it is in your `PATH` (QuietPosts needs it to analyze and prepare videos).
3. Open `QuietPosts\QuietPosts.exe`. Windows may show a SmartScreen warning the first time because the app is not signed: choose *More info*, then *Run anyway*.

A window opens and an icon appears in the system tray. Closing the window keeps the app publishing; use the tray icon and *Quit* to stop it.

## Important: Instagram

QuietPosts publishes with an **unofficial** library, because Instagram's official API needs a professional account. Using unofficial tools goes against Instagram's rules and can lead to limits or a ban of your account, especially with many posts per day. The gradual ramp-up, the daily cap and the safety pause reduce the risk but do not remove it. Start with one test post and a few posts a day.

## Privacy

Everything stays on your computer. There is no account, no server and no analytics. The app only talks to Instagram when it publishes. Your Instagram password is kept in the Windows credential vault, not in a file.

## Feedback

Found a bug or have an idea? Open an [issue](https://github.com/Quiet115/QuietPosts/issues), or use the *Feedback* tab inside the app, which prepares one for you.
