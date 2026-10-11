# Yu Yu Hakusho: Gate to Demon World — English Translation

An unofficial, free, nonprofit English fan translation for **Yu Yu Hakusho Dai-3-dan - Makai no Tobira Hen (Japan)** on Game Boy.

## Final packaged editions — v0.40

Both editions contain the same current English translation and presentation fixes. Choose the fight behavior you prefer:

| Edition | Final Sensui battle after entering Demon World |
| --- | --- |
| Pre-adjustment / Original Sensui | Preserves the original fight behavior. |
| Post-adjustment / Adjusted Sensui | Allows hits during the brief transition between kicks. Rush protection, attack timing, health, damage, movement, and normal hit recovery remain unchanged. |

Each edition is provided in IPS and xdelta formats. These are the final packaged versions for this publication; the translation remains a playable draft with full playthrough verification pending.

## What has been translated

- The extracted story and NPC dialogue script: 190 entries, including the school, psychic encounters, Genkai's explanation, and later story scenes.
- Opening monologue, English title and subtitle, main-menu labels, and password-screen lettering.
- Playable-character names, boss HUD names, boss defeat messages, level-up messages, knocked-out status, and game-show reward messages.
- Selected scenery lettering, including mahjong/arcade signs and the Sarayashiki station banner.
- Minigame instructions and selection text, plus extracted ending/result dialogue.

This does not claim that every decorative Japanese graphic has been found. Remaining scenery lettering and contextual wording may still need review.

## Major changes

- Added variable-width dialogue rendering and measured line wrapping to fit English into the existing text boxes while preserving script control sequences.
- Corrected dialogue sequencing and truncation around the rooftop, Kuwabara, Keiko, and Kido scenes.
- Revised wording against the Japanese script, including Genkai's opening, Kamiya's mid-fight taunt, Koenma's location, and Murota's **Wiretap** ability.
- Made level-up messages fit a single bubble and clarified game-show rewards as a pool of level-ups distributed among eligible characters.
- Corrected dynamic boss defeat names, long-name wrapping, and narrow-font glyphs such as N.
- Centered boss labels on white backgrounds and constrained the longest shifted health bars to the HUD area without changing actual HP.
- Reworked the title styling and outlined subtitle; retained the original Sensui eye artwork and native intro/menu transition structure with compact English scrolling text.
- Distinguished password O from zero and corrected the cave minigame selection cursor.
- Restored ordinary building roof graphics that had incorrectly inherited a hospital label.
- Included an optional, narrowly scoped final Sensui balance adjustment as a separate edition.

## Applying a patch

1. Supply your own clean Japanese ROM. This repository does not distribute ROMs or save states.
2. Confirm the original ROM SHA-1: `FFAFF18CC2028CA7F823ED1C2A025ED5A61D1B9D`.
3. Choose one edition and apply **either** its IPS **or** its xdelta patch. Do not apply both, stack editions, or patch an earlier English build.
4. Start a new game or use an in-game password. Older emulator save states can retain obsolete graphics or state.

## Verification

All 190 extracted script control streams were checked. All 154 dialogue-rendering cases passed. Both editions' IPS and xdelta patches were independently decoded and reproduced their target ROMs exactly. Archive integrity was checked. The editions differ only in the final Sensui transition hurtbox and the corresponding ROM checksum.

For the adjusted edition, native collision checks covered 2,240 animation cases; only the intended final Sensui transition pose changed. A native damage check confirmed that the newly hittable pose takes damage with normal recovery. Full end-to-end mGBA playthrough testing remains pending.

## Copyright and nonprofit notice

This is an unofficial fan project, distributed free of charge for nonprofit purposes. It is not affiliated with, endorsed by, or sponsored by the original creators, publishers, or rights holders.

Yu Yu Hakusho, its characters, story, artwork, trademarks, and the original game remain the property of their respective rights holders. Original game credits include Yoshihiro Togashi, Shueisha, Fuji TV, Studio Pierrot, and TOMY. This project claims no ownership of those materials and grants no rights to them.

Only translation patches and project documentation are distributed here. No original or patched ROM, emulator save state, or contact email is included. Do not sell the patches or bundle them with ROMs. Obtain the original game lawfully and comply with applicable law. Nonprofit distribution is not a claim of copyright authorization or immunity.

Please use GitHub Issues for technical reports or rights-holder concerns.


## Screenshots

Representative emulator previews; both editions share the same translated presentation. The final Sensui image shows the battle scene, not a visual difference between editions.

![main menu](https://raw.githubusercontent.com/blackhowling2020/yu-yu-hakusho-makai-no-tobira-english/main/screenshots/main-menu.png)

![title screen](https://raw.githubusercontent.com/blackhowling2020/yu-yu-hakusho-makai-no-tobira-english/main/screenshots/title-screen.png)

![password screen](https://raw.githubusercontent.com/blackhowling2020/yu-yu-hakusho-makai-no-tobira-english/main/screenshots/password-screen.png)
