**To get JSON and Mocha/Chai:**
  1. `cd` to correct folder
  2. `npm init` to get the `.json`
  3. `git add` and `git commit`
  4. `npm install --save mocha chai`


**Random Stuff**
* `html + tab` fills in basic HTML starting point
* `browser-sync start --server --directory --files="css/*css *.html js/*.js` to get browser sync to respond to all of your updated files
* You can create a `<style>` tag and play with CSS in HTML
* "Most hipsters use a CSS preprocessor" - Instructor David

**Font Awesome**
* Paste a link in the header
* Follow font-awesome's web instructions

**SCSS/sass**
* The browser doesn't understand `sass`, it understands `css`
* `scss` is modeled similar to `html`
* `sass` is synonymous with `scss`
* `sass` acts like a translator and a compressor
* `npm install node-sass --save` will install it locally
* `npm install --global node-sass --save` will install it globally meaning you can find it in the `/usr/local/lib/` and this means every user on your computer will have access to it

**HTML**
* The basic structure of an HTML tag:
      * `<tag-name attribute-name="attribute value"> <!-- tag contents --> </tag-name>`

**Self-Closing Tags**
* The following are examples of "self-closing tags", meaning that they don't need a closing tag:
      * `<img>`
      * `<hr>`
      * `<meta>`
      * `<link>`
      * `<break>`

**Package.json**
* `package.json` is a dictionary for specific functions
* It stores information and you can pull API information from this
* It's kind of like the manifest (aka packing slip) for your project, like the sheet of paper from Amazon that tells you all about your order
* You can look in the `package.json` to see what scripts other developers are running for you
