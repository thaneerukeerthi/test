# Modal Component

## Overview
This modal component is designed using Tailwind CSS. It can be easily customized and integrated into your web projects.

## Usage
This Markdown file provides an overview of the modal component, its usage, customization details, an example of the modal, and a code snippet demonstrating how to use it. You can adjust the styles and details based on your specific needs.

## Modal Properties
| Modal Custom Properties | Description |
|--------------------------|-------------|
| [Small] = "true" | Generates a small-sized modal. |
| [Medium] = "true" | Generates a medium-sized modal. |
| [Large] = "true" | Generates a large-sized modal. |
| [Title] = "'password'" | Specifies the modal title as a string, for example, 'password'. |
| [Keypoints] = "true" | Displays points as keypoints; mandatory for point display |
| [point] = "['length 12', 'include space']" | Displays keypoints such as 'length 12' and 'include space'. |
| [Content] = "'It must be 8 characters'" | Displays the content within the modal, for example, 'It must be 8 characters'. |
| [StartButton] = "true" | Places a button at the bottom right of the modal. |
| [CenterButton] = "true" | Places a button at the bottom center of the modal. |
| [EndButton] = "true" | Places a button at the bottom left of the modal. |


## Button Properties
| Button Custom Properties | Description |
|--------------------------|-------------|
| [isSquareValue] = "true" | Generates a square-shaped button with curved corners. |
| [isRoundedValue] = "true" | Creates a fully rounded button. |
| [isPlainValue] = "true" | Applies a border radius of 3px, sets the border color to green, and uses a normal font. |
| [isMediumValue] = "true" | Creates a button in a small size. |
| [isLargeValue] = "true" | Creates a button in a large size. |
| [isSmallValue] = "true" | Creates a button in a medium size. |
| [isPrimaryValue] = "true" | Fills the background color with green (#7eac8c) and, on hover, changes the border color to green.|
| [isSecondaryValue] = "true" | Fills the background color with orange (#bdaf7f) and, on hover, changes the border color to orange. |
| [hasCheckMarkIcon] = "true" | Adds a check mark icon to the button. |
| [isPointerNone] = "true" | Disables the button and disallows the cursor interaction. |
| [ButtonTitle] = "['Cancle', 'Submit']" | Sepecifies the name of the button. here 'Cancle' and 'Submit' are the name of the buttons. It will create buttons based on name quantity. |

## Example

```html
<cui-modal [Title]="'password'" [Content]="'disply content here'"></cui-modal>
```
It defines a modal component with a title "password" and content that displays the text "display content here.

## Images

| Combinations | images |
|--------------|---------|
| modal | ![Alt text](../assets/img/modal/modal.png) |
 
