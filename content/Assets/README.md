# Assets — Portraits & Crests

The vault uses **ITS Theme** embeds. Place image files here; Obsidian resolves `![[filename]]` from any folder if linked by name.

## Folder structure

```
Assets/
  portraits/     NPC Portrait.png (per candidate)
  crests/        House Crest.png (per faction)
```

## NPC portraits

| Candidate                   | File path                                                 | Embed in note                                             |
| :-------------------------- | :-------------------------------------------------------- | :-------------------------------------------------------- |
| [[Sir Garrick Thornfield]]  | `Assets/portraits/Sir Garrick Thornfield - Portrait.png`  | `![[Sir Garrick Thornfield - Portrait.png\|locl+hs-med]]` |
| [[Brindle Cogwort]]         | `Assets/portraits/Brindle Cogwort - Portrait.png`         | same pattern                                              |
| [[Mother Elira Voss]]       | `Assets/portraits/Mother Elira Voss - Portrait.png`       |                                                           |
| [[Fenwick Vale]]            | `Assets/portraits/Fenwick Vale - Portrait.png`            |                                                           |
| [[Lady Seraphine Ashcroft]] | `Assets/portraits/Lady Seraphine Ashcroft - Portrait.png` |                                                           |
| [[Tobin Reed]]              | `Assets/portraits/Tobin Reed - Portrait.png`              |                                                           |
| [[Jester Corvin]]           | `Assets/portraits/Jester Corvin - Portrait.png`           |                                                           |
| [[Dame Lysa Fairward]]      | `Assets/portraits/Dame Lysa Fairward - Portrait.png`      |                                                           |
| [[Aldric Penn]]             | `Assets/portraits/Aldric Penn - Portrait.png`             | ![[Aldric Penn - Portrait.png]]                           |
| [[Captain Mira Windale]]    | `Assets/portraits/Captain Mira Windale - Portrait.png`    |                                                           |
| [[Archivist Thalen Moss]]   | `Assets/portraits/Archivist Thalen Moss - Portrait.png`   |                                                           |
| [[Sister Kesh Oaken]]       | `Assets/portraits/Sister Kesh Oaken - Portrait.png`       |                                                           |
| [[Healer Rowan Sable]]      | `Assets/portraits/Healer Rowan Sable - Portrait.png`      |                                                           |

Copy portraits into `NPCs/` only if you prefer co-location; update embed path in frontmatter.

## House crests

| House | File path |
|:--|:--|
| [[House Thornwood]] | `Assets/crests/House Thornwood - Crest.png` |
| [[House Ashcroft]] | `Assets/crests/House Ashcroft - Crest.png` |
| [[House Reed]] | `Assets/crests/House Reed - Crest.png` |
| [[House Voss]] | `Assets/crests/House Voss - Crest.png` |
| [[House Cogwort]] | `Assets/crests/House Cogwort - Crest.png` |

Embed: `![[House Thornwood - Crest.png|locl+hs-med]]`

## Notes

- **Do not commit** large binaries if using git; `.gitkeep` optional.
- Recommended size: portrait ~600×800; crest ~512×512 PNG.
- If missing, notes still play; placeholder callout shows in Templates.
