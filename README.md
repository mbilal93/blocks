/******************************************

    **Blocks CSS Framework**

    Author: Muhammad Bilal
    Last Modified: 22/04/2017
    Status: BETA

    </ Coded, Compiled from Pakistan with Love! :) />

*******************************************/

Blocks is a very initial, basic and tiny [8kb gzipped] but fully responsive and block structured CSS framework. 

Compiled and deployed originally using SCSS.

I build this framework for my personal use initially to get rid of bloatware of Bootstrap (<- still love ya) and a clean CSS having least useless styles.

For instant examples, please follow block.html

Websites using Blocks (probably initial builds :bowtie:):

 http://olympiapublishers.com/
 
 https://superiorsurfaces.co.uk/
 
 http://novae.mc/

********************************************************************

css/blocks.scss is a fully customizable file to customize preferred blocks, gutters, container etc size. If you are not familiar with .scss, i would not recommend to touch this file as it is intended for development purpose only.

>>*****Features and Structure******

>>Block Classes:

.block-1 to .block-12 basically holds entire block structure.

.tab-1 to .tab-12 holds block structure for screen sizes up to 980px width overriding .block- classes.

.phone-1 to .phone-12 holds block structure up to 750px overriding .tab- and .block- classes.

Note: Unlike bootstrap, Blocks does not comes with float property pre-defined. Therefore .fl and .fr can be used along with blocks to achieve floating elements.

Custom number of blocks can be defined using SCSS.

Example:
```
<div class="row-fluid">
  <div class="[block] fl"></div>
  <div class="[block] fr"></div>
</div>
```
where 'block' is the developer choice of block and .row-fluid fills out extra spaces around to fill up entire container.

>>Space Classes:

Adds horizontal spaces between elements.

.space1 to .space10 adds padding-top to current element to add vertical space. Alternative to <br> in short but cleaner method.

>>Font sizes

Blocks comes with pre-defined font sizes up to font-size:65px by default, so you to reduce the hassle to set font sizes repeatedly.
Font sizes are customizable using SCSS.

>>Flex

Unlike bootstrap, blocks does come with pre-defined CSS3 .flexbox and .flex-wrap properties to let you build amazing structures.

New to Flexbox? Get started here: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

>>Gutters

Blocks comes with pre-defined gutter sizes up to 10 choices to let you use different gutters between blocks.

Basic usage:

```
<div class="gutter-[number]">
  <div class="[block] fl"></div>
  <div class="[block] fr"></div>
</div>
```

where 'number' and 'block' are developer choices respectively.

>>Colors

By default, blocks SCSS file comes with an empty array of colors. You can define and compile colors as key=>value of your choice

and use it by classes: .color-[color] and .bg-[color] for text and background colors respectively where color is the actual key defined in $colors array.

>>Print

Blocks also comes with print media properties .print_show and .print_hide to show and hide printable elements respectively.
(I will figure out what else i can place here)

>>Others

Blocks comes with predefined frequently used general properties. Please refer to css/blocks.css for complete list as I am too lazy to list each one here.  :sleeping:

**********************************************************************************************************************

Got any more ideas?

Shout out to me at m.bilal93@outlook.com 

I may add your ideas and whatever my tiny brain suggest me more..

Have a Good day!  :smile:
