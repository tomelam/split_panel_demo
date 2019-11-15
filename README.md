# Dynamic Stylesheets Demo from Sitepen.com

A <a href="https://sitepen.com">sitepen</a> article by Dojo Toolkit contributor
Sam Foster,
<a href="https://www.sitepen.com/blog/dynamic-stylesheets-part-1/">
Dynamic Stylesheets, Part 1</a>, links to a demo of dojox.html.style,
which, as Sam says, "give you the ability to query the stylesheets collection
in a document, add and remove rules, and dynamically create new sheets."
The article is brilliant, but it is so old that the source file for Dojo
that the demo includes has already been removed. This Git project has
been created to resurrect the demo.

## System dependencies

Version 1.13.0 of Dojo. The file index.html
uses Google's API CDN to source this.

## How to understand this dynamic stylesheet demo

Browse <a href="demo">demo</a>. Open the browser's
developer tools. Play with the reset and present buttons and the "nubbin"
(small, blue, inverted pyramid) to adjust the relative sizes of the
pink and blue table (built using <code>&lt;div&gt;</code>s)
and watch the style of the <code>&lt;div&gt;</code> element with
id "dv1" change as you make the adjustments.
Add rows to the table by pressing the "+" button to verify that the
new row is using the same styles as the first row.

## Summary

This demo of dynamic stylesheets is mainly for just that: a demo.
However, the code is there to be copied and used if someone finds it useful.

## To Do

* It would be nice to have various versions of this demo for newer libraries.
Version 1.13.0 of Dojo might seem to be old.

* The capability of saving the modified styles in a CSS file
on a website's backend would an interesting feature.
