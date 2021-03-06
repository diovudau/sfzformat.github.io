---
layout: "sfz/opcode"
lang: "en"
opcode_name: "fil2_type"
---
When used, there are two filters applied to the region in series.

## Examples

```
fil2_type=hpf_2p
```

This could be used to have both a high-pass and a low-pass filter, like this:

```
cutoff=1200
resonance=6
fil2_type=hpf_2p
cutoff2=250
resonance2=3
```

## Players support

Both ARIA and LinuxSampler supports all SFZ v1 filter types.
The following table describes which SFZ v2 filter types they support:

{% include sfz/fil2_type_players_compatibility_table.html %}
