# 🔄 Tailwind CSS Transform & Transition Utilities

Tailwind gives you full control over element transformations and transitions using simple, chainable utility classes.

---

## 🧠 What is **Transition** vs **Transform**?

| Concept     | Description |
|-------------|-------------|
| **Transform** | Applies a visual change like rotate, scale, translate, or skew. It affects the element's appearance. |
| **Transition** | Controls **how fast/smoothly** a property changes from one state to another (like hover effects). |

> 🔁 **Transform** = *What to change*  
> ⏱️ **Transition** = *How to animate the change*




## 🔧 Enable Transforms

To apply transforms, use:

```
transform         // Enables transform
transform-gpu     // GPU-accelerated transform
transform-none    // Disable transform
```



## 🔁 Scale

```
scale-0
scale-50
scale-75
scale-90
scale-95
scale-100
scale-105
scale-110
scale-125
scale-150
```

🧪 Custom:

```
scale-\[1.3]
```



## 🔃 Rotate

```
rotate-0
rotate-45
rotate-90
rotate-180
-rotate-45
```

🧪 Custom:

```
rotate-\[270deg]
```

🧠 **Interview Tip:**  
> Use `rotate-45` to rotate elements; negative values flip in the opposite direction.



## ↔️ Translate

```
translate-x-full
-translate-x-1/2
translate-y-0
translate-y-1/2
-translate-y-1/2
```

🧪 Custom:

```
translate-x-\[10px]
translate-y-\[2rem]
```



## 🔄 Skew

```
skew-x-6
-skew-y-3
```

🧪 Custom:

```
skew-x-\[15deg]
```



## 🧲 Enable Transition

To animate transform or other changes:

```
transition            // Applies to all animatable properties
transition-none
transition-transform
transition-colors
transition-opacity
transition-shadow
```



## 🕒 Duration

```
duration-75
duration-100
duration-200
duration-500
duration-1000
```

🧪 Custom:

```
duration-\[800ms]
```



## ⏱️ Delay

```
delay-100
delay-300
delay-500
```

🧪 Custom:

```
delay-\[250ms]
```



## 🧭 Timing Functions

```
ease-linear
ease-in
ease-out
ease-in-out
```

🧪 Custom:

```
ease-\[cubic-bezier(0.4, 0, 0.2, 1)]
```



## ✅ Summary Cheatsheet

| Feature           | Classes Example                       |
|-------------------|----------------------------------------|
| Transform         | `rotate-45`, `scale-110`              |
| Translate         | `translate-x-full`, `-translate-y-2`  |
| Skew              | `skew-x-6`, `-skew-y-3`                |
| Enable Transition | `transition`, `transition-transform`  |
| Duration          | `duration-300`, `duration-[500ms]`    |
| Delay             | `delay-200`, `delay-[700ms]`          |
| Easing            | `ease-in`, `ease-[custom]`            |



🔙 [Back to Home](../README.md)

