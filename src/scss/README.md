# README file 
This is a README.md file for my SASS Page Builder in which we learned about the features that make Sass so useful. Explains the use of each folder and files in each folder of SASS Structure.

**utilities/** 
- Under the utilities folder contain the help files such as variables, functions, mixins.

    - _variables.scss//

Variables are straightforward: you assign a value to a name that starts with $, and then refer to that name rather than the value itself. Place where you can save data that you want to reuse across your CSS.

    - _functions.scss//

You can construct complicated operations on SassScript data with functions, which you can reuse throughout your stylesheet.

    - _mixins.scss//

Mixins are similar to the extend feature, but they allow you to pass arguments as well. The syntax is just a little different this time.    

**base/**
- Base stores common style like resets, typography guidelines. Any files that can be reused across your project.

    - _typography.scss//

Style, proportions, and spacing are all important factors in typography. Even when the same text is typeset in different ways, it can evoke distinct emotions in different people.

    - _reset.scss//

**components/**
- Contains all the buttons, sliders, header, other page component styles, and widgets.

    - _buttons.scss//

    - _carousel.scss//

    - _slider.scss//  

**layout/**
- This category includes all styles related to the layout of your project. Styles for your header, footer, navigation, and grid system.

    - _navigation.scss//

    - _header.scss//

    - _footer.scss// 

    - _forms.scss//

    - _sidebar.scss//

    - _grid.scss//    

**pages/**
- This is where you'll find any page-specific styles your site's home page may require that no other page receives.

    - _home.scss//

    - _about.scss//

    - _contact.scss//  

