# flex

## ex01: put three divs horizontally

### challenge

- Make a parent div.
- Create a class `row` and apply this to the div.
- Now create three divs as children.
- The children should go horizontal.


---


### ex02: practice align

Take a parent div and three child divs. parent should align all children to center. However, the third child needs to go end of flex.

Give your parent a height of 500 pixels.

---

## ex03: Create a card

### challenge

- Create a div
- Create a class `card` for the div
- Add text in it in `p` tag
- Add a button in the div `Primary Button` too.
- The p and button should go vertically.

---

## ex04: justify-content

### understanding

The justify-content property aligns the flexible container's items when the items do not use all available space on the main-axis (horizontally).

`justify-content: flex-start|flex-end|center|space-between|space-around|space-evenly;` 

### challenge

When there's more text in one card you would want the primary buttons to align.

---

## ex05: Shrink and Grow

### understanding

The flex is useful to control what happens when something grows and shrinks. That's where it shines. So what happens if you add a `heading` in this card too? The previous exercise won't work out now. 

We need to control what grows and fills the empty space. 

See the demo: [https://developer.mozilla.org/en-US/docs/Web/CSS/flex-grow](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-grow)

And see how the shrink works: [https://developer.mozilla.org/en-US/docs/Web/CSS/flex-shrink](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-shrink)

This is applied to the child.

### challenge

Make use of `flex-grow` and `flex-shrink` on the right element to make this work when size changes.

This is without the grow/shrink.

---

## ex06: Thumbnail Image to the Card

Note: Give your card class a max-width of 200px otherwise the image will stretch. We'll cover putting card in grid and then making image responsive and this issue will go away. 

### challenge

Use the placeholder for image: [`https://via.placeholder.com/150`](https://via.placeholder.com/150)

---

## ex07: make the cards wrap

### understanding

When window size decreases the cards shrink. But we can `wrap` the items in a row so that when the width decreases card will go down.

Syntax.

```css
flex-wrap: nowrap; /* Default value */
flex-wrap: wrap;
flex-wrap: wrap-reverse;
```

### challenge

Apply `flex-wrap` on `row` class and then cards will start wrapping.

---


