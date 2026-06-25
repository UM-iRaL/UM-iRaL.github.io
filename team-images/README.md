# Team profile photos

Drop a photo here to override the WordPress-hosted image for that person.

**How it works** — for each team member, `team.html` first tries to load
`team-images/<slug>.jpg`. If that file doesn't exist, it automatically falls
back to the WordPress URL (`vasileiostzoumas.com/.../`), and if that also
fails, to a generated initials placeholder. So you only need to add files for
the people whose photos you want to host locally; everyone else is untouched.

**Naming** — use lowercase, accents stripped, spaces → hyphens, `.jpg`
extension. Square-ish images look best (they're cropped to a 1:1 aspect ratio).

| Member | Filename |
| --- | --- |
| Jiawei Xu | `jiawei-xu.jpg` |
| Jose Díaz Peón González Pacheco | `jose-diaz-peon-gonzalez-pacheco.jpg` |
| Robin Inho Kee | `robin-inho-kee.jpg` |
| Atharva Navsalkar | `atharva-navsalkar.jpg` |
| Hongyu Zhou | `hongyu-zhou.jpg` |
| Zirui Xu | `zirui-xu.jpg` |
| Amjad Aljarallah | `amjad-aljarallah.jpg` |
| Pranjal Sharma | `pranjal-sharma.jpg` |
| Mingtian Tan | `mingtian-tan.jpg` |
| Andrew Zhao | `andrew-zhao.jpg` |
| Sara Gregg | `sara-gregg.jpg` |
| Gavriil Stavrakas | `gavriil-stavrakas.jpg` |
| Amrith Malli Reddi | `amrith-malli-reddi.jpg` |
| Jackie Lin | `jackie-lin.jpg` |
| Meli | `meli.jpg` |
| Ladi | `ladi.jpg` |

If a name changes in `team.html`, the expected filename changes too. You can
also force a specific file by adding a `photo: 'team-images/whatever.jpg'`
field to that member's entry in `team.html`, which bypasses the slug rule.
