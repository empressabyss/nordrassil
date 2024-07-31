# **N**OR**DR**AS**S**I**L**
**N**or**dr**as**s**i**l** is a keyboard layout designed for English that provides an elegant and balanced typing experience by its use of a thumb alpha, emphasis on middle fingers, deprioritisation of pinkies, and [`repeat`](https://docs.qmk.fm/#/feature_repeat_key "QMK Documentation for the Repeat Key Feature") key (or [`arcane`](https://github.com/empressabyss/nordrassil/blob/main/README.md#arcane-) keys).


**Vanilla** **N**or**dr**as**s**i**l** (likely preferable to most)
```
  j y o u -   q g n w x
z h i e a .   c d r s l
  k ' / , ;   b p m f v
        ␣ *     t
```
`*` denotes a [`repeat`](https://docs.qmk.fm/#/feature_repeat_key "QMK Documentation for the Repeat Key Feature") key. It isn't essential, but highly recommended.

___

**Abyssal** **N**or**dr**as**s**i**l** (my personal variant)
```
  q y o u -   j g n w k
z h i e a .   c d r s l
  x / ' , ;   b p m f v
        ␣ ⟐  ⟐ t 
```
 `⟐` denotes my `arcane` keys (see [**`ARCANE ⟐`**](https://github.com/empressabyss/nordrassil/blob/main/README.md#arcane-) section for details)
 
## DESIGN 
### The specific ideas that I brought with me on this quest were:
1. Take advantage of a thumb-alpha to alleviate other design restrictions (this became `t`).
2. On the consonant hand, use the upper middle finger key to its utmost potential (this became `n`).
3. Create a high-frequency middle->index roll on the top row (this became `ng`).
4. Utilise a `repeat` key on a thumb (this allowed `s` and `l`, which repeat frequently, to sit on weaker fingers).
	- Eventually, a `magic` key was added opposite `repeat`, and eventually this system matured into [`arcane`](https://github.com/empressabyss/nordrassil/blob/main/README.md#arcane-) keys.

### As **N**or**dr**as**s**i**l** took root, these ideas also were incorporated:
- The vowel hand has slightly higher use if we include `space` and `repeat`, but the consonant hand has higher *movement*, which is more taxing (it's roughly a 40 / 60 split). I'd suggest mirroring the layout if you are left-handed.
- `iy`, `eo`, `au` vowel block is used, flanked by `h` to maximise left-hand in-rolling and minimise redirects. It also gives maximum workload to the middle finger.
  - Naturally, punctuation is on this hand, which is often not used during casual chats. This alleviates some responsibility of the left hand at those times, further minimising movement, and eliminating lateral index stretches entirely.
- `t`, the most common consonant, was chosen on the for the thumb-alpha because it usually appears predictably at the beginning or end of words / syllables, which is easier to mentally parse than alternatives such as `e` or `r`, that would appear anywhere in a word.
  - This also answered the "`h`-vowels or `th` roll?" question that plagued my mind in previous layouts.
- With the position of `n` (and `g`) decided, the `drsl` homerow sprouted, as did the mnemonic, titular `ndrsl` string.
- Digits are appropriately burdened, based on strength and dexterity, and pinkies are especially deprioritised.
- Extending fingers is preferred, except pinkies, which should curl.
- Redirects, lateral stretches, and pinky / ring scissors are avoided, especially on the left hand.
- Unrelated to **N**or**dr**as**s**i**l** specifically, I like to push `z` into a lateral pinky position in favour of another symbol key: `/`. `z` can go on whichever pinky you prefer.

## ANALYSER STATS
### [Cyanophage](https://cyanophage.github.io/index.html)
![alt text](https://i.imgur.com/wvZC1Kf.jpeg "Vanilla Nordrassil Stats - Cyanophage")

### [Keysolve](https://clemenpine.github.io/keysolve-web/)
![alt text](https://i.imgur.com/el2Eyhh.jpeg "Vanilla Stats - Keysolve")

### [Layout Playground](https://oxey.dev/playground/index.html)
![alt text](https://i.imgur.com/7n19M5E.jpeg "Vanilla Stats - Layout Playground")

## SOME MUSINGS
### Things I love about **N**or**dr**as**s**i**l**:
- Extremely low redirects and pinky / ring scissors, a near 3:1 in:out rolling ratio, a good balance between rolls and alternation, and `repeat` make typing feel effortless, elegant, and deeply satisfying. Of the layouts I've learned (Qwerty, Dvorak, Hands Down Neu (kinda), two iterations of Just Rhea (an old layout of mine; writeup is a wip)), **N**or**dr**as**s**i**l** is by far my favourite.
- The 83:1 ratio for in:out-rolls of the `hiea` homerow is such stuff as dreams are made on.
- Having `t` on the consonant hand's thumb is much nicer that `r` as I've had in the past.
- `ld`! I absolutely adore pinky-and-index rolls! `could`, `should`, etc. are wonderful. I also have this pattern on my symbols layer, for `<3`.
- Any words that include `ng`, `nd` or `rd`  go extremely hard due to index->middle finger rolling.
- Learning this layout forced me to use homerow mods, which I had been intending to do for a long time. (This seems now to be my endgame mods system!)
- And lastly, of course, I love `you`, reader. <3

### The elekk in the room: `nrm`
The `nrm` column seems at first to be a rather sore point of **N**or**dr**as**s**i**l**, as these letters combine with each other as SFBs moderately, and 2u skipgrams quite a lot. However, middle fingers are effectively invincible, and can tank anything you throw at them. One of **N**or**dr**as**s**i**l**'s core goals is to take advantage of that fact.

Almost *half of all SFBs*, and *three-quarters of 2u skipgrams* are given to the middle fingers. They brush these blows off, granting the rest of the party the space they need to cast their own spells.

I will admit that I had an initial scepticism of `nrm`'s viability, but real experience dispelled it entirely, and I no longer believe that this column is problematic. Earlier, pre-release iterations of **N**or**dr**as**s**i**l** did attempt to solve the anticipated pain, but the results were considerable downgrades and always skewed workload to more more fragile fingers.

### Why not place the higher-frequency `n` on the homerow, instead of `r`?
`n` is a better candidate for the upper middle-finger position than I initially realised when **N**or**dr**as**s**i**l** was a sapling. Creating a layout with a deliberate priority for the upper middle-finger key was an experiment in creativity, and the resulting choice to give that place to `n` was initially based on intuition. Moons later, I managed to find the words to explain it:
- I consider the verticality of rolls to be important, and 'downward' rolls are comfier than 'upward' ones. I'd suppose this is because our fingers have more strength in curling than extending (like a crocolisk's maw!).
- `n` rolls predominantly as `n`-to-consonant, so in this position, it rolls downwards fairly consistently.
- `r` rolls both ways with any letter without much overall bias which would cause many and various 'upward' rolls if placed on the top row.

## `REPEAT` AND `MAGIC`
From **N**or**dr**as**s**i**l**'s conceptual stage, I included a [`repeat`](https://docs.qmk.fm/#/feature_repeat_key "QMK Documentation for the Repeat Key Feature") key, and about a month into learning it, I added a [`magic`](https://github.com/Ikcelaks/keyboard_layouts/blob/main/magic_sturdy/magic_sturdy.md "Ikcelaks' Write-Up of 'Magic Sturdy'") key as well. Eventually, I hybridised these to create my [`arcane ⟐`](https://github.com/empressabyss/nordrassil/blob/main/README.md#arcane-) keys, which have superseded `repeat` and `magic` entirely for me!

A `repeat` key is a wonderful addition to any layout, providing you have a spare thumb key at your disposal! Double-letter SFBs make up a total of ~2.5% of all bigrams, and are only [slightly better than most other SFBs](https://old.reddit.com/r/KeyboardLayouts/comments/191i64f/actual_bigram_typing_data_from_136_million/); a `repeat` key solves this, by turning every double-letter SFB into an inward roll or alternate. If KLAs included double-letter SFBs in their SFB calculations, most modern layouts would have their total SFBs *tripled*, or worse! A `repeat` key offers an excellent enhancement to a layout at the cost of very little cognitive load--it is very easy to recommend.

A `magic` key on the other hand is less clear with what it offers, as the 'library' you use is self-set and deeply personal, and the cognitive load can be quite noticeable compared to `repeat`.

Personally, I treat the `magic` similarly to `combos`, where for them to feel worthwhile, they must save time by sending a multi-character string, or preventing chording / hand contortions. I didn't find the usual SFB-reducing possibilities of `magic` to work for me.

For a more detailed look at `magic` and its uses, see Ikcelaks' write-up of *Magic Sturdy* [here](https://github.com/Ikcelaks/keyboard_layouts/blob/main/magic_sturdy/magic_sturdy.md "Ikcelaks' Write-Up of 'Magic Sturdy'")!

## `ARCANE ⟐`
More recently, I wound up creating a hybridised version of `repeat` and `magic` keys, which I call `arcane` keys, represented by `⟐`. `arcane`'s output is dynamically changed based on the preceding key, as expected, but it crucially also factors in which *hand* pressed the preceding key.

[Here is my original reddit post where my `arcane` keys debuted](https://www.reddit.com/r/KeyboardLayouts/comments/1cb2v3l/showcasing_my_implementation_of_hybrid_repeat/), which contains some discussion! The body of the post is more or less just the text written in the sections below, though.

### Usage
If the preceding key is on the **same hand** as the `arcane` key, it acts as a `repeat` key. This creates an inward roll for any letter that must repeat: finger->thumb. Double letters make up ~2.5% of all bigrams, which is a significant increase to inward rolling for *any layout*.

If the preceding key is on the **opposite hand** to the `arcane` key, it acts as `magic`, which, as mentioned in above, will provide varied benefits completely decided by the individual. 

### Showcase
Here is a video showcasing the way `arcane` works in practice: https://www.youtube.com/watch?v=P8a-Mzgbl8c

The innermost thumb keys are the `arcane` keys, and each use of them in this video is for the `repeat` functionality only. This hopefully shows that the rhythm gained by this implementation is quite nice and flows smoothly. I found that having my left hand be responsible for `repeat` entirely was noticeably taxing, and splitting it between both hands like this solved that in addition to improving in-rolling stats.

As an aside, my key labelled `j` is set to `backspace` in this showcase, because I'm currently on an arduous quest to figure out where I like it to lay. As of 2024-07-28, I have two `backspace` keys, which flank the thumbs (they are also `layer-taps`, and give `delete` when used with `shift`).

### Implementation
My simple implementation is to define two [custom alternate repeat keys](https://docs.qmk.fm/#/feature_repeat_key?id=additional-alternate-keys) (one for each hand) and manually curate a library of outputs. This is very human-readable and easy to understand and configure, but the initial setup could be a bother. I haven't set up a repository for my keymap on Github, but here's a pastebin copy of my `keymap.c`, which contains everything you'll need: https://pastebin.com/j0pfKzBR

I will also gladly help anyone with this implementation if they run into issues! <3 You can message me on reddit; /u/empressabyss.

I'm sure the magi among you can find a way to base their function on matrix positions and *actually* call the `repeat` or `magic` functions case-by-case, and I will leave that possibility in your very capable hands. I'm just a girl in a world.

### Caveats
- Layouts with a thumb-alpha (like **N**or**dr**as**s**i**l** lol xd) will unfortunately have to have said alpha as an *alternate* instead of an in-roll to avoid it being an SFB. I've had no issues with this in practice (muscle memory is doing its job), but mentally its a bother due to inconsistency. Alas, to live is to suffer.
- My `arcane` keys are set are on opposite thumb keys. They're symmetrically placed and intuitive to read as sisters or equivalents. `arcane`'s concept may not work so cleanly if your implementation looks more like [Magic Sturdy](https://github.com/Ikcelaks/keyboard_layouts/blob/main/magic_sturdy/magic_sturdy.md), where `magic` is part of the alphas' 10x3.

## ABYSSAL **N**OR**DR**AS**S**I**L**
```
  q y o u -   j g n w k
z h i e a .   c d r s l
  x / ' , ;   b p m f v
        ␣ ⟐  ⟐ t 
```
`⟐` are my `arcane` keys.

This is the variant that I personally use (as of 2024-07-28), which is much closer to **N**or**dr**as**s**i**l**'s original release, as that was designed specifically for my keyboard, hands, and taste (whereas *Vanilla* is designed to be better for the general audience).

Key changes:
- `x` swapped with `k` to lower redirects and skew workload away from my weak left pinky.
- `q` swapped with `j` for a pinky->index roll when typing `qu`. I also love it mnemonically!!
- `'` swapped with `/` because it distributes workload more appealingly, and it feels 'wrong' to me (in practice and theory) to place such a rare character on the very stronk middle finger. Punctuation also often takes a back seat when chatting casually, so `'` doesn't result in nearly as many SFBs as corpora suggest!

## KEY COMFORT MATRIX
For a little more context for my decision-making, I thought the key comfort matrix that I used while designing **N**or**dr**as**s**i**l** would be useful to see.

Each position considers the assigned finger's strength and dexterity, and the effort required to move from the home position during regular typing. Everyone will have a different opinion about this, but this should help to contextualise some decisions I made.

```
A lower value is better~

  9 7 1 3 9   9 3 1 4 7
9 2 1 0 0 6   6 0 0 1 2 9
  5 6 3 4 8   8 4 3 6 5
          0   0
```

Notice the keys in the upper pinky positions: for my hands, the left pinky is notably worse than the right pinky. This is reflected in the *Abyssal variant* of **N**or**dr**as**s**i**l**, which displaces `k` in favour of the lower-frequency `q`.

## ETYMOLOGY
**N**or**dr**as**s**i**l** is a mnemonic expansion of the defining features of the layout: its middle finger, top-row `n`, and unique `drsl` homerow.

In Warcraft, Nordrassil is the sacred World Tree of the night elves, which grew over the Well of Eternity atop the summit of Mount Hyjal. Standing thousands of kilometers tall, its roots grow deep in the earth, spreading life-giving energy across the Azeroth.

As an extra branch of fun (something I realised months after creating **N**or**dr**as**s**i**l**), when read bottom-to-top, **N**or**dr**as**s**i**l** could become **T**el**dr**as**s**i**l**. Teldrassil is the second World Tree--that sprouted from an acorn of the first--and became home to the night elves. Given that both `t` and `n` were the most important letter-placement decisions through the design process, the fact that it turned out so mnemonically perfect like this is deliciously satisfying. A~~n Emerald~~ dream come true.

In its early stages, this layout was almost called Yg**gdr**as**s**i**l**, before I realised that **N**or**dr**as**s**i**l** was even more perfect.

## OTHER LINKS (wip lol rip)
### **Hyjal**, my full keymap
Naturally, **N**or**dr**as**s**i**l** sits atop **Hyjal**; you can find the write-up for my keymap here: [to-do]

### General keyboard theory
I also have some related thoughts on keyboards that I didn't want to burden **N**or**dr**as**s**i**l** or **Hyjal**'s pages with, so I've collected them here instead: [to-do]
