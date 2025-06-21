# 🧱 Tailwind CSS Border, Outline & Related Utilities

Tailwind CSS provides powerful utilities for controlling border appearance, outlines, rings, shadows, and spacing between elements.


## 1> 🧩 Border Width

Use to control how thick the border is.

```
border       // default (1px)
border-0     // no border
border-2
border-4
border-8
```

Side-specific:

```
border-t-2
border-r-4
border-b-8
border-l-0
```

## 🎨 Border Color

Use to set the **border color**.

### ✅ Example with Green:

```
border-green-50
border-green-100
border-green-200
border-green-300
border-green-400
border-green-500
border-green-600
border-green-700
border-green-800
border-green-900
border-green-950
```

### ⚫ For Black & White:

```
border-black
border-white
```


## 🖌️ Border Style

Used to define the **style** of the border.

```
border-solid
border-dashed
border-dotted
border-double
border-none
```

## 🟠 Border Radius

Use `rounded` to control corner radius:

```
rounded
rounded-none
rounded-sm
rounded-md
rounded-lg
rounded-xl
rounded-2xl
rounded-3xl
rounded-full
```

Side-specific radius:

```
rounded-t-lg
rounded-r-md
rounded-b-xl
rounded-l-sm
```

## 📐 Border Side Colors

Set color for a specific side:

```
border-t-blue-500
border-r-red-400
border-b-green-300
border-l-yellow-600
```

## 📏 Border Opacity

Adjust border transparency:

```
border-opacity-0
border-opacity-25
border-opacity-50
border-opacity-75
border-opacity-100
```

## 🧩 Divide Utilities (Borders Between Children)

Used for placing borders between child elements in flex/grid layouts:

```
divide-x
divide-y
divide-x-2
divide-y-reverse
divide-gray-300
```
---

##  2> 🔲 Outline Utilities

Used mostly for **focus** and **accessibility** states.

### 📏 Outline Width

```
outline-0
outline-1
outline-2
outline-4
outline-8
```

### 🎨 Outline Color

```
outline-black
outline-white
outline-blue-500
outline-red-400
outline-green-600
```

### 🟦 Outline Style

```
outline-solid
outline-dashed
outline-dotted
```

### 📐 Outline Offset (distance between element and outline)

```
outline-offset-0
outline-offset-1
outline-offset-2
outline-offset-4
outline-offset-8
```

---

## 3> 🔵 Ring Utilities (Focus Rings)

Tailwind’s special abstraction for focus outlines using box-shadow.

### 📏 Ring Width

```
ring        // default 1px
ring-0
ring-1
ring-2
ring-4
ring-8
```

### 🎨 Ring Color

```
ring-black
ring-white
ring-blue-500
ring-pink-400
ring-green-600
```

### 📏 Ring Offset

```
ring-offset-0
ring-offset-1
ring-offset-2
ring-offset-4
```

### 🎨 Ring Offset Color

```
ring-offset-white
ring-offset-black
ring-offset-blue-200
```


## 💠 Box Shadow (Alternative to borders for depth)

```
shadow-sm
shadow
shadow-md
shadow-lg
shadow-xl
shadow-2xl
shadow-inner
shadow-none
```


## 🚫 Remove All Borders / Outlines / Shadows

```
border-none
outline-none
ring-0
shadow-none
```


🔙 [Back to Home](../README.md)

