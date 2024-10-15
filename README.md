# CSS Layouts: Grid and Flexbox

This project demonstrates the use of **Grid Layout** and **Flexbox** for building modern, responsive layouts in CSS.

## Grid Layout

The **Grid Layout** is a two-dimensional system that allows you to create layouts with rows and columns. It provides fine control over the positioning and sizing of elements within a grid structure.

### Key Features:
- Two-dimensional control (rows and columns).
- Explicit grid definition using `grid-template-rows` and `grid-template-columns`.
- Grid items align relative to grid lines for flexible layout designs.

```css
.grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* 3 equal-width columns */
    gap: 10px;
}
.grid-item {
    background-color: lightblue;
    padding: 20px;
}
