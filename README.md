# DeskKey — Desktop style Keyboard

**Full PC layout with Alt, Ctrl, Shift & more — privacy-first, no internet.**

DeskKey is an offline virtual keyboard: a compact 104/105-key PC board with real modifiers, on-device dictionaries, clipboard history, and a settings/theme studio. Nothing is fetched from the network. There are no accounts, ads, analytics, or remote word lists.

DeskKey is freeware.

You may install and use the official APK for free.

## Privacy guarantees

- Android manifest does **not** request `INTERNET` or `ACCESS_NETWORK_STATE`. `RECORD_AUDIO` is used only for dictation when you turn the microphone chip on.
- Dictionaries, learned words, clipboard history, themes, and layouts stay on-device.
- **Private mode** (off by default) stops learning new words. Suggestions still use words you already learned. Clipboard history still saves system copy.
- Backup is a JSON file you save yourself. Restore brings back every setting (languages on, current language, layout, theme, IME chips), learned words, suggestion extras, clipboard, and emoji recents. No server.

## Enable as the system keyboard

### Android (signed APK included)

1. Allow “Install unknown apps” if asked.
2. **Settings → System → Languages & input → On-screen keyboard → Manage keyboards → enable DeskKey.**
3. Open any text field and switch to DeskKey from the keyboard picker.

---

## Layout

DeskKey follows a real PC 104/105 keyboard, not a phone 3-row pad.

- **Function row:** Esc, F1–F12, PrtSc, ScrLk, Pause — hide from **Settings → Layouts** or the **F / Fn** chip (off by default on phones)
- **Number row** with dual-legend shift glyphs (`!` `@` `#` `$` …). Shift types the upper symbol.
- **QWERTY / QWERTZ / AZERTY / Dk /k  / Col/ Co Colemvorak / Colemak** letter block (Tab, Caps, dual Shift, Enter, Backspace)
- **ISO Enter** option for 105-key boards
- **Bottom modifiers:** Ctrl, Win/Super, Alt, Space, Alt, Win, Menu, Ctrl
- **Navigation cluster:** Ins, Home, PgUp, Del, End, PgDn and inverted-T arrows
- **Numpad** with Num Lock, `/` `*` `-` `+`, Enter — **Pad / 123** in the More (⌃) panel hides or shows it immediately
- **Lock LEDs:** NUM LOCK, CAPS LOCK, SCROLL LOCK — hide with the F-row. Hidden while the clipboard or emoji overlay is open

---

## Full Size and Ultra Compact

**Settings → Layouts** has a radio group:

- **Full Size Keyboard** — classic PC 104/105 board (Tab, Caps, dual Shift, Enter, two Win keys, Menu).
- **Ultra Compact Keyboard** — photo-matched compact PC board. **Default on phones.** Fn row, inverted-T arrows, Ins cluster, and numpad are **off** by default on Ultra.

Ultra still has real **Ctrl / Alt / Shift / Win** combos. Shift still capitalizes letters. Sticky and lock modifiers work the same as Full Size.

**Ultra Compact details**

