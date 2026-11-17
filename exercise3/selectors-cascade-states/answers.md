# CSS selectors and which rule wins: my answers

## 1. When must you use a class selector, and not an element selector?
You must use a class selector instead of an element selector whenever you need to style only a specific subset of elements rather than every single instance of that HTML tag on a page.

## 2. What does the space mean in `.material-shelf p`?
The selector .material-shelf p means: find each <p> element inside an element with class="material-shelf".

## 3. What does `>` mean in `.quick-nav > a`?
The selector .quick-nav > a means: find each <a> element that has an element with class="quick-nav" as its direct parent.

## 4. Why must a button link have a `:hover` style and a `:focus` style?
Button links need both a :hover style and a :focus style because they cater to different input methods and are essential for accessibility and usability 

## 5. If `a` and `.quick-nav > a` both set `color` on a navigation link, which selector wins in the stylesheet of this lesson?
.quick-nav > a wins because it has higher CSS specificity than the element selector a.
