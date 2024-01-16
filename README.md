# **N**or**dr**as**s**i**l**
**N**or**dr**as**s**i**l** is a keyboard layout that provides an elegant and balanced typing experience by its use of a thumb-alpha, emphasis on middle fingers, and de-prioritisation of pinkies.
```
  q y o u -   j g n f k
z h i e a .   p d r s l
  x ' / , ;   b c m w v
        ␣       t
```

## Design
### The specific ideas that I brought with me on this quest were:
1. Take advantage of a thumb-alpha to alleviate other design restrictions (this became `t`).
2. On the consonant hand, use the top row middle finger key to its utmost potential (this became `n`).
3. Create a high-frequency middle->index roll on the top row (this became `ng`).

### As **N**or**dr**as**s**i**l** took root, these ideas also were incorporated, based on taste:
- The vowel hand has slightly higher use if we include `space` and `repeat`, but the consonant hand has higher *movement*, which is more taxing (it's roughly a 40/60 split). I'd suggest mirroring the layout if you are left-handed.
- `iy`, `eo`, `au` vowel block is used, flanked by `h` to maximise left-hand in-rolling and minimise redirects.
  - Naturally, punctuation is on this hand, which is often not used during casual chats. This alleviates some responsibility of the left hand at those times, further minimising movement, and eliminating lateral index stretches.
- `t`, the most common consonant, was chosen on the for the thumb-alpha because it usually appears predictably at the beginning or end of words/syllables, which is easier to mentally parse than alternatives such as `e` or `r`, that would appear anywhere in a word.
  - This also answered the "`h`-vowels or `th` roll?" question that plagued my mind in previous layouts.
- With the position of `n` (and `g`) decided, the `drsl` homerow sprouted, and the mnemonic, titular `ndrsl` homerow was formed.
- Digits are appropriately burdened, based on strength and dexterity, and pinkies are especially deprioritised.
- Extending fingers is preferred, except pinkies, which should curl.
- Redirects, lateral stretches, and pinky/ring scissors are avoided, especially on the left hand.
- Unrelated to **N**or**dr**as**s**i**l** specifically, I like to push `z` into a lateral pinky position in favour of another symbol key.

## Analyser statistics
### [Cyanophage](https://cyanophage.github.io/index.html)
![alt text](https://i.imgur.com/ODcQI0j.png "Nordrassil Stats - Cyanophage")


### [Layout Playground](https://oxey.dev/playground/index.html)
![alt text](https://i.imgur.com/wKF99xs.png "Nordrassil Stats - Layout Playground")

### [Keysolve](https://clemenpine.github.io/keysolve-web/)
![alt text](https://i.imgur.com/ZOy2KhK.png "Nordrassil Stats - Keysolve")

## Some musings
### Things I love about **N**or**dr**as**s**i**l**:
- Extremely low redirects, pinky/ring scissors, a near 3:1 in:out rolling ratio, a good balance between rolls and alternation, and `repeat` and `magic` keys make typing feel effortless, elegant, and deeply satisfying.
- Mentally, the 83:1 ratio for in:out-rolls that `h`-vowels boasts is enough to make me weep.
- Having `t` on the consonant hand's thumb is much nicer that `r` as I've had in the past.
- `qu` and `ld`--I absolutely adore pinky-and-index rolls! `could`, `should`, `queen`, etc. are wonderful. I also have this pattern on my symbols layer, for `<3`.
- Any words that include `ng`, `nd` or `rd`  go extremely hard due to index + middle finger rolling.
- Learning this layout forced me to use homerow mods, which I had been intending to do for a long time.
- And lastly, of course, I love `you`, reader. <3

### Here's what I *don't* like:
- The `nrm` column is the sad spot for this layout, as these letters combine with each other as SFBs and skipgrams fairly frequently. SFBs are mostly solved by the `magic` key (detailled below), but the skipgrams must be tanked by my middle finger, and while it does this comfortably, it still wouldn't *have* to, ideally.
  - An earlier iteration saw some rotations and an `xlm` consonant pinky for lower SFBs and "better stats", but my pinky was on fire, and not in a good way.
- This layout did *not* cure my mental illness.

### Why not place the higher-frequency `n` on the homerow, instead of `r`?
`n` is a better candidate for the upper middle-finger position than I initially realised when **N**or**dr**as**s**i**l** was but a sapling. Creating a layout with a deliberate priority for the upper middle-finger key was an experiment in creativity, and the resulting choice to give that place to `n` was initially based on intuition. Many moons later, a revelation visited me...

- I consider the verticality of rolls to be important, and 'downward' rolls are comfier than 'upward' ones. I'd suppose this is because our fingers have more strength in curling than extending (like a crocodile's maw!).
- `n` rolls predominantly as `n`-to-consonant, so in this position, it rolls downwards fairly consistently.
- `r` rolls both ways with any letter without much overall bias which would cause many and various 'upward' rolls if placed on the top row.
- placing `r` on the central, middle finger homerow position of the hand feels 'grounding' (I wish I could explain this feeling a bit better)

## Further optimisations
From the beginning, I included a [`repeat`](https://docs.qmk.fm/#/feature_repeat_key "QMK Documentation for the Repeat Key Feature") key in this layout, and about a month in, averaging ~65wpm, I added a [`magic`](https://github.com/Ikcelaks/keyboard_layouts/blob/main/magic_sturdy/magic_sturdy.md "Ikcelaks' Write-Up of 'Magic Sturdy'") key as well.

The full layout I use looks like this:
```
  q y o u -   j g n f k
z h i e a .   p d r s l
  x ' / , ;   b c m w v
        ␣ *   & t
```
`*` denotes the [`repeat`](https://docs.qmk.fm/#/feature_repeat_key "QMK Documentation for the Repeat Key Feature") key, and `&` the [`magic`](https://github.com/Ikcelaks/keyboard_layouts/blob/main/magic_sturdy/magic_sturdy.md "Ikcelaks' Write-Up of 'Magic Sturdy'") key.

I believe that a `repeat` key is a wonderful addition to any layout, providing you have a spare thumb key at your disposal! Double-letter SFBs make up a total of ~2.5% of all bigrams, and are only [slightly better than most other SFBs](https://old.reddit.com/r/KeyboardLayouts/comments/191i64f/actual_bigram_typing_data_from_136_million/); a `repeat` key solves this, by turning every double-letter SFB into an inward roll or alternate. If KLAs included double-letter SFBs in their SFB calculations, most modern layouts would have their total SFBs *tripled*, or worse! A `repeat` key offers an excellent enhancement to a layout at the cost of very little cognitive load--it is very easy to recommend.

A `magic` key on the other hand is less clear with what it offers, as the 'library' you use is self-set and deeply personal, and the cognitive load can be quite noticible. I tend to think of at as an "SFB-removal key", but as I use it more, I'm wondering if its true power lies in its ability to send strings to complete common n-grams in fewer keystrokes. Regardless, it is a powerful and versatile tool that you might also like to try! For a more detailed look, take a look at Ikcelaks' write-up of Magic Sturdy [here](https://github.com/Ikcelaks/keyboard_layouts/blob/main/magic_sturdy/magic_sturdy.md "Ikcelaks' Write-Up of 'Magic Sturdy'")!

## Variations
### Bring `z` back
I type (and speak!) British English, where `z` is even more rare than in American English. Other than in the layout itself, or talking about `z`, this page has no cases of `z` being used! For this reason, I exclude it from the usual 10x3 matrix and place it in a lateral pinky position (or on a combo). I know this isn't for everyone; were I to bring `z` back, I'd replace `/`, and arrange the layout as follows:

```
k y o u -   q g n f z
h i e a .   p d r s l
x j ' , ;   b c m w v
      ␣       t
```

To avoid SFBs, this change must make a few small rotations, most notable of which is `k` swapping hands. Compared to vanilla **N**or**dr**as**s**i**l**, this swap marginally lowers SFBs at the cost of increasing redirects and scissors a bit, and it transfers ~1% on finger load to the left pinky. I personally prefer `q` with `you`, but `k` is a good candidate, and works with this `z`-variation a bit better than `q`.

### Lean further into `magic`
This was as experimental variation I made in order to maximise the use that `magic` would get. In vanilla **N**or**dr**as**s**i**l**, `magic` can't solve for both the `rn` and `rm` SFBs, which are equally common, and that bothers me some. With `f` and `m` swapped, `magic` now solves `fr` with much greater consistency!

```
  q y o u -   j g n m k
z h i e a .   p d r s l
  x ' / , ;   b c f w v
        ␣ *   & t
```

This variation achieved its goal of making better use of `magic`, but I found that `m` felt odd up there for probably personal reasons. Also, the SFBs according to KLAs are quite a bit worse here, as they can't/don't account for `magic`. Still, I think this variation has merit, and I'd be interested to see what some other layouts might look like if they were changed to make fuller use of `magic`--or better yet, be designed from scratch with `magic` in mind!!

## Entomology
N/A.

## Etymology
**N**or**dr**as**s**i**l** is a mnemonic expansion of the defining features of the layout: its middle finger, top-row `n`, and unique `drsl` homerow.

In the Warcraft universe, Nordrassil is the sacred World Tree of the night elves, which grew over the Well of Eternity atop the summit of Mount Hyjal. Standing thousands of kilometers tall, its roots grow deep in the earth, spreading life-giving energy across the world.

This layout was almost called Yg**gdr**as**s**i**l**, before I realised that **N**or**dr**as**s**i**l** was even more magnificent!~

## Other links
### My full QMK keymap, Hyjal
Naturally, **N**or**dr**as**s**i**l** sits atop **Hyjal**; you can find the write-up for my keymap here: [to-do]

### General keyboard theory
I also have some related thoughts on keyboards that I didn't want to burden **N**or**dr**as**s**i**l** or **Hyjal**'s pages with, so I've collected them here instead: [to-do]
