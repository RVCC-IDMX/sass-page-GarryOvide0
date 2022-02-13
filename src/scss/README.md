# README file 
This is a README.md file for my SASS Page Builder in which we learned about the features that make Sass so useful. Explains the use of each folder and files in each folder of SASS Structure.

## What is SCSS file
SCSS (Syntactically Awesome Stylesheet) is the second Sass syntax that uses brackets instead of indentations. SCSS is a more advanced CSS variant. A valid CSS3 file is also a valid SCSS file, according to SCSS's design. The.scss extension is used to store SCSS files. 
                                          
**utilities/** 
- Under the utilities folder contain the help files such as variables, functions, mixins.

    - _variables.scss//

Variables are straightforward: you assign a value to a name that starts with $, and then refer to that name rather than the value itself. Place where you can save data that you want to reuse across your CSS.

    - _functions.scss//

You can use functions to define complicated operations on SassScript data and reuse them throughout your stylesheet.The @function at-rule, which is written @function name>(arguments...>)..., is used to define functions. The name of a function can be any Sass identifier. 

    - _mixins.scss//

Mixins: allow you to create reusable styles that may be used across your CSS, and customized. The @mixin at-rule, which is written @mixin name>... or @mixin name(arguments...>)..., is used to define mixins

**base/**
- Base stores common style like resets, typography guidelines. Any files that can be reused across your project.

    - _typography.scss//

Style, proportions, and spacing are all important factors in typography. Even when the same text is typeset in different ways, it can evoke distinct emotions in different people.

    - _reset.scss//

The purpose of resetting is to remove all default browser styling from elements. 

**components/**
- Contains all the buttons, sliders, header, other page component styles, and widgets.

    - _header.scss// 

**layout/**
- This category contains all the CSS styles related to the layout, including the container, footer, forms, navigation, and the grid system.

    - _grid.scss//

A grid, often known as a grid system, is a set of vertical and horizontal lines that provide a structure for stacking design elements in a logical and controllable manner. 
 
A grid is made up of rows, columns, and gutters (the space between the rows and columns). They also allow you to stack design elements vertically or horizontally. 

**pages/**
- This is where the styles for each individual page are contained in the Pages. Almost every page requires its own set of styles that are only to be utilized on that page.

    - _home.scss//
 