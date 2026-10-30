# yt-wallpaper

YouTube の動画を [Plash](https://sindresorhus.com/plash) で壁紙にするための1枚のページ．

YouTube は 2025 年末から，埋め込みの URL（`youtube.com/embed/...`）を直接開くと「エラー 153」を出すようになった．このページは動画を iframe で包み，Referer を付けて再生させる．

## 使い方

Plash に次の形の URL を登録する．

- 普通の動画（ループ）：`https://shion826.github.io/yt-wallpaper/?v=<動画ID>`
- ライブ配信：`https://shion826.github.io/yt-wallpaper/?v=<動画ID>&live`
- 音を消す：末尾に `&mute=1`

動画 ID は `youtube.com/watch?v=XXXX` の `XXXX`．投稿者が埋め込みを禁止している動画は再生できない．
