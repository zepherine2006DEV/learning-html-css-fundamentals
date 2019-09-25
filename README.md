# Learning the Fundamental Concepts of HTML and CSS

## Description

## Cascade
### Selector Specificity
### Style Order

## Units

## Box Model

### Block and Inline Boxes (Outer Display Types)

Set using the display property, block or inline.

There are two types of boxes, block and inline. The full box model only applies to block boxes.  

Inline boxes can't have a height and width set. The border, margin and padding can be set but aren't always respected by elements around them.  

There is another type of box called inline-block, which combines the properties of block and inline boxes.

### Inner Display Types

Boxes also have an inner display type, which says how elements inside the box are arranged.

The default normal flow can be changed to values like flex.

### Standard and Alternative Box Model

The default behaviour is for the width / height to not include any padding, border, or margin. i.e. only the content. This is known as the standard box model.

To include the border and padding we can use the alternative box model, by setting box-sizing: border-box.

Quite often this is set at for all elements globally, by adding this style property to the html element.

### Margin

Transparent (invisible) space around the box, which pushes other elements away. Can have positive or negative values.

Margin collapsing happens when two margins touch. The total margin is not the sum of the two but the size of the largest individual margin.

### Border

### Padding

Typically used to push the content away from the border. Padding cannot be negative, unlike margins.


## Resources Uses

[Mozilla Dev Box Model Guide](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)