# READ ME

## CSS Overflow & Positioning

The objective of this task is to understand how overflow and positioning properties work.

You are not expected to complete this in one session. What you do not finish in class, spend time practicing at home. Always start from the beginning. **Do not copy and paste code; always type it in by hand.**

## Instructions

Clone this repository by clicking the "Clone or Download" button, then select "Download ZIP".

Included in the directory on your computer are the following files:

- css/
  - overflow.css
  - positioning.css
- img
  - grace-hopper.jpg
- overflow.html
- positioning.html

### Here is what you need to do

**All work needs to be done in the `exercise-11` folder.** (It may be named `exercise-11-master`.) There are two files, `overflow.html` and `positioning`. Make sure you are aware of which folders you are working out of at any time.

Other than correcting any validation errors, you **MAY NOT** change any of the HTML. Each file contains multiple `div`s with unique ids. You will use an id selector to style these. If there are rules which already exist in the style sheets, do not change these.

1. Open `css/overflow.css` in Atom, and `overflow.html` in your browser. In the CSS block already created for `div`m set the `width` at 200 pixels and the `height` at 200 pixels. Set the margin-bottom to 30 pixels and the border with at 1 pixel, its style as `solid` and its color as `rgb(219,81,73)`.

2. **box01**: Set overflow to `visible`.

3. **box02**: Set overflow to `hidden`. What happens to the text?  Can you find it using Chrome Dev Tools?

4. **box03**: Set overflow to `scroll`.

5. **box04**: Set overflow to `auto`. Do you notice any difference between `scroll` and `auto`?

You are finished with `overflow.html`! Let's move on to positioning.


1. Open `css/positioning.css` in Atom and `positioning.html` in your browser.

2. Create a CSS block which changes every `em` inside the section with an `id` of `relative` as follows: Set the background color to `#ccc`, position `em` as `relative`, move it 20 pixels up and 30 pixels right. (Yes, it is going to look really weird.)

3. Create a CSS block which turns `nav` into a fixed element. Set its width to `100%` and its background color as `rgb(219,81,73)`. Set its positioning as `fixed`. Move it all the way to the top and all the way to the left. (Bonus: As you can see, the `header` is hidden underneath the `nav`. Create a CSS block for `header` and use the correct box model property to adjust the header so it shows up just below the sticky nav.)

4. Create a CSS block for `div` which sets its width at 200 pixels and its height at 200 pixels. Create an `id` selector for **each** div which sets the background color accordingly (i.e. for 'red', use a shade of red). All `div`s are to be contained within `article`.

5. Add a 2 pixel, solid, dark gray border to `article`. Set its minimum height to be 500 pixels.

6. Position the `red` block in the bottom right corner and offset it by 20 pixels from the right. Position the `yellow` div in the top right corner and offset it 20 pixels from the top. Position the `green` div in the top left corner and offset it 20 pixels from the top and 20 pixels from the left. Position the `blue` div in the bottom left corner. There are no offsets for the `blue` div.

7. When the page scrolls, our relatively positioned `em`s hover over our sticky nav. Change the `z-index` property of `nav` so it will always be in front of the content on the page.

You are finished with `positioning.html`!

If you complete all these tasks, feel free to experiment with other selectors, properties to style the page as you see fit.

### How to tackle this project

Decide what you need to do, one step at a time.

Write down each task as you go. When you complete it, check it off. Decide on the next task to tackle.

Once you get into marking up content within the body, it is okay if you get stuck. Set aside that task and move on to another. Note the item you struggled with (so you can spend time on it later) and keep moving forward.

### Am I done?

Again, it is not expected for you to complete this exercise in class.  If you finish, have your professor give it a look.  If you *are* finished, re-download the repository files and go through the fixes again. Practice, repetition is an excellent way to learn.

### Why isn't X working?

Before asking for help, try working through the problem first. Refer to your notes, book or any resources made available to you for this course.

When something does not appear to work as you expect, ask yourself:

  - HTML
    - Did I forget to close a tag?
    - Are there typos in element, attribute, value names?
    - Did I forget to include quotes around attributes?
  - CSS
    - Did I forget a semicolon at the end of a declaration?
    - Did I close my curly braces?
    - Are my property names, values valid?
  - Are my file names, directory paths correct?

Remember, you can always refer to your notes, book or any resources made available to you for this course.

**Good luck!**
