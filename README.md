![pnohty@4x](https://user-images.githubusercontent.com/16619392/147719604-40cfd0fa-5fde-4c3e-927e-486d6c296122.png)

# Pnohty

**naw** · tee

An optimized keyboard layout for people who like Python, Vim, and tiny split keyboards ;)



- [Quick start](#quick-start-ease-into-it)
- [Design principles, or how to be Pnohty ;)](#design-principles)
- [FAQ](#hesitant-to-join-in-the-fun)
- [Effort model](#effort-model)
- [Frequency analysis](#frequency-analysis)

## Features

- 3X5+3, but compatible with 34 key (2 thumb keys each side) and even 32 keys (no top row pinky keys, W+P=Q).
- Coding usage priorised. Symbols and numbers are within reach. Bigrams are easy to roll.
- Combos for mods. No fiddly settings and timing issues with homerow mods. No flow breaking holds with autoshift or hold-taps in general. 
- ...but not so many combos that it feels like dance dance revolution. Only 3–6 combos in comfortable positions.
- Vim navigation layer, activated with the right thumb and pinky on home positions.
- Leaves 12 keys unassigned for your favourite shortcuts. 4 of these positions are quite nice.

## Quick start: ease into it

- `_` is on the right middle finger, typable with one hand on the NUM layer. Underscore is the most frequent symbol, just like **E** is the most frequent letter.
- `-` is above `_` (or that underscore is under it), typed with extended middle finger.
- Parentheses, square and angle brackets, as well as curly braces are all in the middle column.
- `( )` are on the left ring and middle fingers. associated symbols `:` and `*` sit just beside it.
- On the right hand, there are the quotes `'`(on SYM) and `"` (on NUM). The semicolon rests on the pinky.
- Equal `=` is on the key **I**, think **I**dentity.
- Vim navigation layer is actuated by thumb on NUM and pinky on **O** (their home positions!). "**HJKL**" as you expect for QWERTY.
- Numbers are on a modified numpad, with 321 on the home row, 0 on thumb, and a `.` on the pinky for quicker access. `~` can mean approximately, so it is under `.` at the bottom left corner.

![pnohty@4x](https://user-images.githubusercontent.com/16619392/147719604-40cfd0fa-5fde-4c3e-927e-486d6c296122.png)


- Hash `#` is on **H**. `+`, hash's lookalike, is on the same key.
- If you draw a line from the **NUM** mod, at **L** you get `|`. If you draw a slanted line to **Y**, you get `/`
- If you draw a line from the **SYM** mod, at **P** you get `$`, which has a straight line through it. If you draw a slanted line to **W**, you get `\`.
- For punctuations, `?` is on `,` and `!` is on `.`. The question mark can imply an anticipated response, while an exclamation mark is more finished. This hopefully mirrors `,` and `.`.
- `%` and `&` remain paired with their numbers. `@` is below **2**.
- ` ` ` gets the better remaining spot on X. `^` takes the L.

## Design principles
### It should feel real good! Most comfortable positions reserved for frequenters

- Incorporates additional analysis specific to tiny split keyboards.
- Space or Enter, which way does it swing? Avoids same thumb bigrams.
- Common Python bigrams are respected and positioned to faciliate rolls.

### Was that too fast? Time is not of the essence

- Eschew functionalities which require precise timings (or waiting) that may otherwise misfire.
- No homerow mods!
- Low frequency bigrams in comfortable positions are used for combos instead.

### **P**ython and **V**im: a match made in heaven

- A base of Colemak-DH mixed with fresh Python, plus a splash of Vim.
- But all are welcome! If you have a more deviant use case, feel free to do...
  
### What it is that we do ;)

- The vanilla version is perfectly good on its own, but there are 12 open slots in the middle for your favourite things (shortcuts, rgb control, etc), 4 of which are quite comfy.
- Swap em! If you use other programming languages, a good place to start is switching `{ }` and `[ ]`. The heavy use of brackets over braces is quite peculiar of Python.
- Really want to hit that spot? Open slots make it easy to rearrange your layout.

### Size doesn't matter

- Pnohty is compatible with most split keyboards. In its most concise configuration, only 32 keys are needed. This has no top row pinky keys and only two thumb keys per side.
- With more keys, some of the combo mods can move onto extra thumb keys.

## Hesitant to join in the fun?

### Why is enter on the right thumb?

- If you use the mouse with the right hand, then left thumb on space should be well practiced.
- As opposed to prose, code has very short lines. A good practice is to limit lines to 80 characters, but often lines are under 25 characters. The frequency of return is thus a lot higher for programmers. This is further increased with command line usage and Vim.
- I also happen to enjoy outliners, especially [Logseq](https://logseq.com/). Enter usage is high, as each thought is broken down into bitsized components.

### Why no homerow mods?

- Some popular key layouts such as the [Miryoku](https://github.com/manna-harbour/miryoku) uses homerow mods. But you will often hear of complaints about them being fiddly and error prone.
- See [Callum Oakley](https://github.com/qmk/qmk_firmware/tree/master/users/callum) for an example of why some user may not like homerow mods or mod-taps in general
- Do take a gander at [precondition](https://precondition.github.io/home-row-mods)'s definitive guide on home 
row mods, if you would like to try and make it work.
- But I prefer wearing clothes that look good without me having to measure and tailor it to every aspect of my body and appendages.

### Why no Callum-style mods?

- Callum-style or [Seniply](https://stevep99.github.io/seniply/)-style mods obviates the use of mod-taps, that's great!
- However, mods take up 4 of the best spots on each layer.
- That's 8 symbols evicted from the homerow!

### Hasn't Precondition's article ruled out alternatives to home row mods?

- Not quite. It was said that sticky combo home row mods are more prone than home row mods for misfires. But misfires are next to impossible for uncommon combination of letters that are nonetheless easy to type!
- Take W+F, the combo for Shift, for example. How many words containing WF or FW can you think of?
- It may just take you quite a while, since it is a very rare bigram.
- There are the words awful, lawful, newfound, halfway, etc.
- [Bigram based on google corpus](https://gist.github.com/lydell/c439049abac2c9226e53) and my testing reveals that W+F ranks 259 out of 351 total 2 letter combinations. For any two letters typed, it will be a combination of W and F 0.00000018% of the time! 
- The number is 0.00000027% for the Python corpus, presumably because some acronyms may involve fw, e.g. firewall, firmware. 
- Note that distribution of bigrams has a long tail, the Top 100 bigrams are responsible for about 76% of all bigrams.
- X+C is ranked 193 out of 351. W+P, my preference of combo for Q, is ranked 255.

## Wait a minute!
### Aren't combos just mod-taps in disguise?
		
- Yes and No. Combos are a bit like mod-taps (or hold-taps in general), because timing is involved. 
- However, rather than having to wait until the mod actuates, combos fire the moment all requisite keys are pressed down. This obviates the awkward and flow-disrupting wait for mods. 
- Further, by selecting rare bigrams for combos, there is little chance of misfires. 
- The default timing for combos probably works out of the box, but you may further reduce the already hardly perceptible delay by reducing the time window for combos. 
- This is not possible for hold-taps, which have to set a high waiting time (thereby a large delay) to avoid setting off a hold behaviour when the finger lingers on the key for too long.

### Isn't space+return the most common bigram for Python code?

- This figure is greatly inflated by the automatic space insertions handled in most editors, i.e. no manual typing required, to maintain the important identations of Python code. In reality, I have never needed to type a space before or after an enter.

### The number layout is bizzare!

- Yes. Numbers are not priortized in Pnohty; their occurance in python code is fairly low. 
- Normally in a right hand side numpad, numbers are written 123. In a mirrored left hand side numpad though, I figure that numbers are written 321.


## Effort model

Inspired by Workman and Colemak-DH, I have came up with the following effort model.

<img src="https://user-images.githubusercontent.com/16619392/147722505-37ec029c-ff89-4a5a-8c6e-f5f75fb0fd77.png" data-canonical-src="https://user-images.githubusercontent.com/16619392/147722505-37ec029c-ff89-4a5a-8c6e-f5f75fb0fd77.png" width="400" height="400" />

I found that when holding down layer mods, key positions very close to the thumb (mostly the lower row) are less comfortable, due to needing to squeeze the hand together. I am fortunate to have been to play the piano, which has significantly improved my finger independence and strength. I don't find the pinky to be weaker than my other fingers (from smashing them octaves in quick succession), but this effort model is made with an untrained hand's strength and weaknesses in mind. My pinky is nonetheless my shortest finger, 

There are two further negative experiences that I wanted to avoid. First, the switching of layers while typing a long string of characters should be minimized. Holding down the same layer mod and tapping two keys are more comfortable than having to release a mod and shift to the other hand. Switching back and forth rapidly is inefficient and extra work. This is why `( ) : '` are all on SYM, and `+ - =` are all on NUM. `(':')` is typed with thumb on SYM and `+=` is typed with thumb on NUM. Second, same thumb bigrams are bad. As thumbs are used for both layer mods and the keys space and enter, there may be occasions where e.g the thumb need to switch from pressing NUM to enter (and back). Suppose that the colon `:` is now on the NUM layer. `:` is very frequently followed by enter, which then requires a lifting of thumbs for each occurance. 

## Frequency analysis

#### Overal character frequency

![overall_char_freq](https://user-images.githubusercontent.com/16619392/147722766-c9d89557-e6cf-4f83-9a81-eee5c4c74189.png)

#### Overal symbol frequency

![overall_symb_freq](https://user-images.githubusercontent.com/16619392/147722767-e9da5842-994e-4803-844d-389be5b6a860.png)

#### Overal bigram frequency

![bigrams](https://user-images.githubusercontent.com/16619392/147722776-49b1f2e5-df36-4717-9ec8-0c0fae184d5e.png)

### Corpus
#### Notebooks

- jupyter-naas/awesome-notebooks
- rossant/ipython-minibook
- rajathkmp/Python-Lectures
- eka-foundation/numerical-computing-is-fun
- ricardoduarte/python-for-developers
- jakevdp/PythonDataScienceHandbook 
- thomas-haslwanter/statsintro_python
- jdwittenauer/ipython-notebooks
- huggingface/notebooks

#### Python files

- TheAlgorithms/Python
- mwaskom/seaborn
- numpy/numpy
- tensorflow/tensorflow
- django/django
- pallets/flask
- psf/requests

#### Mixed

- google-research/google-research 
- rasbt/python-machine-learning-book-3rd-edition
- deepmind/deepmind-research

## Additional keyboard layout reading material

- [Colemak-DH](https://colemakmods.github.io/mod-dh/)
- [T34](https://www.jonashietala.se/blog/2021/06/03/the-t-34-keyboard-layout/), which also includes several revisions.
- [Kombol](https://github.com/skychil/kombol), which is a lot of much combos.
- [Hands Down](https://sites.google.com/alanreiser.com/handsdown/home/design-notes), an interesting read.

## Practice tools

- [Monkeytype](https://monkeytype.com/)
- [Typelit](https://www.typelit.io/), type literature.
- [typing.io](https://typing.io/)
- [speedcoder.net](https://www.speedcoder.net/)
