---
title: Social Uploader
---

Social Uploader is a personal publishing tool. Its owner uploads one vertical video once, and it posts that video to the owner's own TikTok account and other channels (Facebook Page Reels, YouTube Shorts, Threads, Zalo OA) in one click.

## What it does with TikTok

Social Uploader uses the official [TikTok Content Posting API](https://developers.tiktok.com/doc/content-posting-api-get-started). After the owner signs in with TikTok and clicks **Allow**, it can:

- **Read basic profile info** (`user.info.basic`): display name and avatar, to show which TikTok account is connected.
- **Upload a video as a draft** (`video.upload`): the video goes to the TikTok inbox. The caption and visibility are set, and the video is posted, in the TikTok app.
- **Post a video directly** (`video.publish`): only when direct posting is chosen. The app reads the privacy options the account allows, posts with the chosen title and visibility, then checks the upload status.

It only posts videos the owner uploads and confirms. It does not read followers, messages, likes or anyone else's content.

## How it works

1. Social Uploader runs on the owner's own computer.
2. In **Settings**, the owner connects TikTok with **Get credentials**. TikTok shows its own sign-in and consent screen.
3. On the **Upload** page, the owner picks a video, types a title, chooses TikTok (draft or direct post) and the other channels, then clicks **Upload**.
4. Each channel shows its own progress and a link to the posted video.

Access tokens and videos stay on the owner's computer. Nothing is sent to any other server. See the [Privacy Policy](/privacy) for details.

## Legal

- [Privacy Policy](/privacy)
- [Terms of Service](/terms)

Contact: [trieu.ngohuy@gmail.com](mailto:trieu.ngohuy@gmail.com)

Social Uploader is an independent project. It is not affiliated with or endorsed by TikTok or ByteDance.
