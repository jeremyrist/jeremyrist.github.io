![img](https://www.3weekdiet.com/images/bigbooks2.png)
## What did we do in week 3? 

![img](http://farm6.static.flickr.com/5098/5477777136_bc952ebe7e_m.jpg)
* Much like Scott Walker, I'm about to drop out...just kidding. But I wanted to make a Scott Walker joke so there you have it. For anyone interested, [that article we saw on NY Times](http://www.nytimes.com/2015/09/23/us/politics/scott-walkers-demise-shows-limits-of-super-pac-money-model.html?&hp&action=click&pgtype=Homepage&module=photo-spot-region&region=top-news&WT.nav=top-news&_r=0a) this morning was pretty neat about how Walker failed despite having millions of dollars from Super PACs. Money can't always buy you elections, but it can buy you intensive classes in Front-End Engineering! _(Transition...)_ 

### Below you will find some bullet points from the highlights of week 3.

##`CSS`
##### _CSS was the main focus of week 3. It stands for Cascading Style Sheets. It's used to alter the look and the format of websites._

* 3 CSS properties that can affect layout are:

        1. Display: `block, inline, flex, inline-block, none`
    
        2. Float: `left and right`
    
        3. Position: `relative, absolute, fixed`
        
* In CSS everything inherits from the Body tag, so it's a good place to start for default properties.

`3 rules of the cascade:`

      1. Inheritance - some properties are inherited by the children

      2. Specificity - if you increase specificity you can override inheritance, use more selectors or different selectors

      3. Order - based on the entire rule, top to bottom, earlier rules get clobbered by later properties

##`jQuery`
* `jQuery` is a brand new thing that we learned. It's an external library. It serves to help abbreviate common JavaScript terms like "addEventListenerAll" or others. It seems like most JavaScript (JS) language follows similar patterns and so `jQuery` was created to take those patterns and shorten them. If writing good code is synonymous with being "short and sweet" then you can see how this would help. You just have to be sure to include a link to the `jQuery` library in the header of your HTML.

##`User Stories`
* User story is a way to pseudo code some web function.
* Example: A `user` can do `something` so that `someone` can get `some benefit`.

##`Github Yak-Shaving`
* Review on how to Github properly:

        1. Read the assignment

        2. New Issue (name it and paste the checklist into the description)

        3. Merge PRs

        4. Create new branches

        5. Make changes, minimal first

        6. Open new PR for each Repo being altered

        7. Paste link to PR in Issue

##`Commit Messages`
* "If applied this commit will..." is a good way to think about how to write commit messages

##Random Review:
* Here's a couple code examples that we should remember:
* JS.....

          if (condition) {
            statements;
          }

* CSS....

          selector {
            property: value;
          }


## Super Fun Lil' Thang:

* The other peeps in the class seem to have a good grasp on the command line stuff but here's a fun one that I found today that helps make a little short cut.

* A [shortcut](http://stackoverflow.com/questions/6089294/why-do-i-need-to-do-set-upstream-all-the-time), which doesn't depend on remembering the syntax for `git branch --set-upstream` is to do:

         `git push -u origin my_branch`

## Another helpful trick:

* This is helping us turn our `sass` into readable `css`:

        `node-sass --output-style expanded --output css/ scss/styles.scss`
