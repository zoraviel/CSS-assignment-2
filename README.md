# CSS Assignment 2 (Assignment 4)

This repo contains your assignment starter files, including three images.

1. **Fork** this repo (make sure you are logged into GitHub).

2. **Clone** your new repo so you have it on your hard drive. Remember to save it into the folder where you are keeping all your projects for this course. If you forgot how, [see the previous assignment](https://github.com/macloo/CSS-intro-with-GitHub-2017/blob/master/README.md).

**Note:** Make sure you **clone** the repo with *your name* at the top! NOT my repo. NOT the one with my name in the URL.

3. Use your GitHub app to **create a branch** named *gh-pages*. See the LAST 2 PAGES of this [illustrated guide](http://bit.ly/newGHapp). Stay in that branch, and do all your work in that branch. Note that the hyphen and all lowercase letters are essential in the branch name *gh-pages*.

## Part 1

Use the files *index.html* and *main.css* provided. DO NOT change *index.html* in any way. All the HTML tags and all the classes you need are already there.

**REPEAT: DO NOT change *index.html* in any way.**

You must write style rules in *main.css* to make the HTML page (*index.html*) look similar to the first "Sea Mammals" page in [this video](https://www.youtube.com/watch?v=RKXZBsOr0JM&list=PLZFU-W6LLeecJuSQh20QUU_gCmS30sLTB&index=31). Note that a color palette has been provided for you in *main.css* -- **our focus here** is not on finding new colors but on margins and padding, as well as effective use of CSS selectors.

1. Specify background colors for the three `section` elements, using the IDs that are in the HTML. Each `section` must have a different background color. Robbins introduced *id and class attributes* in chapter 5. Using an ID in the stylesheet is demonstrated in the video [Intro to Web Apps Robbins Chapter 14 part 1](https://www.youtube.com/watch?v=9saJfaXfux8&index=26&list=PLZFU-W6LLeecJuSQh20QUU_gCmS30sLTB).

2. Specify a suitable width for the `article` element and give it a white background.

3. Figure out how to center the `h2`, the `img`, the image source paragraph, and the `article`. There are different methods for centering - do not use the text centering method for the article or the image. **DO NOT center the text inside the `article`!** This covered in your book and in the videos. NOTE: If you Google centering, you might find an incorrect method that is old and no longer used, and that will cost you points.

4. Specify padding for `article`.

5. Center the text in the `footer` and specify padding for `footer`.

6. In the `header`, use the **width** property, the **float** property, and techniques for making a navigation bar (Robbins chapter 15) to set up the header as shown in the video. **DO NOT change any of the HTML in *index.html*!**

7. Adjust margins and padding as needed to finish the page and make it look nice.

**A note about the `header`:** I would like it to stay put when scrolling. However, if you can't figure that out, at least get the `h1` to go left and the `nav` to go right and inline, as seen in the video.

**FINISH Part 1 before starting Part2!**

## Part 2

Now you will make a different page layout using the same HTML file and new CSS. **Make sure you've finished Part 1 first.**

* Copy the file *index.html* and name the new copy *twosides.html*.

* Copy your final *main.css* and name the new copy *twosides.css*. The following instructions assume that Part 1 is completed and *main.css* is completely finished to include all the steps in Part 1.

* Edit the `link` element in *twosides.html* to attach the new style sheet file.

You will make your second "Big Cats" page look similar to the second "Sea Mammals" page in [the video](https://www.youtube.com/watch?v=RKXZBsOr0JM&list=PLZFU-W6LLeecJuSQh20QUU_gCmS30sLTB&index=31), with side-by-side content.

1. The new layout will be much easier to create if you *wrap* the `h2`, `img` and image source paragraph together in *one* `div`. **This is the ONLY change you may make to the HTML. Make this change only in *twosides.html*.** Do exactly the same thing within each of the three `section` elements. [This video](https://www.youtube.com/watch?v=qNdgzyIYKS0&index=10&list=PLZFU-W6LLeecJuSQh20QUU_gCmS30sLTB) will help you use the `div` element correctly (but -- warning! -- **DO NOT put the `div` styles in the `head`!** All styles go into the .css file).

2. Use the CSS **float** property to achieve the side-by-side layout shown in the second half of [the video](https://www.youtube.com/watch?v=RKXZBsOr0JM&list=PLZFU-W6LLeecJuSQh20QUU_gCmS30sLTB&index=31). This will be tricky and frustrating. The best way to learn floats is to try, try, try. Lots of saving and reloading. Do not add a lot of CSS declarations -- more is NOT better. Keep it simple. The three videos for chapter 15 will help a lot, especially [Intro to Web Apps Robbins Chapter 15 part 3](https://www.youtube.com/watch?v=cEgwqCWuJXs&list=PLZFU-W6LLeecJuSQh20QUU_gCmS30sLTB&index=30).

3. **TIPS:** a) You will find that *percentages* work better than *pixels* (or anything else) for all widths when you are floating elements. b) If your colors for the sections disappear, read Robbins, "Containing floats," pages 351-352 for the solution. c) Pay attention to Robbins's advice about the **clear** property (pages 347-348).

4. Remove the white background from `article`. Best to do this last, because having the background color will help you as you adjust the floats, widths and padding.

5. Adjust padding and margins as needed to finish the page and make it look nice.

**DO NOT use the *position* property** on any part of the `section` or `article` here. Floats will work.

## Part 3

When you have finished, you must **commit and push** to GitHub. Don't forget to also post the URL of your GitHub repo in Canvas before the deadline!

DO NOT make a pull request.

There is a bonus to your new branch. By naming it *gh-pages* you are taking advantage of a GitHub feature that allows us to publish live Web pages. After you commit and push, you can see your handiwork here:

http://[ your username ].github.io/CSS-assignment-2/

And here:

http://[ your username ].github.io/CSS-assignment-2/twosides.html

If you need to fix anything after your first commit-and-push, you will need to commit and push AGAIN to get your changes up on GitHub. Don't forget to do all your work in your *gh-pages* branch!

## Check the rubric and submit in Canvas

Be sure to [check the rubric](rubric.md) and **SUBMIT THE URL of your GitHub repo in Canvas** to complete this assignment!
