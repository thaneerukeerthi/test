# Button Component

## Overview
This button component is designed using Tailwind CSS. It can be easily customized and integrated into your web projects.

## Usage
This Markdown file provides an overview of the button component, its usage, customization details, an example of the button, and a code snippet demonstrating how to use it. You can adjust the styles and details based on your specific needs.


| Tailwind Custom Property | Description |
|--------------------------|-------------|
| [Small] = "true" | It will creates small button |
| [Medium] = "true" |It will creates Medium button |
| [Large] = "true" | It will creates Large button |
| [Primary] = "true" | It will fill Background color with green(#7eac8c) and when we hover on button it will give border color green |
| [Secondary] = "true" | It will fill Background color with orange(#bdaf7f) and when we hover on button it will give border color orange |
| [isRounded] = "true" | It will creates full rounded button |
| [isSquare] = "true" | It will creates Square button with curved corners |
| [Plain] = "true" | It will give Border radious 3px, border color green, font normal |
| [CheckMark_Icon] = "true" | It will creates Check mark icon |
| [Title] = "'hello'" | Give Name of the Button in string. Here hello is the name of the button |
| [Pointer_None] = "true" | It will disable the button and don't allow the cursor |

*Note: By default, without specifying any size attribute, the button will be rendered in an extra-small size. Each additional property modifies the default styling to create buttons of different sizes, shapes, colors, and behavior.

## Example

```html
<cui-button [Title]="'Submit'" [Small]="true" [isRounded]="true"></cui-button>
This specific button, indicated by the "cui-button" tag, is set to display a small, rounded "Submit" button based on the attributes and their assigned values. 

![Alt text](https://img.freepik.com/free-vector/ballpoint-pen-school-stationary_78370-631.jpg)
