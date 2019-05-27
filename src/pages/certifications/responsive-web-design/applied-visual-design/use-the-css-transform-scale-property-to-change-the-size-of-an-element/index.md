---
title: Use the CSS Transform scale Property to Change the Size of an Element
---
## Use the CSS Transform scale Property to Change the Size of an Element

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/responsive-web-design/applied-visual-design/use-the-css-transform-scale-property-to-change-the-size-of-an-element/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

<!-- Here is an example of the transform scale property being put to use: Notice the transform element in ball#2. It increases it's size 1.5 times the size of ball #1...-->

<style>
  .ball { 
    width: 40px;
    height: 40px;
    margin: 50 auto;
    position: fixed;
    background: linear-gradient(
      35deg,
      #ccffff,
      #ffcccc
    );
    border-radius: 50%;
  }
  #ball1 {
    left: 20%;
  }
  #ball2 {
    left: 65%;
    transform:scale(1.5);
    }
    
  }


</style>

<div class="ball" id= "ball1"></div>
<div class="ball" id= "ball2"></div>
