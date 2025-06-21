# 🎯 Tailwind CSS Interactivity Classes

Tailwind provides a rich set of classes to control how users interact with elements on the page.



## 🖱️ Pointer Events

Control whether an element responds to pointer events.

```
pointer-events-none     // Disables pointer interactions
pointer-events-auto     // Enables pointer interactions
```



## 👆 Cursor Styles

Set the type of mouse cursor when hovering over an element.

```
cursor-auto
cursor-default
cursor-pointer
cursor-wait
cursor-text
cursor-move
cursor-help
cursor-not-allowed
cursor-progress
cursor-cell
cursor-crosshair
cursor-grab
cursor-grabbing
cursor-zoom-in
cursor-zoom-out
```



## 🧱 User Select

Control whether the user can select text.

```
select-none      // Text cannot be selected
select-text      // Text can be selected
select-all       // Select all text when clicked
select-auto      // Default browser behavior
```



## 🛑 Resize

Enable or disable resizing of an element (usually for textareas).

```
resize-none
resize
resize-x
resize-y
```



## 📱 Touch Action

Control touch screen behavior.

```
touch-auto
touch-none
touch-pan-x
touch-pan-left
touch-pan-right
touch-pan-y
touch-pan-up
touch-pan-down
touch-pinch-zoom
touch-manipulation
```



## 🧭 Scroll Behavior

Control how smooth the scrolling is.

```
scroll-auto        // Default scroll
scroll-smooth      // Smooth scrolling
```



## 🎹 Scroll Snap (Container)

Enable snap scrolling behavior on scroll containers.

```
snap-none
snap-x
snap-y
snap-both
snap-mandatory
snap-proximity
```



## 📍 Scroll Snap (Child)

Control how an element aligns within a snap container.

```
snap-start
snap-end
snap-center
snap-align-none
```



## 🔒 Appearance

Hide the native styling of form elements.

```
appearance-none
```



## 🎛️ Will Change

Hint which properties are likely to change, for performance optimizations.

```
will-change-auto
will-change-scroll
will-change-contents
will-change-transform
```



## 🎯 Accent Color

Change the accent color of inputs like checkboxes or radio buttons.

```
accent-[color]       // e.g., accent-blue-500
```



## 🔘 Caret Color

Control the color of the text input caret.

```
caret-[color]        // e.g., caret-red-500
```



## ✅ Checkbox / Radio Customization

Control how checkboxes or radios behave or appear.

```
checked:bg-[color]
checked:border-[color]
checked:text-[color]
```



## 💡 Focus, Hover, Active, and Disabled States

Use variants to apply styles when an element is in a certain state:

```
hover:bg-blue-500
focus:outline-none
active:scale-95
disabled:opacity-50
```

👉 Combine with interaction classes:

```
hover:cursor-pointer
focus:ring
active:translate-y-1
disabled:cursor-not-allowed
```


🔙 [Back to Home](../README.md)
