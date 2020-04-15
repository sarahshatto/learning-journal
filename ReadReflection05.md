# ReadReflection 05

Chapters 10 and 11 in HTML/CSS Book: 
- CSS stands for Cascading Style Sheet
  - CSS allows you to create rules that dictate how each element is presented. Essentially, it assosciates rules to elements. 
  - contains two major parts: a selector and a declaration

<br>

Ex: p { font family: Arial }

p is the selector

everything in the curly brackets is the declaration

- selectors indicate what element the rule applies to
- declarations indicate how the elements will be styled
  - declarations are made up of two parts: a property and a value. 
    - properties indicate the aspects of the element that you want to change. (Ex. Color, font, width, height, border)
  - Values specify the settings you want to use for properties.

You can use External or Internal CSS
- External CSS utilizes a style sheet on a completely different file
- Internal CSS is found within the same file as the html coding and is typically within the < style > tag. 

When building a site with multiple pages, it is recommended that you use an external styling sheet to streamline changes that apply to multiple pages. 

Types of selectors: 
- Universal selectors target all elements on the page. 
- Type selectors target elements with the same name
- Class selectors match an element whose class attribute has a value that matches the one specified after the period symbol. Ex: .note targets any element whose class attribute has the value of a note
- ID selectors
- Child selectors
- Descendant selectors
- adjacent sibling selectors
- General sibling selectors


## How CSS rules cascade

- if two identical rules are present, the most recent will be the one that applies. 
- if one of the rules is more specific, it will be applied. 
- you can add " !important " to anything to establish importance.

## CH. 11, Color

- Colors are identified via RGB values, HEX codes, and Color names. 

-Background colors apply to whatever "box" that the element lives in. 
  -default is transparent 

### Hue, Saturation, Brightness
- Hue refers to color
- Saturation: how much gray is present 
- Brightness: How much black is present

Contrast has a direct relation to readability. 

Opacity can be controlled
