# 📱 Tailwind CSS Media Queries & Breakpoints

Tailwind uses **mobile-first breakpoints**, meaning styles are applied from the smallest screen and scale up.



## 📏 Default Breakpoints

Use these **prefixes** to apply styles at specific screen sizes:

```
sm     → 640px
md     → 768px
lg     → 1024px
xl     → 1280px
2xl    → 1536px
```

You apply them like this:

```
text-center        // Applies to all screen sizes
md:text-left       // Applies from ≥768px (md and up)
lg:text-right      // Applies from ≥1024px
```



## 💡 Usage Example

```
<p class="text-sm sm:text-base md:text-lg lg:text-xl xl:text-2xl">
  Responsive Text
</p>
```

This means:

* `text-sm` by default
* `text-base` on small screens (≥640px)
* `text-lg` on medium (≥768px)
* `text-xl` on large (≥1024px)
* `text-2xl` on extra-large (≥1280px)



## 🧩 Custom Breakpoints (Optional)

Define your own breakpoints in `tailwind.config.js`:

```js
module.exports = {
  theme: {
    screens: {
      xs: '475px',
      sm: '640px',
      md: '768px',
      lg: '1024px',
      xl: '1280px',
      '2xl': '1536px',
    }
  }
}
```

Then use like:

```
xs:text-green-500
```



## 🪟 Orientation Media Queries

Tailwind supports **orientation-based** styles via `@media` queries:

```css
@media (orientation: portrait) {
  /* Custom styles for portrait */
}
```

To use in Tailwind, you must extend it with custom plugins.



## 🔃 Breakpoint Utilities Work With:

You can prefix **any utility class** with a breakpoint:

```
sm:bg-red-500
md:p-8
lg:grid-cols-4
xl:rounded-2xl
```



## 🧠 Tips

✅ **Mobile-first**: Start without a prefix, then add styles for larger screens.
✅ Use **responsive design** by layering classes.
✅ Tailwind makes breakpoints **compositional** – no need for complex CSS media queries.




🔙 [Back to Home](../README.md)
