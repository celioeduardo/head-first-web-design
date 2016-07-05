#Head First - Web Design

http://www.headfirstlabs.com/books/hfwd/

##Chapter 1. Building Beautiful Web Pages

Need to thinking in navigation twice in the design process:
	1) Think about navigational elements (buttons and nav bars) while working in the overall layout
	
	2) Writing code and building the layout elements as well as linking your pages together

You need to start by organizing your top level navigation. Keep your IA diagram close at hand.


###DETERMINE YOUR TOP LEVEL NAVIGATION

###SKETCHES KEEP THE FOCUS ON FUNCTIONALITY
Draw at least three more concepts on your own sheets of paper.

###CODE THE PROTOTYPE

###SCANNABILITY
Instead of reading your content from left to right, beginning to end, like a book, users scan the text for keywords and concepts—to give them an idea about the contents of the page. 

####Scannability Checklist
* You don’t have to use them all, just the ones that work for your content.
* Clearly written headers
* Small(ish) paragraphs
* Use bold and italics to emphasize important words or phrases.
* Use lists (ordered or unordered) for appropriate content.

###The process you followed in this chapter
* **Pre-production** using Information Architecture and storyboards to build a blueprint for your site so that you’re as efficient and focused as possible when you go digital.
* **Navigation** is based on your IA diagram. It’s more than just linking pages together. Navigation helps your users find information.
* **Layout** uses HTML and CSS to build the site’s interface (which you already came up with on paper back in the pre-production phase).
* **Writing** “fills” the design up with the scannable content that your visitors come to the site for.

###BULLET POINTS
* When you design sites, you should practice user-centered design—creating sites that focus on meeting the needs of your users.
* A design process helps you structure a project so that you stay on task and get things done in an efficient manner.
* Most, if not all, web design projects have 4 components: pre-production, layout, navigation, and writing.
Information Architecture is the process by which your website’s content is broken into chunks and then organized hierarchically in relation to one another.
* Developing your site’s IA is a two step process: organizing your site’s information, and building an IA diagram.
* An IA diagram visually represents the hierarchical organization of sections and subsections of information in your site.
* Top level navigation usually links to those sections in your information architecture one tier below your home/main page.
* The design of your top level navigation depends on the overall design and layout.
* There are a handful of great models for designing top level navigation: horizontal tabs, horizontal buttons, vertical menu, vertical tabs.
* Storyboards are used to visualize your design and test basic layout concepts before you jump into code.
Storyboards are a great way to catch potential design problems before you spend time coding your site.
* Writing for the web is different than writing for print.
* Web users scan webpages instead of reading them from beginning to end.
* Web content needs to be written so that it’s scannable.


##Chapter 2. Pre-Production

**Visual Metaphor** can range from subtle (using colors that give the user an abstract feeling that the designer wants to associate with the site’s theme) to direct (using graphics that tie right into the site’s name or identity–like using graphics of rocket ships for a site called Rocket Ship Designs).

**Theme** is your site’s purpose and content. So, the theme of amazon.com is an online merchant that focuses mostly on books. The visual metaphor uses design elements (color, graphics, typography, etc.) that reinforce the site’s theme.

###BULLET POINTS
* When you pre-produce a site, you are able to try out design ideas on paper–thereby avoiding potential mistakes in coding which could cost time, effort, and possibly money.
* A visual metaphor leverages visual elements (images, icons, colors, or fonts) in order to unconsciously reinforce the site’s subject matter.
* When applying a visual metaphor to your site, be subtle and don’t overdo it.
* Storyboards are hand drawn concept art storyboards that are used to visualize your design as a complete entity.


##Chapter 3. Organizing Your Site

Information architecture is just a way to organize the content you already have into groups that are meaningful and logical both for you and for your users. 

Information architecture is all about taking a step back and really looking at what sort of content you’ve got... how does it all fit together?

