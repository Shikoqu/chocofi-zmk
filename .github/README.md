# Chocofi Layout

![chocofi build](/.github/assets/chocofi-build.jpg)

## Key principles

### 1. Use toggleable layers

Rather than flexing fingers to strike couple of keys at once (activate layer, press layer key even when additional modifier - already 3 keys!) this allows to toggle layer and frealy type whatever, then switch back to base.

This is not popular approach since it is easy to get lost... *On which layer am I again??*
To remedy that I will keep return to base layer on all layers (but base) so It is always easy to orinent yourself.
The key on tha base layer would of course be used in other ways so if I'm lost and I definately don't want to type any unwanted characters, I can just jump to next layer and and back to base.

The nice feature worth adding is:
toggle when clicked,
sticky when hold - so when I have to type only one key I dont have to jump back and forth.
This is my original idea and I will definately need to experiment with it.

### 2. Home-row mods

Home-row mods can be tricky and annoying when not set up correctly.
Espeically ones that influence letter being typed.
Unfortunately in Polish language we have *diacritics* (letters with dicks sticking out - `ą` `ć` `ę` `ł` `ń` `ó` `ś` `ź` `ż`) that are typed by holding down alt/option and pressing a letter key.
So aside from `shift ⇧` that swithes to implicit capital layer, we also have `opt ⌥` that switches to diacritics.

I don't want to tinker with microscopic delay parameters and I expect HRM to not interfeer with rolling while typing.
So I will keep `shift ⇧` and `opt ⌥` as sticky modifiers activated on thumb keys.
That leaves `cmd ⌘` and `ctrl ⌃` as *HRM*, well maybe I will add `MEH ⌃⌥⌘ = ∴` or `HYPER ⌃⌥⌘⇧ = ∷` in.

### 3. Things to remember

* **`cmd ⌘` + `tab ⇥` - app switcher** --
`cmd ⌘`, `tab ⇥`, ``backtick ` ``, `shift ⇧` & `Q` (for quiting apps) - all keys need to be easily accessible in the same layer
(do I really need to switch between windows of the same app?? - ``backtick ` ``)

* **`backaspace ⌫` or `forward delete ⌦` on left hand** --
so it's easy to operate and delete text with mouse in right hand

* **Cursor and text select with arrows** --
`←` `↑` `→` `↓` with `shift ⇧` to select text, `opt ⌥` to jump words, `cmd ⌘` to jump lines & `ctrl ⌃` because some programs ar not compliant with MacOS standards

* **Window management - earospace** --
letters and easily stackable modifiers

* **Thumbs do not write hcaracters** --
one change at a time... thumbs are for mods, navigation and `space`, `return ⏎` & `tab ⇥`

---

## Chocofi size

* 36 keys
* column stagger with 3 keys for each column where index has two columns
* 3 keys per thumb

```txt
0 1 2 3 4  |  5 6 7 8 9
0 1 2 3 4  |  5 6 7 8 9
0 1 2 3 4  |  5 6 7 8 9
    l l l  |  r r r
```
**legend**:
* l - left thumb
* 0 - left pinky
* 1 - left ring
* 2 - left middle
* 3 - left index
* 4 - left index
* 5 - right index
* 6 - right index
* 7 - right middle
* 8 - right ring
* 9 - right pinky
* r - right thumb

---

## Layers

### Base - AL (alphanumeric)

Letter layout: ***Desend thumbshift***

```txt
x c l f v  |  . - u p q       X C L F V  |  ? _ U P Q       ź ć ł F √  |  ! / U P Q
r s n t g  |  , a e h i       R S N T G  |  ; A E H I       R ś ń T G  |  : ą ę H I
z w m d b  |  ' o y k j       Z W M D B  |  " O Y K J       ż W M D B  |  ` ó Y K J
    ∴ ⇧ ◡  |  ↷ ⌥ ⏎               ∴ █ ◡  |  ↷ ⌥ ⏎               ∴ ⇧ ◡  |  ↷ █ ⏎
```

letters + most used symbols for prose and programming:
`. , : ; ? ' - _`

#### Additional functionalities:

**Implicit layers**:
* `⇧ shift` - capitalize
* `⌥ opt` - polish diacritics

**HRM**:
* middles `⌘ cmd` (letters: `n` & `e`)
* pinkies `⌃ ctrl` (letters: `r` & `i`)

**Thumbs**:
| Key | Tap                | Hold           |
|-----|--------------------|----------------|
| L3  | `⌫ fw-delete`      | `∴ MEH`        |
| L2  | `⇪ caps` for words | `⇧ shift`      |
| L1  | `◡ space`          | `◡` repeated   |
| R1  | `↷ next layer`     | `↷ next layer` |
| R2  | `⇥ tab`            | `⌥ option`     |
| R3  | `⏎ return`         |                |

**Symbols**:
| symbol | shift | option  |
|--------|-------|---------|
| `.`    | `?`   | `!`     |
| `,`    | `;`   | `:`     |
| `'`    | `"`   | `` ` `` |
| `-`    | `_`   | `/`     |

### Symbols & Arrows - SA

```txt
_ _ _ _ _  |  _ _ _ _ _       _ _ _ _ _  |  _ _ _ _ _
< { [ ( _  |  ◁ △ ▽ ▷ ␛       > } ] ) _  |  ← ↑ ↓ → ␛
_ _ _ _ _  |  _ _ _ _ _       _ _ _ _ _  |  _ _ _ _ _
    ∴ ⇧ ↶  |  ↷ _ ⏎               ∴ █ ↶  |  ↷ _ ⏎
```

**More symbols to fit**:
`@` `#` `$` `%` `^` `&` `*` `+` `=` `~` `|` `\` 
`.` `?` `!` `,` `;` `:` `'` `"` `` ` `` `-` `_` `/`
`€` `¡` `¿` `←` `↑` `↓` `→`

#### Additional functionalities:

**HRM**:
* left middle `⌘ cmd` (key: `[`)
* right ring `⌥ option` (key: `{`)
* pinkies `⌃ ctrl` (key: `<`)


### Numbers - NB

```txt
_ _ _ _ _  |  / 7 8 9 -
_ _ _ _ _  |  * 4 5 6 +
_ _ _ _ _  |  0 1 2 3 .
    ∴ ⇧ ↶  |  ↷ _ ⏎
```

Numbers like on a numpad (except 0 not on thumb)

### Game - GM

```txt
⇢ q w e r  |  _ _ _ _ _
⇧ s d f g  |  _ _ _ _ _
⌃ z x c v  |  _ _ _ _ _
    ␛ _ ◡  |  _ _ _
```
