# 🌀 Tailwind CSS Animation Utilities

Tailwind provides utility classes to easily apply pre-defined and custom animations to any element.

---

## ✨ Basic Animation Utility

Enable animation:

```

animate-none
animate-spin
animate-ping
animate-pulse
animate-bounce

````

| Class           | Effect Description                                    |
|----------------|--------------------------------------------------------|
| `animate-none` | No animation                                           |
| `animate-spin` | Continuous rotation (like a loader)                   |
| `animate-ping` | Ping effect (expands + fades)                         |
| `animate-pulse`| Subtle fading in and out                              |
| `animate-bounce`| Element bounces up and down repeatedly               |

🧪 Example:

```html
<div class="animate-spin w-8 h-8 border-4 border-t-transparent border-white rounded-full"></div>
````

---

## 🎞️ Custom Keyframe Animations

To use custom animations, define keyframes and names in your Tailwind config:

```js
// tailwind.config.js
module.exports = {
  theme: {
    extend: {
      animation: {
        wiggle: 'wiggle 1s ease-in-out infinite',
      },
      keyframes: {
        wiggle: {
          '0%, 100%': { transform: 'rotate(-3deg)' },
          '50%': { transform: 'rotate(3deg)' },
        },
      },
    },
  },
}
```

Then use it like:

```html
<div class="animate-wiggle">I'm wiggling!</div>
```

---

## ⏱️ Duration

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
duration-\[800ms]
```

---

## 🕒 Delay

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

---

## ⏳ Repetition & Iteration

You can set repetition with custom classes via config:

```js
animation: {
  blink: 'blink 1s step-end infinite',
},
```

Or by setting animation shorthand:

```css
animation: my-animation 1s linear infinite;
```

Note: Tailwind doesn’t have built-in `animation-iteration` classes — add custom classes or use inline styles if needed.

---

## 🧭 Easing

```
ease-linear
ease-in
ease-out
ease-in-out
```

🧪 Custom:

```
ease-\[cubic-bezier\(0.4, 0, 0.2, 1\)]
```

---

## 📽️ Visual Slide Reference

![Tailwind Animation Overview](../assets/slides/animation-overview.png)

Covered:

* ✳️ Animate: spin, pulse, ping, bounce
* 🛠️ Custom keyframes
* 🧪 Animation + transform
* 🧾 Interview Q: How to animate rotation, blinking, fade-in etc.

---

## ✅ Summary Cheatsheet

| Feature   | Class Examples                       |
| --------- | ------------------------------------ |
| Animation | `animate-spin`, `animate-pulse`      |
| Duration  | `duration-300`, `duration-\[600ms]`  |
| Delay     | `delay-100`, `delay-\[500ms]`        |
| Easing    | `ease-in-out`, `ease-linear`         |
| Custom    | Define via `keyframes` + `animation` |

---

🔙 [Back to Home](../README.md)

