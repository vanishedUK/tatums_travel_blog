![logo](https://user-images.githubusercontent.com/44912347/201934171-c10d95d5-2727-4f1f-83b3-9da8e3ca9794.jpg)

# Tatums Travel Blog
Create a blog page to describe Tatum's day of traveling in Paris.

![Exemplar](https://user-images.githubusercontent.com/44912347/201934252-33c5e85d-2087-464f-b773-1829df885d77.png)

## Project Specs
The HTML for this project has already been provided for you. Your will be writing CSS rulesets to create the final styled page. Use the following specifications when creating your travel blog.

### Create stylesheet
- Create style.css in the root of the project (right next to index.html), 
- Use the link tag to link to it as we’ve learned using external CSS. 
  - **PRO-TIP**: You can make sure the html file linked to the css by temporarily styling something red.

### Font
You can select for everything on the document using the `*` selector. An example of this type of selector would look like:
```css
* {
    /*  CSS GOES HERE */
}
```
- Use the `*` selector and declare `font-family: Arial`, that will change all the text to Arial.  
- The headers should be a different color. Create a selector for `h1` and `h3`. You can choose any font you’d like.  We chose Geneva for the headings.

### Backgrounds
- Create a selector for the `body`. Add a `background-color` of your choice the body, 
- Create a selector for the `article` element. Add a gradient of any kind to the article.
- For the header, use a `background-image`, and what we put in the `url()` should be any panoramic image.  
  - Don’t have an image? Feel free to use the following: https://images.unsplash.com/photo-1470125634816-ede3f51bbb42?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8c3Vuc2V0JTIwcGFub3JhbWF8ZW58MHx8MHx8&w=1000&q=80
- Make sure the header doesn’t repeat, by adding a property of `background-size: cover`; to the header selector.

### Color the Text
- Set the header text color to any light color (we chose white).
- Add a bit of color to the `a` tags. We chose `lightseagreen`.  
- While you’re at it, play around with the `text-decoration` so that the a tags are NOT underlined.
  - PRO SKILL: If you like, you can even use the [pseudo-class](https://www.w3schools.com/cssref/sel_hover.php) 🔍 `a:hover` to add the underline back in only when the mouse hovers over the anchor tags!

### Add a Comment
- Add comments to explain what each portion of your CSS does so that you can reference it when you come back for Part 2. E.g. Right before your two a declarations, add something like “link styles”.

### Image Display
**PROBLEM**: The images look a little strange: The first line of text “hugs” the side of the image, and the rest flows underneath.  That’s because images are display: inline by default.  
- Select for the images 
- Set the display of each image to be `display: block;`

### Image Size
**PROBLEM**: The images are also a bit unwieldy: The first is square and the other wide, so the second one overflows out of the box if we size down the screen. 
- In the image ruleset, set the `image height: 20%;`. 

### Image Border
- In the image ruleset, add a `border` property. 
- Use whatever color you like!  We used the same color our link uses: `lightseagreen`.

### Header Border
- Create a ruleset for the `.subheading` class
- Add `border-bottom` to the ruleset. Create a solid line of the size and color of your choice.

### Round the Corners
- To the `header`, `img`, and `article` elements add a `border-radius` property to round the corners.
- To round the corners, use the `border-radius` property. You can choose the `border-radius` of your choice, we used a value of `0.75em`.

### Margin and Padding
- Add a padding amount of your choice to the `header` and `article` rulesets.
- Add a `margin-bottom` amount of your choice to the images.

### Apply Shadow
- For the `img`, `header`, and `article` rulesets, add `box-shadow`. The amount and color is up to you!
- For the `header` ruleset, add `text-shadow` as well. The amount and color is up to you!

### Commit & Push
- `add`, `commit`, and `push` your code to GitHub so that your coach can see your work.
