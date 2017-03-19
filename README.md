# code_lens
A simple, locally loaded webpage to highlight sources of frequent coding issues in JavaScript. code_lens is a self contained HTML page using simple JavaScript and CSS. You can use it while you're offline and without worrying that your source code is being submitted to some unknown server.

# Purpose
Programmers-- especially novices-- struggle with syntax and style issues where often a single missing semicolon can cause code execution to fail-- sometimes with no error message generated.

code_lens is designed to reduce the extraneous cognitive load (http://www.instructionaldesign.org/theories/cognitive-load.html) associated with looking at your source code in order to draw your attention to sources of frequent errors. All characters other than those of immediate interest are greyed out.

There’s a method in hand drawing called “upside-down drawing”. The core idea is that when you see something in the world, your mind tries to make sense of it and, in so doing, causes you to skip over the details of what you’re seeing. By starting with an image that’s upside-down, your brain is thwarted-- it can’t replace the intricate detail in front of you with the simplified notion of “woman sitting in chair”. So, if you try to draw the upside-down image, you’re able better to focus on the lines, edges, shadows, and so on (http://www.learn-to-draw.com/drawing-basics/07-drawing-pencil.shtml). I’d be remiss were I not to mention that the causal talk about left-brian/right-brain is largely disproven (https://braindecoder.com/post/neil-degrasse-tyson-elegantly-debunk-right-left-brain-myth-1120713524), but the insight that seeing something from a different perspective can give one added ability to focus on detail seems valid.

code_lens (https://github.com/WilDoane/code_lens) is much the same. It tries to get your eye to stop seeing A Program™ and just focus on patterns. I’ve often referred to my own process when debugging as squinting my eyes and tilting my head to one side-- again, trying to see A Program™ from a different perspective.

I designed code_lens to reinforce the kinds of checks I myself perform: focus your attention on parentheses, curly braces, and so on. The "Unique Symbols" option in there produces a list of all the ways you’ve typed something. This is to explicitly get your mind to stop thinking of your code as "A Program™" with some special properties that are beyond your ken to understand and make it just... symbols... most of which you type yourself.

None of this is fool-proof, but the different code_lens views are supposed to help refocus your attention away from what you *intended* to program and toward the patterns that the JavaScript interpreter attends to in your code.

Over time, these checks become more second nature and code_lens is less important.

# To use
1. [Download this repository](https://github.com/WilDoane/code_lens/archive/master.zip) and, if necessary, unzip it.
2. Open index.html in your browser.
3. Paste source code into the text area.
4. Review your code using any of the available lenses: parentheses, braces, brackets, comments, end of line characters, etc.
5. Tweak your source code to test changes.
6. Copy and paste your source code back into your preferred text editor.
