# Nexus ASCII Color Editor

Web tool to colorize neofetch ASCII **char by char** — no more manual `${c1}`.

- Click a color (c1..c6), then click any `+`/`=` character
- `ascii_colors` palette editable (e.g. `4,6,1,2,3,5`)
- Export → copy-paste to `/usr/share/neofetch/ascii/distro/nexus`
- Download `nexus` file directly

**Use:**
```
python3 -m http.server 8000
# open http://localhost:8000
# or just open index.html
```


**For Nexus Live ISO:** `archiso/airootfs/usr/share/neofetch/ascii/distro/nexus:1`

Monorepo: https://github.com/nexuslinux-os/NexusLinux
