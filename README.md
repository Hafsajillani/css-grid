
---

### Responsive Masonry Layouts Using CSS Grid

#### Day: 1/30



1. Grid: Grid layout is a method for creating complex layouts on web pages using a two-dimensional grid system. It divides a page into rows and columns, allowing you to place elements in specific grid cells. This makes it easier to design responsive layouts and control page structure.



2. Flex container: Flexbox is a CSS layout model that enables you to design flexible and efficient layout structures. It helps align and distribute space among items in a container, even when their size is unknown or dynamic.



3. Position relative: The `position: relative;` CSS property positions an element relative to its normal position in the document flow. It lets you move the element without affecting the layout of other elements on the page.



4. Padding and Margin: Padding is the space between an element's content and its border, while margin is the space between an element's border and adjacent elements. Padding creates space inside an element, while margin creates space around an element.



5. grid-template-columns and grid-template-rows: These properties define the number and size of columns and rows in a grid container. For example, `grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));` creates columns that are at least 300px wide but can expand to fill available space (`1fr`). `grid-template-rows: minmax(100px, auto);` sets the minimum height of rows to 100px but allows them to expand (`auto`) if needed.



6. .container .box:nth-child(1): This selector targets the first box element inside a container and sets it to span 2 columns and 1 row. This creates a layout where the first box is larger than the others.



7. .container .box{ grid-column: unset !important; grid-row: unset !important; }: This CSS rule inside a media query resets the `grid-column` and `grid-row` properties for all box elements inside a container. It ensures that on smaller screens, the boxes do not maintain their specified column and row spans, and instead flow according to the new grid layout defined in the media query. The `!important` keyword is used to give this rule higher specificity and ensure it overrides any conflicting styles.

---
