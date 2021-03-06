---
title: CSS3 Flexible Box
---
## CSS3 Flexible Box
The Flexbox model provides for an efficient way to layout, align, and distribute space among elements within your document — even when the viewport and the size of your elements is dynamic or unknown.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
#### Basic usage
Flexbox can be used to center any amount of given elements inside one element. A basic example of this is the following code:

``` css
.center-elements-inside {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
```

Let's break down this example. First we set the display property to "flex" so we can apply our flexbox properties. Next we declare the way flexbox will handle our elements. This can either be in a row, or in a column. Setting it to row will align the elements horizontal inside the element. The column will align them vertical.

Now lets have a short look at "justify-content". This property declares how elements are distributed inside the parent element. We chose the "center" value. This means all elements inside this element will be centered.

#### More Information:
To get a complete understanding of Flexbox, read <a href="https://medium.freecodecamp.org/understanding-flexbox-everything-you-need-to-know-b4013d4dc9af" target='_blank' rel="nofollow">Understanding Flexbox Everything you need to know</a> on the FreeCodeCamp Medium page.

For an interactive guide go through <a href="https://medium.freecodecamp.org/the-ultimate-guide-to-flexbox-learning-through-examples-8c90248d4676" target="_blank" rel="nofollow">The Ultimate Guide to Flexbox — Learning Through Examples</a>

Both of these are great resources by Ohans Emmanuel. 


