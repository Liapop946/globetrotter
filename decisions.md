# Globetrotter — Decisions Log

## Milestone 0: Setup and Planning
- Destination chosen: Bandung, Indonesia
- Primary audience: Group travellers/first-time travellers
- One design decision that reflects the destination: Earthy colour palette
- Wireframe format used (hand-drawn / Figma / other): hand-drawn

## Milestone 1: HTML Structure
_Add entries after building each page._
- HTML structure choice: using <div> for card container because it felt like a simple way to group together the cards with the class attribute defining what it is.
- One thing Claude generated that I changed: Footer tag and section were removed because it was not included in my design plan and felt unnecessary
- One place where your wireframe guided a specific decision about structure: The layout for the attraction cards in my attraction homepage wireframe guided the structure for the rest of the pages and I even decided to change some of the structures of the other pages from their original wireframe so the layout looked more cohesive.

## Milestone 2: CSS Styling
_Add entries after applying styles._
- One color or font choice you made, and why it serves your destination: I chose the cursive font style because I think it encapsulates the feeling of the destination. The cursive font also shows more of the European influences that Indonesia posesses.
- One Claude suggestion you rejected, and why: Font sizing was too small, so I opted for a clearer text size to improve readability.
- One style that didn't look right at first, and what you changed: The brighter shade of green that I initially had because it looked to abrasive, so I opted for a darker shade and color palette.

## Milestone 3: Flexbox Layout
_Add entries after implementing Flexbox._
- One Flexbox property choice you made deliberately, and why: I wanted to use have my cards be in the middle of the page so everything looked centered, which is why I wanted to use the justify-content property to align the cards in the way that I wanted.
- One place where Claude generated a layout that didn't match your plan, and what you changed: There were no issues with layouts with Claude, so I didn't need to change anything.
- One layout challenge that required adjusting your HTML structure, and why: I had to change the <div> tags and change the names of classes so that the code could be more simple and all of the cards followed the same rule ensuring that they get styled the same way.

## Milestone 4: Responsive Design
_Add entries after implementing media queries._
- One layout challenge that required adjusting your HTML structure, and why: I used breakpoints for 320px, 768px, and 1024px because those are the sizes of the most common devices such as phones, tablets, and desktops.
- One section where the mobile layout needed to feel genuinely different, and what you did: Since phone screens are much smaller then desktops, text sizes would look smaller and harder to read on a phone, so I decided to increase the font sizes to increase the readability. In addition, I ensured that only two cards would appear in a row for smaller device layouts compared to the three cards in a row for desktop layouts.
- One Claude suggestion about breakpoints you accepted or rejected, and why: Mainly that the text sizing was too small which made it difficult to read for phone users, so I rejected and set a larger font size myself.

## Stretch Features
_Add entries if you implement any stretch features._