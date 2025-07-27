# 📍 Tailwind CSS Position Utilities

Tailwind provides utilities to control the **positioning** of elements on the page using `static`, `relative`, `absolute`, `fixed`, and `sticky` — along with offset helpers (`top`, `right`, `bottom`, `left`, and `inset`).

---

## 📌 Position Types

```
static     // Default (no positioning)
relative   // Position relative to its normal position
absolute   // Position relative to the nearest positioned ancestor
fixed      // Position relative to the viewport
sticky     // Behaves like relative until it hits a threshold, then becomes fixed
```



## 📍 Offsets: Top, Right, Bottom, Left

Use these to move positioned elements:

```
top-0
right-0
bottom-0
left-0

top-1/2
bottom-full
left-4
right-10
```

You can also use negative values:

```
-top-1
-left-2
```

And custom values:

```
top-[25px]
left-[50%]
```



## 🔄 Inset (shorthand for all sides)

Set **top, right, bottom, and left** in one go:

```
inset-0
inset-x-4    // left + right
inset-y-2    // top + bottom
-inset-1     // all sides with negative value
```



## 📐 z-Index (Stacking Order)

```
z-0
z-10
z-20
z-30
z-40
z-50
z-auto
z-[999]
```



## 🧪 Arbitrary Positioning Values

```
top-[20px]
bottom-[10%]
inset-[8rem]
z-[9999]
```



### 🧠 Common Use Case Example

```
<div class="relative">
  <div class="absolute top-0 right-0 size-6 bg-red-500"></div>
</div>
```


🔙 [Back to Home](../README.md)