###Card Sorting
1. A stack of 3x5 cards
2. A pen and a clear table (or the floor)
3. A solid idea of your site’s content

![Card Sorting](imgs/card-sorting.jpg)

###IA Diagrams are NOT just links between pages
IA diagrams are not about links—they’re all about the hierarchical relationship between sections and subsections of content. If you were to try to create a diagram that showed links between sections, you would end up with a useless, spaghetti-looking mess that wouldn’t give you any kind of information whatsoever about this vital hierarchical relationship between the site’s content.

Think about it like this... most sites have links all over the place, cutting across categories and site sections. That would make for a pretty messy IA!

![Card Sorting](imgs/ia-links.jpg)


###Pre-production to production: The complete process
1 Gather all the your content.

![Card Sorting](imgs/ch3 - gather all the your content.jpg)

2 Brainstorm a theme and visual metaphor ideas.

![Card Sorting](imgs/ch3 - brainstorm a theme and visual metaphor ideas.jpg)

3 Develop a visual metaphor and think about layout.

![Card Sorting](imgs/ch3 - develop a visual metaphor and think about layout.jpg)

4 Build a storyboard (on paper).

![Card Sorting](imgs/ch3 - build a storyboard on paper.jpg)

5 Do a few card sorts and create an IA diagram.

![Card Sorting](imgs/ch3 - do a few card sorts and create an ia diagram.jpg)

6 Markup your content and style with CSS.

![Card Sorting](imgs/ch3 - markup your content and style with css.jpg)


###BULLET POINTS
* The point of a website is to communicate information–if that information is organized badly, your users will leave and not come back.
* The organization of a site’s information has a direct impact on its navigation and usability.
* Card sorting is a cheap and easy technique used to impose an information structure on a site’s content.
* Never rely upon your own card sort of a site’s information–you aren’t designing for yourself, you are designing for the site’s audience.
* A card sort often results in orphaned cards–which are a clear indication of content that should either be rethought or discarded entirely.
* An Information Architecture (IA) diagram is a representation of the hierarchical relationship between sections and subsections of the site’s information.
* Information Architecture diagrams are not designed to show the links between pages in a site.

##Chapter 4. Layout and Design: Follow the Golden Rule

###The Golden Ratio

If you take a length of a line and multiply by .62, you get a ratio that can be used to create a pleasing, natural-looking grid—that’s the Golden Ratio!

###The rule of thirds: A shortcut to the Golden Ratio

The Golden Ratio says that if you take the entire width of something, and multiply it by 0.62, you’ll get a nice wide area that you can put content into. The remaining 0.38 is great for sidebars, extra content, things that the eye should look at second.

Fortunately, 0.62 is awfully close to 2/3... and the remaining 0.38 is pretty close to 1/3. So if you divide something into thirds, two of those thirds are perfect for your main content, and the remaining 1/3 is great for sidebars, navigation, blogs...

![](imgs/ch4 - thirds rule.jpg)

![](imgs/ch4 - thirds rule 2.jpg)

![](imgs/ch4 - thirds rule 3.jpg)

![](imgs/ch4 - rpm example.jpg)

###Important content should “weigh” more.

You should already be putting your most important content into the 2/3 part of your 2/3-to-1/3 page ratios. But is that the only way to draw attention to something? Not at all!
When you’re laying out your page, you’re creating a balance between larger elements and smaller ones. The larger elements have more weight, and the smaller ones have less weight. Plus, there’s how the elements relate to each other:

![](imgs/ch4 - weight.jpg)

When you are laying out your web page, you need to consider two kinds of balance: symmetrical and asymmetrical.

**Symmetrical balance** occurs when elements on either side of a line (either horizontal or vertical) have the same weight.

**Asymmetrical balance** occurs when the weight of a site’s elements is not evenly distributed around a central line. So you’ve got one really large element only partially offset by other, smaller elements.

