# CSS Assignment 2 (Assignment 4)

This repo contains your assignment starter files, including three images.

**DO NOT USE any CSS layout properties we have not covered,** such as `float`, `position` or `display: grid`.

The [rubric](rubric.md) is in this repo.

## Do these steps first

1. **Fork** this repo (make sure you are logged into GitHub).

2. **Clone** your new repo so you have it on your hard drive. Remember to save it into the folder where you are keeping all your projects for this course. If you forgot how to fork or clone, [see the previous assignment](https://github.com/macloo/CSS-and-GitHub-intro/blob/master/README.md). **Note:** Make sure you **clone** the repo from the URL with *your name* at the top! NOT my repo. NOT the one with my name in the URL.

3. Use your GitHub Desktop app to **create a branch** named *gh-pages*. See the LAST 2 PAGES of this [illustrated guide](http://bit.ly/newGHapp). Stay in that branch, and do all your work in that branch. Note that the hyphen and all lowercase letters are essential in the branch name *gh-pages*.

## Part 1

Use the files *index.html* and *main.css* provided.

DO NOT change *index.html* in any way. All the HTML elements, IDs and classes you need are already there.

**REPEAT: DO NOT change *index.html* in any way.**

You must write style rules in *main.css* to make the HTML page (*index.html*) look similar to the first "Sea Mammals" page in [this video](TK).

**Note that a color palette has been provided for you in *main.css*.**

The palette for "The Big Cats" is different from the palette for "Sea Mammals."

**Your focus here** is not on finding new colors but on margins, padding, and flex properties, as well as effective use of CSS selectors.

**TIP:** Don't fail to use `box-sizing: border-box` correctly!

### Steps for part 1

1. Specify background colors for the three `article` elements, using the IDs that are in the HTML. Each `article` must have a different background color. Robbins introduced *id and class attributes* in chapter 5, pp. 100–102. Using an ID in the stylesheet is demonstrated in video 17 [CSS Used with Classes and IDs](https://www.youtube.com/watch?v=3Z_vzE1RILs).

2. All `section` elements on this page should have the same `max-width` property. This prevents the lines of paragraph text from being too long (too wide) for comfortable readability. Unlike `width`, `max-width` allows the width to shrink (no flex styles are needed).

3. Assign a white background color to all sections with the `text` class.

4. Make suitable adjustments to `padding`, `font-size` and `line-height` for all sections with the `text` class. Refer to the "Sea Mammals" example in the video for guidance. **DO NOT center or justify the P text in the `text` class!**

5. Center the `h2` text in all sections that have the `text` class. Do not use any flex properties to do this.

6. Make the `article` elements act as flex containers. Each `article` will be a flex container. Use CSS flex properties to center all the child elements that are inside the container. **DO NOT center the P text in the `text` class!** This is demonstrated in video 24 [Intro to CSS flexbox](https://www.youtube.com/watch?v=mTtG3HWjmg4). This is a vertical flex arrangement.

7. Style the `footer` and `footer p` as needed to match the "Sea Mammals" example in the video. You can do this without flex.

8. Make the `header` element act as a flex container. Follow the example in video 25 [Use CSS flex to style a header and nav with buttons](https://www.youtube.com/watch?v=3iUscQU0yKg) to style the navigation links and the header overall using flex properties. **DO NOT change any of the HTML in *index.html*!**

Adjust or add `margin` and `padding` values as needed to make the spacing on your "Big Cats" page look as close as possible to the "Sea Mammals" example. Don't forget that sometimes we need `margin: 0;` to get rid of browser defaults. Margins are covered in video 19 [Intro to the CSS box model: Margins](https://www.youtube.com/watch?v=KivtDY-cbMQ) and padding is covered in video 20 [Padding and the CSS box model](https://www.youtube.com/watch?v=z33gP_PE-7Q).

Assign suitable text colors and link pseudo class colors for good contrast and legibility *as needed* in the articles and sections. This was demonstrated in video 18 [CSS, Links and Pseudo Classes](https://www.youtube.com/watch?v=otVUAinxGKk).

Note that both `header` and `footer` have a dark gray background color in the "Sea Mammals" example.

**FINISH Part 1 before starting Part 2!** The header will be identical on your second HTML page and in your second CSS file, so get it all working and looking right before you continue. There should be no differences in the header and nav in your two CSS files.

## Part 2

Now you will make a different page layout using the same HTML file and new CSS. **Make sure you've finished Part 1 first.**

* Copy the file *index.html* and name the new copy *version2.html*.

* Copy your final *main.css* and name the new copy *version2.css*. The following instructions assume that Part 1 is completed and *main.css* is completely finished to include all the steps in Part 1.

* Edit the `link` element in *version2.html* to attach the new stylesheet file.

You will make your second "Big Cats" page look similar to the second "Sea Mammals" page in [this video](TK), with side-by-side content in each article.

### Steps for part 2

1. Edit the `article` rule in your CSS so that the flex container now places the two `section` elements side by side. This is a horizontal flex arrangement. You will have to change, remove, and add various flex properties to make this work. You will not need more than two or three different flex properties in this rule.

2. Edit the `section` rule or rules in your CSS so that the two sides are of equal width. This might require adding a flex property you had not used before.

3. Remove the white background color from all sections with the `text` class.

4. Un-center the `h2` text in all sections that have the `text` class. make sure your `h2` headings look similar to those in the video for the second "Sea Mammals" example.

5. Adjust `margin` and `padding` values as needed to make the spacing on your second "Big Cats" page look as close as possible to the second "Sea Mammals" example. In particular, without the white background on the text section, you will not need the same `padding`.

**DO NOT USE any CSS layout properties we have not covered,** such as `float`, `position` or `display: grid`.

## Part 3

When you have finished, you must **commit and push** to GitHub. **If you have trouble doing this,** a likely reason is that you did not **clone** correctly at the beginning. If you cloned from *my* GitHub.com repo and not *your own,* you'll need to clone all over again. Before doing so, copy your two CSS files into a safe other folder beforehand so you don't lose them.

**Don't forget to also post the URL of your GitHub repo in Canvas before the deadline!**

DO NOT make a pull request.

### Why gh-pages are cool

There is a bonus to your new branch. By naming it *gh-pages* you are taking advantage of a GitHub feature that allows us to publish live Web pages. After you commit and push, you can see your handiwork here:

http://[ your username ].github.io/CSS-assignment-2/

And here:

http://[ your username ].github.io/CSS-assignment-2/version2.html

### Subsequent edits to yur files

If you need to fix anything after your first commit-and-push, you will need to commit and push AGAIN to get your changes up on GitHub. Don't forget to do all your work in your *gh-pages* branch!

## Check the RUBRIC and submit in Canvas

Be sure to [check the rubric](rubric.md) and **SUBMIT THE URL of your GitHub repo in Canvas** to complete this assignment!
