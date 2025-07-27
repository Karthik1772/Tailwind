# 🔄 Tailwind CSS Transform & Transition Utilities

Tailwind gives you full control over **element transformations** and **CSS transitions** using intuitive utility classes.

---

## 🧠 What is Transition vs Transform?

| Concept     | Description |
|-------------|-------------|
| **Transform** | Visually modifies an element — e.g., rotate, scale, translate, skew |
| **Transition** | Controls how smoothly/quickly properties change over time |

> 🧪 Example: `hover:scale-125 transition duration-300`  
> 🔁 Transform = *What* to animate  
> ⏱️ Transition = *How* to animate



## 📽️ Visual Slide Reference

![Transition vs Transform](../assets/slides/transition-vs-transform.png)

Topics covered:
- ✅ What is Transition vs Transform
- ⏱️ Apply Transition with duration
- 🔃 Apply transform
- 🖼️ Transition vs Transform with image
- ❓ Interview Question:  
  ▫️ How to rotate element or image



## 🎛️ Enable Transform

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

scale-\[1.25]
scale-x-\[1.1]
scale-y-\[0.8]

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



## ↔️ Translate

```

translate-x-0
translate-x-1
translate-x-1/2
translate-x-full
-translate-x-1/2

translate-y-0
translate-y-1
translate-y-1/2
translate-y-full
-translate-y-1/2

```

🧪 Custom:

```

translate-x-\[25px]
translate-y-\[10%]

```



## ➰ Skew

```

skew-x-0
skew-x-3
skew-x-6
skew-x-12
-skew-x-6

skew-y-0
skew-y-3
skew-y-6
skew-y-12
-skew-y-3

```

🧪 Custom:

```

skew-x-\[8deg]

```



## ⏱️ Transition

```

transition              // Applies to all animatable properties
transition-none
transition-all
transition-colors
transition-opacity
transition-shadow
transition-transform

```



## 🕒 Duration

```

duration-75
duration-100
duration-150
duration-200
duration-300
duration-500
duration-700
duration-1000

```

🧪 Custom:

```

duration-\[1200ms]

```



## 🧩 Delay

```

delay-75
delay-100
delay-150
delay-200
delay-300
delay-500
delay-700
delay-1000

```

🧪 Custom:

```

delay-\[250ms]

```



## 🧭 Easing / Timing Functions

```

ease-linear
ease-in
ease-out
ease-in-out

```

🧪 Custom:

```

ease-\[cubic-bezier$0.4, 0, 0.2, 1$]

```



## ✅ Summary Cheatsheet

| Feature           | Class Example                          |
|-------------------|-----------------------------------------|
| Transform         | `transform`, `transform-gpu`            |
| Scale             | `scale-125`, `scale-x-75`               |
| Rotate            | `rotate-45`, `-rotate-90`               |
| Translate         | `translate-x-full`, `translate-y-1/2`   |
| Skew              | `skew-x-6`, `-skew-y-3`                  |
| Transition        | `transition`, `transition-opacity`      |
| Duration          | `duration-300`, `duration-\[800ms]`     |
| Delay             | `delay-200`, `delay-\[500ms]`           |
| Easing            | `ease-in-out`, `ease-\[cubic-bezier\(...\)]` |

---

🔙 [Back to Home](../README.md)
```

---

Let me know if you'd like the same for `Animation`, `Interactivity`, or any Tailwind topic. I can also generate PNG visuals for transform/transition effects if needed!
