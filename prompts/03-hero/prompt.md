# 03 A hero that does something

A complete build prompt for one section, the first screen. It is written for a fictional paint maker, Ochrewell; change the four lines under THE BUSINESS, and the idea under THE IDEA, for yours. The visitor does what the business does.

See what an AI coding agent built from it: https://vibesignet.com/website-prompts/demo/ (we have changed one thing since, the slider, which jerked on phones)

Works in Claude Code, Codex, Cursor and any AI coding tool.

```
Build the first screen (the hero) of a home page, as one HTML file, one CSS file and one small JavaScript file. No frameworks, no libraries, no images to download: everything is drawn in code.

THE BUSINESS (change these four lines for yours)
Business: Ochrewell, a small paint maker in Bristol that grinds its own pigments
Visitor: someone choosing a colour for a room, who has been burned by tester pots that look different on the wall
One action: order a sample pot
The verb: mixing. The visitor mixes the colour themselves.

THE IDEA
The first screen is a paint mixer. Two pigments sit at either end of a long horizontal strip: Raw Ochre on the left, Prussian Blue on the right. The visitor drags a marker along the strip, and a large swatch fills most of the screen with the mix. As the mix changes, three things change with it: the colour's name, its recipe ("64% Raw Ochre, 36% Prussian Blue"), and the colour of the button. The swatch is the hero image.

HOW IT LOOKS
- A warm off-white ground (#F3EEE4) with dark ink text (#1D1B18). The swatch is the only strong colour on the screen.
- The swatch is a soft-edged painted rectangle, not a flat box: a faint grain, slightly uneven edges, as if brushed onto paper.
- Headline in a high-contrast serif, about 7vw on desktop and 11vw on a phone: "Mix it before you paint it."
- One line below it: "Drag between the two pigments. Order the colour you made as a sample pot."
- The brand name top left in small capitals, one link top right ("Colours"), nothing else in the header.
- The strip sits under the swatch, full width of the content, with each pigment shown as a small ground pile of colour at its end and its name beneath.

HOW IT BEHAVES
- Mixing is not a straight blend. Mix the two pigments the way paint does (in a perceptual colour space such as OKLab), so the middle is a muddy green-olive, not grey.
- Give 9 named stops along the strip (for example "Harvest", "Lichen", "Estuary", "Slate") and show the nearest name. Snap gently to a stop when the drag ends.
- The swatch answers within 100 ms of any movement.
- Works by touch, by mouse and by keyboard: the marker is a real range input underneath, styled, so arrow keys move it and screen readers announce the name and recipe.
- The button reads "Order a sample of [name]" and takes the current colour.
- With reduced motion on: no grain animation and no easing; the swatch changes instantly.
- Start at the "Lichen" stop so the first frame already shows a mixed colour.

RULES
- Phone first: it must work at 360 px wide. Touch targets at least 44 px. No sideways scroll.
- No text over the busiest part of the swatch.
- No preloader, no capsule-shaped buttons, no drop shadows on everything.
- When it works, open it in a browser at 1440 px and 390 px wide, drag the marker from one end to the other, and list anything you could not check.
```

Previous: [02 Three directions](../02-three-directions/prompt.md)

From [Vibesignet](https://vibesignet.com), website templates with build prompts for Claude Code and Codex.
