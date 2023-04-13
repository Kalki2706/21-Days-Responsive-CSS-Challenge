# CSS em & rem

### Em is Compounding Unit

<br/>

- If you give `font-size` property in em to parent element it will inherite by its child element.
- By default `1em` is equivallent to `16px`.
- In em's the font sizes are compounding on top of each other. i.e. if there's a div whose font size is `1em` i.e `16px` if we put a child into the parent div and specify the font size as `2em` then it becomes `(2 \* 16px) `+ `(16px of parent's)` i.e. `(32px + 16px = 48px)` and so on and so forth.
- `font-size` is always looking at the parent but the `margin`, `padding`, `width` and any other unit of the element is looking at the element's own `font-size`.

<br/>

### Rem is root unit

<br/>

- According to mozilla developer network _Rems were actually invented with the sole purpose of fixing that whole compounding problem_ we just saw in Em.
- `Rem` stands for `root em`.
- `Rem` take its property value from root element i.e. from `html` whereas `em` take its property value from its `parent element` & all the other properties we can apply looks at the `font-size` of that element
