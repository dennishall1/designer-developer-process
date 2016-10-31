# Designer to Developer Process

Let's improve our designer-developer process.


## Photoshop

Once upon a time, I used to push for photoshop documents to be better organized.  But that never actually happened.  To this very day, every photoshop document I've opened, if you click the eye next to a layer group, does nothing, you still have to go into that folder and figure out which individual layers to turn on.  Screw that.

Do developers really need photoshop?  I use pixel perfect chrome extension and have not needed to open a PSD in ages.  If I need a color, I ask the designer.  And if I need to ask for a new color, I also ask for a reason we need another color, and ask that it be added to the style guide, which should be a living document that exists from the very conceptual stages of the project, through to the final handoff and beyond.


## Responsive Web Design

This topic was really the impetus for the genesis of this document.

First, a very brief correction of a common misconception.  Responsive web design does not mean designing for mobile, tablet, and desktop.  It means designing for screens of certain width ranges.  That is an important distcinction because, although a phone in landscape is still a phone, it is not still the same width. This is not just a point of issue for designers and developers, but something that should likely be handled at the client-education level.  If you rotate your phone over to landscape, you've just decided to pretend you're holding a very short tablet, and the site will render accordingly.

"Mobile first" is an oft-heard anthem.  But it has only been enacted perhaps once or twice in Razorfish history to date. I think that UX might be doing a little better, but creative tends to design desktop first.  If different designers are assigned to desktop and mobile, they need to work very closely together, with daily cross-reviews at minimum.  Any time a change is made to either breakpoint, we must always think about how it will affect the other breakpoint(s)--and update the cr,ux for consistency.

"Tablet" (or 'medium breakpoint').  The tablet breakpoint usually receives the least love, with the assumption often being that desktop will more or less just work here.  It _usually will not "just work"_.  An example of a frequent last-second compromise is to use the same global navigation as mobile for tablet because the full desktop navigation---at 960px width or more---simply won't fit at 7


Practical Points:

Order matters.  If a thing appears above or to the left of another thing on one breakpoint, it should never be to the right or below at another breakpoint.  The flow is just like reading: Left to right, top to bottom.

The copy deck is not responsive.  We have occasionally made super-obscene-hackish concessions for this, but if there are 3 words at one breakpoint, do not show only 1 or 2 words at another breakpoint. (Bad: "See Details" on desktop, just "Details" on mobile.)

Images.  If an image will only ever be as big as perhaps half the width of the content well, and not as big as half the width of the screen, then we can just go ahead and use the same image on all breakpoints.  However, if an image is meant to be full content well width, and especially if it is meant to be full screen width, we should probably have a mobile size image as well.  Any time that we want a different aspect ratio for one breakpoint versus another, we should strongly consider having a separate image for that instance, because simply cropping an image is usually less than ideal.


## Miscellaneous

Try to get an accurate sense of how much text needs to go into a given spot.  Will this headline ever wrap to two lines? Three?  Do we need ellipses?  Character count?  What about the paragraph(s) that follow?  How tall could that potentially be?  Will we be translating the site?  How much longer will the text be in other languages?

Consistency.

