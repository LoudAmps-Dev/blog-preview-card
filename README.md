Small practice project from Frontend Mentor.
The goal was to recreate a simple blog preview card using only HTML and CSS.

Notes / Things I ran into
Spacing issues (badge + date)
The badge and the date were sticking together.
I first tried adding margin-bottom to the badge, but nothing changed.
Later I realized the badge was a <span> (inline), so vertical margins don’t work there.

The proper fix would be to make it display: inline-block or block, but since I wasn’t thinking about that at the moment, I solved it using margin-top on the date. Not the cleanest solution, but it worked and matched what I knew at the time.

Image alignment
The main image wasn’t centered and the border radius didn’t show.
I fixed it by making the image a block element and giving it width: 100% and border-radius.

General layout
Most of the work was adjusting spacing and understanding how each element behaves.
Good reminder of how inline vs block elements affect margins.

Tech: HTML & CSS
