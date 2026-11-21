---
title: Social Uploader
---

<p><img src="/logo-rounded-1024.png" alt="Social Uploader logo" width="96" height="96"></p>

**Upload one video. Publish it everywhere.**

Social Uploader is a desktop publishing tool for creators. You pick one vertical video, type the title once, and it posts the video to your own TikTok account and your other channels (YouTube Shorts, Facebook Page Reels, Threads, Zalo OA) in one click, with live progress for each.

## Features

- **One upload, five platforms.** TikTok, YouTube Shorts, Facebook Page Reels, Threads and Zalo OA from a single form.
- **TikTok draft or direct post.** Send the video to your TikTok inbox to finish in the app, or post it directly with the visibility you choose.
- **Live progress.** Each platform shows its upload status and a link to the posted video.
- **Your data stays with you.** The app runs on your own computer. Tokens and videos never go to a third-party server.

## Screenshots

![Upload page: choose a video, type the title, pick TikTok and other platforms](/screenshots/upload.png)

![Settings page with the TikTok account connected](/screenshots/settings.png)

![Upload finished: TikTok and the other platforms show their results](/screenshots/result.png)

## What it does with TikTok

Social Uploader uses the official [TikTok Content Posting API](https://developers.tiktok.com/doc/content-posting-api-get-started) and asks for these permissions:

| Permission | Why |
|---|---|
| `user.info.basic` | Show the display name and avatar of the connected TikTok account. |
| `video.upload` | Send your video to your TikTok inbox as a draft. You add the caption and post it in the TikTok app. |
| `video.publish` | Post your video directly, only when you choose direct posting, with the title and visibility you picked. |

It only posts videos you upload and confirm. It does not read your followers, messages, likes, comments or anyone else's content.

## How to connect TikTok

1. Open **Settings** and click **Get credentials** on the TikTok card.
2. Sign in on TikTok's own page and click **Allow**.
3. The TikTok card shows your account as connected.
4. On the **Upload** page, pick a video, type the title, choose **TikTok** (draft or direct post), then click **Upload**.

You can disconnect at any time in TikTok under **Settings and privacy > Security > Manage app permissions**.

## Legal and contact

- [Privacy Policy](/privacy)
- [Terms of Service](/terms)
- Contact: [trieu.ngohuy@gmail.com](mailto:trieu.ngohuy@gmail.com)

---

<small>&copy; 2026 Social Uploader. Not affiliated with or endorsed by TikTok, ByteDance, Google, Meta or Zalo. · [Privacy](/privacy) · [Terms](/terms)</small>
