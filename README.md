# Sitetransform.css
# Note that this README is very buggy!
Turn your bad-looking site into a great-looking site with Sitetransform.css. Make everything modern with it. **No difficult classes to remember.** And what's even better? **It's 10KB unzzipped, 2KB gzzipped!** If you need more, you can add them easily! Read this to get started.
## Getting started
Download Sitetransform.css in the `sitetransform.css` folder of this repository.
## How to use
Just code as you do. Here's an example:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="dist/sitetransform.min.css">
</head>
<body>
    <h1>Lorem, ipsum.</h1>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aut neque nemo molestias animi sed exercitationem, dignissimos ut labore, hic quae blanditiis possimus distinctio? Recusandae, iure sapiente sed architecto aliquid nesciunt sint fugiat voluptatem debitis cum, alias laboriosam quibusdam maiores harum doloremque dolores dolorem officia labore consequuntur atque, eum impedit. Ratione!</p>
    <blockquote>Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam doloremque tempora necessitatibus quidem dolor laboriosam, impedit tempore alias eligendi non itaque dolores enim harum est quaerat quasi ut aut. Deserunt.</blockquote>
    <code>/* Demo CSS comment */</code><br>
    <button>Click Me!</button>
    <button disabled>I can't be clicked...</button>
    <input type="text" placeholder="Try me!">
    <input type="text" placeholder="Sorry, I can't be tried..." disabled>
    <textarea placeholder="Have some fun with multi-line text!"></textarea>
    <input type="checkbox" id="check">
    <label for="check">Check me out!</label>
    <input type="date">
    <input type="color">
    <select><option>Option 1</option><option>Option 2</option><option>Option 3</option></select>
    <a href="#">I am a link.</a>
    <table>
        <tr>
          <th>th</th>
          <th>th</th>
          <th>th</th>
        </tr>
        <tr>
          <td>td</td>
          <td>td</td>
          <td>td</td>
        </tr>
        <tr>
          <td>td</td>
          <td>td</td>
          <td>td</td>
        </tr>
        <tr>
          <td>td</td>
          <td>td</td>
          <td>td</td>
        </tr>
        <tr>
          <td>td</td>
          <td>td</td>
          <td>td</td>
        </tr>
        <tr>
          <td>td</td>
          <td>td</td>
          <td>td</td>
        </tr>
        <tr>
          <td>td</td>
          <td>td</td>
          <td>td</td>
        </tr>
      </table>
</body>
</html>
</body>
</html>
```
This would give you some beautiful output, but be sure to inclue Sitetransform.css in your project.
## Typography
CSS3 introduces a few new units, which includes the rem unit, which stands for "root em". Its reletive to the font size of the root element (html). In Sitetransform.css, the font size is set to 62.5% to make calculations easier. `font-size` in Sitetransform.css is defined as 1.6rem, or 16px and `line-height` as 1.6, or 24px. We use the font family Roboto, created by Christian Robertson and is provided by Google.
## Blockquotes
A blockquote is a piece of text quoted from another source.
```<blockquote>
  <p><em>Lorem ipsum dolor sit amet.</em></p>
</blockquote>```
## Buttons
Ah, the Button, an essential part of user experience. We have 3 types of buttons. The `<button>`, `<input type="button"> ,`<input type="submit"`> and buttons with a class of `.transbtn` have a flat royalblue color by default, while `.transbtn-outline` has only an outline around it and `.transbtn-clear` has no outline and no fill.
```
<a class="transbtn" href="#">Default Button</a>
<button class="transbtn transbtn-outline">Outlined Button</button>
<input class="transbtn transbtn-clear" type="submit" value="Clear Button">
```
## Lists
The List is a common way to display items. We have 3 different types of lists. `<ul>` is marked as outline bullets, `ol` as numbers, and `dl` as only spacings.
```
<ul>
  <li>Unordered list item 1</li>
  <li>Unordered list item 2</li>
</ul>
<ol>
  <li>Ordered list item 1</li>
  <li>Ordered list item 2</li>
</ol>
<dl>
  <dt>Description list item 1</dt>
  <dd>Description list item 2</dd>
</dl>
```
## Forms
Creating forms is a headache for many people, the layout being terrible and the on-screen keyboard breaking things. Sitetransform.css relives it, the design focused on accessibility and user experience.
```
<form>
  <fieldset>
    <label for="nameField">Name</label>
    <input type="text" placeholder="X Quentavers" id="nameField">
    <label for="ageRangeField">Age Range</label>
    <select id="ageRangeField">
      <option value="0-13">0-13</option>
      <option value="14-17">14-17</option>
      <option value="18-23">18-23</option>
      <option value="24+">24+</option>
    </select>
    <label for="commentField">Comment</label>
    <textarea placeholder="Hello everyone..." id="commentField"></textarea>
    <div class="float-right">
      <input type="checkbox" id="confirmField">
      <label class="label-inline" for="confirmField">Send a copy to yourself</label>
    </div>
    <button class="button-primary" type="submit" value="Send">
  </fieldset>
</form>
```
## Tables
A table represents data in 2 dimensions or more.
```
    <table>
        <tr>
          <th>th</th>
          <th>th</th>
          <th>th</th>
        </tr>
        <tr>
          <td>td</td>
          <td>td</td>
          <td>td</td>
        </tr>
        <tr>
          <td>td</td>
          <td>td</td>
          <td>td</td>
        </tr>
        <tr>
          <td>td</td>
          <td>td</td>
          <td>td</td>
        </tr>
        <tr>
          <td>td</td>
          <td>td</td>
          <td>td</td>
        </tr>
        <tr>
          <td>td</td>
          <td>td</td>
          <td>td</td>
        </tr>
        <tr>
          <td>td</td>
          <td>td</td>
          <td>td</td>
        </tr>
      </table>    
```
## Grids
The grid is a fluid system with a `max-width` of 112.0rem. Sitetransform.css is different from most frameworks because of its use of the CSS FlexBox Layout Module standard.
```
      <div class="container">

  <div class="row">
    <div class="column">.column</div>
    <div class="column">.column</div>
    <div class="column">.column</div>
    <div class="column">.column</div>
  </div>

  <div class="row">
    <div class="column">.column</div>
    <div class="column column-50 column-offset-25">.column column-50 column-offset-25</div>
  </div>

</div>
```
## Code
Well, if you are reading this then you have probably saw code (unless you close your eyes everytime you are going to see code). To add code, wrap computer code in a `<code>` tag. If you need a block, wrap the code in a `<code>` tag and then a `<pre>` tag. 
```
<pre><code>
.test {
  background-color: blue;
  color: white;
}
</code></pre>  
```
## Utilities
We have some utillity classes to improve perfomance and productivity.
```
<div class="clearfix">
  <div class="float-left"></div>
  <div class="float-right"></div>
</div>  
```
