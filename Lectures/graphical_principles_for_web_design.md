# Web Design Principles


## Native UIs & Widgets


There was a time when it seemed, for a little while, that UI design was solved.
The UI developers had WIMP and had native widgets for various platforms. 
Then cross-platform UI widget libraries appeared: e.g. C++/Qt, Tcl/Tk, Swing for Java.

Developers also had GUI builders. These were drag and drop interfaces in which you would create your windows with mouse drag-and-drop and then simply associate events to the various elements in the UI design. 

They also had guidelines for how to create these native interfaces, like the most excellent and still relevant Apple [Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/).


## The Early Web
And then the web happened. And everybody started doing their own widgets and designs, and programmers were free again to be creative. And then followed the age of interactive-full-of-color-and-animation websites made in Flash. They had zero accessibility but were creative. This idiosincracy resulted in the interaction with many new websites needing to be "learned". In all this chaos, some order was required. 
Slowly the web developers started converging towards a set of web design principles. 


## Don't Make Users Think

A first important step on the road to a better web was a little book, that appeared in 2000, entitled "Don't Make me Think" by S. Krug. It talked about web usability and about how a good software program or web site should let users accomplish their intended tasks as easily and directly as possible. 

Krug observed that we're not reading web pages; we're *scanning* them. And we're scanning because we're busy. And we want to get something done. That was true back then; and it's just as true now. (In fact, if you think about it, it's also true about the way we look at posters; we scan them, we don't "read" them. )

This has implications on how we design a good website. Ideally a good website has: 

1. a clear hierarchy on each page = the more important something is, the more prominent it is
2. reused conventions = conventions help users make sense faster of what they see (e.g. login on top right, home page link as site logo on top left; a button is clickable on all it's body; the old app of Danske Bank with the rotating wheel)
3. clearly defined areas on every page = things that are related logically, are also related visually
4. obvious markers of what's clickable (make a distinction between links and buttons)
5. as little noise as possible = this includes text; nobody wants to read a lot of text; but this also includes visual clutter too.

We face choices on the web; making the choices as simple as possible (mindless, if you want) is one of the main things that makes a web app easy to use. Also, making the important actions and info visible is important too.


## Graphical Design Principles for the Web

In a way, this really is the result of the web as a medium. Going back to McLuhan and Portmann who talked about the way the nature of a communication medium determines the kind of communication is possible in it. And the way we have to design for it. 

And also, this means that this kind of knowledge, will be useful for you for other situations besides web design; e.g. designing a poster, preparing presentations; etc.


### Hierarchy

- Emphasize the important information
- Emphasize by de-emphasizing
- Separate visual hierarchy from document hierarchy
- Semantic coloring is not always a good idea
- Don't rely only on font size
- Use weight and color to emphasize/de-emphasize


### Layout & Spacing
- Give elements enough room “to breathe”
- Busy UIs also have their place
- Don't choose sizes ad hoc
- Do not fill the whole width of the screen
- Think in columns
- Grids can be useful
- You do not always need a grid
- Relative size does not scale
- Avoid ambiguous spacing

### Color
- You need more colors than you think
- Define your shades upfront
		1. greys (you'll need more grays than you think)
		2. primary colors (what makes facebook feel blue)
		3. accent colors (highlight a new feature, warning message, dangerous action, positive trend)
- You need more grays than you think
- Use HSL instead of HEX
- Ensure sufficient contrast
- Never convey info only through color


### Typography
- Optimize for legibility
- Predefine a good scale for your text
- Keep line lenght in check
- Align multiple text styles on baseline not center
- Line height can help with readability
- Line height and font size are related
- Don’t center long text
- Right align numbers
- Hyphen narrow justified text
- Narrow justified text can be awkward


## Design systems

To make sure that a whole team is on the same page, one collects all the rules 
regarding the above mentioned aspects of layoutn, color, typography, spacing, but also other project-wide conventions (like icons, layouts) 
in a living document called a design system. 

Some design systems are very popular: e.g. Fluent from Microsoft, Material from Google. 



# Further Reading

- [Dieter Rams: the 10 principles of good design](https://www.vitsoe.com/eu/about/good-design) - for the reader who is curious about principles of design in general.
- [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/) - even if specific for OS X incredibly well written; the web designer can still learn from it
- [Mailchimp Pattern Library](http://ux.mailchimp.com/patterns/helpers) - a good example of how a design system for a product can look.
- https://blog.adobe.com/en/publish/2017/11/29/prototyping-difference-low-fidelity-high-fidelity-prototypes-use.html#gs.bwzcw2 - a good overview of prototyping, types, and why we need them
