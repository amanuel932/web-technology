# web-technology
Bootstrap is powerful and feature are packed frontend toolkits.

Built anything from prototype to production in a minutes.

Bootstrap is a free, open-source development framework for the creation of websites and web apps. Designed to enable responsive development of mobile-first websites, Bootstrap provides a collection of syntax for template designs.

**include bootstrap’s CSS and JS**

by place and use <link> tag in the <head> for our css and script tag for our javascript bundle before closing </body>. 

### **Bootstrap in CSS?**

The most popular CSS framework for developing responsive and mobile-first websites is Bootstrap.

Bootstrap makes responsive web design a reality.

**responsive** website means that can manage the display or pixel of any device and display depending on the screen size.

 

[https://itknowledgeexchange.techtarget.com/coffee-talk/files/2022/01/bootstrap-12-column-grid.gif](https://itknowledgeexchange.techtarget.com/coffee-talk/files/2022/01/bootstrap-12-column-grid.gif)

Example

| Breakpoint | Class infix | Dimensions |
| --- | --- | --- |
| Extra small | None | <576px |
| Small | sm | ≥576px |
| Medium | md | ≥768px |
| Large | lg | ≥992px |
| Extra large | xl | ≥1200px |
| Extra extra large | xxl | ≥1400px |

<div class="container-sm">100% wide until small breakpoint</div>
<div class="container-md">100% wide until medium breakpoint</div>
<div class="container-lg">100% wide until large breakpoint</div>
<div class="container-xl">100% wide until extra large breakpoint</div>
<div class="container-xxl">100% wide until extra extra large breakpoint</div>

### **What is bootstrap CDN?**

Bootstrap CDN is a free content delivery network that helps to quickly load Bootstrap CSS, Javascript, and jQuery libraries on projects to make them responsive, mobile friendly, and attractive.

**SCSS**

Sassy Cascading Style Sheets

The term SCSS is an acronym for **Sassy Cascading Style Sheets**. It is basically a more advanced and evolved variant of the CSS language.

**containers**

## Default container

Our default `.container` class is a responsive, fixed-width container, meaning its `max-width` changes at each breakpoint.

## Responsive containers

Responsive containers allow you to specify a class that is 100% wide 
until the specified breakpoint is reached, after which we apply `max-width`s for each of the higher breakpoints. For example, `.container-sm` is 100% wide to start until the `sm` breakpoint is reached, where it will scale up with `md`, `lg`, `xl`, and `xxl`.

## Fluid containers

Use `.container-fluid` for a full width container, spanning the entire width of the viewport.

## **Grid**

grid system to build layouts of all shapes and sizes, and grid system has twelve column system.

Bootstrap’s grid system uses a series of containers, rows, and columns to layout and align content. It’s built with flexbox and is fully responsive.

### Example

`<div class="container text-center">
  <div class="row">
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
  </div>
</div>`

**Columns**

Columns build on the grid’s flexbox architecture. When building grid layouts, all content goes in columns.

Bootstrap includes predefined classes for creating fast, responsive layouts.

## Alignment

Use flexbox alignment utilities to vertically and horizontally align columns

### Vertical alignment

Change the vertical alignment with any of the responsive `align-items-*` classes.

## Example

<div class="container text-center">
<div class="row align-items-start">
<div class="col">
One of three columns
</div>
<div class="col">
One of three columns
</div>
<div class="col">
One of three columns
</div>
</div>
</div>

# Gutters

Gutters are the padding between your columns, used to responsively space and align content in the Bootstrap grid system.

## Horizontal gutters

`.gx-*` classes can be used to control the horizontal gutter widths. The `.container` or `.container-fluid` parent may need to be adjusted if larger gutters are used too to avoid unwanted overflow, using a matching padding utility.

example 

`<div class="container px-4 text-center">
  <div class="row gx-5">
    <div class="col">
     <div class="p-3">Custom column padding</div>
    </div>
    <div class="col">
      <div class="p-3">Custom column padding</div>
    </div>
  </div>
</div>`
