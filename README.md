# Title

A page advertising a (fake) organisation at Dartmouth College. It's dedicated itself to cherrypicking the best napping spots on capmus, and distributing them via newsletter, as well as nominating a couple of such spots per month.

Landing pages referenced: [Starbucks](https://www.starbucks.com/) (90% of it), as well as [Flour Bakery](https://flourbakery.com/) (the remaining 10%).

[deployed url](https://dartmouth-cs52-21s.github.io/lab1-landingpage-michellecchen/)

## What Worked Well

Transitions and other hover effects: for links, for GIFs, etc. Helped spiff 'em up.

It isn't immediately apparent, but if you hover your cursor over the top GIF, it moves. If you mouse away, it goes back to its default frame.

## What Didn't

Preserving the GIFs for mobile dimensions was, apparently, an insurmountable task. Manually lowering the size of the images for the media query... a no-go. Many other attempts... also, no-go's.

I went with simply removing them altogether through `display: none`, but was unhappy with the compromise.

Also, the page violates a lot of design precepts that I would have followed, had I more time... The color palette I eventually settled for was the least painful one among several iterations.

## Extra Credit

- Animated GIF in the uppermost container that only moves if your cursor is currently hovering over it.
- Links in the header and footer that gradually darken & expand outward upon hovering.
- Hamburger menu. CREDIT: I used [this Medium piece](https://medium.com/@heyoka/responsive-pure-css-off-canvas-hamburger-menu-aebc8d11d793) as a close guide, and learned a lot about the pros/cons of using either the "checkbox hack" or the `:target` pseudo class.

## Screenshots

HTML layout:

![html](https://i.imgur.com/PDATSoa.png)
