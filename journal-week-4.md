##**Howzabout Week 4?**##

Week 4 was a difficult week for me but I made it and now I can look back on it. It's funny how time smoothes everything over. I was really frustrated last week because I was starting to feel left out and left behind when it came to the material we were covering. Coming into this course it was clear that you didn't need a background in coding to succeed here but I found myself questioning that a lot. The Chessboard Assignment was a real beast of a task and I came nowhere close to solving the logic behind it...I was happy enough just getting my pieces on the board and centered in their squares. I was pretty sure everyone else in the class was in a similar boat but on Monday we saw Karlo, Shay, and David's successful chessboards. I was thoroughly impressed.   

I like to think that I'm navigating this class like a good cornerback would, say a Josh Norman-type, it's obvious at this point that I might not be the strongest player on the field but even though I might get beat a lot...I'll make the plays that matter and I'll get better as the game goes on.

![img](http://i1.wp.com/blackandbluereview.com/wp-content/uploads/2015/09/EBX3362.jpg?resize=675%2C475)

That being said, I'm still happy with my progress and happy with how the class is moving. Last week I was able to help out Matt with some Command Line stuff and yak-shaving things and that made me feel really good. There is a lot of value in being able to teach/help a classmate. Finding the right balance between teaching and getting taught will be important moving forward. 

I was most frustrated last week around Wednesday when I thought we were going to have a lecture on how to setup the chessboard but instead went over `package.json` stuff and command line controls. The lecture was over my head and I think I was mostly upset because I was experiencing that awful feeling of being lost and I was too embarrassed to speak up. Part of that is on the instructor but a larger part of that is on me. I need to be sure not to allow a whole hour to go by where I'm not engaged and clueless when it comes to what the lecture is about. The stakes are too high here to allow for that.

But at the end of the day it comes back to what am I doing, or what are we doing, to learn how to make websites and to a larger extent how to _think_ better. Break large problems down into smaller ones. I've started making my own personal website on the side for my producer-nickname "Funkleberry" and I'm planning on taking things we learn from class to build a website for that. This will be a good way to take what we're learning in class and translate it to a real-world scenario. I would suggest everyone else do the same!

###_Here's a recap of my notes from class:_###

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
