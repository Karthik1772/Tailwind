# 🧱 Tailwind CSS Column Classes

Tailwind provides utility classes to define **multi-column layouts** using the `columns` property from CSS.

---

## 📐 Column Count

Control how many columns content should be split into:

```
columns-1       // 1 column
columns-2       // 2 columns
columns-3       // 3 columns
columns-4       // 4 columns
columns-5       // 5 columns
columns-6       // 6 columns
columns-7       // 7 columns
columns-8       // 8 columns
columns-9       // 9 columns
columns-10      // 10 columns
columns-11      // 11 columns
columns-12      // 12 columns
```



## 📏 Column Width

Set a minimum width for columns and let Tailwind auto-fill columns based on that width:

```
columns-xs      // min-width: 20ch
columns-sm      // min-width: 24ch
columns-md      // min-width: 28ch
columns-lg      // min-width: 32ch
columns-xl      // min-width: 36ch
columns-2xl     // min-width: 42ch
```

> These allow responsive content splitting based on character width (`ch` units).



## 💡 Example

```html
<div class="columns-3 gap-4">
  <p>Column 1</p>
  <p>Column 2</p>
  <p>Column 3</p>
  <p>Column 4</p>
</div>
```

➡️ This creates **3 columns** and distributes content into them with a **gap of 1rem (gap-4)**.



## 🪄 Combine With Breakpoints

Make your column layout **responsive**:

```html
<div class="columns-1 sm:columns-2 md:columns-3 lg:columns-4">
  <!-- Content -->
</div>
```



## 🎨 Styling Column Gaps

Use regular spacing utilities to style gaps between columns:

```
gap-0
gap-2
gap-4
gap-6
gap-8
```



## 🔍 Overflow and Break Inside

Sometimes content breaks weirdly across columns. Use these to fix:

```
break-inside-auto       // Default
break-inside-avoid      // Prevent breaking inside this element
break-inside-avoid-page // Avoid page breaks (print)
break-inside-avoid-column
```

Example:

```html
<div class="columns-2 gap-6">
  <div class="break-inside-avoid bg-white p-4">Card 1</div>
  <div class="break-inside-avoid bg-white p-4">Card 2</div>
</div>
```



🔙 [Back to Home](../README.md)


