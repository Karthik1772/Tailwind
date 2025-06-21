# Tailwind CSS Flex Classes - Visual Guide

## Display Classes

### `flex`
Creates a flex container
```html
<div class="flex">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>
```
![flex](https://via.placeholder.com/400x100/3B82F6/white?text=Item1+Item2+Item3)

### `inline-flex`
Creates an inline flex container
```html
<div class="inline-flex">
  <div>Item 1</div>
  <div>Item 2</div>
</div>
```
![inline-flex](https://via.placeholder.com/200x60/10B981/white?text=Item1+Item2)

---

## Flex Direction

### `flex-row` (default)
Items arranged horizontally, left to right
```html
<div class="flex flex-row">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![flex-row](https://via.placeholder.com/300x80/3B82F6/white?text=1+2+3)

### `flex-row-reverse`
Items arranged horizontally, right to left
```html
<div class="flex flex-row-reverse">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![flex-row-reverse](https://via.placeholder.com/300x80/EF4444/white?text=3+2+1)

### `flex-col`
Items arranged vertically, top to bottom
```html
<div class="flex flex-col">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![flex-col](https://via.placeholder.com/100x200/10B981/white?text=1%0A2%0A3)

### `flex-col-reverse`
Items arranged vertically, bottom to top
```html
<div class="flex flex-col-reverse">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![flex-col-reverse](https://via.placeholder.com/100x200/F59E0B/white?text=3%0A2%0A1)

---

## Flex Wrap

### `flex-nowrap` (default)
Items stay on one line
```html
<div class="flex flex-nowrap">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
  <div>Item 4</div>
</div>
```
![flex-nowrap](https://via.placeholder.com/400x60/3B82F6/white?text=Item1+Item2+Item3+Item4)

### `flex-wrap`
Items wrap to new lines as needed
```html
<div class="flex flex-wrap">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
  <div>Item 4</div>
</div>
```
![flex-wrap](https://via.placeholder.com/300x120/10B981/white?text=Item1+Item2%0AItem3+Item4)

### `flex-wrap-reverse`
Items wrap to new lines in reverse order
```html
<div class="flex flex-wrap-reverse">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
  <div>Item 4</div>
</div>
```
![flex-wrap-reverse](https://via.placeholder.com/300x120/EF4444/white?text=Item3+Item4%0AItem1+Item2)

---

## Justify Content (Main Axis Alignment)

### `justify-start` (default)
Items aligned to the start
```html
<div class="flex justify-start">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![justify-start](https://via.placeholder.com/400x80/3B82F6/white?text=123................)

### `justify-center`
Items centered
```html
<div class="flex justify-center">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![justify-center](https://via.placeholder.com/400x80/10B981/white?text=.......123.......)

### `justify-end`
Items aligned to the end
```html
<div class="flex justify-end">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![justify-end](https://via.placeholder.com/400x80/EF4444/white?text=................123)

### `justify-between`
Items with space between them
```html
<div class="flex justify-between">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![justify-between](https://via.placeholder.com/400x80/F59E0B/white?text=1.......2.......3)

### `justify-around`
Items with space around them
```html
<div class="flex justify-around">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![justify-around](https://via.placeholder.com/400x80/8B5CF6/white?text=..1....2....3..)

### `justify-evenly`
Items with equal space between and around
```html
<div class="flex justify-evenly">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![justify-evenly](https://via.placeholder.com/400x80/EC4899/white?text=...1...2...3...)

---

## Align Items (Cross Axis Alignment)

### `items-stretch` (default)
Items stretch to fill container height
```html
<div class="flex items-stretch h-24">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![items-stretch](https://via.placeholder.com/300x100/3B82F6/white?text=Full%0AHeight%0AItems)

### `items-start`
Items aligned to the start (top)
```html
<div class="flex items-start h-24">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![items-start](https://via.placeholder.com/300x100/10B981/white?text=123%0A%0A%0A)

### `items-center`
Items centered vertically
```html
<div class="flex items-center h-24">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![items-center](https://via.placeholder.com/300x100/EF4444/white?text=%0A123%0A)

### `items-end`
Items aligned to the bottom
```html
<div class="flex items-end h-24">
  <div>1</div>
  <div>2</div>
  <div>3</div>
</div>
```
![items-end](https://via.placeholder.com/300x100/F59E0B/white?text=%0A%0A123)

### `items-baseline`
Items aligned to their text baseline
```html
<div class="flex items-baseline">
  <div class="text-2xl">Big</div>
  <div class="text-sm">small</div>
  <div>normal</div>
</div>
```
![items-baseline](https://via.placeholder.com/300x80/8B5CF6/white?text=Big+small+normal)

---

## Flex Grow & Shrink

### `flex-1`
Item grows and shrinks, takes available space
```html
<div class="flex">
  <div class="flex-1">Flexible</div>
  <div>Fixed</div>
</div>
```
![flex-1](https://via.placeholder.com/400x60/3B82F6/white?text=Flexible..........+Fixed)

### `flex-auto`
Item grows and shrinks based on content
```html
<div class="flex">
  <div class="flex-auto">Auto flex</div>
  <div>Fixed</div>
</div>
```
![flex-auto](https://via.placeholder.com/400x60/10B981/white?text=Auto+flex.......+Fixed)

### `flex-initial`
Item shrinks but doesn't grow
```html
<div class="flex">
  <div class="flex-initial">Initial</div>
  <div class="flex-1">Grows</div>
</div>
```
![flex-initial](https://via.placeholder.com/400x60/EF4444/white?text=Initial+Grows.........)

### `flex-none`
Item doesn't grow or shrink
```html
<div class="flex">
  <div class="flex-none">Fixed</div>
  <div class="flex-1">Flexible</div>
</div>
```
![flex-none](https://via.placeholder.com/400x60/F59E0B/white?text=Fixed+Flexible.......)

### `grow` / `grow-0`
Controls if item can grow
```html
<div class="flex">
  <div class="grow">Grows</div>
  <div class="grow-0">No grow</div>
</div>
```
![grow](https://via.placeholder.com/400x60/8B5CF6/white?text=Grows.............+No+grow)

### `shrink` / `shrink-0`
Controls if item can shrink
```html
<div class="flex">
  <div class="shrink">Can shrink</div>
  <div class="shrink-0">No shrink</div>
</div>
```
![shrink](https://via.placeholder.com/400x60/EC4899/white?text=Shrink+No+shrink)

---

## Align Self (Individual Item Alignment)

### `self-auto` (default)
Inherits parent's align-items value
```html
<div class="flex items-center h-24">
  <div class="self-auto">Auto</div>
</div>
```

### `self-start`
Individual item aligned to start
```html
<div class="flex items-center h-24">
  <div>Center</div>
  <div class="self-start">Start</div>
</div>
```
![self-start](https://via.placeholder.com/300x100/3B82F6/white?text=Start%0ACenter%0A)

### `self-center`
Individual item centered
```html
<div class="flex items-start h-24">
  <div>Start</div>
  <div class="self-center">Center</div>
</div>
```
![self-center](https://via.placeholder.com/300x100/10B981/white?text=Start%0ACenter%0A)

### `self-end`
Individual item aligned to end
```html
<div class="flex items-start h-24">
  <div>Start</div>
  <div class="self-end">End</div>
</div>
```
![self-end](https://via.placeholder.com/300x100/EF4444/white?text=Start%0A%0AEnd)

### `self-stretch`
Individual item stretches to fill height
```html
<div class="flex items-start h-24">
  <div>Start</div>
  <div class="self-stretch">Stretch</div>
</div>
```
![self-stretch](https://via.placeholder.com/300x100/F59E0B/white?text=Start+Full%0A+Height%0A)

---

## Common Flex Patterns

### Center Everything
```html
<div class="flex items-center justify-center h-screen">
  <div>Perfectly Centered</div>
</div>
```
![center-everything](https://via.placeholder.com/400x200/3B82F6/white?text=Perfectly%0ACentered)

### Navigation Bar
```html
<div class="flex justify-between items-center">
  <div>Logo</div>
  <div class="flex space-x-4">
    <div>Home</div>
    <div>About</div>
    <div>Contact</div>
  </div>
</div>
```
![navbar](https://via.placeholder.com/500x60/10B981/white?text=Logo+++++++Home+About+Contact)

### Card Layout
```html
<div class="flex flex-col">
  <div class="flex-shrink-0">Header</div>
  <div class="flex-1">Content grows</div>
  <div class="flex-shrink-0">Footer</div>
</div>
```
![card-layout](https://via.placeholder.com/300x200/EF4444/white?text=Header%0AContent%0AGrows%0AFooter)

---

## Responsive Flex Classes

All flex classes support responsive prefixes:
- `sm:flex` - Applies flex on small screens and up
- `md:flex-col` - Applies flex-col on medium screens and up  
- `lg:justify-center` - Applies justify-center on large screens and up
- `xl:items-start` - Applies items-start on extra large screens and up
- `2xl:flex-wrap` - Applies flex-wrap on 2xl screens and up

Example:
```html
<div class="flex flex-col md:flex-row lg:justify-between">
  <div>Responsive</div>
  <div>Layout</div>
</div>
```

This layout will be:
- Column on mobile
- Row on medium screens and up
- Space between items on large screens and up