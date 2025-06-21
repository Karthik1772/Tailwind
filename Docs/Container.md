# 📦 Tailwind CSS Container Utility

The `container` class in Tailwind is used to create a **responsive fixed-width layout wrapper**. It adapts based on the screen size and provides a consistent content boundary across breakpoints.


## 🧱 Basic Usage

```
<div class="container mx-auto">
  <!-- Your content here -->
</div>
```

* `container`: Adds fixed width and responsive padding.
* `mx-auto`: Centers the container horizontally.


## 📐 Default Widths (by Breakpoint)

| Breakpoint | Width  |
| ---------- | ------ |
| `sm`       | 640px  |
| `md`       | 768px  |
| `lg`       | 1024px |
| `xl`       | 1280px |
| `2xl`      | 1536px |

* These values are configurable in `tailwind.config.js`.


## 🧩 Customizing the Container

You can extend or modify how `container` behaves in your `tailwind.config.js`:

```
// tailwind.config.js
module.exports = {
  theme: {
    container: {
      center: true,
      padding: '1rem',
      screens: {
        sm: '600px',
        md: '728px',
        lg: '984px',
        xl: '1240px',
        '2xl': '1496px',
      },
    },
  },
};
```


## 🔧 Utility Pairing Examples

```
<div class="container mx-auto px-4 py-8 bg-gray-100 rounded-lg">
  <h1 class="text-2xl font-bold">Welcome to my site</h1>
</div>
```


## 🔍 When to Use `container`

✅ Use `container` when:

* You need **consistent horizontal padding** across breakpoints.
* You're building **centered layouts** with max-width limits.
* You're creating **responsive layouts** with grid/flex inside.


## ❌ Don't use `container` when:

* You need full-width sections (`w-full`).
* You're working with layout components like **cards**, **modals**, or **grid items**.


🔙 [Back to Home](../README.md)
