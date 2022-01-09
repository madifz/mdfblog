---
title: CSS Properties and Selectors
author: Danial
type: post
date: 2020-09-03T15:27:44+00:00
url: /css-properties-and-selectors/
categories:
  - Code
  - Uncategorized

---
Pretty fun refresher on css properties and selectors today and playing around with stylesheets.

&#8211; [CSS Tricks][1]: cheatsheets and guides on everything CSS

&#8211; [Paletton Color Picker][2]: color scheme picker when choosing colors to mix and match

&#8211; [W3C Selectors list][3]

&#8211; [MDN Reference on Cascading and Inheritance][4] 

&#8211; [Specificity Calculator][5] 

CSS Cheat Sheet

Reference:  
*https://www.w3schools.com/cssref/css_selectors.asp  
*https://css-tricks.com/almanac/

Cascading Style Sheets at the most basic level it indicates that the order of CSS rules matter.

.class

#id

*  
element  
element, element  
element element  
element > element  
element + element  
:hover  
:last-child  
:first-child  
!important (not recommended)

What selectors win out in the cascade depends on:  
-Specificity  
-Importance  
-Source Order

Days since last Zero Day: 3 (31/8/2020)

 [1]: https://css-tricks.com/almanac/selectors/
 [2]: http://paletton.com
 [3]: https://www.w3schools.com/cssref/css_selectors.asp
 [4]: https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance
 [5]: https://specificity.keegan.st