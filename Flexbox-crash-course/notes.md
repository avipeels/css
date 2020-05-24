# Create a new file in windows -
echo.> filename.ext

# Css Flex-box
It is a css3 layout mode that provides an easy and clean way of arranging items with in a container.
1. **NO FLOATS**
2. Responsive and mobile friendly
3. Positioninig child elements is very much easy
4. Flex-container margins will not collapse with its content's
5. Order of elements can be changed with out editing the HTML
6. Ability to order item's height and width to best fit in the container's avaialable free space
7. Flexbox is direction-agnostic(un-biased in terms of vertical and horizontal block directions)
8. Built for smal-scale layouts while **Grid** is for large scale layouts

## Properties
1. **display: flex | inline-flex** - main property
2. **flex-direction: row(*horizontal*) | column(*vertical*)** - alignments
    Note: For flex-directio: row - the *cross-axis* is meant to be vertical and *main-axis* is meant to be horizontal and vice-versa
3. **flex-wrap: wrap | no-wrap | wrapreverse** - if we change the browser size, how the items will act
4. **flex-basis: <length>** - similar to width
5. **justify-content: flex-start(*left aligned*) | flex-end(*right aligned*) | center** - similar to floats
6. **align-self: flex-start(*left aligned*) | flex-end(*right aligned*) | center** - for individual items
7. **align-items: flex-start(*left aligned*) | flex-end(*right aligned*) | center** - aligns the items inside the flex container along the cross-axis.
8. **align-content: flex-start(*left aligned*) | flex-end(*right aligned*) | center** - aligns multiline flexboxes. It has no affect on single line 
Refer: https://stackoverflow.com/questions/27539262/whats-the-difference-between-align-content-and-align-items
9. **flex-grow:<length>** - can assign more length for individual items in a row or column
10. **flex-shrink:<length>** - can assign less length for individual items in a row or column
11. **flex:<integer>** - combination of flex-grow and flex-shrink
12. **order:<integer>** - can reorder elements with out changing the html

## Complete example set
https://www.youtube.com/watch?v=k32voqQhODc

