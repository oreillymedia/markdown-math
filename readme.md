# Here's a test of some math


The new version of Atlas supports Markdown as a source format as well as HTML. So, if you like, you have the option of authoring .md files in Atlas, and then when you add them to the build list, we convert to proper HTMLBook behind the scenes (we take care of generating the necessary <section> tags, so you don’t need to worry about that)

Regarding math, you can indeed use the Latex equation editor. Or if you’re adding equations manually, just wrap them in a &lt;span&gt; with the attribute data-type=“tex”, like the following:

<span class="math-tex" data-type="tex">
   $ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $
</span>

Here's a formula:

<span class="math-tex" data-type="tex">
 $ lim_{x \to \infty} \exp(-x) = 0 $
</span>

And, one Ms. Rogers from High School algebra would love:

<span class="math-tex" data-type="tex">
 $ a^2 + b^2 = c^2  $
</span>


And finally:

<span class="math-tex" data-type="tex">

$ 
 begin{matrix}
  a & b & c 
  d & e & f
  g & h & i
 end{matrix}
$
</span>