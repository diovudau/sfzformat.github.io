---
layout: "sfz/opcode"
lang: "en"
opcode_name: "delay"
---
If a `delay` value is specified, the region playback will be postponed for the
specified time. If the region receives a note-off message before `delay` time,
the region won't play.

Sample playback and all envelope generators' delay stage will start counting
after region delay time - this is the difference between this and [ampeg_delay](ampeg_delay).

## Examples

```
delay=1

delay=0.2
```

Example uses: delaying some regions in a strum or a flam;
delaying regions to emulate more distant microphone positions.