- Number row is `1–0` (no `` ` `` `=` keys on that row). Backspace is labeled **Bksp**.
- **Tab**, **Caps**, **Shift**, **Enter** use the same names as Full Size (not icons).
- Both Shift keys are the **same width**.
- **Win** shows the text `Win` only — no Windows logo.
- Bottom-right, between Alt and Ctrl, is **☰**. That is the OS **Menu** key (same idea as Win). On desktop it opens the field’s system context menu (right-click). On Android it sends the Menu key. On iOS there is no Menu key, so the button stays in place and does nothing extra. It is **not** a Cut / Copy / Paste overlay.
- After **M**: a dual key with **`,`** on the key and **`/`** on top, then a dual key with **`.`** on the key and **`\`** on top.
- Every letter has a **corner symbol** (photo extras): Q `%` W `~` E `|` R `=` T `[` Y `]` U `<` I `>` O `{` P `}` A `@` S `#` D `$` F `-` G `&` H `-` J `+` K `(` L `)` Z `*` X `"` C `'` V `:` B `;` N `!` M `?`.
- **More (⌃)** has a tile to switch Full Size ↔ Ultra Compact without leaving the board.

Portrait and landscape remember height, floating, Fn/arrows/nav/numpad, and form factor **separately**.

---

## Long-press popup

Long-press a letter to open a **small even grid** above the key (equal square cells, no leftover wrapped row).

- The **corner symbol is always bottom-left** and **already selected**. Release without moving to type that symbol. You do **not** slide for the symbol.
- Next cells are the letter in the current Caps/Shift case, then **accents for that letter only** (`á à â ä æ …` on A; capitals when Shift/Caps is on).
- Slide onto another cell, then release to type it.
- Extra stash marks (for example backtick on W, `^` on N) follow the accents.

---

## Overlays (clipboard, emoji, special symbols)

Each overlay covers the key area only. At the bottom: **ABC**, Space, Backspace, Enter — **ABC is the same size** as the other three. ABC returns to the letter keyboard.

**Special symbols** uses fixed 42×42 keys and **scrolls**. Keys do not shrink to fit.

---

## Undo and redo

Curved-arrow chips on the IME bar, plus **Ctrl+Z** / **Ctrl+Y** / **Ctrl+Shift+Z** / **Alt+Backspace**.

Undo actually reverts what you just typed. Redo puts it back.

---

## IME bar

The bar under the keys (toggle in Settings → Appearance). Pad / 123, Fn, T-arrow, Ins, and Settings live in the **More (⌃)** panel next to the DeskKey name. Remaining chips reflow.

| Left → | Right |
|---|---|
| **▾** hide the keyboard | **⌃ More** — Pad / 123, Fn, T-arrow, Ins, Settings |
| **EN** language chip — tap for enabled languages (Settings → Languages) | **DeskKey** name |
| Extra-letter chip (when the language has extra letters) | |
| **Undo / Redo** curved-arrow chips (Ctrl+Z / Ctrl+Y) | |
| **Hand** one-handed half-width (not shown while floating) | |
| **#+=** special-symbol palette | |

Tap **▾** to hide the keyboard. Tap **⌃** for Pad, Fn, arrows, Ins, and Settings. The F-row grows **upward** so the letter rows and IME bar stay put.

---

## Suggestion bar

Left to right:

| Control | What it does |
|---|---|
| Mask | Private mode. Suggestions still use learned words; new learning is paused. |
| Float | Untether the board (see Floating). Hidden while you hide the button in Layouts. |
| Chips | **All** matching words — never truncated with “…”. Long lists scroll with a faint transparent scrollbar. Private / float / clipboard / emoji / the copied-text chip stay put. |
| Copied-text chip | After a copy, a pill to the left of the clipboard button shows the first two words and “…”. Tap to paste. Tap **×** to hide it until the next copy. Not part of the suggestion scroll. |
| Clipboard | Opens the on-device clipboard overlay. Lit while the overlay is open. |
| Emoji | Opens the emoji overlay (right of clipboard). Lit while the overlay is open. |

Password fields never show suggestions and never learn.

---

## Floating keyboard

Off by default. Turn it on from the float button next to private.

---

## Clipboard

- Opens **scrolled to the top** so the newest clips are visible. It does not jump to the middle or bottom.
- **Recent** and **Pinned** tabs sit on the **right**. Opening clipboard always lands on **Recent**.
- Recent shows unpinned copies with the newest at the top.
- Pinned shows every pinned clip, most recently pinned at the top.
- **No pin icon on cells.** Hint text sits **below** the tabs: *To pin text hold text so it will add in pinned list*. Long-press a clip to pin or unpin it.
- 3-column grid of on-device clips
- Long text is clamped to **two lines** with an ellipsis — the panel never grows taller than the keyboard
- **Space, Backspace, and Enter** sit at the bottom of clipboard / emoji / symbol overlays. They are a few pixels shorter than letter keys; Enter matches the keyboard Enter key.
- Scroll inside the overlay; deleting a clip reflows the grid
- Android system copy/cut is captured into history
- **Recent and pinned lists are unlimited.** DeskKey never auto-deletes old clips. Only you delete (Recent: swipe/clear; Pinned: unpin, then delete).
- Private mode does **not** hide clipboard
- NUM / CAPS / SCROLL LOCK LEDs are hidden while this overlay is open
- Clear (Recent tab only) removes unpinned clips

---

## Emoji

The smile button sits **to the right of clipboard**. The picker covers the **key area only** — keyboard height never grows. A long list scrolls inside the overlay.

Category tabs match a system-style emoji bar:

Recent · Smileys · People · Animals · Food · Cars · Play · Objects · Symbols · Flags · `:-)` emoticons

Recently used glyphs stay on-device (included in backup v3).

---

## Settings

### Appearance

Themes: Midnight, Graphite, Paper, Paper contrast, High contrast, Glass, Ember, Moss, Glacier, Terminal. Paper and Paper contrast are high-legibility light boards. Glass, Glacier, Ember, and Moss stay readable with floating transparency.

**Follow system** matches light/dark to the device theme.

Key height, scale, bottom/side padding, suggestion text size, clipboard text size, key previews, bevels, and key borders.

IME switcher bar and editing toolbar can be shown or hidden. Floating transparency lives here.

### Layouts & languages

Layout picker (QWERTY, QWERTZ, AZERTY, Dvorak, Colemak) and navigation cluster.

**Show / hide buttons** (all default on): settings, down arrow, undo, redo, Pad/123, Fn, private, floating, clipboard, emoji, one-hand, special symbols. Hidden chips free space; the rest reflow.

One-handed mode is off by default. The **hand** chip (not shown while floating) shrinks the board to half width. The empty side has **< / >** to flip sides and **↔** to drag-resize (42–82%). Side and width are saved.

The **#+=** chip opens a punctuation/symbol palette over the keys.

Numpad and F-row toggle from **Pad** and **Fn** in the More (⌃) panel. Floating still toggles from the suggestion-strip float button.

### Text correction

Suggestions, next-word, **auto-correction**, auto-cap, double-space period, punctuation chips, learn words, **private mode** (default off). Import word lists. Export learned words.

**Auto-correction** (on by default): on space, replace a misspelled word with the closest on-device match. Off in password, URL, and email fields.

**Auto-capitalization** (on by default): after `.` `!` `?` **and a space**, Shift turns on for the next letter. Backspacing a period does not turn Shift on. Tap Shift off to type lowercase. URL, email, password, and number fields stay lowercase. Tapping a suggestion still capitalizes the first word or a word after a period.

Private mode: suggestions still include words you already learned. DeskKey will not start learning new ones until you turn it off. Password fields never learn.

### Backup

JSON v3 backup of **settings + learned words + imported lists + clipboard + emoji recents**. Restore puts all of them back. File name looks like `deskkey-backup-2026-09-13-140500.json`.
