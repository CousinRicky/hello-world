# hello-world
I’m trying to learn this thing.

Thumbnail test:
![Thumbnail](thumbnail.png)

**`Bold code`** test (with a `regular code` control), because Okular doesn’t seem to handle the nesting.

A [Link to a project document](a_document.html).

---

How Does | GitHub Render | Markdown Tables?
---------|---------------|-----------------
   The   |  quick brown  |       fox
jumps over |    the      |     lazy dog

---

Okular outdents Step 3 improperly, perhaps due to the pound sign. How does GitHub’s renderer do?

1. Set `global_settings { assumed_gamma 1 }` *before* using any of the keywords.

2. An sRGB triplet that comes from a color picker, eyedropper tool, or published Web source is typically in the range <0,0,0> ... <255,255,255>. These are byte triplets. However, POV-Ray does not use byte triplets; these must be divided by 255 to bring them into the range <0,0,0> ... <1,1,1>. This *must* be done first thing, and is the only math that should ever be done at this stage, though it may be combined with step 3. If the color is specified in percentages, of course you would divide by 100 instead of 255.

3. `#declare` (or `#local`) the color with the `srgb` keyword. The resulting identifier contains a linear color. *If and only if* no additional math is required, you may skip the `#declare`/`#local` and use the `srgb` directly in a pigment or light_source.

4. Now, do whatever additional math you need on the identifier. You may do this in a pigment or light_source or wherever.

---

A superscript ^1, and another superscript^2. More superscripts here ^3 and here.^4

^1 Footnote.