###BULLET POINTS
* A survey is an excellent way to get broad information about your audience.
* A persona is an archetype user that embodies and represents your audience.
* Screen real estate refers to the amount of space on the screen of the device that the designer has to work with.
* The lower your resolution, the larger items will be and the more screen real estate they will take up.
* A grid can provide order and visual logic when you are designing your layout on paper.
* The Golden Ratio can produce designs that are more pleasing to the eye.
* The rule of thirds is a quick and easy way to create grids that are based on the Golden Ratio.
* A CSS grid-based framework is a specialized CSS file that contains all of the necessary styles for laying your site out along a grid in CSS.
* The goal of a CSS grid-based framework is to allow the designer to focus on tasks that are unique to their specific project, rather than reinventing the wheel each time around.
* Block hover navs provide users with inf

##Chapter 5. Designing With Color: Moving Beyond Monochrome

###The color wheel (where it all begins)
The color wheel (or color circle as it’s sometimes called) is a circular diagram that displays different colors and shows the **relationship** between those colors.

Those relationships are key... and the color wheel lets us choose colors that go well together. 

![](imgs/ch5 - color wheel.jpg)

**Color schemes** are more than just collections of colors. A color scheme is a certain grouping of colors that goes well together.

And here’s the kicker: all good color schemes start with a single color and your handy-dandy color wheel.

####First, choose your __BASE__ color
The color that most represents the visual metaphor and that all other colors are based on. Then, we base everything else—other colors, their depth, their hue—off of that base color.

####Use the triadic scheme to create usable color patterns

The **triadic color scheme** is one of the most commonly used color schemes around. Triadic uses **three** colors, **equally spaced** around the color wheel. So once you pick your base color, you can just draw an equalateral triangle (three equal sides), and pick your other two colors:

![](imgs/ch5 - triadic scheme color.jpg)

The great thing about the triadic color scheme (or any other type of color scheme) is that as long as you stick to the general location of a color on the color wheel, you can change its saturation. **Saturation** is just a fancy design term for the darkness or lightness of a color. So we can lighten the saturation of our color scheme... it’s the same colors, but a lighter feeling result.

![](imgs/ch5 - saturation.jpg)
![](imgs/ch5 - saturation2.jpg)

####Create a richer color palette with the tetradic color scheme

When people find a site boring, that may mean the colors are too light... but we already know that Sam doesn’t like a darker triadic color scheme for SampleRate. So if you can’t go darker, consider adding colors. In other words, go from a three-color scheme to a four-color scheme.

One of the most common four-color schemes is the **tetradic color scheme**. The tetradic color scheme (which is sometimes also called the **double complementary scheme**) is the richest of all the schemes because it uses four colors arranged into two complementary color pairs.

Be careful, though. Four different colors is a lot to deal with, and you can’t use all four colors equally or your site will look like a mess. But for adding some extra complexity and energy to a site, a fourth color can really make a difference.

![](imgs/ch5 - tetradic color scheme.jpg)

![](imgs/ch5 - tretradic kuler compound.jpg)
	
**Question:** Are there only two color schemes? Triadic and tetradic?

**Answer:** No, there are a bunch of others. Most of the them are simpler schemes: monochromatic, analogous, complementary, and split complementary. All of the schemes follow the same general principles as triadic and tetradic. They find colors related to each other by certain angles that go well together. For more information on these and other color schemes, check out http://www.color-wheel-pro.com/color-schemes.html

**There’s no golden rule for color placement.**

But there are definitely some **principles** you can apply:

##Terms

IA (Information Architecture).

Navigation elements.

Layout elements

Blueprint

Sketches

Storyboards: (Sequence of little sketches that look like a comic strip—the film industry uses to test out shots before rolling the cameras) - or comp (composition)

Wireframes: storyboards

Visual Metaphor: can range from subtle (using colors that give the user an abstract feeling that the designer wants to associate with the site’s theme) to direct (using graphics that tie right into the site’s name or identity–like using graphics of rocket ships for a site called Rocket Ship Designs).