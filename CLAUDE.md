# Lesson authoring rules

## Never promise media that isn't in the lesson

- Only say "watch", "video" or "vídeo" if the slide actually embeds a working video (`<iframe>` or `<video>` with a real, checked URL).
- Talks, podcasts and interviews are **audio**: describe them as "listen to", never "watch".
- Every listening text must have a real recorded MP3 in the lesson's `audio/` folder, played with an `<audio>` player (not browser speechSynthesis). Lesson 3 is the reference: `module-1/lesson-3/audio/talk.mp3`, with transcript highlighting synced by paragraph start times.
- The duration shown on the slide must match the real audio length.
- Before committing a lesson, search it for `watch|video|vídeo|listen|audio` and confirm each mention matches something that actually exists on the slide.
