---
started: false
drafted: false
reviewed: false
ready to publish: false
locked: false
started by: enter name and date
first reviewed by: enter name and date
review comments implemented by: enter name and date
declared ready by: enter name and date
---
External Link [Obsidian Help Markdown Syntax](http://https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax)

Generic formatting
![[basic_markdown.png]]

 You can add comments by wrapping text in double percentages. %%This won't show in reading view %% 
 A single formatting element can be forced to display as plain text by preceding it with a backslash (as in the following examples)
\ > This would blockquote everything until the next double line return, if it wasn't preceded by a backslash

Create an unordered list by preceding each item with a - , \*, or + sign with a space between the marker and the text
- item 1
* item 2

Create ordered list by preceding each item with you own number and a period
1. item 1 
	1. this can be nested by simply tabbing the first element
	2. each return follows nesting
2. item 2
3. item 3

link![[markdown_link.png]]

image ![[markdown_image.png]]

task list, start each item with hyphen and space followed by set of square brackets
- [ ] first item
- [ ] second item

footnotes
comments


Tables/quotes/horizonal-lines are inserted with the right button click 

|     |     |
| --- | --- |
|     |     |
![[markdown_headings.png]]





# the following regards Wikipedia theme specifically

horizontal line is automatically added after a Heading 1 text
# Like This
  
| >[!info\|normal] This will look like a regular callout instead of an infobox.   |
| ------------------------------------------------------------------------------- |
| >[!bug\|right] This is a bug callout, but it floats right like an info callout! |
| >[!quote\|left] This will float to the left.                                    |
| >[!check\|info] This is a **Check** callout, but it looks more like an infobox. |

>[!info|normal] This will look like a regular callout instead of an infobox.
>line 2

>[!bug|no-float] This is a bug callout, but it floats right like an info callout!
>line 2

>[!quote|no-float] This will float to the left.
>Line 2 of quote and much more

>[!check|info] This is a **Check** callout, but it looks more like an infobox.
>Line 2

spacer text
spacer text
line 1
line 2
line 3 Images won't display correctly while you're in edit mode
![[Ash_Tree.jpg]]
spacer text
spacer text
line 1
line 2
line 3
spacer text
spacer text
line 1
line 2
line 3
spacer text
spacer text


- `right` - float a callout right
- `left` - float a callout to the left
- `normal` - add to an Info callout to override the usual infobox styling
- `info` - give another type of callout similar properties to the Info callout, giving it more of an infobox appearance
- `no-float`/`normal` - prevent an image from floating
- `right` - float an image to the right
- `left` - float an image to the left
- `center` - center an image
