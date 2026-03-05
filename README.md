# Fairy Tale

In this guided practice, you'll write CSS to style a text-focused HTML document.

## Getting Started

1. Clone this repository down to your computer.
2. Open the cloned folder with VS Code.
3. Live serve the `index.html` file. You should see the unstyled text of a fairy tale named "The Bamboo-Cutter and the Moon-Child".

## Instructions

1. Create a new `index.css` file. In the `head` of the `HTML` file, add a `link` to the `index.css` file.

   <details>
   <summary>Show solution</summary>

   ```html
   <link rel="stylesheet" href="index.css" />
   ```

   </details>

2. In `index.css`, add a new rule to style all `p` elements. The `font-family` should be set to `sans-serif` and the `font-size` should be set to `12pt`.

   <details>
   <summary>See Solution</summary>

   ```css
   p {
     font-family: sans-serif;
     font-size: 12pt;
   }
   ```

   </details>

3. Add a rule to style `mark` elements with a `background-color` of `#c3ddc3`.

   <details>
   <summary>See Solution</summary>

   ```css
   mark {
     background-color: #c3ddc3;
   }
   ```

   </details>

4. Style all elements with the `subtitle` class to have text that is gray and italicized.

   <details>
   <summary>See Solution</summary>

   ```css
   .subtitle {
     color: gray;
     font-style: italic;
   }
   ```

   </details>

5. Style the element with ID `the-bamboo-cutter` to have a bottom border that is `10px` wide, dotted, and green.

   <details>
   <summary>See Solution</summary>

   ```css
   #the-bamboo-cutter {
     border-bottom: 10px dotted green;
   }
   ```

   </details>

## Solution

The final solution can be found in the **solution** branch of this repository. See: [viewing branches in your repository](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/viewing-branches-in-your-repository)
