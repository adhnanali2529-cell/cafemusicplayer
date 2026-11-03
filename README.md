# Melody Café Music Player

A red, anime-comic themed music player built on a **doubly linked list** (head, tail, prev, next).
Songs are searched with the iTunes Search API and play 30-second previews.

Operations: `addSong`, `insertAfter`, `removeSong`, `displayForward`, `displayBackward`, `playNext` (wraps to the first song after the last).

Static site with no build step. Deploy on Vercel by importing this repo.
