---
title: A beginners’ guide to brewing with Chemex
date: 2018-08-16T12:01+02:00
description: >-
  Brewing with a Chemex probably seems like a complicated, time-consuming
  ordeal, but once you get used to the process, it becomes a soothing ritual
  that's worth the effort every time.
image: /images/uploads/news_item-02.jpg
---

This [week](/wdwdw) we’ll **take** a look at all the steps required to make astonishing coffee with a Chemex at home. The Chemex Coffeemaker is a manual, pour-over style glass-container coffeemaker that Peter Schlumbohm invented in 1941, and which continues to be manufactured by the Chemex Corporation in Chicopee, Massachusetts\*.

In 1958, designers at the [Illinois Institute of Technology](https://www.spacefarm.digital) said that the Chemex Coffeemaker is *"one of the best-designed products of modern times"*, and so is included in the collection of the Museum of Modern Art in New York City.

## The little secrets of Chemex brewing

The Chemex Coffeemaker consists of an hourglass-shaped glass flask with a conical funnel-like neck (rather than the cylindrical neck of an Erlenmeyer flask) and uses proprietary filters, made of bonded paper (thicker-gauge paper than the standard paper filters for a drip-method coffeemaker) that removes most of the coffee oils, brewing coffee with a taste that is different than coffee brewed in other coffee-making systems; also, the thicker paper of the Chemex coffee filters may assist in removing cafestol, a cholesterol-containing compound found in coffee oils. Here’s three important tips newbies forget about:

1. Always buy dedicated Chemex filters.
2. Use a scale, don’t try to eyeball it.
3. Never skip preheating the glass.
4. Timing is key, don’t forget the clock.


The most visually distinctive feature of the Chemex is the heatproof wooden collar around the neck, allowing it to be handled and poured when full of hot water. This is turned, then split in two to allow it to fit around the glass neck. The two pieces are held loosely in place by a tied leather thong. The pieces are not tied tightly and can still move slightly, retained by the shape of the conical glass.

For a design piece that became popular post-war at a time of Modernism and precision manufacture, this juxtaposition of natural wood and the organic nature of a hand-tied knot with the laboratory nature of glassware was a distinctive feature of its appearance.





## A Super-Quick Markup Primer

As discussed in “First Steps”, Ulysses uses special characters around text passages to let you define the meaning of these passages. This is called “markup”, and each character set, such as _underscores for emphasis_, is called a “markup definition”. Any collection of definitions is then called a “markup language”. There are many markup languages in the wild, and you may have come across one or the other on message boards or blogging platforms: Textile, Setext, or the increasingly popular Markdown by John Gruber.

By default, Ulysses uses its native markup language, dubbed “Markdown XL”.

## Do You Speak Markdown XL?

If not, don’t worry — it is dead-easy to learn. Markdown XL consists of 25 definitions, and it will only take you little time to get the hang of it. Soon you will be able to just type away, with no need to reach for the mouse.

Until then, the full list of available definitions is accessible via `⌘9` or the toolbar’s `A|` button.

Found it? Great. Now tear it off and leave it open for reference. The definitions work in three different ways: They either mark up an entire paragraph (e.g., Heading, Comment Block), or they mark up a word or a phrase (e.g., Strong, Marked), or they add a so-called text object (e.g., Link, Footnote).

Let’s have a quick run through all available definitions and their respective uses.

## The Writing Phase

To mark up a _heading_, start a line with one or more hashes. The number of hashes corresponds to the heading’s hierarchical level. That is, type `##` for a second level heading, `###` for a third level heading, and so on.

If you want to _emphasize_ a word or phrase, or mark it up as **important**, you can do so with single underscores or double asterisks, respectively, or use the shortcuts `⌘B` and `⌘I`.

_Ordered_ and _unordered lists_ can be created by simply typing dashes or numbers at the beginning of a line. And they will automatically continue, if “Smart Lists” are enabled in the Edit menu (Edit › Substitutions):

- This is
- An example
- Of an unordered list

If you want to create _block quotes_, e.g. to provide a motto, or to highlight famous quotes from even more famous people, simply start a line with a `>` character:

> That’s one small step for a man, one giant leap for mankind.
> (Neil Armstrong)

And with a _divider_ you can, well, divide. Text sections, for example.
----

## The Editing Phase

The next part of the markup is helpful for editing purposes: It lets you ::highlight text::, as you would with a classic highlighter, or mark text for deletion|| because it’s somewhat redundant||. ++You can also add comments inline, or let comments span entire paragraphs.++

%% Span.
%% Entire.
%% Paragraphs

While these definitions serve important purposes on screen, their true power will only become apparent during export. As an example, when creating a PDF with the “Swiss Knife” style applied, comments and deletions will be absent from the output file, since this is a style meant to deliver a finalized PDF. But when using the “Rough Cut” style, comments will be included, since that style is meant to be used for printed drafts.
## Text Objects

Headings, emphasis and comments may be all that’s needed for general prose, but some texts require images or footnotes, and online publications may require the insertion of links.

Enter what we call text objects — “these colored bubbles” you have already come across in this introduction. They are a bit different from standard text markup, as you can double-click a text object and add additional content (a photo, a URL). Their creation, however, is just as simple:

To [add a link], type square brackets around a word or phrase (or use the `⌘K` shortcut). This will open a popover which lets you add, well, a link to a webpage. If you type curly brackets around a phrase instead, you will create an {annotation}, which is basically a note added to that phrase. ++ Double click the annotation’s annotation, please. ++

You can also add images or footnotes, again by typing only a few characters. (fn) Enter `(img)` and you’ll be asked to provide either an image file or a URL. Of course, you can also just drag an image into your text, but where’s the fun in that?

### Image Preview

Ulysses will, per default, display small image previews in the editor. You can tweak the size of this preview in Ulysses’ “General” preferences, or turn it off completely: Images will then be indicated by a little bubble dubbed `IMG`.

## The Geek’s Corner

Finally, there’s markup to either add `sample code` or ~raw source code~. The former is indispensable for writing technical documentation, and the latter is really advanced stuff, with which you can add code that will be executed during export.

You can also insert whole paragraphs of both code variants. Here is a truly advanced Swift code example — released under GPL:

let myString = "You are beautiful."
print("Hello World. " + myString)

Note: If you indicate a programming language, the syntax of your code will be highlighted in the editor and relevant export formats.

And here is an example of a Raw Source block, which inserts a table when exported as HTML (and just vanishes when exported as PDF):

<table border="1">
 	<tr><th>City</th><th>Country</th><th>River</th></tr>
 	<tr><td>Hamburg</td><td>Hungary</td><td>Hérault</td></tr>
 	<tr><td>Leipzig</td><td>Latvia</td><td>Llobregat</td></tr>
</table>
