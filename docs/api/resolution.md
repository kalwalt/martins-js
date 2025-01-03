# Resolution

A `Resolution` is a setting defined by a string. It is mapped to a size measured in pixels according to special rules. You may use it, for example, to set the [resolution of the camera](camera-source.md#resolution), to adjust the [resolution of the tracker](image-tracker.md#resolution), or to set the [rendering resolution](viewport.md#resolution) of the virtual scene.

The table below shows examples of how resolution strings are converted to pixels:

| Resolution | Alias | 16:9 | 16:10 | 4:3 | Notes |
| ---------- | ----- | ---- | ----- | --- | ----- |
| `"120p"` | `"xs"` | 214x120 | 192x120 | 160x120 | |
| `"144p"` | `"xs+"` | 256x144 | 230x144 | 192x144 | |
| `"240p"` | `"sm"` | 426x240 | 384x240 | 320x240 | SD |
| `"288p"` | `"sm+"` | 512x288 | 460x288 | 384x288 | |
| `"320p"` | `"md"` | 568x320 | 512x320 | 426x320 | |
| `"360p"` | `"md+"` | 640x360 | 576x360 | 480x360 | SD |
| `"480p"` | `"lg"` | 854x480 | 768x480 | 640x480 | SD |
| `"600p"` | `"lg+"` | 1066x600 | 960x600 | 800x600 | |
| `"720p"` | `"xl"` | 1280x720 | 1152x720 | 960x720 | HD |
| `"768p"` | | 1366x768 | 1228x768 | 1024x768 | |
| `"900p"` | `"xl+"` | 1600x900 | 1440x900 | 1200x900 | |
| `"960p"` | | 1706x960 | 1536x960 | 1280x960 | |
| `"1080p"` | `"xxl"` | 1920x1080 | 1728x1080 | 1440x1080 | Full HD |