# mpv-config

My mpv configuration.

## Video and Audio Settings

- Use GPU-accelerated video output by default.
- Resolution of 1080p or next best, FPS of 60 or next best, NEVER use vp9 codec, always use best audio.
- Do not resample audio.
- Audio device set to: alsa/default:CARD=PCH

## Subtitle Settings

- Use embedded fonts (if available).
- External subs don't have to match the file name exactly to autoload.
- Set subtitle language to english.
- Disable display of subtitles, but still load them if available.
- Search for subtitles in any sub-directory labeled: "ass", "srt", "sub", "subs", or "subtitles".

## Cache Settings

- Cache is enabled.
- Size of 2GB both backwards and forwards.
- Cache is seekable.

## Screenshot Settings

- Format: PNG
- Compression: None
- Tag colorspace as metadata.
- Allow high bit-depth screenshots.
- Save screenshots to `/home/valley/pictures/mpv`.

## Misc Settings

- Save position of video automatically.
- Disable screensaver during media playback.
- Log mpv to `/home/valley/.config/mpv/mpv.log`.
- Automatically prefetch/buffer files later in the playlist.
